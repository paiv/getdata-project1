# Getting and Cleaning Data - Course Project

## Summary
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

You should create one R script called run_analysis.R that does the following.
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## run_analysis.R
Running the script from command line

    Rscript run_analysis.R

The script loads data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and writes resulting dataset into `averages.txt`.

See [CodeBook.md](CodeBook.md) for description of processed data.

The script was tested on R v3.1.1, Mac OS X
