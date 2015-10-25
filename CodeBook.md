#Codebook

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

##Subject and Activity Variables

    Subject: values of 1-30; each identify an individual that participated in the original study
    Activity: the activity the observed individual performed; a total of 6 different activities have been observed for each individual

##Feature Variables

The original variables come from the accelerometer and gyroscope 3-axial raw signals timeAcceleraion-XYZ and timeGyroscope-XYZ. The variable is either a "time domain signal", indicated by the prefix 'time', or a "frequency domain signals", indicated by the prefix 'frequency'.

The original time domain signals were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (timeBodyAcceleration-XYZ and timeGyroscopeAcceleration-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (timeBodyAccelerationJerk-XYZ and timeBodyGyroscopeJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (timeBodyAccelerationMag, timeGravityAccelerationMag, timeBodyAccelerationJerkMag, timeBodyGyroscopeMag, timeBodyGyroscopeJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing frequencyBodyAcceleration-XYZ, frequencyBodyAccelerationJerk-XYZ, frequencyBodyGyroscope-XYZ, frequencyBodyAccelerationJerkMag, frequencyBodyGyroscopeMag, frequencyBodyGyroscopeJerkMag. (frequency domain signals).

These signals were used to estimate variables of the feature vector for each pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

Each of these variables contains the average of each variable for each activity and each subject of the original data. Each variable contains either the mean or the standard deviation of the original variable.

    timeBodyAccelerationMeanX
    timeBodyAccelerationMeanY
    timeBodyAccelerationMeanZ
    timeBodyAccelerationStdX
    timeBodyAccelerationStdY
    timeBodyAccelerationStdZ
    timeGravityAccelerationMeanX
    timeGravityAccelerationMeanY
    timeGravityAccelerationMeanZ
    timeGravityAccelerationStdX
    timeGravityAccelerationStdY
    timeGravityAccelerationStdZ
    timeBodyAccelerationJerkMeanX
    timeBodyAccelerationJerkMeanY
    timeBodyAccelerationJerkMeanZ
    timeBodyAccelerationJerkStdX
    timeBodyAccelerationJerkStdY
    timeBodyAccelerationJerkStdZ
    timeBodyGyroMeanX
    timeBodyGyroMeanY
    timeBodyGyroMeanZ
    timeBodyGyroStdX
    timeBodyGyroStdY
    timeBodyGyroStdZ
    timeBodyGyroJerkMeanX
    timeBodyGyroJerkMeanY
    timeBodyGyroJerkMeanZ
    timeBodyGyroJerkStdX
    timeBodyGyroJerkStdY
    timeBodyGyroJerkStdZ
    timeBodyAccelerationMagMean
    timeBodyAccelerationMagStd
    timeGravityAccelerationMagMean
    timeGravityAccelerationMagStd
    timeBodyAccelerationJerkMagMean
    timeBodyAccelerationJerkMagStd
    timeBodyGyroMagMean
    timeBodyGyroMagStd
    timeBodyGyroJerkMagMean
    timeBodyGyroJerkMagStd
    frequencyBodyAccelerationMeanX
    frequencyBodyAccelerationMeanY
    frequencyBodyAccelerationMeanZ
    frequencyBodyAccelerationStdX
    frequencyBodyAccelerationStdY
    frequencyBodyAccelerationStdZ
    frequencyBodyAccelerationJerkMeanX
    frequencyBodyAccelerationJerkMeanY
    frequencyBodyAccelerationJerkMeanZ
    frequencyBodyAccelerationJerkStdX
    frequencyBodyAccelerationJerkStdY
    frequencyBodyAccelerationJerkStdZ
    frequencyBodyGyroMeanX
    frequencyBodyGyroMeanY
    frequencyBodyGyroMeanZ
    frequencyBodyGyroStdX
    frequencyBodyGyroStdY
    frequencyBodyGyroStdZ
    frequencyBodyAccelerationMagMean
    frequencyBodyAccelerationMagStd
    frequencyBodyBodyAccelerationJerkMagMean
    frequencyBodyBodyAccelerationJerkMagStd
    frequencyBodyBodyGyroMagMean
    frequencyBodyBodyGyroMagStd
    frequencyBodyBodyGyroJerkMagMean
    frequencyBodyBodyGyroJerkMagStd
