# Neural_Network_Charity_Analysis
## Purpose 
- Using my knowledge of neural networks, I used the charity data CSV file from Alphabet Soup in order to create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results 
### Deliverable 1: Preprocessing Data for a Neural Netowrk Model 
- For Deliverable 1, I preprocessed the dataset in order to compile train, and evaulate the neural netowrk mode used later in the analysis.
  - The variable considered to be the target is the "IS_SUCCESSFUL" columns
  - Variables that can be considered for the model are "APPLICATION_TYPE" as well as the "INCOME_AMT" columns.
  - The cariables that are not considered targets nor features are the "EIN" and "NAME" columns since they do not add anything to our analysis. They were removed during    the preprocessing portion of this analysis.
  
#### Deliverable 1 Merged DataFrame
![merged_df](merged_df.png)

### Deliverable 2: Compile, Train, and Evaluate the Model
- Using my knowledge of Tensorflow, I designed a deep learning model to create a binary classification model that can predict if an Alphabet SOup-funded organization will be sucessful based on the features in the dataset used previously.
  - For my main  model, I had two hidden layers with 100 neurons and 60 neurons respectively. 

#### Deliverable 2: Model Creation 
(insert pictures here)

### Deliverable 3:
  - Unfortunately, I was unable to reach the target model performace despite my attempts to tweak the models functionality. 
    - My first attempt I changed the number of neurons and added a third input layer to my model but kept the same number of epochs.
      - My evaluated accuracy reached 0.69%
    - My second attempt consisted of jus chaging the number of neurons while leaving the everything else unchanged.
      - My accuracy reach 0.53%
    - For my third and final attempt, I just increased the number of epochs while using the same amount of neruons from my second attempt.
      - My accruacy reach 0.69%

### Deliverable 3: First Attempt at Optimization 
(insert pictures here)

### Deliverable 3: Second Attempt at Optimization 
(insert pictures here)

### Deliverable 3: Third Attempt at Optimization 
(insert pictures here)

## Summary 
Overall, the deep learning model had an accuracy of around 53%. Through optimization, I was able to reach an accuracy of 69%. I believe that the loss in accuracy was form overfitting the model. One way to fither otpimize the model by removing more columns that have little or no inpact on the dataset and model. I also think that using other classifiers (such as RandomForestClassifier) can futher optimize the model because the model itself is faster and the number of estimators and tree depth could help with issues like overfitting. 

## Resources
- mlenv
- jupyter notbook
