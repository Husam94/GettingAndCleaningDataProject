# GettingAndCleaningDataProject
End of course project 

This repository contains the following files:

- `README.md`: Provides an overview of the project and its manipulations
- `tidy_data.txt`: Provides the final tidy data from a series of manipulations of published data.
- `CodeBook.md`: Provides the code book describing the variables used to manipulate data
- `run_analysis.R`: Provides the final R script that was used to create tidy_data.txt

# Creating the tidy data

run.analysis.R is split into MAJOR and MINOR goals to split up the requirements of the project. 
MAJOR GOALS are those that are requested in the assignment. 
These include: 
- Merge the training and the test sets to create one data set.
- Extract only the measurements on the mean and standard deviation for each measurement.
- Use descriptive activity names to name the activities in the data set.
- Appropriately label the data set with descriptive variable names.
- Create a second, independent tidy set with the average of each variable for each activity and each subject.
MINOR GOALS are those that help break down the code. 

This script was created using R version 3.4.2 (2017-09-28). The dplyr function is required. 

# The Data Source 

The data comes from a publically available UCI Machine Learning Repository. In that particular study,
researches logged activity from wearable technoogy (Samsung Galaxy SII on the waist) from 30 particpants,
measuring six activities in total. The accelorometer and the gyroscope in the technology submitted signals that
were processed by applying noise flters and then sampled. 

The researchers randomly split the 30 participants into 2 groups: train and test. The completed
data tidy set combines the results of these two groups as one. 
