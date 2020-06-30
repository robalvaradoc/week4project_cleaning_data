#Previous Steps
#Download File
Make sure that in this step you set the working directory to your own folder
#Read the tables in R

This is were we create the variables in R needed to creat the Tidy Data

#Step 1: Merges the training and the test sets to create one data set.
 first we row bind the test and train tables for the x and y users.
 then we do the same wit the x and y subjets
 at last we merge the data biding the columns of the subjects with their corresponding data.
 
 #Step 2: Extracts only the measurements on the mean and standard deviation for each measurement.
Be sure to load the "tidyverse" Library, otherwise the code wont work.
Using this library we choose only the columns that have contain the words "mean" and "std" 

#Step 3: Uses descriptive activity names to name the activities in the data set.
Here we change the codes in the data for their descriptive activity (located in the "activites" variables previusly created

# Step 4: Appropriately labels the data set with descriptive variable names.
We use the gsub and to change the names of the variables to make them more comprehensible.

# Step 5: From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
At last we create the avarage for each activity of each subjetct in the TidyData table.
First we group the data by Subject.ID and by Activity.
Second we summarize all the data using the mean function for each column needed.

