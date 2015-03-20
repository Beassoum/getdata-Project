# getdata-Project
This repo contains one R script called run_analysis.R that performs the project on Getting and Cleaning Data from John Hopkins University. It also provides a code book describing the variables in the tidy data.

## The Script
The code in run_analysis.R does the following.
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
It works with Samsung data either downloaded and unziped in the working directory or from web site.
If data are available in the working directory, the procedure is:
source("run_analysis.R")
run.analysis()
Otherwise:
source("run_analysis.R")
download.data()
run.analysis()

## The Code Book
The code book describe the variables in the tidy data resulting from run.analysis() function.
