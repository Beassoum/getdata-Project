# Code Book
Bellow are the 68 variables in the tidy data:

[1] "label"                "subject"              "tBodyAccMeanX"       
 [4] "tBodyAccMeanY"        "tBodyAccMeanZ"        "tBodyAccStdX"        
 [7] "tBodyAccStdY"         "tBodyAccStdZ"         "tGravityAccMeanX"    
[10] "tGravityAccMeanY"     "tGravityAccMeanZ"     "tGravityAccStdX"     
[13] "tGravityAccStdY"      "tGravityAccStdZ"      "tBodyAccJerkMeanX"   
[16] "tBodyAccJerkMeanY"    "tBodyAccJerkMeanZ"    "tBodyAccJerkStdX"    
[19] "tBodyAccJerkStdY"     "tBodyAccJerkStdZ"     "tBodyGyroMeanX"      
[22] "tBodyGyroMeanY"       "tBodyGyroMeanZ"       "tBodyGyroStdX"       
[25] "tBodyGyroStdY"        "tBodyGyroStdZ"        "tBodyGyroJerkMeanX"  
[28] "tBodyGyroJerkMeanY"   "tBodyGyroJerkMeanZ"   "tBodyGyroJerkStdX"   
[31] "tBodyGyroJerkStdY"    "tBodyGyroJerkStdZ"    "tBodyAccMagMean"     
[34] "tBodyAccMagStd"       "tGravityAccMagMean"   "tGravityAccMagStd"   
[37] "tBodyAccJerkMagMean"  "tBodyAccJerkMagStd"   "tBodyGyroMagMean"    
[40] "tBodyGyroMagStd"      "tBodyGyroJerkMagMean" "tBodyGyroJerkMagStd" 
[43] "fBodyAccMeanX"        "fBodyAccMeanY"        "fBodyAccMeanZ"       
[46] "fBodyAccStdX"         "fBodyAccStdY"         "fBodyAccStdZ"        
[49] "fBodyAccJerkMeanX"    "fBodyAccJerkMeanY"    "fBodyAccJerkMeanZ"   
[52] "fBodyAccJerkStdX"     "fBodyAccJerkStdY"     "fBodyAccJerkStdZ"    
[55] "fBodyGyroMeanX"       "fBodyGyroMeanY"       "fBodyGyroMeanZ"      
[58] "fBodyGyroStdX"        "fBodyGyroStdY"        "fBodyGyroStdZ"       
[61] "fBodyAccMagMean"      "fBodyAccMagStd"       "fBodyAccJerkMagMean" 
[64] "fBodyAccJerkMagStd"   "fBodyGyroMagMean"     "fBodyGyroMagStd"     
[67] "fBodyGyroJerkMagMean" "fBodyGyroJerkMagStd" 

In the fitures_info.txt file provide with the data set, we can read following inforaion:
"The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.
These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz.
Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz 
to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals 
(tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 
Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals 
(tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using 
the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 
Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, 
fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 
These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions."
