# Feature Selection 

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (time_Body_acceleration-XYZ and time_Gravity_acceleration-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (time_Body_accelerationJerk_XYZ and time_Body_GyroJerk_XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (time_Body_accelerationMag, time_Gravity_accelerationMag, time_Body_accelerationJerkMag, time_BodyGyroMag, time_BodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing frequentcy_BodyAcc-XYZ, frequentcy_BodyAccJerk-XYZ, frequentcy_BodyGyro-XYZ, frequentcy_BodyAccJerkMag, frequentcy_BodyGyroMag, frequentcy_BodyGyroJerkMag.

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.


# ID Variables

 1. "subject" - ID of the test subject
 1. "activity_label" - Activity performed (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING and LAYING)

# Averages
 Each row holds the averages for the subject performing the activity.

 1. "time_Body_acceleration_mean_value_X" 
 1. "time_Body_acceleration_mean_value_Y" 
 1. "time_Body_acceleration_mean_value_Z" 
 1. "time_Body_acceleration_standard_deviation_X" 
 1. "time_Body_acceleration_standard_deviation_Y" 
 1. "time_Body_acceleration_standard_deviation_Z" 
 1. "time_Gravity_acceleration_mean_value_X" 
 1. "time_Gravity_acceleration_mean_value_Y" 
 1. "time_Gravity_acceleration_mean_value_Z" 
 1. "time_Gravity_acceleration_standard_deviation_X" 
 1. "time_Gravity_acceleration_standard_deviation_Y" 
 1. "time_Gravity_acceleration_standard_deviation_Z" 
 1. "time_Body_accelerationJerk_mean_value_X" 
 1. "time_Body_accelerationJerk_mean_value_Y" 
 1. "time_Body_accelerationJerk_mean_value_Z" 
 1. "time_Body_accelerationJerk_standard_deviation_X" 
 1. "time_Body_accelerationJerk_standard_deviation_Y" 
 1. "time_Body_accelerationJerk_standard_deviation_Z" 
 1. "time_BodyGyro_mean_value_X" 
 1. "time_BodyGyro_mean_value_Y" 
 1. "time_BodyGyro_mean_value_Z" 
 1. "time_BodyGyro_standard_deviation_X" 
 1. "time_BodyGyro_standard_deviation_Y" 
 1. "time_BodyGyro_standard_deviation_Z" 
 1. "time_BodyGyroJerk_mean_value_X" 
 1. "time_BodyGyroJerk_mean_value_Y" 
 1. "time_BodyGyroJerk_mean_value_Z" 
 1. "time_BodyGyroJerk_standard_deviation_X" 
 1. "time_BodyGyroJerk_standard_deviation_Y" 
 1. "time_BodyGyroJerk_standard_deviation_Z" 
 1. "time_Body_accelerationMag_mean_value" 
 1. "time_Body_accelerationMag_standard_deviation" 
 1. "time_Gravity_accelerationMag_mean_value" 
 1. "time_Gravity_accelerationMag_standard_deviation" 
 1. "time_Body_accelerationJerkMag_mean_value" 
 1. "time_Body_accelerationJerkMag_standard_deviation" 
 1. "time_BodyGyroMag_mean_value" 
 1. "time_BodyGyroMag_standard_deviation" 
 1. "time_BodyGyroJerkMag_mean_value" 
 1. "time_BodyGyroJerkMag_standard_deviation" 
 1. "frequency_Body_acceleration_mean_value_X" 
 1. "frequency_Body_acceleration_mean_value_Y" 
 1. "frequency_Body_acceleration_mean_value_Z" 
 1. "frequency_Body_acceleration_standard_deviation_X" 
 1. "frequency_Body_acceleration_standard_deviation_Y" 
 1. "frequency_Body_acceleration_standard_deviation_Z" 
 1. "frequency_Body_accelerationJerk_mean_value_X" 
 1. "frequency_Body_accelerationJerk_mean_value_Y" 
 1. "frequency_Body_accelerationJerk_mean_value_Z" 
 1. "frequency_Body_accelerationJerk_standard_deviation_X" 
 1. "frequency_Body_accelerationJerk_standard_deviation_Y" 
 1. "frequency_Body_accelerationJerk_standard_deviation_Z" 
 1. "frequency_BodyGyro_mean_value_X" 
 1. "frequency_BodyGyro_mean_value_Y" 
 1. "frequency_BodyGyro_mean_value_Z" 
 1. "frequency_BodyGyro_standard_deviation_X" 
 1. "frequency_BodyGyro_standard_deviation_Y" 
 1. "frequency_BodyGyro_standard_deviation_Z" 
 1. "frequency_Body_accelerationMag_mean_value" 
 1. "frequency_Body_accelerationMag_standard_deviation" 
 1. "frequency_BodyBody_accelerationJerkMag_mean_value" 
 1. "frequency_BodyBody_accelerationJerkMag_standard_deviation" 
 1. "frequency_BodyBodyGyroMag_mean_value" 
 1. "frequency_BodyBodyGyroMag_standard_deviation" 
 1. "frequency_BodyBodyGyroJerkMag_mean_value" 
 1. "frequency_BodyBodyGyroJerkMag_standard_deviation"