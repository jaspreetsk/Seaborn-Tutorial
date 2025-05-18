# 🌟 Seaborn Data Visualization Project

Welcome to my **Seaborn Data Visualization** project! 🎨📊 This repository explores powerful visualization techniques using `matplotlib`, `seaborn`, `numpy`, and `pandas`, leveraging built-in datasets and custom styling to create stunning plots.

---

## 📌 Project Overview
🔹 **Platform**: VS Code with WSL2 (Ubuntu 24 LTS)  
🔹 **Libraries Used**: `numpy`, `pandas`, `matplotlib`, `seaborn`  
🔹 **Datasets**:  
   - [`ComputerSales.csv`](https://github.com/derekbanas/seaborn/blob/master/ComputerSales.csv)  
   - [`Financial Sample.xlsx`](https://github.com/derekbanas/seaborn/blob/master/Financial%20Sample.xlsx)  
   - [`icecreamsales.csv`](https://github.com/derekbanas/seaborn/blob/master/icecreamsales.csv)  
   - Built-in datasets: `car_crashes`, `tips`, `flights`

---

## 🖼️ Key Features & Visualizations
### 🎯 **Distribution & Pair Plots**
✔️ `sns.jointplot(x='speeding', y='alcohol', data=crash_df, kind='reg')`  
✔️ `sns.pairplot(tips_df)`  
✔️ `sns.kdeplot(data=car_crashes, x='speeding', y='alcohol')`  

### 🎨 **Styling & Customization**
✔️ Theme Options:
```python
sns.set_style('whitegrid')  # Options: 'white', 'darkgrid', 'dark', 'ticks'
sns.set_context('paper', font_scale=1.5)
plt.figure(figsize=(8,4))
```
✔️ Removing Axes Rulers:
```python
sns.despine(left=True, bottom=True)
```

### 📊 **Categorical Plots**
✔️ `sns.barplot()`, `sns.countplot()`, `sns.boxplot()`, `sns.violinplot()`  
✔️ `sns.stripplot()`, `sns.swarmplot()`

### 🔥 **Matrix & Regression Plots**
✔️ Heatmaps with the `flights` dataset  
✔️ Cluster maps, Pair grids, Facet grids, and Regression plots

---

## 🔗 Source Code & References
📌 **GitHub Repository**: [Seaborn Project](https://github.com/derekbanas/seaborn)  
📌 **Data Files**: Available in the repository  
📌 **YouTube Tutorial**: [Seaborn Crash Course](https://youtu.be/6GUZXDef2U0?si=0pmGPQAHGZO52aox)

---

## 📢 Contributing & Feedback
Feel free to **star** ⭐ this repository and explore the power of **Seaborn**!  
For contributions, open a pull request or drop a suggestion.  

**Happy Coding & Data Visualizing! 🚀**
