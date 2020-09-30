## My submission for the Getting and Cleaning Data Course Project
## where data was obtained

## [http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones]

## data for the project

## [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip]

The run_analysis.R can be run as long as setting your working directory to the UCI HAR Dataset folder. Dplyr package required to run.

Analysis will read all the test data and train data merge them into one data set. Each variables were names accordingly based on the features listed in the features.txt file.

Using the combined data set, independent tidy data set with the average of each variable for each activity and each subject was created and written into tidydataset.txt file.
