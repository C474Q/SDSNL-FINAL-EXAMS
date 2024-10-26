# City Population Annual Timeseries Analysis - UN Statistics Division
City Population Annual Timeseries Analysis - UN Statistics Division

## Dataset Description
Dataset Description
This dataset from the UN Statistics Division focuses on tracking population trends in various cities across the globe. It includes annual population data for multiple countries, highlighting variations based on city types and demographic factors. The dataset encompasses variables such as city name, country, city type, year of data collection, and total population.

The dataset can be accessed from the following URL: Dataset.

Data Columns and Descriptions
Year: The year of data collection for the population record.
Country_or_Area: Name of the country or area where the city is located.
City: Name of the city.
City_Type: Category of the city (e.g., metropolitan, urban).
Sex: Gender demographic (e.g., Male, Female).
Population: Total population recorded for the specified year.
GeoLocation: Geographic coordinates (latitude and longitude) of the city.
City_ID: Unique identifier for the city.
Country_ID: Unique identifier for the country or area.
StratificationCategory1: Category used for stratification (e.g., city type, year).
Stratification1: Specific stratification within the category (e.g., "Urban").
Summary of Findings
The analysis reveals significant insights into population distribution across various cities and countries. Key findings include:

City Type Distribution: A notable variance in population numbers based on city types, indicating urban areas generally have higher populations compared to rural areas.
Population by Sex: The analysis demonstrates demographic variations, with slight differences in male and female populations across different cities.
Top Countries: Certain countries consistently feature in the top population rankings, showcasing their urbanization trends.
Data Preprocessing
Preprocessing steps included:
Data Cleaning:
Removed missing values and irrelevant columns.
Imputed values for missing entries where applicable.
Feature Engineering:
Encoded categorical columns such as City_Type and Sex.
Scaled features using StandardScaler for model training.
Exploratory Data Analysis
Key exploratory steps involved examining the distribution of population data across different demographics and cities. Descriptive statistics for numeric variables were calculated, and categorical data visualizations highlighted significant trends.

Visualization
Various visualizations were created to illustrate findings:

Distribution of City Types: Visualizes how many cities fall into each category.
Population by Sex: Bar plot showcasing the total population distributed by gender.
Top 20 Countries by Population: A horizontal bar chart displaying the total population of the top 20 countries.
Top 25 Cities by Population: A bar chart illustrating the population distribution among the largest cities.
Model Development
The following models were developed to predict population based on various factors:

Linear Regression
Random Forest Regressor
Decision Tree Regressor
XGBoost Regressor
Model Evaluation
Each model was evaluated based on Mean Absolute Error (MAE), R² Score, and accuracy. The results are summarized below:

Model	Mean Absolute Error	R² Score	Accuracy
Linear Regression	19.02	83.20%	80.98%
Random Forest Regressor	9.57	95.61%	90.43%
Decision Tree Regressor	7.83	98.54%	92.17%
XGBoost Regressor	9.14	98.13%	90.86%
Interpretation of Results
The Random Forest Regressor and Decision Tree Regressor models exhibited superior performance, achieving high R² scores and low MAE. These models can effectively predict city populations based on city type and other factors.

Conclusion
This project provides a comprehensive analysis of city population trends using the UN Statistics Division dataset. The insights generated can help inform urban planning and public policy decisions related to population management and resource allocation.