Human-Activity-Recogntion

Human activity recognition, or HAR, is a challenging time series classification task. It involves predicting the movement of a person based on sensor data and traditionally involves deep domain expertise and methods from signal processing to correctly engineer features from the raw data in order to fit a machine learning model.

This is a multi-class classification problem wherein the activity of the user has to be classified into 6 different categories. The dataset has been collected by the experiments carried out with a group of 30 volunteers within an age bracket of 19-48 years, where each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz were captured. The resulting dataset thus has 561 attributes and over 3500 observations, making dimensionality reduction an essential part of this project.

Dataset link :
https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition

Tools Required
The code in this repository is created using Python 3.6. Furthermore, following libraries are required to run the code provided in this repository:

Numpy
Matplotlib
Pandas
sklearn
