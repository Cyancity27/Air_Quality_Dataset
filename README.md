# Air_Quality_Dataset
This dataset records the changes in air quality (PM2.5 concentration) over time in a certain area, provides detailed timestamps and decomposed time fields, and is suitable for analyzing time series changes in air quality, seasonal patterns, and associations with external factors.


## Data Structure
The dataset contains 36,192 records with 6 columns. Below is a detailed description of each column:

1. **Timestamp**: The timestamp in "YYYY-MM-DD HH:MM:SS" format, precise to the hour, indicating the specific time of data collection.
2. **Year**: The year of data collection (e.g., 2017).
3. **Month**: The month of data collection (1-12).
4. **Day**: The day of data collection (1-31).
5. **Hour**: The hour of data collection (0-23).
6. **PM2.5**: PM2.5 concentration in micrograms per cubic meter (µg/m³), an essential metric for assessing air pollution levels.

---

## Key Features
- **Time Range**: Data begins in 2017, with continuous records spanning multiple years, making it suitable for long-term trend analysis.
- **Data Frequency**: Hourly recorded data.
- **Completeness**: All fields are non-null, ensuring high data integrity and readiness for analysis.

---

## Use Cases
1. **Time Series Analysis**: Study trends in PM2.5 concentration to identify seasonality, periodicity, or anomalies.
2. **Pollution Pattern Exploration**: Examine the temporal distribution of pollution, such as differences between weekdays and weekends.
3. **Environmental Research**: Combine with weather or other environmental data to investigate the drivers of air quality changes.
4. **Predictive Modeling**: Provide training data for building PM2.5 concentration forecasting models.

---

## Data Preprocessing Recommendations
1. **Time Field Handling**: Convert `Timestamp` to a datetime format for seamless time series processing.
2. **Outlier Detection**: Check for and handle anomalies in PM2.5 values (e.g., sudden spikes or drops).
3. **Aggregation**: Aggregate data by day, week, or month for higher-level trend analysis.

---

## Sample Data

| Timestamp           | Year | Month | Day | Hour | PM2.5  |
|---------------------|------|-------|-----|------|--------|
| 2017-11-07 12:00:00 | 2017 | 11    | 7   | 12   | 64.51  |
| 2017-11-07 13:00:00 | 2017 | 11    | 7   | 13   | 69.95  |
| 2017-11-07 14:00:00 | 2017 | 11    | 7   | 14   | 92.79  |
| 2017-11-07 15:00:00 | 2017 | 11    | 7   | 15   | 109.66 |
| 2017-11-07 16:00:00 | 2017 | 11    | 7   | 16   | 116.50 |

---

## Notes
1. The PM2.5 concentration values are real-time monitoring results and may be influenced by short-term pollution sources or weather conditions.
2. If used for model training, consider incorporating additional environmental factors (e.g., temperature, humidity) to improve predictive accuracy.

---

## Contact Information
For further assistance or feedback, please contact the data provider.
