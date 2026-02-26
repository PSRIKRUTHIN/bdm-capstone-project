# bdm-capstone-project
# 📊 Industrial Growth Analysis in Telangana Backward Districts

## 🧠 Project Overview
This project analyzes industrial growth patterns in backward districts of Telangana using real government datasets. The goal is to identify key issues such as low exports despite high investments, unequal investment distribution, and lack of awareness of industrial incentives.

The analysis is based on datasets from June 2024 to December 2024 collected from official Telangana Government Open Data sources.

## 🎯 Problem Statement
Many districts in Telangana receive significant industrial investments but show:
- Low export ratios
- Unequal investment distribution
- Low awareness of government incentives
- Over-dependence on Micro and Small industries

This project aims to discover data-driven insights and policy recommendations to improve industrial growth and exports.

## 📁 Datasets Used
- Telangana MSME Dataset (June–Dec 2024)
- Industrial Incentives Dataset
- Factories in Telangana Dataset
- Industrial Investment & Employment Data
- Raw Material Availability Data

Source: Telangana Government Open Data Portal

## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## 🔍 Methodology

### 1. Data Preprocessing
- Data cleaning (handling missing values using `dropna`)
- Outlier detection using box plots
- Merging multiple monthly datasets using Pandas
- Column standardization and normalization

### 2. Exploratory Data Analysis (EDA)
- District-wise investment analysis
- Export ratio calculation
- Industry category distribution (Micro, Small, Medium, Mega)
- Descriptive statistics using `.describe()` and `.info()`

### 3. Feature Engineering
- Export Ratio = Export Units / Total Units × 100
- District-level aggregation using GroupBy
- Investment categorization by industry type

### 4. Regression Analysis
- Independent Variable: Investment (₹)
- Dependent Variable: Export Ratio (%)
- Correlation Analysis (0.68 moderate positive correlation)
- Identified outliers affecting regression interpretation

### 5. Time Series Analysis
- Monthly investment trends across districts
- Incentive awareness trends over 7 months
- Identification of top investment districts (Medchal, Rangareddy, Sangareddy)

## 📊 Key Insights & Findings
- Investments are highly concentrated in 3 districts
- Most districts have **zero export ratio** despite investments
- Micro and Small industries form ~80% of total industries
- Medium and Mega industries (export-driven) are underrepresented
- Incentive awareness is low in backward districts
- High investment does NOT always lead to high exports (data contradiction found)

## 📈 Visualizations
- Bar Charts
- Stacked Bar Plots
- Regression Plots
- Time Series Analysis Graphs
- District-wise Investment vs Export Comparison

## 💡 Recommendations
- Increase investment in Medium and Mega industries
- Promote industrial incentives awareness campaigns
- Develop infrastructure in backward districts
- Balanced investment distribution across districts
- Government policy focus on export-oriented sectors

## 🏗️ Real-World Impact
This project can help:
- Policy Makers
- Government Agencies
- Industrial Development Boards
- Business Analysts
- Economic Researchers
