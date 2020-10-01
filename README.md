### This documents gather all scripts for the evaluation of Cousera's Getting and Cleaning Data course.




### Goals

As described by Coursera's evaluation:

"The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis"

And I was supposed to follow this instructions:

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Scripts of the project and how they work

The code book is [here](https://github.com/antoniovcm/datasciencecoursera/blob/master/CodeBook.md).
It explains the what is done in this project and has information about the original dataset.

The original dataset utilized is [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).
It is the original dataset that had not suffered any transformation by this author.

The code utilized to run analysis is [here](https://github.com/antoniovcm/datasciencecoursera/blob/master/run_analysis.R).
Running this code you can exactly reproduce what I have done to obtain the tidy dataset.

The result is a tidy dataset located [here](https://github.com/antoniovcm/datasciencecoursera/blob/master/tidyData.txt).
After run the code you get as result this tidy dataset

