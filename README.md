# ML-Classification-Case-Study
Personality-Driven Experiences


1. **Data Loading & Exploration**
* Loaded the personality_dataset.

* Explored the dataset’s shape, data types, missing values, and value counts for categorical columns.

2. **Statistical Summary & Visualization**

* Generated descriptive statistics for all numerical features.
  
* Visualized distributions using histograms.

* Created a correlation matrix to assess relationships among numerical variables.

3. **Target Variable Identification**

* Identified 'Personality' as the target variable for classification.

4. **Data Cleaning**

***Handled missing values:***

* Imputed median for numerical features.

* Imputed mode for categorical features.

* Detected and removed duplicate rows.

5. **Outlier Detection & Handling**
* Used the Interquartile Range (IQR) method to detect outliers and capped them with upper and lower bounds.



6. **Hypothesis Testing**

* ANOVA for numerical features vs. 'Personality'.

* Chi-Square test for categorical features vs. 'Personality'.


7. **Data Preparation**
* Applied One-Hot Encoding to convert categorical variables to numeric.

8. **Feature Engineering**

* Created polynomial features.

* Evaluated correlation of engineered features with the target.

* Removed low-correlation or redundant features to reduce dimensionality.

9. **Feature Scaling**
* Applied Min-Max Scaling to normalize numerical variables.


10. **Data Splitting**
* Split the dataset into Train,Test and Validation sets.

11. **Model Training**

*Trained four supervised classification models:*

* Decision Tree

* K-Nearest Neighbors (KNN)

* Logistic Regression

* Random Forest

12. **Hyperparameter Tuning**
* Used GridSearchCV to tune hyperparameters for each model.

* Selected the best parameter combinations based on cross-validated performance.

13. **Model Evaluation**

*Evaluated final models on the test set using:*

* Accuracy

* Precision

* Recall

* F1-Score

#**Conclusion**

Although all models performed well, Logistic Regression stands out as the most efficient and interpretable model, offering top-tier performance with minimal complexity. It is particularly suitable when model transparency and explainability are important.

However, if robustness to variance is required,then  Random Forest remains a strong candidate.
