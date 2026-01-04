# Total ADHD Medication Consumption

## Abstract
The COVID-19 pandemic and associated public health measures have affected mental health service utilization and psychotropic medication use. This study analyzed U.S. pharmaceutical sales from 2014 Jul to 2019 Dec to characterize pre-pandemic trends in attention deficit hyperactivity disorder (ADHD) medication consumption. A machine learning model was developed to forecast expected consumption for 2020 and 2021 under non-pandemic conditions. The deviation between the actual and predicted sales under non-pandemic conditions generates the quantitative estimation of the pandemic’s impact. Results showed that 3.3% of the U.S. population aged 6 and older were receiving ADHD medications with a stable rate from 2015 to 2019. Approximately 60% of individuals diagnosed with ADHD were treated with medication, consistent with expected treatment rate. Our machine learning model identified a lower consumption rate of ADHD medication in 2020, indicating a transient disruption following the onset of COVID-19. However, by 2021, the actual consumption rebounded and aligned with forecasted trends, suggesting recovery of ADHD treatment patterns.
<img width="975" height="344" alt="image" src="https://github.com/user-attachments/assets/f7f6c349-5a6a-4dc6-b1d1-05be888acf3f" />



## Paper
S. Lloyd, M. Liu, W. Lu, “Lightweight Detection of Reconnaissance Attacks in IoMT Networks with Mobile Visualization Support,” accepted and orally presented at 2025 IEEE MIT Undergraduate Research Technology Conference (URTC), in press on IEEE Xplore. 

## Oral Presentation 
[Link: MIT, Oct 11, 2025](https://drive.google.com/file/d/1uUHdaXFJeAz8ocFRRaTW9gRNLxCVh_cU/view)

# Individual ADHD Medication Consumption 

## Description:
This project is an extended part of ADHD Medication Use. The aim is to forecast the future sales and prescriptions for individual ADHD medicine such as Adderall or Ritalin based on historic data. Unlike the forecasting model for total ADHD medication consumption, the algorithm for individual ADHD drug use forecasting needs to integrate additional factors like competitive product market share and clinical value (e.g extended release formulations would reduce the number of takes in a day and increase compliance). I am able to augment the original XGBoost model with principal component analysis (PCA) to predict the consumption of Adderall and Ritalin. These individual drug prediction models can be translated to regional sales input and predict the future sales of each drug in a region or a store, improving  inventory planning and medication accessibility for patients.

## Modelling Method
We employed a hybrid time series approach combining lag-based feature engineering, Holt-Winters exponential smoothing, and an eXtreme Gradient Boosting (XGBoost) regression model. This initial model captured temporal dependencies, seasonal structure, and nonlinear relationships in the individual drug data. The second model is to implement a machine learning-based method for forecasting individual drug market shares using XGBoost regression, PCA, and lag feature engineering.

## Coding Environment
R (R Core Team, 2024), version 4.4.1, was used for data analysis of the actual and predicted data. All machine learning model executions were performed using Python, executed within the Google Colaboratory (Colab) IDE.






