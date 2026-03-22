# 🌍 World Happiness Report Analysis (2015–2019)

This project presents a detailed Exploratory Data Analysis (EDA) of the World Happiness Report dataset from 2015 to 2019. The goal is to uncover global happiness trends, analyze regional differences, and understand how socio-economic factors influence well-being.

---

## 📊 Dataset Information

### Files Used
- `2015.csv`
- `2016.csv`
- `2017.csv`
- `2018.csv`
- `2019.csv`

### Description
The dataset contains country-wise happiness scores along with key contributing factors:
- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perception of corruption

---

## 🚀 Project Objectives

- Analyze global happiness trends over multiple years  
- Compare happiness scores across regions  
- Identify key factors influencing happiness  
- Build a unified dataset for consistent analysis  
- Create a composite Well-Being Index  

---

## 🛠️ Key Techniques & Tools

- **Python (Pandas, NumPy)**
- Data Cleaning & Preprocessing
- Handling Missing Data:
  - Mean Imputation
  - Forward Fill
  - Interpolation
- GroupBy Operations
- Pivot Tables
- Multi-Level Indexing
- Boolean Indexing & Filtering
- Vectorized Computations

---

## 📈 Analysis Performed

- Data cleaning and column standardization across years  
- Merging datasets into a single unified structure  
- Regional analysis using `groupby()`  
- Correlation analysis between GDP and Happiness Score  
- Year-wise comparison using aligned indices  
- Hierarchical indexing (Region + Country)  
- Identification of highly happy countries using Boolean filtering  
- Creation of a **Composite Well-Being Index**  
- Comparison of top 20 vs bottom 20 countries  
- Impact analysis of missing data handling  
- Multi-level pivot table analysis across years and regions  

---

## 🔍 Key Insights

- Happiness is multi-dimensional and not solely dependent on GDP  
- Social support and life expectancy strongly influence happiness  
- Significant regional disparities exist across the world  
- Data preprocessing techniques can impact final insights  
- Composite indices give a more balanced view of well-being  

---

## 🎯 Conclusion

The exploratory analysis of the World Happiness dataset reveals that national well-being is a multi-dimensional concept driven by economic stability, social support systems, and health conditions. Although GDP per capita contributes to happiness, it is not the sole determinant.

Regions with strong social networks and higher life expectancy consistently rank higher in happiness scores. The analysis also emphasizes the importance of proper data preprocessing, as different techniques can significantly influence outcomes.

By constructing a composite Well-Being Index, this study provides a more holistic view of happiness, reinforcing the need for balanced development policies worldwide.
