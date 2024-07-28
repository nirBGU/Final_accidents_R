# Severity of Road Accidents Analysis

group 14- Nir Levin, Shir Fuchs, Netta Nachtailer.

# Project Overview
This projects investigates how certain characteristics effect the severity of road accidents.
This is our first Data Science project using a raw data csv and perform models. The analysis is conducted using Rstudio

### Prerequisites
- R and RStudio installed on your machine.
- Required R packages: `tidyverse`, `caret`, `rpart.plot`, `randomForest`, `e1071`.
Install them using R command:
  ```R
  install.packages(c("tidyverse", "caret", "rpart.plot", "randomForest", "e1071"))


  ### Data Setup
- The dataset `Road Accident Data.csv` is required for this analysis.
- **Download the dataset**: The dataset can be downloaded from [Kaggle](). Ensure to place the downloaded CSV file in the following directory within the cloned project folder:

place the csv path in line 27
'#Load data set
df <- read.csv("data/Road Accident Data.csv", stringsAsFactors = TRUE)'
