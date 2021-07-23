# Code Book for the final project of Getting and Cleaning Data

1. Load required pakages, in this case, I used the **library dplyr**.
  
2. Then I downloaded and unzipped the dataset provided.
    
3. Then assigned all the dataframes , i.e., features, activities, subject_test, x_test, y_test, subject_train, x_train and y_train.
    
4. Using **rbind**, x_train and x_test is merged; y_train and y_test is merged; and subject_train and subject_test is merged. 

5. Using **cbind**, subject, X and Y are merged into the merged_dataset.

6. Extract only the mean and standard deviation for each measurement, then use descriptive activity names to name the activities inside the datasets.
    
7.  Then create an independent tidy dataset with the average of each variable for each activity and subject.
    
    
    
## Varibles used:
    features <- features.txt file
    activities <- activity_labels.txt file
    subject_test <- subject_test.txt file
    x_test <- X_test.txt
    y_test <- Y_test.txt
    subject_train <- subject_train.txt 
    x_train <- train/X_train.txt
    y_train <- train/y_train.txt
