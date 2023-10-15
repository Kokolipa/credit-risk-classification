# Credit Risk Analysis - Logistic Regression
## Project Overview
Using various techniques to train, evaluate, and identify the creditworthiness of borrowers with logistic regression on the loan and risk historical dataset. 

### About the dataset
Our dataset provides an overview on different clients that submit a loan request; the purpose of the analysis is to determine whether a loan is **"healthy loan" (0)** or **"high-risk loan" (1)** considering all the labels specified in the dataset:
* Loan size
* Interest rate
* Borrower income
* Debt to income 
* Number of accounts
* derogatory_marks
* Total debt

<br>

**Additional info:**
* The credit risk dataset included both linear and non-linear features. Logistic regression can also be implemented on features with a non-linear relationship to the target variable, as values along the axis can be segmented based on the decision boundary. 
* Even though the features of our dataset represent a high correlation with one another, it seems that the features in our dataset will not introduce a significant bias on the logistic regression model. 

#### Machine Learning Process: 
1. Describing the data. 
2. Identifying the correnlation between features. 
3. Checking the linearity relationship between the labels and the target variable.
4. Separating the data into labels and target variables (X, y).
5. Splitting the data into testing and training datasets.
6. Instantiating the logistic regression model. 
7. Fitting the model to the training dataset. 
8. Predicting the results on the testing dataset.
9. Generating the confusion matrix and printing the classification report.



### Classification Report Results:
**Label 0  - Healthy Loan**
1. Precision - The precision 1.0 indicates that when the model predicts a healthy loan, it is correct 100% of the times. 
2. Recall - The recall score is 0.99, suggesting that the model correctly identifies 99% of the actual loans as healthy loans.
3. f1-score - The f1-score is 1, indicating a perfect performance of the model.
<br>

**Label 1 - High-Risk Loan**
1. Precision - The precision is 0.85, indicating that when the model predicts a high-risk loan, it is correct 85% of the times.
2. Recall - The recall score is 0.91, indicating that the model correctly identifies 91% of the actual loans as high-risk loans.
3. f1-score - The f1-score is 0.88, indicating a good performance overall with an accuracy of 88%. 


#### Summary
In summary, the logistic regression model performs exceptionally well predicting healthy and high-risk loans. It demonstrates high precision, recall, and accuracy, making it a reliable model for this classification task. While precision, accuracy and f1 score are high, **recall can be considered as the most crucial parameter** to determining the overall performance of the model as it showcases how the model correctly identifies healthy and high-risk loans, which is the main component of building credibility on the purpose of the analysis (classifying healthy and high-risk loans).

#### Libraries Used
1. Numpy
2. Pandas
3. Seaborn
4. Matplotlib
5. Sklearn


#### Folder structure
``` yml
.
│   ├── Starter_Code 
│   |   ├── Resources   
│   |   |   ├── lending_data.csv  
│   |   ├── credit_risk_classification.ipynb             
|___README.md    
|.gitignore          
``` 
