# Getting and Cleaning Data - peer assessment project

==================================================================
Human Activity Recognition Using Smartphones Dataset
Peer Assessment - Sivarajan N. Aug 24 2014
==================================================================

There is only one R file:run_analysis.R, which is creating tidy data.

run_analysis.R is doing following steps:

==================================================================
Step 1 & 2 - Merge and Extract
==================================================================
* Function for reading subject_train, X_train, y_train from the folder 'train'
* and labelling and extracting the data for mean and standard deviation.
* reading the test dataset
* reading the train dataset
* merging the two datasets and giving proper column names

==================================================================
Step 3 & 4 - name activities and label data
==================================================================

* Reading the activity labels and creating a column for activity labels
* Merge the activity labels to the merged dataset

==================================================================
Step 5 - Another Tidy Data set
==================================================================
* Create one more independent tidy data set with the average of each variable for each activity and each subject.
* Recast, use , row.name=FALSE
* Getting the clean tidy dataset


The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

In the run_analysis.R script, functions were created for each step