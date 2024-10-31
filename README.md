# Flight delay
Final assignment of Data Scitech

## Objective

In this assignment, I will analyse a dataset on the on-time performance of domestic flights operated by major airlines to forecast flight delays for a travel booking website focused on enhancing customer experience. Using machine learning, I aim to determine whether delays are likely to occur due to weather conditions.

The dataset includes both scheduled and actual departure and arrival times reported by U.S. airlines that contribute at least 1% of domestic passenger revenues. It was compiled by the Office of Airline Information, Bureau of Transportation Statistics (BTS). Covering flights from 2014 to 2018, the dataset includes information such as date, time, origin, destination, airline, distance, and delay status. The data is organised into 60 compressed files, with each file containing a CSV of monthly flight details over the five years.

## onpremises.ipynb
- Process and create a dataset from downloaded ZIP files;
- Exploratory data analysis (EDA); and
- Establish a baseline model to predict the flight delay and improve it by feature engineering.

## oncloud_v1.ipynb
- Perform the machine learning pipeline using Amazon SageMaker for combined_csv_v1.csv;
- Build and evaluate the baseline model as linear model;
- Build and evaluate ensemble models as XGBoost; and
- Compare the results of implementing the ML pipeline on-premises versus on the cloud.

## oncloud_v2.ipynb
- Perform the machine learning pipeline using Amazon SageMaker for combined_csv_v2.csv;
- Build and evaluate the baseline model as linear model;
- Build and evaluate ensemble models as XGBoost; and
- Compare the results of implementing the ML pipeline on-premises versus on the cloud.
