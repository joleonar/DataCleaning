This Code Book describes the variables, the data, and any transformations or work that 
it was performed to clean up the data.


1. Data is located in the directory ./Data_Set
2. In this directory are available data for the train and test data
4. The variables contained in test and train data are the following:
   tBodyAcc-mean()-X
   tBodyAcc-mean()-Y
   tBodyAcc-mean()-Z
   tBodyAcc-std()-X
   tBodyAcc-std()-Y
   .....
  561 variables in total
5. The files "x_test.txt" (with data) "y_test.txt" (with the activity performed) and "s_test.txt" (the subject) were joined in one data frame. Same for trainig data, both data frame were joines in one data.frame called Data_set (10299 rows, 563 columns). The firts two column contain Subjec and Activity variables the rest 561 column are the variables coontained in the file "features.txt".
6.  There was extracted only the measurements on the mean and standard deviation for each measurement (with patterns "mean()" and "std()"  ) we create a second data frame (data_set2) with 81 columns (Activities + Subject + 79 variables)
7. The data was ordered by "Activity" and "Subject" variables; Activity column use numbers "1","2","3" ... for describing activities (data was called data_set3)
8. There were used descriptive names for Activities, the labels were obtained from file "activity_lables.txt "
   - 1 WALKING
   - 2 WALKING_UPSTAIRS
   - 3 WALKING_DOWNSTAIRS
   - 4 SITTING
   - 5 STANDING
   - 6 LAYING

9. The data was labeled with appropiate names that describe the variables for example
  - tBodyAcc was labeled as "TimeBodyAcc": Describe Body Acceleration in time
  - tGravityAcc was labeled as "TimeGravityAcc": Describe Gravity Acceleration in time
  - tBodyGyro was labeled as  "TimeBodyGyr": Describe Body Gyroscope in time
  - fBodyAcc was labeled as "FreqBodyAcc": Describe Body Acceleration in frequency
  - fGravityAcc was labeled as "FreqGravityAcc": Describe Gravity Acceleration in frequency
  - fBodyGyro was labeled as "FreqBodyGyr": Describe Body Giroscope in frequency.
  - X, Y and Z refer to the components X Y and Z of tha variables
  
10. A file called "Tidy_Data_S.txt" was created and uploaded. This file contain 10299 rows and 81 columns as it was described above. (Activities using descriptive names + Subject + 79 variables related with "mean" and "standard deviation"). Data set was labeled set with descriptive variable names. There was found a typo in some of the names (i.e. fBodyBodyAccJerkMag). There was manually changed by fBodyAccJerkMag in "features.txt" file
 
