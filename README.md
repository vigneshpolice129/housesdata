# 🏠 Real Estate Data Analysis & Visualization

## 📄 Overview

This project involves comprehensive analysis and visualization of a real estate dataset containing information such as house prices, number of bedrooms/bathrooms, living area size, location, and more. The objective is to apply data cleaning, exploratory data analysis (EDA), NumPy operations, pivot table analysis, and visualization techniques to extract meaningful insights.

## 📂 Dataset Information

- **Source**: Provided as `data.csv`
- **Records**: 4600+
- **Fields**: Includes `price`, `bedrooms`, `bathrooms`, `sqft_living`, `floors`, `city`, `condition`, `yr_built`, `sqft_basement`, and more.

## 🧰 Technologies & Libraries Used

- **Python**: Core programming language
- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical and array-based operations
- **Matplotlib & Seaborn**: For visualization
- **Google Colab**: For interactive development environment

## 📊 Methodology

### 1. Data Loading & Cleaning
- Loaded `data.csv` using Pandas
- Converted date column to `datetime`
- Verified data types and null values

### 2. Exploratory Data Analysis (EDA)
- Explored statistical summaries of price, size, and features
- Grouped and pivoted data by bedrooms, city, and condition
- Created box plots, histograms, scatter plots

### 3. NumPy Operations
- Mean, median, and standard deviation calculations
- Z-score normalization
- Condition-based filtering using NumPy
- Max/min identification using NumPy functions

### 4. Pivot Table Analysis
- Created pivot tables to show average price per `city` and `condition`
- Grouped by bedrooms and calculated average prices

### 5. Data Visualization
- Histogram of house prices
- Scatter plot of sqft_living vs price
- Box plots for price vs number of bedrooms

## 📈 Results & Insights

- Most houses have 3 bedrooms and 2 bathrooms
- Strong positive correlation between `sqft_living` and `price`
- Majority of properties are priced within 2 standard deviations of the mean
- Cities like Seattle show a higher average price

## 📝 Conclusion

This project illustrates end-to-end data analysis on a structured real estate dataset. It highlights how simple statistical and visual techniques can reveal trends, patterns, and outliers in housing data.

## 🚀 Future Enhancements

- Incorporate machine learning models for price prediction
- Add interactive dashboards using Plotly or Streamlit
- Perform geospatial mapping using city/statezip data

---
