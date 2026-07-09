# Data Analysis on Mall Customers Dataset

## Objective

The main goal of this project is to understand the Mall Customers dataset by performing data cleaning, preprocessing, exploratory data analysis (EDA), and visualization. This helps in exploring customer information and identifying meaningful patterns in the data.

## Dataset

- **Dataset Name:** Mall Customers
- **Total Records:** 200
- **Total Features:** 5

## Tools and Libraries Used

- Pandas
- Matplotlib
- Scikit-learn (LabelEncoder)

## Data Cleaning

The dataset was first loaded into Python and examined to understand its structure. Missing values and duplicate records were checked to ensure the data quality. The `Genre` column was renamed to `Gender` to improve readability.

## Data Preprocessing

Since the `Gender` column contains categorical values, Label Encoding was used to convert them into numerical values. This makes the data easier to analyze and work with.

## Exploratory Data Analysis (EDA)

Several statistical techniques were used to better understand the dataset, including:

- Summary statistics
- Mean and median calculations
- Correlation analysis
- Frequency counts for categorical values

## Data Visualization

Different charts were created to explore the data visually:

- Histogram to study age distribution
- Bar chart and pie chart for gender distribution
- Box plot to identify the spread of annual income
- Scatter plot to examine the relationship between annual income and spending score
- Correlation heatmap to understand relationships between numerical features

## Conclusion

This project provided a basic understanding of the Mall Customers dataset through data cleaning, preprocessing, statistical analysis, and visualization. The visualizations helped in identifying customer characteristics, spending behavior, and relationships between different features. Overall, this exercise demonstrates the complete workflow of basic exploratory data analysis using Python.
