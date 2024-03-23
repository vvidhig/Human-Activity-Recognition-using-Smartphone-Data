# Human-Activity-Recognition-using-Smartphone-Data
<hr>

## Experiment
<p>Description of experiment
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.</p>
<hr>

## Project Description

<p>This project aims to recognize human activities using smartphone sensor data, including accelerometers and gyroscopes. By analyzing this data, a machine learning model is developed to accurately classify activities like walking, running, sitting, and standing. Algorithms like KNN, SVM, Decision Tree and Random Forest are employed to achieve high accuracy and real-time performance. The project showcases the potential of machine learning in utilizing sensor data from everyday devices to enhance applications like fitness tracking, health monitoring, and gesture recognition, thereby improving user experiences.</p>

<hr>
## Notebook - Table of Content
<p>
<h3>Importing necessary libraries</h3>
<h3>Loading data</h3>
<h3>Data preprocessing</h3>
  Checking for duplicates<br>
  Checking for missing values<br>
  Checking for class imbalance<br>
<h3>Exploratory Data Analysis</h3>
  Analysing tBodyAccMag-mean feature<br>
  Analysing Angle between X-axis and gravityMean feature<br>
  Analysing Angle between Y-axis and gravityMean feature<br>
  Visualizing data using t-SNE<br>
<h3>Model Prediction and Evaluation</h3>
  Logistic regression model with Hyperparameter tuning and cross validation<br>
  Linear SVM model with Hyperparameter tuning and cross validation<br>
  Kernel SVM model with Hyperparameter tuning and cross validation<br>
  Decision tree model with Hyperparameter tuning and cross validation<br>
  Random forest model with Hyperparameter tuning and cross validation<br>
</p>
