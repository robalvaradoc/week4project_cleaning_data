# Tidy_data_Means set description

### The variables in the tidy data
Tidy data contains 180 observations and 88 variables. 

### What the data represent?
The data was grouped by Subject.ID and by Activity to calculate the mean of all the columns.

Subject.ID column is numbered sequentially from 1 to 30. Activity column has 6 types as listed below.
1.	WALKING
2.	WALKING_UPSTAIRS
3.	WALKING_DOWNSTAIRS
4.	SITTING
5.	STANDING
6.	LAYING

### Variable classes
Subject.ID is an integer class
Activity is a character class
The rest of the Variables are numeric.
 
### Listed Variables
 [1] "Subject.ID"                                            
 [2] "Activity"                                              
 [3] "Time.BodyAccelerometer..mean...X"                      
 [4] "Time.BodyAccelerometer..mean...Y"                      
 [5] "Time.BodyAccelerometer..mean...Z"                      
 [6] "Time.GravityAccelerometer..mean...X"                   
 [7] "Time.GravityAccelerometer..mean...Y"                   
 [8] "Time.GravityAccelerometer..mean...Z"                   
 [9] "Time.BodyAccelerometer.Jerk.mean...X"                  
[10] "Time.BodyAccelerometer.Jerk.mean...Y"                  
[11] "Time.BodyAccelerometer.Jerk.mean...Z"                  
[12] "Time.BodyGyroscope..mean...X"                          
[13] "Time.BodyGyroscope..mean...Y"                          
[14] "Time.BodyGyroscope..mean...Z"                          
[15] "Time.BodyGyroscope.Jerk.mean...X"                      
[16] "Time.BodyGyroscope.Jerk.mean...Y"                      
[17] "Time.BodyGyroscope.Jerk.mean...Z"                      
[18] "Time.BodyAccelerometer.Magnitude..mean.."              
[19] "Time.GravityAccelerometer.Magnitude..mean.."           
[20] "Time.BodyAccelerometer.JerkMagnitude..mean.."          
[21] "Time.BodyGyroscope.Magnitude..mean.."                  
[22] "Time.BodyGyroscope.JerkMagnitude..mean.."              
[23] "Frequency.BodyAccelerometer..mean...X"                 
[24] "Frequency.BodyAccelerometer..mean...Y"                 
[25] "Frequency.BodyAccelerometer..mean...Z"                 
[26] "Frequency.BodyAccelerometer..meanFreq...X"             
[27] "Frequency.BodyAccelerometer..meanFreq...Y"             
[28] "Frequency.BodyAccelerometer..meanFreq...Z"             
[29] "Frequency.BodyAccelerometer.Jerk.mean...X"             
[30] "Frequency.BodyAccelerometer.Jerk.mean...Y"             
[31] "Frequency.BodyAccelerometer.Jerk.mean...Z"             
[32] "Frequency.BodyAccelerometer.Jerk.meanFreq...X"         
[33] "Frequency.BodyAccelerometer.Jerk.meanFreq...Y"         
[34] "Frequency.BodyAccelerometer.Jerk.meanFreq...Z"         
[35] "Frequency.BodyGyroscope..mean...X"                     
[36] "Frequency.BodyGyroscope..mean...Y"                     
[37] "Frequency.BodyGyroscope..mean...Z"                     
[38] "Frequency.BodyGyroscope..meanFreq...X"                 
[39] "Frequency.BodyGyroscope..meanFreq...Y"                 
[40] "Frequency.BodyGyroscope..meanFreq...Z"                 
[41] "Frequency.BodyAccelerometer.Magnitude..mean.."         
[42] "Frequency.BodyAccelerometer.Magnitude..meanFreq.."     
[43] "Frequency.Body.Accelerometer.JerkMagnitude..mean.."    
[44] "Frequency.Body.Accelerometer.JerkMagnitude..meanFreq.."
[45] "Frequency.Body.Gyroscope.Magnitude..mean.."            
[46] "Frequency.Body.Gyroscope.Magnitude..meanFreq.."        
[47] "Frequency.Body.Gyroscope.JerkMagnitude..mean.."        
[48] "Frequency.Body.Gyroscope.JerkMagnitude..meanFreq.."    
[49] "Angle..TimeBody.Accelerometer.Mean.Gravity.."          
[50] "Angle..TimeBody.Accelerometer.JerkMean..Gravity.Mean." 
[51] "Angle..TimeBody.Gyroscope.Mean.Gravity.Mean."          
[52] "Angle..TimeBody.Gyroscope.JerkMean.Gravity.Mean."      
[53] "Angle..X.Gravity.Mean."                                
[54] "Angle..Y.Gravity.Mean."                                
[55] "Angle..Z.Gravity.Mean."                                
[56] "Time.BodyAccelerometer..std...X"                       
[57] "Time.BodyAccelerometer..std...Y"                       
[58] "Time.BodyAccelerometer..std...Z"                       
[59] "Time.GravityAccelerometer..std...X"                    
[60] "Time.GravityAccelerometer..std...Y"                    
[61] "Time.GravityAccelerometer..std...Z"                    
[62] "Time.BodyAccelerometer.Jerk.std...X"                   
[63] "Time.BodyAccelerometer.Jerk.std...Y"                   
[64] "Time.BodyAccelerometer.Jerk.std...Z"                   
[65] "Time.BodyGyroscope..std...X"                           
[66] "Time.BodyGyroscope..std...Y"                           
[67] "Time.BodyGyroscope..std...Z"                           
[68] "Time.BodyGyroscope.Jerk.std...X"                       
[69] "Time.BodyGyroscope.Jerk.std...Y"                       
[70] "Time.BodyGyroscope.Jerk.std...Z"                       
[71] "Time.BodyAccelerometer.Magnitude..std.."               
[72] "Time.GravityAccelerometer.Magnitude..std.."            
[73] "Time.BodyAccelerometer.JerkMagnitude..std.."           
[74] "Time.BodyGyroscope.Magnitude..std.."                   
[75] "Time.BodyGyroscope.JerkMagnitude..std.."               
[76] "Frequency.BodyAccelerometer..std...X"                  
[77] "Frequency.BodyAccelerometer..std...Y"                  
[78] "Frequency.BodyAccelerometer..std...Z"                  
[79] "Frequency.BodyAccelerometer.Jerk.std...X"              
[80] "Frequency.BodyAccelerometer.Jerk.std...Y"              
[81] "Frequency.BodyAccelerometer.Jerk.std...Z"              
[82] "Frequency.BodyGyroscope..std...X"                      
[83] "Frequency.BodyGyroscope..std...Y"                      
[84] "Frequency.BodyGyroscope..std...Z"                      
[85] "Frequency.BodyAccelerometer.Magnitude..std.."          
[86] "Frequency.Body.Accelerometer.JerkMagnitude..std.."     
[87] "Frequency.Body.Gyroscope.Magnitude..std.."             
[88] "Frequency.Body.Gyroscope.JerkMagnitude..std.."

