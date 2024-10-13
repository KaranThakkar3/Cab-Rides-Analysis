# Cab Rides Data Analysis and Modeling

This project analyzes a dataset of cab rides and builds predictive models to estimate ride prices based on various factors like distance, surge multiplier, time of day, and cab type. The project is divided into two main parts: basic exploratory data analysis (EDA) and advanced modeling using machine learning techniques.

## Project Structure

- **Basic Analysis:**
  - Data cleaning, handling missing values, and feature extraction.
  - Exploratory data analysis (EDA) using visualizations.
  
- **Advanced Modeling:**
  - Predictive models using Linear Regression and Random Forest.
  - Model evaluation using metrics like RMSE and R².

## Dataset

The dataset used for this project contains information on 693,071 cab rides with the following columns:

- `distance`: The distance traveled for each ride.
- `cab_type`: The type of cab service (e.g., "Lyft", "Uber").
- `time_stamp`: Timestamp of when the ride occurred.
- `destination`: Ride destination.
- `source`: Ride source.
- `price`: The price of the ride.
- `surge_multiplier`: Surge pricing factor.
- `id`, `product_id`: Identifiers.
- `name`: The specific service type (e.g., "Shared", "Lux").

The dataset can be found here: https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?select=cab_rides.csv

