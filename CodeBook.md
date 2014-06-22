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
6.  There was extracted only the measurements on the mean and standard deviation for each measurement (patterns mean() and std()  ) we craete a second data frame with 81 columns.
7.  The data was ordered by Activity and subject
8. There were used Descriptive names for Activities the label were obtained from file "activity_lables.txt "
   - 1 WALKING
   - 2 WALKING_UPSTAIRS
   - 3 WALKING_DOWNSTAIRS
   - 4 SITTING
   - 5 STANDING
   - 6 LAYING
9. A file called "Tidy_Data_S.txt" was created.
10. The data was labeled with appropiate names that describe de variables for example
  - tBodyAcc was labeled as TimeBodyAcc: Describe Body Acceleration in time
  - tGravityAcc was labeled as TimeGravityAcc: Describe Gravity Acceleration in time
  - tBodyGyro was labeled as  TimeBodyGyr: Describe Body Giroscope in time
