# Image recognition of Currency using Support Vector Machines or SVM 

Support Vector Machines or SVM is one of the Supervised Learning Algorithm. SVM is used in both Regression and as well as Classification. SVM draws a decision boundary which is a hyperplane between any two classes in order to separate them or classify them. Support vectors are the data points, which are closest to the hyperplane. These points will define the separating line better by calculating margins. These points are more relevant to the construction of the classifier.
For image recognition we are using SVM classification.
The dataset for image recongnition of country's currency are China,Indonesia and Norway.
In pynotebook -
Import the System , Data handling and Data Visualization libraries.
Import the Scikit Image library for image processing.And set the working directory for china,Indonesia and Norway datasets separately.
Read all the images in the datasets separately.
Convert the images from RGB images to gray or black and white images and resize the images.
Flatten the image because in multi-dimensional array takes more memory while 1-d takes less memory.
Change the position os axis and the dimensions.Convert the array into a dataframe.
Label the dataframe to the respective dataset.
Repeat the same steps for other 2 datasets.
After creating the 3 dataframes.Combine the 3 dataframes into one dataframe.
Shuffle the dataframes.And assign the dependent values to x variable and independent values to y variable.
Assign the training set and test set .
Perform Principle Component Analysis or PCA for Feature Extraction Technique.
And using the SVM perform the prediction.
Print the predicted images and compare with the test set.
Perform the performance metrics i.e. confusion matrix and accuracy_score.
Confusion matrix is the easiest way to measure the performance of a classification problem where the output can be of two or more type of classes. 
Accuracy_score is defined as the number of correct predictions made as a ratio of all predictions made.


# Group Members Name:
 1.AARTHY.k
 2.SRIMATHY
