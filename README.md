# Bike-Share-Service-Demand-Forecasting-using-R

## Overview
This project analyzes how natural factors like weather and time affect bike-sharing usage in Ahmedabad, India. We built models to predict the number of bike rentals based on various environmental and temporal factors, helping bike-share operators better plan their resources.

## Dataset
We used a 2-year dataset (2018-2019) from Ahmedabad's bike-sharing system that includes:
- Date and time information
- Weather conditions (temperature, humidity, wind speed)
- Day type (holiday, working day)
- Seasonal information
- User types (casual and registered users)

## What We Did

### 1. Data Cleaning
- Checked for missing and NULL values
- Verified data types
- Removed duplicate entries
- Ensured data consistency

### 2. Data Pre-processing
- Removed irrelevant columns (year and date fields)
- Created dummy variables where needed
- Tested feature collinearity
- Scaled numerical variables
- Split data into 80% training and 20% testing sets

### 3. Model Building
We created three linear regression models to predict:
- Casual users
- Registered users
- Total number of users

### 4. Key Findings
- Average temperature has the strongest positive impact on bike rentals
- Working days significantly affect casual users (negative correlation)
- High temperatures negatively impact registered users
- Model performance:
  - Casual Users: R² = 0.66
  - Registered Users: R² = 0.49
  - Total Users: R² = 0.51

## Future Improvements
The model could be enhanced by including additional factors such as:
- Population density
- Public transport availability
- Traffic density
- Service awareness levels

## Notes
- The model's accuracy (40-60%) is consistent with typical public transport prediction models
- While not perfect, the model provides useful insights for resource planning

## Team
- Kushagra Jain
- Harshita Kala
- Ananya Canakapalli
- Ramya Padmini Jandhyala
- Sai Tarun Angadipeta
