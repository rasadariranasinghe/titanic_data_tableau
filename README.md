# Titanic Incident Data Analysis Project

![Titanic Dashboard](https://raw.githubusercontent.com/rasadariranasinghe/titanic_data_tableau/9a88756fd9b780b7a85bd1aa3a80144d1d37da9e/Titanic1_dahboard.png)

## Overview
This project aims to analyze the survival rates of passengers aboard the Titanic to understand the impact of passenger class and age on survival outcomes. The findings provide insights into socio-economic factors and their role in disaster survival, guiding recommendations for designing safer ships and equitable emergency response systems.

## Goals
- Investigate whether survival rates were influenced by passenger class.
- Explore the correlation between survival rates and age groups (children, youth & adults, seniors).
- Provide visual representations of survival trends for effective communication of findings.

## Data Sources
The dataset contains details about Titanic passengers, including survival status, class, age, and other demographic information. Key variables include:
- `Survived`: 0 = No, 1 = Yes
- `Pclass`: 1 = 1st, 2 = 2nd, 3 = 3rd
- `Age`: Passenger age in years
- `Sex`: Gender

## Analysis Steps
1. **Data Cleaning**:
   - Handle missing values in the `Age` column by imputing with the average age.
   - Convert the `Age` column into integer values.
   - Categorize passengers into age groups:
     - Children: 0-14 years
     - Youth & Adults: 15-64 years
     - Seniors: 65+ years

2. **Data Exploration**:
   - Generate summary statistics and assess data quality.
   - Create new categorical columns for age group analysis.

3. **Visualization**:
   - Develop bar plots to show total survivors across passenger classes.
   - Create a pie chart for survival distribution by class.
   - Visualize survival rates by age group and class using grouped bar plots.

4. **Dashboard Creation**:
   - Build a Tableau dashboard to present findings interactively. Key features include:
     - Filters for age categories.
     - Clear visual distinctions of survival trends.

## Key Findings
1. **Survival by Passenger Class**:
   - First-class passengers had a survival rate nearly three times higher than those in third class.
   - All children in second class survived (100%), compared to 41% in third class.

2. **Survival by Age and Class**:
   - No seniors survived in second or third class.
   - Youth and adults in first class showed significantly higher survival rates.

3. **Age Distribution**:
   - Most passengers were youth and adults, influencing overall trends.

## Tools and Technologies
- **Python**: For data cleaning and processing.
- **SQLite**: To manage and query the dataset.
- **Tableau**: For interactive data visualization.

## Deliverables
- **Processed Dataset**: Cleaned and enriched Titanic data.
- **Visualizations**: Bar plots, pie charts, and histograms.
- **Interactive Dashboard**: A Tableau dashboard to explore survival trends by class and age.

## Conclusion
The analysis highlights significant disparities in survival rates based on passenger class and age. These findings emphasize the need for equitable emergency planning and resource allocation to ensure fair chances of survival for all passengers.

## How to Run the Project
1. **Data Processing**:
   - Run the provided Python code to clean and process the data.
   - Export the cleaned data to a format compatible with Tableau (e.g., Excel).

2. **Visualization**:
   - Use Tableau to load the processed data and explore the dashboard.

3. **Insights**:
   - Review the findings to understand survival trends.

-

