# Campus-recruitment
predict whether the student is getting placed or not in campus drive by using Machine learning algorithm.
Abstract and Figures:
  1.Each student dreams of having a work offer in their hands before leaving college.
  2.A selection probability indicator lets students get an sense of where they're standing and what to do to ensure a decent selection.
  3.A placement project that can forecast the probability or form of business that a student in the pre-final year has chances of placing. 
  4.While a forecasting project could help in the academic preparation of an institution for future years.
  5.With the emergence of data mining and machine learning, through analyzing the data set of the previous student year, numerous predictive models were applied. 

Steps Involved in Data Cleaning & Preprocessing:
Step 1: Importing Necessary libraries
Step 2: Importing dataset from local directory
Step 3: Using unique to show what are the unique value present in each column
Step 4: To check any null values are present in our dataset
Step5: Drop unnecessary columns (these column does not affect out target, if we delete these column) in permanently.
Step 6: To check any outliers are present in our dataset by using BoxPlot. If any outliers are present we have to replace or remove outlier using IQR method.
Step 7: Using countplot we have to know how many students are getting placed and how many male and female students are placed or not.
Step 8: Using heat map and pairplot, To check  how to correlate with each column in our dataset.
Step 9: we need to convert our categorical value into numerical value so we use LabelEncoder and Get_dummies to covert our dataset.

Building Machine Learning Model:

We have to split our input(Independent) and target variable (Dependent).
Using ExtraTreesRegressor, we find which feature is closest or important in our target output.
We use standardscaler to the values are modified and lies between 0 to 1.because the variation of values is high.
Now, we have to import necessary libraries for building a machine learning model.
We use traintestsplit and it is used to estimate the performance of machine learning algorithm.
Now we use LogisticRegression, Decisiontree  for predicting our dataset. We find Classification report for getting Precision, Recall and Confusion matrix(TP,TN,FP,FN) and Accuracy Score(It show how much of percentage your prediction is correct) of our dataset.
Now we have to check our test input using model testing and check whether the student is getting placed or not.

Conclusion:
After Analysis of data I can conclude that whether the students are getting placed depends upon their individual knowledge, Degree percentage and work Experience..


