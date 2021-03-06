Output file 'tidy_data.txt' that is produced by run_analysis.R is generated from original data obtained from:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

<ol>
<li>Training data sets and test data sets were merged to create a single data set.</li>
<li>Only measurements on the mean and standard deviation for each measurement were included, ie only column labels that contained 'mean()' or 'std()' were included in the new data set.</li>
<li>Descriptive names were added for activities, and columns were given appropriate variable names.</li>
<li>New data set includes the mean of each reading for each activity and each subject.</li>
</ol>

Variable Descriptions:

subject     
     Subject ID - 1:30        
            
activity         
     One of six activities performed by subjects
     
     WALKING
     WALKING_UPSTAIRS
     WALKING_DOWNSTAIRS
     SITTING
     STANDING
     LAYING

The remaining columns pertain to the mean and standard deviation of accelerometer and gyroscope readings recorded as the subjects
performed the various activities. These values represent the mean of all readings for each subject and activity.
              
     tBodyAcc-mean()-X               
     tBodyAcc-mean()-Y              
     tBodyAcc-mean()-Z               
     tGravityAcc-mean()-X           
     tGravityAcc-mean()-Y            
     tGravityAcc-mean()-Z           
     tBodyAccJerk-mean()-X           
     tBodyAccJerk-mean()-Y          
     tBodyAccJerk-mean()-Z           
     tBodyGyro-mean()-X             
     tBodyGyro-mean()-Y              
     tBodyGyro-mean()-Z             
     tBodyGyroJerk-mean()-X          
     tBodyGyroJerk-mean()-Y         
     tBodyGyroJerk-mean()-Z          
     tBodyAccMag-mean()             
     tGravityAccMag-mean()           
     tBodyAccJerkMag-mean()         
     tBodyGyroMag-mean()             
     tBodyGyroJerkMag-mean()        
     fBodyAcc-mean()-X               
     fBodyAcc-mean()-Y              
     fBodyAcc-mean()-Z                       
     fBodyAccJerk-mean()-X          
     fBodyAccJerk-mean()-Y          
     fBodyAccJerk-mean()-Z             
     fBodyGyro-mean()-X              
     fBodyGyro-mean()-Y             
     fBodyGyro-mean()-Z                   
     fBodyAccMag-mean()                     
     fBodyBodyAccJerkMag-mean()      
     fBodyBodyGyroMag-mean()         
     fBodyBodyGyroJerkMag-mean()     
     tBodyAcc-std()-X                
     tBodyAcc-std()-Y               
     tBodyAcc-std()-Z                
     tGravityAcc-std()-X            
     tGravityAcc-std()-Y             
     tGravityAcc-std()-Z            
     tBodyAccJerk-std()-X            
     tBodyAccJerk-std()-Y           
     tBodyAccJerk-std()-Z            
     tBodyGyro-std()-X              
     tBodyGyro-std()-Y               
     tBodyGyro-std()-Z              
     tBodyGyroJerk-std()-X           
     tBodyGyroJerk-std()-Y          
     tBodyGyroJerk-std()-Z           
     tBodyAccMag-std()              
     tGravityAccMag-std()            
     tBodyAccJerkMag-std()          
     tBodyGyroMag-std()              
     tBodyGyroJerkMag-std()         
     fBodyAcc-std()-X                
     fBodyAcc-std()-Y               
     fBodyAcc-std()-Z                
     fBodyAccJerk-std()-X           
     fBodyAccJerk-std()-Y            
     fBodyAccJerk-std()-Z           
     fBodyGyro-std()-X               
     fBodyGyro-std()-Y              
     fBodyGyro-std()-Z               
     fBodyAccMag-std()              
     fBodyBodyAccJerkMag-std()       
     fBodyBodyGyroMag-std()         
     fBodyBodyGyroJerkMag-std()
