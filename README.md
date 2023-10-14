# Diabetes_Prediction_Project

We have built a machine learning system that can predict whether a person has diabetes or not. We are using a machine learning algorithm called Support Vector Machine. The support vector machine model is a supervised learning algorithm where we feed the data to our machine learning model and the machine learning model learns from the data and its respective labels. 
We train our model with several medical information such as the BMI of the patient, their blood glucose level, and the insulin level along with whether the person has diabetes or not, so these act as labels.
Once we feed this data to our support vector machine model, it tries to plot the data in a graph and finds a hyperplane. This hyperplane separates the data.
Firstly, we have imported all the dependencies. 
•	We have imported numpy for making arrays and
•	pandas for creating the data frame. 
•	We have the StandardScaler function to stabilize the data. 
•	We add a train_test_split to split our data into training and test data. 
•	We have imported the support vector machine model(svm) from sklearn.
•	 We have imported this accuracy_score for evaluating our model.
Now, we load our data set which is in a csv file to a pandas data frame.
We analyze the data by taking the first 5 rows and then find that our dataset has 9 columns and 768 rows.
Then, we count the number of values for diabetic cases and non-diabetic cases and here the label 0 represents the person who doesn't have diabetes and 1 represents those who have diabetes.
Now we find the mean values for patients with diabetes and non-diabetes. We observe that people with diabetes usually have high glucose levels and are aged.
We now standardize all this data because it was in a different range. 
After that, we split the data into training data and test data. So, we take 20% test data and we load our model support vector machine classifier into the variable classifier.
We train our machine learning model with the help of X_train and their respective labels Y_train.
So, once we obtain the model we find the accuracy score on both the training data and the test data. When we have a good accuracy score we make a predictive system that can predict whether a person has diabetes or not with the help of this input data.
