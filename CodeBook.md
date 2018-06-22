# Variables 
- Activity (Actions of subjects tested) 
  - WALKING
  - WALKING_UPSTAIRS 
  - WALKING_DOWNSTAIRS 
  - SITTING
  - STANDING
  - LAYING

Transformations 
Original data is located: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The following manipulations were done: 
  - Marged training and test sets together 
  - Only those measurements of mean and standard deviation were kept
  - Activity identifiers were replaced with descriptive (see variables) 
  - Varible names were replaced using following: 
      f expanded to Frequency 
      t expanded to Time 
      Acc, Gyro, Mag, mean, std changed to Accelerometer, Gyroscope, Magnitude, Mean, and StandardDeviation
  - Final data set contained the means of each variable grouped by activity 
