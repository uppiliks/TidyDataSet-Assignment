Getting and Cleaning Data - peer assessment project

The original data was transformed by

Merging the training and the test sets to create one data set.

Extracting only the measurements on the mean and standard deviation for each measurement.

Using descriptive activity names to name the activities in the data set

Appropriately labeling the data set with descriptive activity names.

Creating a second, independent tidy data set with the average of each variable for each activity and each subject.

The data contained in secTidySet.txt is produced using the run_analysis.R script. The data are summarized values of measurements smartphone activity data. The data values are the means values for the subject and activity type. The variable subject refers to the observation person, while the activity type refers to one of 6 activity types that were recorded by the smartphones. Below is list of the variables.

subjectId	

activity

TimeBodyAccelerometerMean()-X

TimeBodyAccelerometerMean()-Y

TimeBodyAccelerometerMean()-Z

TimeBodyAccelerometerSTD()-X

TimeBodyAccelerometerSTD()-Y

TimeBodyAccelerometerSTD()-Z

TimeGravityAccelerometerMean()-X

TimeGravityAccelerometerMean()-Y

TimeGravityAccelerometerMean()-Z

TimeGravityAccelerometerSTD()-X

TimeGravityAccelerometerSTD()-Y

TimeGravityAccelerometerSTD()-Z

TimeBodyAccelerometerJerkMean()-X

TimeBodyAccelerometerJerkMean()-Y

TimeBodyAccelerometerJerkMean()-Z

TimeBodyAccelerometerJerkSTD()-X

TimeBodyAccelerometerJerkSTD()-Y

TimeBodyAccelerometerJerkSTD()-Z

TimeBodyGyroscopeMean()-X

TimeBodyGyroscopeMean()-Y

TimeBodyGyroscopeMean()-Z

TimeBodyGyroscopeSTD()-X

TimeBodyGyroscopeSTD()-Y

TimeBodyGyroscopeSTD()-Z

TimeBodyGyroscopeJerkMean()-X

TimeBodyGyroscopeJerkMean()-Y

TimeBodyGyroscopeJerkMean()-Z

TimeBodyGyroscopeJerkSTD()-X

TimeBodyGyroscopeJerkSTD()-Y

TimeBodyGyroscopeJerkSTD()-Z

TimeBodyAccelerometerMagnitudeMean()

TimeBodyAccelerometerMagnitudeSTD()

TimeGravityAccelerometerMagnitudeMean()

TimeGravityAccelerometerMagnitudeSTD()

TimeBodyAccelerometerJerkMagnitudeMean()

TimeBodyAccelerometerJerkMagnitudeSTD()

TimeBodyGyroscopeMagnitudeMean()

TimeBodyGyroscopeMagnitudeSTD()

TimeBodyGyroscopeJerkMagnitudeMean()

TimeBodyGyroscopeJerkMagnitudeSTD()

FrequencyBodyAccelerometerMean()-X

FrequencyBodyAccelerometerMean()-Y

FrequencyBodyAccelerometerMean()-Z

FrequencyBodyAccelerometerSTD()-X

FrequencyBodyAccelerometerSTD()-Y

FrequencyBodyAccelerometerSTD()-Z

FrequencyBodyAccelerometerMeanFreq()-X

FrequencyBodyAccelerometerMeanFreq()-Y

FrequencyBodyAccelerometerMeanFreq()-Z

FrequencyBodyAccelerometerJerkMean()-X

FrequencyBodyAccelerometerJerkMean()-Y

FrequencyBodyAccelerometerJerkMean()-Z

FrequencyBodyAccelerometerJerkSTD()-X	

FrequencyBodyAccelerometerJerkSTD()-Y

FrequencyBodyAccelerometerJerkSTD()-Z

FrequencyBodyAccelerometerJerkMeanFreq()-X

FrequencyBodyAccelerometerJerkMeanFreq()-Y

FrequencyBodyAccelerometerJerkMeanFreq()-Z

FrequencyBodyGyroscopeMean()-X

FrequencyBodyGyroscopeMean()-Y

FrequencyBodyGyroscopeMean()-Z

FrequencyBodyGyroscopeSTD()-X	

FrequencyBodyGyroscopeSTD()-Y	

FrequencyBodyGyroscopeSTD()-Z	

FrequencyBodyGyroscopeMeanFreq()-X

FrequencyBodyGyroscopeMeanFreq()-Y

FrequencyBodyGyroscopeMeanFreq()-Z

FrequencyBodyAccelerometerMagnitudeMean()

FrequencyBodyAccelerometerMagnitudeSTD()

FrequencyBodyAccelerometerMagnitudeMeanFreq()

FrequencyBodyAccelerometerJerkMagnitudeMean()	

FrequencyBodyAccelerometerJerkMagnitudeSTD()	

FrequencyBodyAccelerometerJerkMagnitudeMeanFreq()

FrequencyBodyGyroscopeMagnitudeMean()	

FrequencyBodyGyroscopeMagnitudeSTD()	

FrequencyBodyGyroscopeMagnitudeMeanFreq()

FrequencyBodyGyroscopeJerkMagnitudeMean()

FrequencyBodyGyroscopeJerkMagnitudeSTD()	

FrequencyBodyGyroscopeJerkMagnitudeMeanFreq()

activityType


To produce the secTidySet.txt data the raw data was collected from UCI Machine Learning Repository. The training and test datasets were combined along with the features and activity labels to provide the column names and activity titles. Once the raw data sets were combined, the data was subset to only the valriables measuring the mean or standard deviation of any feature. The remaining variables were averaged by subject and activity. Some minor changes were made to the variable names to make them more meaningful.
