
# Assignment - 2  
The data from the csv file is consists of alphabetical letters and float data with a total of 16 features. 
 
Loading Data: 
  
  Importing libraries of OS, Pandas, Numpy are useful for converting libraries extracting data from CSV file. The file is saved in the same working directory but for reasons of misplacing its better using of os.path for accessing the file. The data is imported into data frame with the help of read_csv method from pandas. 

Task -1 : 
Print out count of the A12& A13 columns combined
Using the group by function the below result is generated    


A12         f       t       
A13     g  p  s  g   p   s

A16     338 7 29  287 1   28

Task -2  :

Building a Model

Cleaning data:
 The data is converted into float data where every column consists of float/ int format only. 

The columns are with alphabetical letters re converted into numerical values,  based on their uniqueness  column values and are assigned to the columns .

Defining target of model with the class label values which are assigned from the last column of the data frame. 

Defining removing columns method which is used to remove some columns like id, class label values and changing data as Numpy array for the passing into model. The missing with ‘?’ are identified and replaced with 0. 

Splitting the data into X_train,X_test,Y_train,Y_test  with  the use sklearn libraries of model_selection and use of function train_test_split

Building model :

For Decision tree classifier is used in building the model and it is import from sklearn . Creating an ins -tance for it and fit the data into model passing X_train and y_train.  A decision tree classifier is created and x_test is passed to predict the values. 

Accuracy :

Calculating the accuracy of model with the use of sklearn.metics package and its score is 0.83, the score as the data is randomly split and assigned to the training and test set. 

Task -3 :
There are more in number combination of f and g with ‘-‘ class labels and more repeated of  between the users with a  combination of letters with one column and another with same letters occurring twice. 






