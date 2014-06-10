Getting and Cleaning Data Project
=========================

The run_analysis.R script uses original data sourced from the following URL:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The script merges the train and test data sets, assigns descriptive activity names for each of the activities performed, labels the data set with appropriate variable names, subsets for the columns pertaining to the mean and standard deviation for each reading, and then outputs a new file with the mean for each feature across all readings for each subject and each activity.

Instructions to replicate are as follows:


1. Extract following .zip file to your working directory: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

    You should now have a path similar to C:\Users\your-name\working-directory\getdata_projectfiles_UCI HAR Dataset

2. Run the run_analysis.R script.

3. This will create a file named tidy_data.txt in your working directory.

Additional detail on variables can be found in the Codebook document.

