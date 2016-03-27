# Getting-and-Cleaning-Data-Course-Project

This is the project for Coursera Getting and Cleaning Data course. The R script *run_analysis.R* does the following:

1. Downloads the data sets for training and test and merges them into one data frame
2. Extracts the columns that contain measurements for mean and standard deviation 
3. Use the *activity_labels.txt* to name the subjects activities
4. Labels each variable using the *features.txt*
5. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The final dataframe is shown in *tidy_df.txt* with a step-by-step explanation of the analysis in *run_analysis.Rmd*. 

