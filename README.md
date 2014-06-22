DataCleaning
============

Course Data Cleaning coursera

I have created one script ("Project_01.R") for project of Data Clening Course, 
the script is separated y 5 parts, that does the following:

* 1.  Merges the training and the test sets to create one data set.
* 2.  Extracts only the measurements on the mean and standard deviation for each measurement. 
* *3.  Uses descriptive activity names to name the activities in the data set
4.  Appropriately labels the data set with descriptive variable names. 
5.  Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

En parts 4 and 5 additionally are created  two text files: "Tidy_DataS_1.txt" in part 4 and "Tidy_DataS_2.txt" in part 5.

"Tidy_DataS_1.txt":  is a text file with the training and test data merged with the mesurements of the mean 
and standard deviation of each measurement. Contain  10299 rows and   81 columns. 


"Tidy_DataS_2.txt": is a text file  with the average of the some variables for example
I take the mean of: "TimeBodyAcc-Mean-X","TimeBodyAcc-Mean-Y", "TimeBodyAcc-Mean-Z" and create a new variable called 
"TimeBodyAcc-Mean-XYZ.
