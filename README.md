# CA05 – Logistic Regression 
## Data Source and Contents 

Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients collected from a 15 year heart study cohort is made available for this assignment. The dataset has 16 patient features. Note that none of the features include any Blood Test information.

The dataset is obtained from NSRR Sleep Heart Health Study and is found at the following url in csv format: 

"https://github.com/ArinB/CA05-B-Logistic-Regression/raw/master/cvd_data.csv”, a Github location. Use the GitHub link in 
your Python code to “read” the data into a Data-frame. 

        cardiodis = pd.read_csv('https://github.com/ArinB/CA05-B-Logistic-Regression/raw/master/cvd_data.csv') 

Other content includes: 

1. logistic_regression_answers.docx -> Word Document with answers to given questions 

----------------------------------------------------------------------------------------- 
## Computer Assignment Road Map

**Part 1:** Building a binary classifier model to predict the CVD risk (Yes[1]/No[0])

    1. Read in data and import necessary packages 
    2. EDA 
    3. Assign columns to represent independent variables (x) and dependent variable (y)
    4. Split into train and test data 
    5. Implement model  

**Part 2:** Feature importance 

    1. Create new dataframe with (x) variables as the columns and the absolute value coefficients of said variables
    2. Sort them in descending order 

**Part 3:** Evaluate Performance of the model 

    1. Outputs: 
      a. Accuracy Score
      b. Confusion Matrix
      c. F1-Score, Precision, & Recall
      d. AUC Score
      e. Display ROC curve visualization with AUC score 

-----------------------------------------------------------------------------------------
## Additional Comments 
Google Colab File has been linked to this repository.  However, should you make any adjustments, create a copy of your own to edit. 
