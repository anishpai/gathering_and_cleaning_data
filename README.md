# gathering_and_cleaning_data
Week 4 Course Project
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

DATA Description 
The variables in the data X contain sensor signals measured from a waist mounted smartphone. The variable in the data Y indicates the activity type the the subjects performed during the recording. 

CODE Description 
The code combines the training data set and training data set and extraction of partial variables to form another dataset with averages of each variable fo reach activity.

The  new data set generated contains variables calculated on the basis of mean and standard deviation. 

1. Merges the training and test data to create one data set, using rbind command.
2. Extracts the measurement based on the mean and standard deviation fo reach measurement. Using gprep command to get column indices for variable name.
3. Using descriptive activity names to name the activities in the data set, converting activity labes to characters, adding a new column -factor
4. Labeling data set with descriptive variable names. Give the selected descriptive names to variable columns
5. Creating an indepent tidy data set with the average of each variable for each activity and each subject. Using group_by and summarize  command.

