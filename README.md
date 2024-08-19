# EDA-on-Air-Quality-Index
## Objectives
The goal of this project is to perform exploratory data analysis (EDA) on an Air Quality Index (AQI) dataset to understand air quality trends, identify areas with potential air quality issues, and analyze the impact of various pollutants. Python libraries such as Pandas, Matplotlib, and Seaborn are used for this analysis.

## Dataset Description
The dataset includes the following fields related to air quality measurements:
- `Date of measurement`
- `Overall AQI value`
- `Main Pollutant`
- `Name and ID of the measurement site`
- `Source of the AQI value`
- `Levels of various pollutants` (e.g., Ozone, PM2.5, CO, PM10, NO2)
- `AQI category` (e.g., good, moderate, unhealthy)
- `City and State name`

## Analysis Steps

### 1. Data Cleaning and Preparation
- Loaded the dataset and handled missing or incorrect values.
- Converted the `Date` column to a datetime type and ensured all pollutant level columns are numeric.

### 2. Descriptive Statistics
- Provided summary statistics for the numeric columns, including pollutant levels and AQI values.
- Identified the date with the highest recorded AQI value.

### 3. Distribution Analysis
- Created histograms to visualize the distributions of AQI values and key pollutants such as PM2.5 and Ozone.

### 4. Categorical Data Analysis
- Analyzed the frequency of different AQI categories across the dataset.
- Counted and visualized the number of measurements by state.

### 5. Time Series Analysis
- Plotted the monthly average AQI to observe seasonal trends in air quality.
- Determined if certain times of the year consistently show higher pollutant levels.

### 6. Correlation Analysis
- Analyzed the relationship between different pollutants to see which ones tend to rise together.
- Explored the correlation between AQI values and various pollutants.

### 7. Grouped Data Analysis
- Compared the average levels of key pollutants across different AQI categories.
- Analyzed average AQI values by city and state to identify areas with the worst air quality.

### 8. Text Data Analysis
- Extracted the most frequently mentioned main pollutants on days categorized as 'unhealthy'.

### 9. Multivariate Analysis
- Created scatter plots to investigate relationships between Ozone levels and temperature with AQI values.

### 10. Anomaly Detection
- Identified unusual patterns or outliers in AQI values across different cities or states.

## Results
The analysis provided insights into air quality trends, identified areas with potential air quality issues, and highlighted the impact of various pollutants on AQI values.
