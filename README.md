This is the project created for CourseEra for getting and cleaning data.run_analysis.R will perform the following steps

Download the dataset if it does not already exist in the working directory
get the  activity and features information
Loads training and test datasets
filters based on some columns as specified
Loads the activity and subject data for each dataset
Merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result would subsequently be stored in the file tidy.txt using the write table.
