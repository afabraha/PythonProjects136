# PythonProjects136

This repository showcases my data science projects, demonstrating my skills in Python and machine learning. 

## Projects

### 1. Corporate Finance Data Project
- **Objective**: Developed a Random Forest model to classify companies as High, Medium, or Low Profit.
- **Tools Used**: Python, Pandas, Random Forest, Scikit-Learn.
- **Highlights**:
  - Achieved 75% model accuracy.
  - Analyzed feature importance and found that of the four input features that were used, total revenue, total assets, capital expenditures, and current ratio, the first two combined contributed to approximately 65% of the model.

### 2. Fortune 500 Classification ML 
- **Objective**: Developed a Logistic Regression model to classify Fortune 500 companies as "Above Average Profit" or "Below Average Profit"
- **Tools Used**: Python, Pandas, Logistic Regression, Scikit-Learn.
- **Highlights**:
  - Achieved 82% model accuracy.
  - Did cross-validation and got an accuracy percentage that was very similar (approx. 79%). 


### 3. Company Data Regression ML
- **Objective**: Developed a Linear Regression model to predict the corporate net income based on input features such as total revenue, total assets, and long term investments. Did the same thing but with a Decision Tree Regression model to compare the results with those of the former. 
- **Tools Used**: Python, Pandas, Scikit-Learn, Linear Regression, Decision Tree Regressor
- **Highlights**:
  - Linear Regression model ahieved an r2 score of approximately 0.84 without cross validation and approximately 0.64 on average with cross validation. 
  - Found that while the r2 score of the  Linear Regression model is much better (0.84) than the Decision Tree Regressor model (0.59) before cross validation, its average cross validation r2 score (0.64) was only slightly higher than that of the latter (0.62), indicating that there wasn't much of an advantage in choosing it over the latter.


### 4. Adult Income Classification Project
- **Objective**: Utilized both a Random Forest and Gradient Boosting model to predict whether adult incomes were above or below $50K.
- **Tools Used**: Python, Pandas, Random Forest, Gradient Boosting, Scikit-Learn.
- **Highlights**:
  - Achieved 85% and 86% model accuracy for Random Forest and Gradient Boosting respectively.Cross-validation largely confirmed this result.  
  - Analyzed feature importance and found that the most predictive features were relationship status, capital gain, and education status.
### 5. Real Estate Valuation Regression Project
- **Objective**: Utilized Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regression, Random Forest Regression, Gradient Boosting Regression, and Bagging Regression to predict house prices. 
- **Tools Used**: Python, Pandas, Linear Regression, Ridge Regression, Lasso Regression, Decision Tree, Random Forest, Gradient Boosting, Bagging, Scikit-Learn.
- **Highlights**:
  - All of the tree models aside from Decision Tree performed better than the linear models. Their (excluding Decision Tree) test validation root mean squared error (approx. 5.7 - 5.9) and cross validation root mean squared error (approx. 7.3 - 7.7) were significantly lower than those of the linear models (approx. 7.3 - 7.5 and 8.8 - 9 respectively) and their test r2 (approxi. 0.79 - 0.8) and cross validation r2 (approx. 0.66 - 0.7) were significantly higher than of the linear models (approx. 0.67 - 0.68 and 0.55 - 0.57 respectively). 
  - Random Forest performed the best out of the tree models attaining a test root mean squared error of approximately 5.7, a cross-validation root mean squared error of approximately 7.3, a test r2 score of approximately 0.8 and a cross-validation r2 score of approximately 0.7.  


 
