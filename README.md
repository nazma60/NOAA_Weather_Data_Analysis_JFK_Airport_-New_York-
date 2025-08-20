# NOAA_Weather_Data_Analysis_JFK_Airport_-New_York-
This notebook focuses on analyzing and forecasting weather patterns using the NOAA Weather Dataset collected from JFK Airport in New York. The dataset comprises 114,546 hourly observations of 12 key climatological variables, including temperature, wind speed, humidity, and pressure. The sample weather data is extracted, cleaned and analyzed and predicts weather trends to help airports schedule better flight times.  
The notebook is organized into three main parts:


**Part 1: Data Cleaning**  

Here, the raw data is prepared for analysis by:
- Removing unnecessary or redundant columns to retain only relevant numerical features
- Converting data types and cleaning inconsistencies
- Handling missing values with appropriate filling strategies
- Encoding categorical weather features for downstream analysis

**Part 2: Exploratory Data Analysis (EDA)**  

Here, visual and statistical exploration of the cleaned dataset is performed:
- Load the cleaned data.
- Generate insightful visualizations of key variables
- Identify trends, patterns, and seasonal effects in the time-series data

**Part 3: Time Series Forecasting**  

Here, the focus is on predicting future temperatures using time-series models:
- Load the cleaned and preprocessed data
- Establish baseline forecasting models
- Train and evaluate advanced statistical forecasting techniques
