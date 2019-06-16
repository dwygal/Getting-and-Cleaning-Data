# Getting-and-Cleaning-Data
Final Project for Getting and Cleaning Data

# Overview
This project takes the UCI HAR Dataset and creates dataframes from the files included in the dataset.

# Dataframes
features is created from the features.txt file
activities is created from activity_labels.txt file
subject_test is created from the test/subject_test.txt file
x_test is created from the test/X_test.txt file
y_test is created from the test/Y_test.txt file
subject_train is created from the train/subject_train.txt file
x_train is created from the train/X_train.txt file
y_train is created from the train/y_train.txt file

# Merge the training and the test sets to create one data set
Temporary dataset are created from the x, y, and subject data then these three datasets are merged into Merged_Data

# Extract the mean and standard deviation for each measurement
A final data set is created by selecting mean and standard deviation data

# Name the activities in the data set
The activities are then named for the given activity names



