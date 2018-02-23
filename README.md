This README document describes the details for the Week 4 assignment in the Getting and Cleaning Data Course for Coursera.

The run_analysis.R file in this repository is a R script file that completes the following steps when run:

1) Downloads the dataset from this location:  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and
unzips it to a local directory.

2) Reads in the data tables from the Training and Test datasets
  Training tables:  x_train
                    y_train
                    subject_train
  
  Test files:  x_test
               y_test
               subject_test

3) Loads the activiy and features files, which can be used to create the label the column names

4) Mereges together the training and test files

5) Subsets the merged data to keep only the ID, mean, and standard deviation data for each measurement.

6) Assign the descriptive activity names to name the activities in the data set.

7) Creates a new dataset named TidyDataFin.txt which contatins the average for each variable for each activity and subject.

8) Writes the TidyDataFin.txt data to the local computer.  This data file was them comitted to this repository.


The codebook for the TidyDataFin.txt dataset is located in this repository in the CODEBOOK.MD file.




