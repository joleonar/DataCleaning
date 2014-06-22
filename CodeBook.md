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
5. The files x_test.txt (with data) y_test.txt (with the Activity performed) and s_test.txt (the subject) were joined in one data frame. Same for trainig data the both data frame were joines in one data.frame called Data_set (10299 rows, 563 columns). The firts two column contain Subjec and Activity variables the rest 561 column are the variables coontained in the file "features.txt".
