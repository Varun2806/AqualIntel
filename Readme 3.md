1. DATA GATHERING
   Gather Data
   Smaller Dimension Plot(Tabular)

2. DATA ANALYSIS

   1. Preliminary analysis
      -Find out the shape(rows\*colmn)
      -Check null values
      -check then info/data of the items
      -describe the data set
      divide into different caters
      -for all null values, fill them the mean values inorder to symmetry out the data sets(Data Cleansing)
      -Check for potability count

   2. Supplementary analysis
      -Plot/Visualise the Potability with the count plot
      -display the ph value with the normal distribution
      -use of hist method to explore the whole dataset

      -heatmap is used to find the co-rellation/symmetry in the figure
      (no such symmetry exists)

      -BOX-PLOT is produced next inorder to cgeck for the out-liers(visible in solid contents), thus this makes the water un-drinkable
      (Keep a check on the solid content and would have to train the model respectively keeping the same in mind);

      -Now Targetting within the model :
      X: Everything except Potability
      Y: Target Feature(Potability)
      This is done for comparison of the target feature with the rest, to train the model further

      -Split the dataset into training and testing using the train-split function
      Role of different Parameters :  
       -X: Independent Features
      -Y: Dependent Feature(Testing Factor)
      -Test-Size: This splits the dataset into training and testing sets, with 20% of the data reserved for testing.
      -Random State: ensures reproducibility
      -Shuffled True: Ensures data shuffling before its splitting
      (IN ALL RETURNS 4 DATA SETS)

3. MODEL TRAINING

   -Decision Tree Classifier
   Define it
   Fit it : learns the parameter from training data C
   Check the model performance based on the test data using the accuracy and recall outcomes

   -Predict only on a single data set, using a particular random input data set

4. HYPER PARAMETER TUNING
