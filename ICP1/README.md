# ICP-5

#### Complete the following:
```
Name: Vinay Reddy Kalluri
Email: vk9ry@umsystem.edu
```
---
```
Partner Name: Karthik Yanagandula
Partner  Email: kyb8k@umsystem.edu
Partner ICP-Link: https://github.com/UMKC-APL-PythonDeepLearing/icp_5-kar-gits

```
### SUBMIT PYTHON NOTEBOOK FILE (ipynb file):

```
Video Link: https://youtu.be/pv1sxuyjqzA 
```
<br/>
 
Write a brief explanation here:

1. Machine Learning algorithms on Titanic Dataset
	* Imported the necessary libraries from NumPy, pandas, matplotlib, seaborn which are used for numerical operations, data analysis, and visualization.
	* Loading data from CSV files for training and testing using Pandas data frame.
	* Printed the Training and Testing Data
	* Printed the columns and data types using info which will give a high-level view about the data set for further analysis as part of data processing
	* Framed correlation between "Survived" and "Sex". It showed there is a significant chance of survival if the sex is female which is extracted from this correlation.
	* It is decided to keep this correlation when final preparation data for training.
	* Visualizations were done for survived - age and survived - sex.
	* Dropped passenger ID from training data because of no importance of feature engineering.
	* Combined the training and testing to find the null in age and replace them with mean and convert them into Int from float for the feature.
	* Embarked - Common Value setting as S, if it is Null.
	* Fare value set as 0 if null and converted data type to int.
	* Converted gender values to binary for male and female for simple feature engineering which will have 0 and 1 as final values.
	* Dropped the "Ticket" column from training, testing data because of no importance of feature engineering.
	* Mapped "Embarked" char values with 0, 1, 2 which will be easy for survival prediction.
	* Mapped "Age" converted to int and values with 1, 2, 3, 4, 5, 6 for age groups which will be easy for survival prediction.
	* Dropped the "name" column and derived Title from the name based on a prefix which will be helpful as a feature.
	* Dropped the "cabin" as no importance as a feature.
	* Imported sklearn algorithms for SVM, KNN, Naïve Bayes operations.
	* From Training data, considered 'Sex', 'Age', 'Pclass','SibSp','Parch','Embarked','Title' all this columns for training and modelled as per the design.
	* Split the data as 80% training and 20% testing data
	* As part of SVM, declared the classifier without tunning, data fit is done between x train and y train.
	* Using classifier predicts x test is passed for Y pred which will have values for prediction.
	* Predicting the result and giving the accuracy of: 80.4
	* Confusion matrix printed for actual and expected predictions.
	* As part of KNN, declared the neighbors as 8, data fit is done between x train and y train.
	* Using knn predicts x test is passed for Y pred which will have values for prediction.
	* Predicting the result and giving the accuracy of 83.57
	* Confusion matrix printed for actual and expected predictions.
	* As part of Naïve Bayes, GaussianNB (It is used in classification and it assumes that features follow a normal distribution) declared the neighbors as 8, data fit is done between x train and y train.
	* Using GaussianNB predicts x test is passed for Y pred which will have values for prediction.
	* Predicting the result and giving the accuracy of 82.02
	* Confusion matrix printed for actual and expected predictions.

2. Machine Learning algorithms on Optical Recognition of Handwritten Digits
	* Imported the necessary libraries from NumPy, pandas, matplotlib, seaborn which are used for numerical operations, data analysis, and visualization.
	* Loaded the digits dataset which is pre-built in sklearn
	* Printed the keys and DESCR of the dataset. which will be given basic info and details about the instances and attributes from the digits dataset.
	* Printed the shape of the images and data keys.
	* Displaying digits 1 - 10.
	* Created feature and target array from digits dataset.
	* Split the data as 80% training and 20% testing data.
	* As part of KNN, declared the neighbors as 7 (Which is found to be giving corrected prediction), data fit is done between x train and y train.
	* Using knn predicts x test is passed for Y pred which will have values for prediction.
	* Predicting the result and giving the accuracy of 93.33
	* Fit and score predicted from KNN.
	* Data plotting is done between the Number of Neighbors and Accuracy.
	* Classification report printed for actual and expected predictions.

3. Machine Learning algorithms on Optical Recognition of Handwritten Digits from Datasource
	* Imported the necessary libraries from NumPy, pandas which are used for numerical operations, data analysis.
	* Preprocessed original TRA and TES files to corresponding CSV without data loss using pandas.
	* Loaded the CSV data as training and testing using pandas.
	* Printed training and testing data for visual understanding.
	* Converted the last column of the data to class as a visual representation of the actual value. which is completely optional.
	* Matrix of independent features and the target label.
	* Fitting the K-NN Classifier model on the training dataset.
	* Predicted the labels.
	* K-Fold Cross Validation applied on the training and testing data.
	* Derived the mean and standard deviation of the accuracies.
	* Classification report on the predicted values derived using KNN.
	* Imported SVM-related libraries SVC and Linear SVC.
	* Declaring the SVC with no tunning.
	* Fitting the data. This is where the SVM will learn.
	* Predicting the result and giving the accuracy.
	* As part of Naïve Bayes, GaussianNB (It is used in classification and it assumes that features follow a normal distribution) declared the neighbors as 8, data fit is done between x train and y train.
	* Using GaussianNB predicts x test is passed for Y pred which will have values for prediction.
	* Predicting the result and giving the accuracy of 81.45
	* Classification report printed for actual and expected predictions.


