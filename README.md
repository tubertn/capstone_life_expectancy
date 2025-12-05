# capstone_life_expectancy
This repository houses the data file and code used for my capstone project - Predicting Life Expectancy in U.S. Cities: How A Machine Learning Solution May Aid in Budgetary Decision-Making

## Files
- Capstone Project_Compiled Code.Rmd: This file contains all of the R code utilized to produce the deliverables for this project. It is broken down into four main sections:
    1. Data Collection, Cleaning and Preprocessing
    2. Exploratory Data Analysis
    3. Model Buidling and Evaluation
    4. Results, Insights, and Recommendations
- BigCitiesHealth.zip: This .zip file contains the .csv file housing all the data for this project. NOTE: the data was compressed into a .zip file due to GitHub's file size limitations. When the .Rmd file was ran on my local machine, the data was accessed via the read_csv() function seen in the code as the data was not stored in the .zip file at that time.
- README.md: This file contains documentation to support the files stored in this GitHub repository.

## How to Run
Open Capstone Project_Compiled Code.Rmd in RStudio and click "Knit," making sure BigCitiesHealth.csv is in the same folder. NOTE: The file may take several minutes to run due to the single and double cross validation procedures.

## Required Packages
- readr
- dplyr
- tidyr
- mice
- ggformula
- ggplot2
- scales
- knitr
- gridExtra
- broom
- naniar
- caret
- MASS
- ggforce
- corrplot
- car
- packcircles
- kableExtra
- grid
- xgboost
- glmnet
- nnet
- SHAPforxgboost
- pdp
  
## Data Source
The data was sourced from the Big Cities Health Coalition - https://bigcitieshealthdata.org/download/survey/

## Author
Nikolas Tubert
