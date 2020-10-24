# Customer-Churn-Predictability-for-Banking-System (Kaggle Dataset)


### Aim of the project: 

#### To correctly identify the customers who will be churning based on the given factors (minimize False negative i.e., reducing the number of cusotmers who are incorrectly classified as non churning customers)

### Implementation: 

#### 1. Visualized the target variable to identify the propportion of imbalance in the dataset
#### 2. Visualized the independent variables using Seaborn package to check the variance in the tagrget variable based on these independent variables
#### 3. Performed #Kruskal Wallis H Test to determine the relation between a categorical varaible (target) and continuous variables (independent variables)
#### 4. Check for variability in the variables of the dataset using pairplot in seaborn
#### 5. Performed Exploratory Data Analysis to identify the influencing features in the dataset with respect to the target variable
#### 6. Implemented Feature Engineering and created dummy variables of those variables that in influence the target variable
#### 7. Normalized the features in the dataset and implemented heatmap to check for multicollinearity between the independent variables
#### 8. Deployed ML models (Logistic Regression, SVM, Random Forest, XGBoost) & performed hyper paramter tuning using GridSearch CV
#### 9. Implemented RFECV with best parameters to check the optimal number of predictors required for prediction
#### 10. Upsampled and Downsampled the dataset using SMOTE to remove the imbalance in the dataset
#### 11. Implemented Data Pipeline and fitted the hyperparameters tuned ML models on the upsampled and downsampled dataset


### Conclusion:

#### The best F1-Score for the Churned=1 i.e churning customers is obtained after applying hyperparamters tuned XGBoost model on downsampled dataset

