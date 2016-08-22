---
title: "README"
author: "MOHAMMAD SHADAN"
date: "August 23, 2016"
output: html_document
---
###INTRODUCTION

run_analysis.R script is created to perform below 5 tasks :

1. Merge the training and the test sets to create one data set

2. Extract only the measurements on the mean and standard deviation for each measurement

3. Use descriptive activity names to name the activities (Walking, Sitting etc.) in the data set

4. Appropriately labels the Column of data set with understandable names

5. Creates a tidy data set with the average of each variable for each activity and each subject


###EXECUTION

Below steps must be performed before the run_analysis.R script is run : 

**Step 1** : 
Download the zipped file from the [URL](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

**Step 2** : 
Unzip the zipped file

**Step 3** : 
Transfer the below files into the same working directory as the run_analysis.R script. It's better to create a new directory and move all the files to it including the R script.

1. X_train.txt		: Training data set.

2. X_test.txt		: Test data set.					

3. y_train.txt		: Training labels.

4. y_test.txt		: Test labels.

5. subject_train.txt	: Each row identifies the subject who performed the activity (train)

6. subject_test.txt	: Each row identifies the subject who performed the activity (test)

7. features.txt		: List of all features.

8. activity_labels.txt	: Links the class labels with their activity name.


**Step 3** :
Install the reshape2 package if it's not already installed. It can be done using the command install.packages("reshape2") on the R console.

**Step 4** :
After completing the above stpes, you can run the run_analysis.R script

**Output** :
Output of the R script will be a tidy data set named "tidydata.csv" in the same working directory

