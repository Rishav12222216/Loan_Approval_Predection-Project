# Loan Approval Prediction using PySpark (Databricks)

## Project Overview

This project focuses on predicting whether a loan application will be **approved or rejected** based on the applicant’s financial and demographic information.

The goal was to understand how machine learning models can assist financial institutions in automating loan approval decisions.

The model was developed using **PySpark on Databricks**, which allows scalable data processing and machine learning workflows.

---

## Technologies Used

* Python
* PySpark
* Databricks
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset

The dataset contains information about loan applicants such as:

* Gender
* Marital Status
* Dependents
* Education
* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Property Area

Target Variable:

**Loan_Status**

* **Y** → Loan Approved
* **N** → Loan Rejected

---

## Project Workflow

1. Loaded the dataset using **PySpark**.
2. Performed **data cleaning and preprocessing**.
3. Handled missing values in both categorical and numerical columns.
4. Converted categorical variables using **StringIndexer**.
5. Created feature vectors using **VectorAssembler**.
6. Built a **machine learning pipeline** in PySpark.
7. Trained a **Decision Tree Classifier** to predict loan approval.
8. Evaluated the model using accuracy and confusion matrix.
9. Created visualizations to understand the data and model behavior.

---

## Model Performance

The model achieved an accuracy of approximately **75–80%** on the test dataset.

Evaluation metrics used:

* Accuracy Score
* F1 Score
* Confusion Matrix

---

## Visualizations

To better understand the dataset and model results, the following visualizations were created:

* **Loan Status Distribution**
  Shows the imbalance between approved and rejected loans.

* **Applicant Income Distribution**
  Displays how applicant income is distributed across the dataset.

* **Confusion Matrix**
  Helps evaluate the performance of the prediction model.

* **Feature Importance**
  Identifies which factors most influence loan approval.

From the feature importance graph, **Credit History** was found to be the most significant factor affecting loan approval.

---

## Key Insights

* Applicants with a **positive credit history** are much more likely to receive loan approval.
* Income and loan amount also influence approval decisions.
* The dataset has more approved loans than rejected ones, indicating a **class imbalance**.

---

## Future Improvements

Some improvements that could be explored:

* Using **Random Forest or Gradient Boosting models**
* Performing **hyperparameter tuning**
* Handling class imbalance using techniques like **SMOTE**
* Deploying the model as a web application or API

---

## Author

Rishav Raj
