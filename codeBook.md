The "run_analysis.R" script will complete the following steps, as required by course assignment req.:

Merging the training and the test sets to create one data set including reading files, trainings tables, testing tables, feature vector
activity labels, assigning column names and merging all data in one set
It then extracts the measurements on the mean and standard deviation for each measurement including reading column names, creating vector for defining ID, mean and standard deviation and making nessesary subset from setAllInOne
Using descriptive activity names to name the activities in the data set and appropriately labeling the data set with descriptive variable names

It then creates a second, independent tidy data set with the average of each variable for each activity and each subject
- Making second tidy data set and writing to a text file (that can also be opened as a delimited file in XL)

Run instructions - 
The code assumes all DATA to  be resident  in the DATA folder that is one down to the R-script location

About variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset