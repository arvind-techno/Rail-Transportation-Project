# Rail-Transportation-Project

## About:

It includes the number of people who took the transport per day per station and per title category.

It includes only data from tramway, bus, subway and Regional Express Network of popular city and its suburbs.

Validation data does not include : 

- Magnetic tickets (for example, the T+ ticket, Mobilis package, Paris Visite package, etc.).

- Users who do not validate when boarding a bus or streetcar, or when entering a station (e.g. if the platform is accessible without going through a control barrier, or if the control barriers are unavailable due to works, etc. )

- Fraudsters.

## Title categories:

- "IMAGINE R": combines the annual Imagine R School and Imagine R Student packages reserved for pupils, apprentices and students which allows to travel at will all year round and in all of Ile-de-France.

- "NAVIGO": includes the Navigo Annuel, Navigo Mois and Navigo Semaine packages.

- " AMETHYSTE ": includes the Amethyst packages: package reserved for seniors or disabled under conditions of means or status, and residing in the Île-de-France region. This package annual allows the beneficiary to move around unlimitedly on all modes of transport. transport within the areas of validity.

- " TST ": groups together weekly and monthly reduced fare packages granted to beneficiaries of the Transportation Solidarity Reduction program, to travel within the selected zones in all the modes of transport in the Île-de-France region.(certain economic range)

- "FGT": accounts for the Navigo Gratuité Transport Packages, a package that allows certain receiving social assistance to travel free of charge throughout the Paris Region.

- "OTHER TITLE": accounts for special packages.

- "NOT DEFINED": records validations for which the type of ticket is not defined (anomalies).

-1 in the column ID REFA LDA means that the data is not defined.

## Features:
- DATE

- TITLE_CATEGORY: Type of ticket purchased
  
- STATION_NAME: Name of different stations
  
- NB_VALID : No of persons travelling

## Problem Statement:
  Forecast the no of people per Station per day

## Description

This project focuses on analyzing and forecasting rail traffic using a dataset containing features such as date, station name, ticket category, and the number of persons traveling on a particular day. The goal is to forecast the number of persons traveling on specific dates.

## Features Explored

- **Date Range Analysis**: Determined the range of dates covered in the dataset.
- **Station Analysis**: Identified unique station names and analyzed traffic patterns across stations.
- **Data Cleaning**: Implemented cleaning steps such as filling unusual values with the most frequent ones.
- **Visual Analysis**: Utilized visualizations to explore insights like traffic variations across months, ticket category sales, and station-wise traffic.
- **Weekend Analysis**: Investigated whether weekends exhibited higher traffic compared to weekdays.

## Methodology

- **Exploratory Data Analysis (EDA)**: Conducted initial EDA to understand data distributions and patterns.
- **Linear Regression Model**: Utilized linear regression to train a model on the dataset, using features like date, station name, and ticket category to predict the number of persons traveling on a particular day.
- **Model Evaluation**: Evaluated the model's performance using train-test data and analyzed the coefficients of each feature.


## Future Work
- Model Improvement: Explore advanced modeling techniques for better forecasting accuracy.
- Feature Engineering: Experiment with additional features to enhance model performance.
- Visualization Enhancement: Improve visualizations to convey insights more effectively.

## Contributing
- Contributions are welcome! Please open an issue or submit a pull request with any enhancements or fixes.

## Credits
Data Source: https://www.kaggle.com/datasets/gatandubuc/public-transport-traffic-data-in-france


  
