

# Project Overview

This notebook analyzed and cleaned a week's operational sensor data from a fictional processing plant.

The dataset was first profiled to identify data quality issues, including missing values, duplicate records, inconsistent categorical values, and invalid sensor readings.

A reusable cleaning function (`clean_ops_data`) was developed to convert timestamps into datetime format, handle missing values using interpolation, remove duplicate records, standardize zone names, and filter out physically impossible pressure readings.

After cleaning, the data was analyzed using time-series techniques by resampling the readings to hourly intervals and calculating a 24-hour rolling average. A summary table was also generated to compare the mean, maximum, and minimum pressure values across different shifts and plant zones.

Finally, a visualization comparing the raw and cleaned data showed that the cleaning process removed invalid spikes and produced a clearer representation of the operational trend, making the data more reliable for analysis and decision-making.
 U can view here https://colab.research.google.com/drive/1_60INY9avGDL2pQ6ygFgVLuOxdLA4p89#scrollTo=OM1B9UerOkuU
