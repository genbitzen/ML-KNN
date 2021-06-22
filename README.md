# ML-KNN

A completed version on ML KNN modelling on Heart Attack Database. 
The project was to use 3 different model algorithms on 1 database to find the best efficiency each model is capable of.
I was tasked with K-Nearest Neighbour(KNN)  
Below is a brief rundown of my thought process.

- Importing the dataset (.csv) into Jupyter.
- Using .info() to examine all columns, datatype and non-null values.
(Assuming the dataset is clean, as it is being checked during the exploration of dataset)
- Extract y value ( the value we want to predict ) 
- Extract x value ( values used to predict ) 
- Using Standard Scalar to normalize data with different units. 
- Using  a for loop, look for the maximum accuracy that we can achieve on this current settings (hyper parameters) 
- Find the optimised K-Values
- Tweaked Train_Test_Split( test size )
- Use Correlation mapping to find the features that affects the predicted value the most. 
- Experiment with different number of features to predict Y. 

- The result is an analysis of different features and different test_Sizes resulting in differences  in test.training accuracy.
- The aim is to look for a high test accuracy with a somewhat similar accuracy on the training data. That would mean we achieved a balance 
and is neither overfitting or underfitting.
