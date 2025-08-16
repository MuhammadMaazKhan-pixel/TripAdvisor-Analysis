# TripAdvisor User Ratings Analysis

## Project Overview
A data analysis project using R that examines user ratings on TripAdvisor for East Asian destinations. The project includes exploratory data analysis, clustering of user preferences, and prediction of ratings using machine learning techniques.  

## Dataset
- Source: TripAdvisor dataset containing traveler ratings across 10 categories.  
- Ratings are mapped as: Excellent (4), Very Good (3), Average (2), Poor (1), Terrible (0).  
- Dataset contains average ratings per user for each category.  
- No missing values.  

## Tools and Libraries
- **R**: primary language  
- Libraries: `tidyverse`, `dplyr`, `ggplot2`, `cluster`, `randomForest`, etc.  

## Analysis Performed
1. **Exploratory Data Analysis (EDA)** – visualize rating distributions and patterns.  
2. **Clustering** – K-Means clustering to segment users based on preferences.  
3. **Prediction** – Random Forest regression to predict ratings for categories.  

## Results
- Key insights from EDA.  
- Summary of user clusters.  
- Accuracy and performance of predictive models.  

## Files in this Repository
- `TripAdvisor.Rmd` – R Markdown script with all code and analysis.  
- `TripAdvisor.pdf` – knitted report from R Markdown.
  
## How to Run
1. Open `TripAdvisor.Rmd` in RStudio.  
2. Install required libraries:  
   ```R
   install.packages(c("tidyverse", "dplyr", "ggplot2", "cluster", "randomForest"))
