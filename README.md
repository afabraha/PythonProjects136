# PythonProjects136

This repository showcases my data science projects, demonstrating my skills in Python and machine learning. 

## Projects

### 1.  Clustering Fortune 500 Companies
- **Objective**: Grouped Fortune 500 companies based on revenue using k-means clustering.
- **Tools Used**: Python, Pandas, Scikit-learn, KMeans
- **Highlights**:
  - Clustered companies into four segments based on profitability.
  - Created a csv file to show the companies broken down into their respective segments.

### 2. Corporate Finance Data Project
- **Objective**: Developed a Random Forest model to classify companies as High, Medium, or Low Profit.
- **Tools Used**: Python, Pandas, Random Forest, Scikit-Learn.
- **Highlights**:
  - Achieved 75% model accuracy.
  - Analyzed feature importance and found that of the four input features that were used, total revenue, total assets, capital expenditures, and current ratio, the first two combined contributed to approximately 65% of the model.

### 3. Fortune 500 Classification ML 
- **Objective**: Developed a Logistic Regression model to classify Fortune 500 companies as "Above Average Profit" or "Below Average Profit"
- **Tools Used**: Python, Pandas, Logistic Regression, Scikit-Learn.
- **Highlights**:
  - Achieved 82% model accuracy.
  - Did cross-validation and got an accuracy percentage that was very similar (approx. 79%). 


### 4. Company Data Regression ML
- **Objective**: Developed a Linear Regression model to predict the corporate net income based on input features such as total revenue, total assets, and long term investments. Did the same thing but with a Decision Tree Regression model to compare the results with those of the former. 
- **Tools Used**: Python, Pandas, Sklearn, Linear Regression, Decision Tree Regressor
- **Highlights**:
  - Linear Regression model ahieved an r2 score of approximately 0.84 without cross validation and approximately 0.64 on average with cross validation. 
  - Found that while the r2 score of the  Linear Regression model is much better (0.84) than the Decision Tree Regressor model (0.59) before cross validation, its average cross validation r2 score (0.64) was only slightly higher than that of the latter (0.62), indicating that there wasn't much of an advantage in choosing it over the latter.

### 5. Medicare Drug Spending Regression Project
- **Objective**: Developed both a Linear Regression model and a Random Forest Regressor model to predict total drug spending in 2022  based on previous years spending (2018 - 2021).
- **Highlights**:
  - Both models achieved an r2 score in the high 0.9s range as well as when cross validation was utilized.  
  - The Random Forest Regression model had a much lower mean squared error (approximately 2.56 * 10^15) than the Linear Regression model (approximately 7.69*10^15), indicating that it could be considered more accurate. 


 
