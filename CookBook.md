---
title: "CookBook"
author: "MOHAMMAD SHADAN"
date: "August 23, 2016"
output: html_document
---
### OVERVIEW

The data for the this project represent data collected from the accelerometers from the Samsung Galaxy S II smartphone.

The experiments have been carried out with a group of **30 volunteers** within an age bracket of 19-48 years

Each person performed **six activities** (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone

For each record in the dataset it is provided : 

* Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 

* Triaxial Angular velocity from the gyroscope. 

* A **561-feature** vector with time and frequency domain variables. 

* Its activity label. 

* An identifier of the subject who carried out the experiment.


### DATASETS
The data was downloaded from the [link](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

For the purposes of this project, the files in the Inertial Signals folders are not used. 

  The 8 data files that will be used to load data are listed as follows.
  
`activity_labels.txt` : IDs and Names for each of the 6 activities 

* WALKING 
* WALKING UPSTAIRS 
* WALKING DOWNSTAIRS 
* SITTING 
* STANDING 
* LAYING

`features.txt` : Names of the 561 features.

`X_train.txt`	: Measurements for 21 of the 30 volunteers, 7352 observations for 561 features.

`X_test.txt`	: Measurements for 9 of the 30 volunteers, 2947 observations for 561 features.

`y_train.txt`	: Vector of 7352 integers, containing activity ID for each observations in X_train.txt.
  			                   
`y_test.txt`	: Vector of 2947 integers, containing activity ID for each observations in X_test.txt.
			                   
`subject_train.txt`	: Vector of 7352 integers, containing subject ID of Volunteers related to each of the observations in X_train.txt.
  			                   
`subject_test.txt` : Vector of 2947 integers, containing subject ID of Volunteers related to each of the observations in X_test.txt.



