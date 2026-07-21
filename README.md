# Customer Churn Prediction using Logistic Regression

## Objective

The objective of this project is to develop a Logistic Regression model to predict whether a customer is likely to leave (churn) based on demographic information and telecommunication service usage. The project involves data preprocessing, model training, prediction, and performance evaluation using standard classification metrics.

---

## Dataset Link

**Telco Customer Churn Dataset**

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

> **Note:** The dataset is not included in this repository. Please download it directly from the Kaggle link above.

---

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Performed data understanding by examining the dataset structure, feature types, and summary statistics.
3. Checked for missing values.
4. Converted the `TotalCharges` column to a numerical data type and handled missing values.
5. Removed the `customerID` column as it does not contribute to prediction.
6. Encoded all categorical variables using Label Encoding.
7. Split the dataset into training (80%) and testing (20%) sets.
8. Built a Logistic Regression model using Scikit-learn.
9. Predicted customer churn on the test dataset.
10. Evaluated the model using Accuracy Score, Precision, Recall, F1-Score, and a Confusion Matrix.

---

## Results

The Logistic Regression model was successfully trained and evaluated on the Telco Customer Churn dataset. The model achieved satisfactory classification performance, with good overall accuracy in predicting customer churn. The evaluation metrics, including Accuracy, Precision, Recall, and F1-Score, demonstrated that the model effectively identified churn patterns while maintaining balanced classification performance. The Confusion Matrix further illustrated the model's ability to correctly classify most customer records, although some churn cases were misclassified.

*Accuracy Score : 0.8168914123491838
*Precision      :  0.6802507836990596
*Recall         : 0.5817694369973191
*F1-Score       : 0.6271676300578035

---

## Conclusion

The project successfully demonstrated the use of Logistic Regression for predicting customer churn using demographic and service-related information. Features such as contract type, tenure, monthly charges, and total charges were found to significantly influence customer churn. Although the model produced reliable classification results, Logistic Regression assumes a linear relationship between the input features and the log-odds of the target variable. More advanced machine learning algorithms may provide improved performance when dealing with complex, non-linear customer behavior patterns.

---

## Repository Contents

* `Assignment-2.ipynb`
* `README.md`

---

**Author:** Soumyodyuti Ray

**Assignment:** Assignment-2

**Topic:** Customer Churn Prediction using Logistic Regression
