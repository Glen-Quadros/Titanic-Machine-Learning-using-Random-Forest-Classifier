# Titanic-Machine-Learning-using-Random-Forest-Classifier

This project is from kaggle and the training and testing dataset was downloaded from kaggle.

In this project, I read the train.csv file using pandas python library. I then proceed to check if the dataset has any sort of missing data, I then fill in the missing data using the average value. I split the dataframe into training and testing data using the train_test_split. 

I use the Random Forest Classifier Machine Learning model and proceed to make predictions using the ML model. I import classification_report and plot_confusion_matrix in order to check the accuracy of the model.

After that, I read in the test.csv file and proceed to drop unnecessary columns. I fill in the missing values and then make the final predictions based on the test.csv data. I finally import gender_submission.csv and save the prediction values to this file and then export the file.
