Approach:


<ol type="1"> 
   <li>
      Import the Dataset
   <ol type="i">
      <li>
         Take a look at the dataset
      </li>
      <li>
         Find the input and the output variables
      </li>
      <li>
         We find that this is a case of classification
      </li>
   </ol>
   </li>

   So here we can use Logistic Regression or Random Forest Tree. We will be using both for comparision

   <li>
      Then Since the categorization is done alphabetically not numericallys so label encoder is used
   </li>


   <li>
      Now we have the find the x and the y co-ordinates for this case.
      <ol type="i">
         <li>The x co-ordinate is generall`y the input variables and since after taking a look at the dataset we can see that the columns from 3rd to   32nd could be the input varible                (or the features for the model) </li>
         <li>The y co-ordinate is the "diagnosis" column, but since its alphabetical so we take the converted value from step 2 </li>
      </ol>
   </li>

   <li> At this phase we split the data for training and testing purposes </li>
   for training we use 75% of the data <br> 
   for testing we use 25% of the data

   <li>
      Predefined models will be used for easier calculations and better results
      <ol type="i">
         <li>Logistic Regression</li>
         <li>Random Forest </li>
      </ol>
   </li>

   <li>Models are run to find the accuracy</li>
   <li>Performance is calculated using Confusion Matrix and Testing Accuracy</li>
</ol>
    
