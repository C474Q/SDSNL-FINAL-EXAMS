# City Population Annual Timeseries Analysis

## Project Description
This project analyzes the City Population Annual Timeseries dataset from the UN Statistics Division to understand population trends across cities from 1972 to 2014. The goal is to evaluate population changes over time, investigate population distributions by city type and sex, and develop predictive models for future population estimates.

## Dataset Description
The dataset consists of annual population data for various cities worldwide. It includes information such as the country or area, city names, city types, and population figures for the years 1972 to 2014. This comprehensive dataset allows for detailed analysis of urban population trends.

## Summary of Findings
The analysis revealed significant insights, including population growth patterns across different cities and the distribution of populations by city type. The Random Forest Regressor model demonstrated the best performance with a Mean Absolute Error of approximately 9.57 and an R² Score of about 95.61%, indicating high accuracy in predicting city populations.

## Data Preprocessing
Data preprocessing involved several key steps to clean and prepare the dataset for analysis. Unnecessary columns were removed, country names were standardized by capitalizing and cleaning special characters, and population figures were converted to integers. Additionally, rows with missing values were dropped to ensure data integrity.

## Exploratory Data Analysis
### Visualization
![Population Distribution from 1972 to 2014](images/image1.png)
*This visualization illustrates the total population trend from 1972 to 2014, showing an overall increase in urban populations during this period.*

![Number of Cities by City Type](images/image2.png)
*This visualization presents the distribution of cities by type, indicating the predominant city types in the dataset.*

![Total Population by Sex](images/image3.png)
*This bar chart displays the total population divided by sex, highlighting gender distribution in the population.*

![Population Distribution for Each Country (Top 20)](images/image4.png)
*This visualization shows the total population for the top 20 countries, providing insights into the largest urban populations worldwide.*

![Population Distribution for the Top 25 Cities](images/image5.png)
*This chart illustrates the population distribution for the top 25 cities, revealing the most populous urban areas.*

## Model Development
The model development process involved selecting relevant features from the dataset, including city type, year, country, and city names. Various machine learning models were trained, including Linear Regression, Random Forest Regressor, Decision Tree Regressor, and XGBoost Regressor. The data was split into training and testing sets to ensure model validation.

## Model Evaluation
The model evaluation process included calculating Mean Absolute Error (MAE) and R² Score for each model. The Random Forest Regressor exhibited the best performance, with a MAE of 9.57 and an R² Score of 95.61%. These metrics demonstrate the model's effectiveness in predicting city populations based on historical data.

## Conclusion
In conclusion, this project effectively analyzed urban population trends and developed predictive models for estimating future populations. The findings highlight the importance of understanding demographic changes in urban areas, which can inform policy decisions and urban planning initiatives.

## Contributors
❗ NOTE: Your professor will be the one to fill this section.
