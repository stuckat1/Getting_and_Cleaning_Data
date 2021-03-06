#The Code Book™

##Files
All data are stored in a single file named **tidy.txt**.  

## Experimental Study Design

> The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

> The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. 

##Fields
* *subject* - Identifies a particular human subject that carried out an experiment.  A number between 1 and 30.
* *activity* - Describes one of the following activities: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING

The following are numerous mean measurments for a specific *subject* and *activity* and can broken down by the following:  
*  Variables beginning with the letter 't' indicates time domain while the letter 'f' indicates fequency domain.  
*  Acceleration information can be decomposed into body and gravity sub components, 'BodyAcc' and 'GravityAcc', respectively. *  Gyroscopic information is indicated by 'Gyro'.
*  'Mean' is mean value.  'Std' is standard deviation.  'MeanFreq' is weighted average of the frequency components to obtain a mean frequency.
*  'X', 'Y', 'Z' indicates axis of the measurement.  

All features have been normalized and bounded within [-1, 1].

* tBodyAccMeanX 
* tBodyAccMeanY 
* tBodyAccMeanZ 

* tBodyAccStdX 
* tBodyAccStdY 
* tBodyAccStdZ 

* tGravityAccMeanX 
* tGravityAccMeanY 
* tGravityAccMeanZ 

* tGravityAccStdX 
* tGravityAccStdY 
* tGravityAccStdZ 

* tBodyAccJerkMeanX 
* tBodyAccJerkMeanY 
* tBodyAccJerkMeanZ 

* tBodyAccJerkStdX 
* tBodyAccJerkStdY 
* tBodyAccJerkStdZ 

* tBodyGyroMeanX 
* tBodyGyroMeanY 
* tBodyGyroMeanZ 

* tBodyGyroStdX 
* tBodyGyroStdY 
* tBodyGyroStdZ 

* tBodyGyroJerkMeanX 
* tBodyGyroJerkMeanY 
* tBodyGyroJerkMeanZ 

* tBodyGyroJerkStdX 
* tBodyGyroJerkStdY 
* tBodyGyroJerkStdZ 

* tBodyAccMagMean 
* tBodyAccMagStd 

* tGravityAccMagMean 
* tGravityAccMagStd 

* tBodyAccJerkMagMean 
* tBodyAccJerkMagStd 

* tBodyGyroMagMean 
* tBodyGyroMagStd 

* tBodyGyroJerkMagMean 
* tBodyGyroJerkMagStd 

* fBodyAccMeanX 
* fBodyAccMeanY 
* fBodyAccMeanZ
 
* fBodyAccStdX 
* fBodyAccStdY 
* fBodyAccStdZ 

* fBodyAccMeanFreqX 
* fBodyAccMeanFreqY 
* fBodyAccMeanFreqZ 

* fBodyAccJerkMeanX 
* fBodyAccJerkMeanY 
* fBodyAccJerkMeanZ 

* fBodyAccJerkStdX 
* fBodyAccJerkStdY 
* fBodyAccJerkStdZ 

* fBodyAccJerkMeanFreqX 
* fBodyAccJerkMeanFreqY 
* fBodyAccJerkMeanFreqZ 

* fBodyGyroMeanX 
* fBodyGyroMeanY 
* fBodyGyroMeanZ 

* fBodyGyroStdX 
* fBodyGyroStdY 
* fBodyGyroStdZ 

* fBodyGyroMeanFreqX 
* fBodyGyroMeanFreqY 
* fBodyGyroMeanFreqZ 

* fBodyAccMagMean 
* fBodyAccMagStd 
* fBodyAccMagMeanFreq 

* fBodyBodyAccJerkMagMean 
* fBodyBodyAccJerkMagStd 
* fBodyBodyAccJerkMagMeanFreq
 
* fBodyBodyGyroMagMean 
* fBodyBodyGyroMagStd 
* fBodyBodyGyroMagMeanFreq
 
* fBodyBodyGyroJerkMagMean 
* fBodyBodyGyroJerkMagStd 
* fBodyBodyGyroJerkMagMeanFreq
