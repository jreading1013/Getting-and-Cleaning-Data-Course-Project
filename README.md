# Getting-and-Cleaning-Data-Course-Project

## Project Requirements

You should create one R script called run_analysis.R that does the following...

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Project Instructions

1. Download the data source https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and save to your local drive in a folder named ```UCI HAR Dataset```.
2. Save ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset``` then set it as your working directory using ```setwd()``` function in RStudio.
3. Run ```source("run_analysis.R")``` then it will generate a new file ```tiny_data.txt``` in your working directory.

## Project Dependencies

```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 
