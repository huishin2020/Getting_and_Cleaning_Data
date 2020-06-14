The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

For each record it is provided in tidy_data.txt:
======================================

- Each activity (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING)
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

The tidy_data.txt combined the following records in the following files as the data in at least 561 columns categorized in 561 features:
=========================================================================

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING).

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. Their descriptions are equivalent. 

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

# The variables are listed below:

"subjectNo" 
            Subject Unique ID number
            range from 1-30
            
"activity"  
            6 activities 
            [1] "WALKING"           
            [2] "WALKING_UPSTAIRS"  
            [3] "WALKING_DOWNSTAIRS"
            [4] "SITTING"           
            [5] "STANDING"          
            [6] "LAYING"   
            
 "tBodyAcc-mean()-X"  
            time domain body acceration mean in X- direction 
            range from [-1,1]
            
 "tBodyAcc-mean()-Y"   
            time domain body acceration mean in Y- direction 
            range from [-1,1] 
            
"tBodyAcc-mean()-Z"  
            time domain body acceration mean in z- direction 
            range from [-1,1] 
            
 "tBodyAcc-std()-X"  
            time domain body acceration standard deviation in X- direction 
            range from [-1,1] 
            
 "tBodyAcc-std()-Y"   
            time domain body acceration standard deviation in Y- direction 
            range from [-1,1] 
            
 "tBodyAcc-std()-Z" 
            time domain body acceration standard deviation in Z- direction 
            range from [-1,1]  
            
 "tGravityAcc-mean()-X"  
            time domain gravity acceration mean in X- direction 
            range from [-1,1]  
            
"tGravityAcc-mean()-Y"  
            time domain gravity acceration mean in Y- direction 
            range from [-1,1] 
            
"tGravityAcc-mean()-Z"  
             time domain gravity acceration mean in Z- direction 
            range from [-1,1] 
            
"tGravityAcc-std()-X"  
            time domain gravity acceration standard deviation in X- direction 
            range from [-1,1]   
            
"tGravityAcc-std()-Y"  
            time domain gravity acceration standard deviation in Y- direction 
            range from [-1,1]  
            
"tGravityAcc-std()-Z"  
            time domain gravity acceration standard deviation in Z- direction 
            range from [-1,1]  
            
"tBodyAccJerk-mean()-X"   
            time domain body linear acceleration and angular velocity mean in X- direction 
            range from [-1,1]  
            
"tBodyAccJerk-mean()-Y"    
            time domain body linear acceleration and angular velocity mean in Y- direction 
            range from [-1,1] 
            
"tBodyAccJerk-mean()-Z"   
            time domain body linear acceleration and angular velocity mean in Z- direction 
            range from [-1,1] 
            
"tBodyAccJerk-std()-X"  
            time domain body linear acceleration and angular velocity standard deviation in X- direction 
            range from [-1,1]   
            
"tBodyAccJerk-std()-Y" 
            time domain body linear acceleration and angular velocity standard deviation in Y- direction 
            range from [-1,1] 
            
"tBodyAccJerk-std()-Z"  
            time domain body linear acceleration and angular velocity standard deviation in Z- direction 
            range from [-1,1] 
            
"tBodyGyro-mean()-X"  
            time domain gyroscope acceration mean in X- direction 
            range from [-1,1] 
            
"tBodyGyro-mean()-Y"  
            time domain gyroscope acceration mean in Y- direction 
            range from [-1,1] 
                     
"tBodyGyro-mean()-Z"  
            time domain gyroscope acceration mean in Z- direction 
            range from [-1,1] 
                     
"tBodyGyro-std()-X"  
            time domain gyroscope acceration standard deviation in X- direction 
            range from [-1,1] 
                      
"tBodyGyro-std()-Y"    
            time domain gyroscope acceration standard deviation in Y- direction 
            range from [-1,1] 
                    
"tBodyGyro-std()-Z"   
            time domain gyroscope acceration standard deviation in Z- direction 
            range from [-1,1] 
                     
"tBodyGyroJerk-mean()-X"  
            time domain body linear acceleration and angular velocity mean in X- direction 
            range from [-1,1] 
            
"tBodyGyroJerk-mean()-Y" 
            time domain body linear acceleration and angular velocity mean in Y- direction 
            range from [-1,1] 
                 
"tBodyGyroJerk-mean()-Z"  
            time domain body linear acceleration and angular velocity mean in Z- direction 
            range from [-1,1] 
                
"tBodyGyroJerk-std()-X"  
            time domain body linear acceleration and angular velocity standard deviation in X- direction 
            range from [-1,1] 
                 
"tBodyGyroJerk-std()-Y" 
            time domain body linear acceleration and angular velocity standard deviation in Y- direction 
            range from [-1,1] 
            
"tBodyGyroJerk-std()-Z"  
            time domain body linear acceleration and angular velocity standard deviation in Z- direction 
            range from [-1,1] 
            
"tBodyAccMag-mean()"  
            time domain body linear acceleration Euclidean norm mean 
            range from [-1,1] 
            
"tBodyAccMag-std()"  
            time domain body linear acceleration Euclidean norm standard deviation 
            range from [-1,1] 
                     
 "tGravityAccMag-mean()"   
            time domain gravity linear acceleration Euclidean norm mean 
            range from [-1,1] 
                
 "tGravityAccMag-std()"   
            time domain gravity linear acceleration Euclidean norm standard deviation 
            range from [-1,1] 
                 
"tBodyAccJerkMag-mean()"  
            time domain body linear acceleration and angular velocity Euclidean norm mean 
            range from [-1,1] 
                
"tBodyAccJerkMag-std()"  
            time domain body linear acceleration and angular velocity Euclidean norm standard deviation 
            range from [-1,1] 
                     
"tBodyGyroMag-mean()" 
            time domain body linear and gyroscope Euclidean norm mean 
            range from [-1,1] 
                        
"tBodyGyroMag-std()"  
            time domain body linear and gyroscope Euclidean norm standard deviation 
            range from [-1,1] 
                                
"tBodyGyroJerkMag-mean()"    
            time domain body linear and gyroscope Euclidean norm mean 
            range from [-1,1] 
            
"tBodyGyroJerkMag-std()"   
            time domain body linear and gyroscope Euclidean norm standard deviation 
            range from [-1,1] 
            
          
"fBodyAcc-mean()-X"          
"fBodyAcc-mean()-Y"          
 "fBodyAcc-mean()-Z"          
"fBodyAcc-std()-X"           
"fBodyAcc-std()-Y"           
"fBodyAcc-std()-Z"           
"fBodyAccJerk-mean()-X"      
"fBodyAccJerk-mean()-Y"      
"fBodyAccJerk-mean()-Z"      
"fBodyAccJerk-std()-X"       
"fBodyAccJerk-std()-Y"       
"fBodyAccJerk-std()-Z"       
 "fBodyGyro-mean()-X"         
 "fBodyGyro-mean()-Y"         
"fBodyGyro-mean()-Z"         
"fBodyGyro-std()-X"          
 "fBodyGyro-std()-Y"          
 "fBodyGyro-std()-Z"          
"fBodyAccMag-mean()"         
"fBodyAccMag-std()"          
"fBodyBodyAccJerkMag-mean()" 
"fBodyBodyAccJerkMag-std()"  
"fBodyBodyGyroMag-mean()"    
"fBodyBodyGyroMag-std()"     
"fBodyBodyGyroJerkMag-mean()"
"fBodyBodyGyroJerkMag-std()" 
