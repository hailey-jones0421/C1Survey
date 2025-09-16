# Class 1 Survey Data Analysis
## Project Description
This repository includes the Class 1 survey dataset and R code used to
analyze it. The project is part of an exercise to practice working with real-
world data in R. 

As the last part of this assigment, I performed a chi-squared 
test to determine if there is a  statistically significant relationship between 
the item an individual would bring on a deserted island and if they like dogs.
There were five kinds of items an individual could have identified that they would bring on an island: An item for escaping the island 
("Escape"), Something to maintain hydration ("Hydration", some form of connection ("Connection"), 
a religious text ("Religious"), or tools for survival ("Survival tools").
For this chi-squared model, there were 4 degrees of freedom. The p-value is 0.644 and,
therefore, not less than 0.05. I failed to reject the null hypothesis. There was not a statistically
significant relationship between the kind item they type of item an individual 
would bring on a deserted isleand and whether or not they like dogs.
## Files Included
- `Cleaned_C1Survey.csv`: Cleaned version of the Class 1 survey dataset
- `Class 1 Survey Code.Rmd`: R script used to summarize and visualize the data
- `README.md`: This file
## What the Code Does
- Reads in the survey dataset
- Performs basic data cleaning (e.g., renaming columns, filtering)
- Creates summary statistics (e.g., age, gender, responses)
- Generates plots to visualize the data

  For the project:
  - Creates a categorical variable based on responses to survey question about what an individual would bring on an island.
  - Creates binomial variable based on survey question about whether an individual likes dogs.
  - Performs chi-squared test to determine if there is a statistically signficant relationship betweeen the kind of item
    an individual would bring on a deserted island and whether they like dogs.
## How to Run the Code
1. Download or clone this repository to your computer
2. Open `Class 1 Survey Code.Rmd` in RStudio
3. Make sure your working directory is set to the folder where the files are
saved
4. Run the script
## Author
- Name: HAILEY JONES
- Course: ADVANCED DATA ANALYSIS
- Date: SEPTEMBER 2025
