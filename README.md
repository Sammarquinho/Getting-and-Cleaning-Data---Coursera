# Getting-and-Cleaning-Data---Coursera
Getting and Cleaning Data Course Project
This is the course project for the Getting and Cleaning Data Coursera course.
The included R script, run_analysis.R, conducts the following:
1 - Download the dataset from web if it does not already exist in the working directory.
2 - Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
3 - Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). 
Also, modify column names to descriptive. (-mean to Mean, -std to Std, and remove symbols like -, (, ))
4 - Extract data by selected columns(from step 3), and merge x, y(activity) and subject data.
Also, replace y(activity) column to it's name by refering activity label (loaded step 3).
5 - Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity.
 The result is shown in the file tidy_dataset.txt.
 
 This course project is to collect, work with, and clean a data set. 
The goal is to prepare tidy data that can be used for later analysis.

The data for this project can be downloaded through the following link:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Full description of the data can be found here:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

CodeBook.md. describes the variables, the data, and any work that are performed to clean up the data.

run_analysis.R contains all the coding for doing the course project, that includes downloading and unzipping the dataset that is used for this project.

averagedata.txt is a written out text file from run_analysis.R, which is the average features of each subject and each activity. Please refer to CodeBook.md. for more explicit information.
