# Black Friday Consumer Spending Analytics

## Overview
Transformed 500K+ retail transaction records through data wrangling to produce structured 
datasets for statistical analysis, aimed at informing retail promotional planning.

## Dataset
- **Source:** Black Friday Sales Prediction dataset (Kaggle)
- **Size:** 500,000+ retail transaction records (train + test merged)
- **Key fields used:** Age, Gender, Occupation, City_Category, Product_Category_1/2/3, Purchase

## Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn), Power BI, Statistical Analysis

## Approach
1. **Data wrangling** — handled missing values (Product_Category_2/3 imputed with mode), 
   encoded categorical labels (Gender, Age, City_Category)
2. **Segmentation** — segmented spending patterns by age, gender, and occupation
3. **Visualization** — Python visualizations across age, occupation, and product category 
   vs. purchase amount
4. **Dashboard** — Power BI dashboard with slicers for age group, gender, and product category

## Key Findings
- Uncovered distinct high-spending demographic clusters across age and occupation groups
- Total purchase amount analyzed: 5bn+ across the dataset
- Occupation and age segments showed measurable variance in average purchase value
- Recommended concentrating future Black Friday promotional spend on identified 
  high-value demographic segments rather than distributing evenly across all customer groups

## Dashboard Preview
![dashboard](images/Black%20friday%20sale%20power%20bi.png)

## How to Run
```
pip install pandas numpy matplotlib seaborn
jupyter notebook blackfriday_analysis_final.ipynb
```
