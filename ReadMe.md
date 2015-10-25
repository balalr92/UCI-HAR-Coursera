#UCI HAR Dataset Analysis

This repo contains an R script that can be used to convert the UCI HAR Dataset into a tidy data set.

Create a R script that does the following

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##R program

The R program that is used for cleaning and tidying is available in the run_analysis.R file.

Source the file in R using the following command and it will automatically download the dataset, perform the transformation, tidy the data and save it in the file tidy_data.txt.

source("run_analysis.R")

The tidy data set can be loaded back into R using the following command

tidy_data <- read.table("tidy_data.txt")

##Data CodeBook

The codebook available in this repo describes the variables, the data, the transformations that are done and the clean up that was performed on the data.