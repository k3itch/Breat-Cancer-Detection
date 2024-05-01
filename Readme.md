Approach:

1) Import the Dataset
   <ol type="i">Take a look at the dataset</ol>
   ii) Find the input and the output variables
  iii) We find that this is a case of classification

So here we can use Logistic Regression or Random Forest Tree. We will be using both for comparision

2) Then Since the categorization is done alphabetically not numericallys so label encoder is used

3) Now we have the find the x and the y co-ordinates for this case.
  i) The x co-ordinate is generall`y the input variables and since after taking a look at the dataset we can see that the columns from 3rd to   32nd could be the input varible (or the features for the model)
 ii) The y co-ordinate is the "diagnosis" column, but since its alphabetical so we take the converted value from step 2

4) At this phase we split the data for training and testing purposes
    for training we use 75% of the data
    for testing we use 25% of the data

5) Predefined models will be used for easier calculations and better results
  i) Logistic Regression
 ii) Random Forest 

6) Models are run to find the accuracy

7) Performance is calculated using Confusion Matrix and Testing Accuracy
