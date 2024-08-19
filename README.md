# Telomere Length Analysis Project

## 1. Project Overview
This project analyzes the relationship between telomere length and various factors such as age, sex, cell type, and clinical conditions using a dataset from a lifespan study.

## 2. Setup and Dependencies
This project uses Python 3.x with the following libraries:
- pandas
- matplotlib
- seaborn
- scipy
- numpy
- statsmodels

To install dependencies:
pip install pandas matplotlib seaborn scipy numpy statsmodels

## 3. Data Description
The dataset 'Lifespan_Study_selected_data.csv' contains information about telomere length, donor age, sex, cell type, clinical condition, and various cellular parameters.

Key columns:
- Telomere_length_Uts_ratio
- Donor_age
- Sex
- Cell_type
- Clinical_condition
- Population_doublings_Utotal_divisions
- Doubling_rate_Udays_per_division

## 4. Data Preprocessing
- Loaded data using pandas
- Checked for missing values
- Dropped rows with missing telomere length or age data
- Created dummy variables for categorical data (Sex)

## 5. Exploratory Data Analysis
- Computed summary statistics for telomere length and age
- Analyzed distribution of telomere length across different categories (sex, cell type, clinical condition)
- Calculated mean telomere length for different groups

## 6. Statistical Analysis
- Performed Pearson correlation between telomere length and age
- Conducted linear regression analysis
- Executed t-test to compare telomere length between males and females
- Implemented multiple linear regression model with age and sex as predictors

## 7. Visualization
Created various plots using matplotlib and seaborn:
- Scatter plot of telomere length vs. age with regression line
- Box plots of telomere length by sex, cell type, and clinical condition
- Scatter plot of telomere length vs. passage number
- Multiple scatter plots showing relationships between telomere length and various factors
![output](https://github.com/user-attachments/assets/edcf56e7-6e97-4ef6-9910-9476058d43ee)
## 8. Results and Interpretation
- Negative correlation between age and telomere length (correlation coefficient: X, p-value: Y)
- Significant difference in telomere length between males and females (t-statistic: X, p-value: Y)
- Multiple linear regression showed significant effects of both age and sex on telomere length (R-squared: X)

## 9. Conclusion
This study provides evidence for significant relationships between telomere length, age, and sex. The findings support telomere length as a biomarker of aging while highlighting the complexity of factors influencing telomere dynamics.

## 10. Future Work
- Investigate additional factors that may influence telomere length
- Conduct longitudinal analysis if data becomes available
- Explore non-linear relationships between variables

