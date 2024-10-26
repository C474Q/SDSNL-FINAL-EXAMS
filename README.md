# City Population Annual Timeseries Analysis

## Dataset Description
This dataset, from the UN Statistics Division, focuses on tracking population trends across various cities and countries over multiple years. It includes variables such as city names, population figures, year of data collection, city types, and countries or areas. 

The dataset can be accessed from the following URL: [Dataset](https://datahub.io/core/population-city/r/unsd-citypopulation-year-fm.csv).

## Data Columns and Descriptions
- **Year**: The year the population data was collected.
- **City**: The name of the city.
- **City_Type**: Type of the city (e.g., metropolitan, urban).
- **Country_or_Area**: The country or area in which the city is located.
- **Population**: The total population of the city for the given year.

## Summary of Findings
The analysis highlights patterns in city populations, revealing insights into urbanization trends, demographic shifts, and factors influencing population growth in different regions.

- **Urban Growth**: Many cities exhibit significant population growth, suggesting trends towards urbanization.
- **Regional Variations**: Population growth rates vary considerably by region, influenced by economic, social, and political factors.
- **Demographic Insights**: The data reveals how different factors, such as city type and geographic location, affect population changes.

## Data Preprocessing
Preprocessing steps included:

- **Data Cleaning**:
  - Removed unnecessary columns and rows with missing population data.
  - Ensured that city names were standardized and consistent.

- **Feature Engineering**:
  - Encoded categorical variables such as `City_Type` and `Country_or_Area` using one-hot encoding.
  - Split the dataset into training and testing sets for model evaluation.

## Exploratory Data Analysis
Key exploratory steps included examining the distribution of populations across cities and years, investigating correlations, and detecting potential outliers. Descriptive statistics were calculated for numerical variables, and categorical data was visualized to identify prominent trends.

## Visualization
Various visualizations were created to illustrate findings (pictures to be added later):

- **Population Growth Trends**: Line graphs showing population changes over time for selected cities.
- **Distribution of City Populations**: Histograms and box plots to visualize the distribution of city populations.
- **Correlation Heatmap**: A correlation matrix visualizing the relationships between variables.

## Model Development
The following models were developed to predict city populations and assess factors affecting population trends:

- **Linear Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **XGBoost Regressor**

Each model was fine-tuned using cross-validation to optimize performance based on accuracy and other relevant metrics.

## Model Evaluation
The models were evaluated using Mean Absolute Error (MAE) and R² Score, with the following results:

| Model                     | Mean Absolute Error (%) | R² Score (%) | Accuracy (%) |
|---------------------------|-------------------------|---------------|--------------|
| Linear Regression          | 19.02                   | 83.20         | 80.98        |
| Random Forest Regressor    | 9.57                    | 95.61         | 90.43        |
| Decision Tree Regressor    | 7.83                    | 98.54         | 92.17        |
| XGBoost Regressor         | 9.14                    | 98.13         | 90.86        |

## Conclusion
This project provides a comprehensive analysis of city populations, identifying key trends and insights that can guide urban planning and policy decisions.

## Future Work
- Further analysis can be conducted to explore additional features and their impact on population changes.
- Incorporate time-series forecasting methods to predict future population trends.

## References
- UN Statistics Division: [Link to the dataset](<insert dataset link>).

