# Final_Project
Predicting with Machine Learning Models

# Final Assessment

## Problem Statement 1: Sales Prediction based on CPI, Discounts, and Offers

### 1. Dataset Description
The dataset comprises information on Customer Price Index (CPI), percentage discounts, rewards offers, and corresponding sales values.

### 2. Machine Learning Models

#### Multiple Linear Regression (MLR)
- **R2 Score:** 0.9517
- **Sample Predictions:**
  - 5000 CPI, 3% Discounts, 20% Offers - Predicted Sales: 826645.34
  - 4000 CPI, 8% Discounts, 19% Offers - Predicted Sales: 732680.36

#### K-Neighbour Regressor
- **R2 Score:** 0.3122 (Poor Performance)
- **Sample Predictions:**
  - 5000 CPI, 3% Discounts, 20% Offers - Predicted Sales: 668000
  - 4000 CPI, 8% Discounts, 19% Offers - Predicted Sales: 668000

#### Random Forest Regressor
- **R2 Score:** 0.9554
- **Sample Predictions:**
  - 5000 CPI, 3% Discounts, 20% Offers - Predicted Sales: 649400
  - 4000 CPI, 8% Discounts, 19% Offers - Predicted Sales: 680450

### 3. Model Selection
K-Nearest Neighbour Regressor performed poorly. Both Linear Regression and Random Forest Regressor are suitable for further consideration.

---

## Problem Statement 2: Loan Offer Prediction based on Customer Details

### 1. Dataset Description
The dataset contains customer details like Cybill Score, age, cards, debit cards, insurance, and loan offers.

### 2. Machine Learning Models

#### Logistic Regression
- **Accuracy Score:** 0.7425

#### Support Vector Machine (SVM)
- **Accuracy Score:** 0.6940

#### K Nearest Neighbour Classifier
- **Accuracy Score:** 0.6866

### 3. Model Selection
Logistic Regression achieved the highest accuracy, making it a preferred choice for predicting loan offers.

---

## Problem Statement 3: Customer Classification based on Geographical and Personal Details

### 1. Dataset Description
The dataset includes customer information such as age, workclass, education, marital status, occupation, etc.

### 2. Machine Learning Models

#### Decision Tree
- **Accuracy Score:** 0.8402

#### Random Forest Classification
- **Accuracy Score:** 0.8585

#### KNN (K-Nearest Neighbors)
- **Accuracy Score:** 0.7950

#### Support Vector Machine (SVM)
- **Accuracy Score:** 0.7971

#### K-Means Clustering
- **Silhouette Score:** 0.5839 (for clustering evaluation)

### 3. Model Selection
Random Forest Classification achieved the highest accuracy among the classification models. K-Means Clustering, being unsupervised, is evaluated using Silhouette Score.

---

## Additional Points

### 1. Data Preprocessing
- Ensure proper handling of missing values, outliers, and categorical variables.
- Normalize or standardize features as required.

### 2. Model Evaluation
- Utilize metrics such as precision, recall, and F1 score for a more comprehensive evaluation.
- Consider cross-validation to assess model robustness.

### 3. Interpretability
- Provide insights into feature importance for decision-making.
- Visualize decision trees or model explanations for better understanding.

### 4. Future Work
- Suggest potential improvements or additional features for enhanced model performance.
- Explore advanced techniques like neural networks for more complex patterns.

### 5. Code Organization
- Arrange code into clear sections such as data preprocessing, model training, and evaluation.
- Include comments and docstrings for better code understanding.

### 6. Acknowledgments
- Mention any external libraries or datasets used.
- Give credit to sources of inspiration or reference.

Feel free to customize this readme based on specific project details and requirements.
