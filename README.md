# Regulatory Affairs of Road Accident Data 2020 India

## Project Overview

Road accidents are one of the leading causes of injuries and fatalities worldwide. Understanding the factors contributing to accidents is essential for improving road safety and reducing accident rates. This project analyzes road accident data from major Indian cities in 2020 to identify accident patterns, causes, and outcomes using data analytics and machine learning techniques.

The project combines data preprocessing, exploratory data analysis (EDA), visualization, and predictive modeling to uncover key insights and support informed decision-making for road safety improvements.

---

## Objectives

- Analyze road accident patterns across major Indian cities.
- Identify the major causes and contributing factors of accidents.
- Study accident outcomes and severity levels.
- Perform exploratory data analysis (EDA) to uncover hidden trends.
- Build a machine learning model to predict accident counts.
- Evaluate model performance using regression metrics.
- Generate actionable insights for road safety improvement.

---

## Dataset

The dataset contains road accident records from major Indian cities for the year 2020.

### Features Include

- Million Plus Cities
- Cause Category
- Cause Subcategory
- Outcome of Incident
- Count

### Target Variable

- Count (Number of Accidents)

---

## Exploratory Data Analysis (EDA)

### Key Insights

- Accident counts vary significantly across different cities.
- Chennai and Delhi recorded some of the highest accident counts.
- Certain accident cause subcategories contribute more heavily to total accidents.
- Most recorded incidents result in injuries rather than fatalities.
- Accident outcomes differ based on underlying causes and city characteristics.

### Visualizations Performed

- Top 10 Cities with Lowest Accident Counts
- Distribution of Accident Outcomes
- Top 15 Accident Cause Subcategories
- Feature Importance Analysis
- Accident Count Distribution by Outcome

---

## Machine Learning Approach

### Model Implemented

- Random Forest Regressor

### Key Techniques

- Data Cleaning
- Missing Value Handling
- Label Encoding
- Train-Test Split
- Feature Engineering
- Regression Modeling

---

## Model Performance

The Random Forest Regressor was used to predict accident counts based on city, accident causes, and incident outcomes.

### Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score

The model demonstrated the ability to capture relationships between accident characteristics and accident frequency.

---

## Feature Importance

The most influential features affecting accident count prediction were:

- City
- Cause Subcategory
- Cause Category
- Outcome of Incident

Feature importance analysis revealed that city location and specific accident causes have a strong impact on accident frequency.

---

## Applications

This project can help:

- Traffic Management Authorities
- Road Safety Departments
- Government Transportation Agencies
- Urban Planning Organizations
- Policy Makers and Researchers

Potential applications include:

- Accident prevention planning
- Road safety policy development
- Infrastructure improvement initiatives
- Risk assessment and monitoring
- Public awareness programs

---

## Limitations

- Dataset covers only the year 2020.
- Weather, traffic volume, and road condition data are not included.
- Predictions depend on the quality and completeness of available data.
- External factors affecting accidents are not fully captured.
- Results should be used as analytical insights rather than exact forecasts.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Contents

- Road_accident(s).ipynb → Complete analysis and machine learning workflow
- Regulatory Affairs of Road Accident Data 2020 India.csv → Dataset
- README.md → Project Documentation

---

## Author

**Sarika T A**  
Aspiring Data Analyst / Data Scientist

---

## Conclusion

This project analyzed road accident data from major cities in India to identify patterns, causes, and outcomes of accidents in 2020. The analysis revealed that cities such as Chennai and Delhi experience higher accident frequencies, largely due to factors such as dense populations, heavy traffic flow, and increased vehicle usage.

The study demonstrated that road accidents are influenced by multiple factors, including traffic violations, road conditions, environmental factors, junction design, and traffic control systems. Most accidents resulted in injuries rather than fatalities, with minor and total injuries being the most common outcomes.

A Random Forest Regressor was implemented to predict accident counts, and feature importance analysis showed that city location and accident cause subcategories are among the most significant factors affecting accident occurrence. Overall, the project highlights how data analytics and machine learning can be used to identify accident trends, support road safety initiatives, and assist policymakers in developing effective accident prevention strategies.

---

## Future Improvements

- Incorporate weather and environmental data into the analysis.
- Include traffic density and road infrastructure information.
- Use advanced machine learning algorithms such as XGBoost and Gradient Boosting.
- Perform hyperparameter tuning to improve prediction accuracy.
- Develop interactive dashboards using Power BI or Tableau.
- Integrate real-time accident reporting systems for live monitoring.
- Build accident risk prediction systems for proactive road safety planning.
- Expand the dataset to include multiple years for trend forecasting and long-term analysis.

---
