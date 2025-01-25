# Diabese_Analysis
This project focuses on analyzing a diabetes dataset to gain insights into the factors that contribute to diabetes. The dataset includes various features such as the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and the outcome (whether the person has diabetes or not).

## Features
- **Pregnancies**: Number of pregnancies (for women)
- **Glucose**: Blood glucose level after a glucose tolerance test
- **BloodPressure**: Blood pressure (mmHg)
- **SkinThickness**: Skin thickness (mm)
- **Insulin**: Blood insulin level (mu U/ml)
- **BMI**: Body Mass Index
- **DiabetesPedigreeFunction**: A function expressing the family history of diabetes
- **Age**: Age (in years)
- **Outcome**: The outcome (0 or 1) where 1 means the person has diabetes and 0 means they don't

## Tools Used
- **Python**: For data analysis and visualization
- **Pandas**: For data manipulation
- **NumPy**: For numerical operations
- **Matplotlib & Seaborn**: For data visualization
- **YData Profiling**: For automated data profiling and report generation

## Project Steps
1. **Data Loading**: The dataset is loaded using Pandas.
2. **Data Profiling**: Automated data profiling is performed using YData Profiling to understand the dataset's structure, missing values, and statistical properties.
3. **Data Visualization**: Various visualizations are created to explore the relationships between different features and the outcome.
4. **Data Cleaning**: Handling missing values and outliers.
5. **Statistical Analysis**: Using statistical methods to identify significant predictors of diabetes.

## Insights from the Analysis
- **Glucose Levels**: Higher glucose levels are strongly correlated with a higher likelihood of diabetes. Individuals with glucose levels above 140 mg/dL are more likely to be diabetic.
- **BMI**: People with a BMI above 30 (considered obese) have a significantly higher chance of developing diabetes.
- **Age**: The risk of diabetes increases with age, particularly for individuals over 40.
- **Insulin Levels**: Lower insulin levels are associated with a higher likelihood of diabetes, indicating potential insulin resistance.
- **Blood Pressure**: While blood pressure has a weaker correlation with diabetes, individuals with higher blood pressure (above 90 mmHg) show a slightly higher risk.
