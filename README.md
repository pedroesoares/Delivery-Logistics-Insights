## Project Overview
This project focuses on predicting delivery times using machine learning techniques to support logistics and delivery operations. 
Accurate delivery time predictions are critical for improving customer experience, operational efficiency, and service reliability.

## Business Problem
Through exploratory data analysis, we identified significant variability between estimated and actual delivery times, also how it has a high correlation with customer satisfaction.
Indicating an opportunity to improve prediction accuracy.
This project aims to develop a predictive model that estimates delivery time with higher accuracy in order to support better planning and improve service levels.

## Dataset Description
The dataset contains historical delivery records, including order timestamps, delivery times, and operational features related to the delivery process.
Data spans multiple deliveries and provides sufficient variability to model real-world delivery time behavior.

## Exploratory Data Analysis
The EDA focused on understanding delivery time distributions, identifying outliers, handling missing values, and analyzing relationships between key variables and delivery duration.
This analysis helped identify patterns, inconsistencies, and key drivers influencing delivery time variability.

## Feature Engineering
Feature engineering included the creation of time-based features (such as hour of day and day of week), handling missing values, and transforming raw inputs into model-ready variables.
These features were designed to capture temporal patterns and operational effects influencing delivery duration.

## Modeling Approach
Multiple regression models were evaluated, including Linear Regression, Random Forest, and Gradient Boosting-based models.
Model selection was based on performance, robustness, and ability to capture non-linear relationships present in the data.

## Evaluation Metrics
Model performance was evaluated using regression metrics such as:
These metrics provide a clear understanding of prediction accuracy and error magnitude from a business perspective.

## Results
The selected model demonstrated improved predictive performance compared to baseline approaches, reducing delivery time prediction errors and generalizing well to unseen data.

## Business Impact
Improved delivery time predictions enable more reliable customer-facing ETAs, better operational planning, and reduced uncertainty in logistics operations.
Even small improvements in prediction accuracy can lead to meaningful gains in customer satisfaction and operational efficiency at scale.

