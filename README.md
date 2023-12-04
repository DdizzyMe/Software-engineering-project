# Software-engineering-project
Software Engineering project about loan approval prediction using machine learning in python
This project aims at analyzing and predicting whether a certain customer should be approved loan from the bank or not.
It uses machine learning models to train on user data and prepare predictive models to get closer to automating the loan approval process.

#Features :
1. Loan Approval Prediction based on users input data (atleast 3 relevant input fields)
2. Loan Amount Adjustment to be done by the user so that he can get the loan approved
3. Final Report Generated for all users in a csv file with approved loan users and loan amount

#Prerequesites

Install Python on your machine and Jupyter Notebook to write the code

#Requirement Engineering

1. Data : i have imported customer profile data in a csv file and a anonymus testing data of customers whom we are gonna test the model  on
2. Libraries and Tools : Pandas , Numpy , Seaborn and Sckitlearn machine learning libraries and Flask deployment
3. Domain Knowledge : Require Basic knowledge about user profile in banking and machine learning algorithms like regression classification and clustering
4. Metrics :
   > Mean Squared Error
   > R2 score
   > Confusion Matrix
   > Accuracy Score
   > Precision Score
5. Data Cleaning and Exploration :
   > We use seaborn plots , co-realation and ANNOVA to explore all fields of data
   > We clean data by filling missing values and dropping non required column data
6. Data PreProcessing:
   > We standardize continous data columns by using standard scaler
   > we encode categorical columns by label encoder or onehotencoding
   > once we have preprocessed data for the machine to understand we define our Target Prediction Variable
   > We Split The Training Data into train test splits
7. Model Building :
   > We use classifiction models like KNN, Decision Tree and Random Forests to predict Yes or No Category for approval
   > We Build Regression Models for Loan Amount Prediction : Linesar Regression , Decision Tree Regressor and Random Forest
8. Tuning Models and Deriving Predictions :
   > We Tune Models Based on Confusion Matrix and Precision Score Metrix
   > We use cross validation and other tuning parameters to reduce overfiting
   > Finally we use the testing dataset and derive predictions based on our model
9. Deployment: Deployment is done using Flask and a HTML page


#UML 

