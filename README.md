# 📊 Exploratory Data Analysis (EDA)

## ✅ Objective
The goal of this task is to perform Exploratory Data Analysis on Titanic Dataset.

---

## 🛠 Tools & Libraries Used
- **Pandas** – for data loading and manipulation  
- **Matplotlib** – for basic static plotting  
- **Seaborn** – for advanced statistical visualizations  
- **Plotly** – for interactive visualizations

---

## Step 1: Load Dataset
- Loaded the dataset using `pandas.read_csv()`
- Previewed the first few rows using `df.head()`

---

## Step 2: Summary Statistics + Data Info
- Used `df.info()` to understand data types and non-null counts
- Used `df.describe()` to get statistical summaries of numeric and categorical columns
- Checked for missing values using `df.isnull().sum()`

---

## Step 3: Univariate Analysis
- **Histograms** plotted for all numeric columns to observe distributions
- **Boxplots** used to identify data spread and potential outliers per feature

---

## Step 4: Feature Relationships
- Created **Pairplot** using Seaborn to analyze relationships between numeric features
- Plotted **Correlation Matrix Heatmap** to identify strongly or weakly correlated variables

---

## Step 5: Interactive Visualizations with Plotly
- Built interactive **Histograms** for key numeric columns using `plotly.express`
- Constructed **Scatter Matrix** if number of numeric columns was less than 5

---

## Step 6: Outlier Detection
- Implemented **IQR method** to detect potential outliers in each numeric feature
- Counted and printed the number of outliers per column

---
