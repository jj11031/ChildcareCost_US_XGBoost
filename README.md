Childcare Costs Prediction Project
Overview
This project focuses on predicting childcare costs in US counties based on various characteristics. The analysis involves exploratory data exploration (EDA), model building, and deployment readiness. The primary goal is to understand the trends, relationships, and predictors influencing childcare expenses.

Data
The dataset, sourced from TidyTuesday, contains information on childcare costs across multiple years and counties. It includes demographic variables, income details, labor force participation, and childcare cost metrics.

Exploratory Data Analysis (EDA)
Explored temporal trends in childcare costs using ggplot2.
Investigated relationships between childcare costs, median household income, and labor force participation for women.
Analyzed the impact of racial makeup on childcare costs, revealing complex relationships between race, income, and location.
Modeling
Used the tidyverse and tidymodels in R for effective modeling.
Employed xgboost as the primary algorithm for predicting childcare costs.
Implemented early stopping regularization methods during model training.
Conducted model tuning, validation, and evaluation to achieve optimal predictive performance.
Extracted insights into feature importance using Variable Importance in Projection (VIP) plots.
Deployment Readiness
Created a deployable model object using vetiver, showcasing readiness for real-world applications.
Files
childcare_costs.csv: The raw dataset used for analysis.
Childcare_Costs_Prediction.Rmd: R Markdown file containing the entire code and analysis.
Childcare_Costs_Prediction.html: HTML file generated from the R Markdown file for easy viewing.
README.md: This file providing an overview of the project.
Getting Started
Clone this repository.
Ensure you have R and RStudio installed.
Open Childcare_Costs_Prediction.Rmd in RStudio.
Run the code chunks sequentially for a complete analysis.
Results
Model achieved a Root Mean Squared Error (RMSE) of approximately $20.
Top predictors included the proportion of Asian population, median household income, median earnings for women, year, and the number of households in the county.
