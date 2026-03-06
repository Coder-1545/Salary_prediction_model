# Employee Salary Prediction Model

## Overview

The **Employee Salary Prediction Model** is a machine learning project that predicts whether an employee earns **more than $50K per year or less than or equal to $50K per year** based on demographic and work-related attributes.

This project uses the **Adult Census Income Dataset** and applies **data preprocessing, exploratory data analysis, and machine learning techniques** to build an accurate classification model.

The goal is to analyze the relationship between employee attributes and income level and develop a predictive model using **Random Forest Classification**.

---

## Dataset

The dataset used in this project is the **Adult Census Income Dataset**, which contains demographic and employment information about individuals.

### Features in the Dataset

Some of the important features include:

* Age
* Workclass
* Education
* Marital Status
* Occupation
* Relationship
* Race
* Gender
* Hours per week
* Native country

### Target Variable

* **Income**

  * `<=50K`
  * `>50K`

---

## Technologies Used

* **Python**
* **Google Colab**
* **Pandas** – Data manipulation and preprocessing
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualizations
* **Scikit-learn** – Machine learning algorithms and evaluation

---

## Project Workflow

The project follows a standard **Machine Learning Pipeline**:

### 1. Data Collection

The dataset is loaded from a compressed ZIP file stored in Google Drive.

### 2. Data Preprocessing

* Removal of unnecessary columns
* Handling categorical variables using **One-Hot Encoding**
* Conversion of dataset into numerical format for machine learning

### 3. Exploratory Data Analysis (EDA)

Several visualizations are created to understand patterns in the dataset:

* Income distribution
* Age vs Income boxplot
* Correlation heatmap
* Feature importance analysis

### 4. Feature Selection

Relevant features are selected for model training, and the target variable is separated from the feature set.

### 5. Model Training

A **Random Forest Classifier** is used to train the model on the dataset.

### 6. Model Evaluation

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Model Used

### Random Forest Classifier

Random Forest is an ensemble machine learning algorithm that builds multiple decision trees and combines their outputs to improve prediction accuracy and reduce overfitting.

Advantages:

* Handles large datasets effectively
* Works well with both categorical and numerical features
* Reduces variance compared to single decision trees

---

## Results

The model predicts whether an employee earns **more than $50K or less than or equal to $50K** with good accuracy.

Evaluation metrics include:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**

A **confusion matrix** is also generated to visualize the prediction performance.

---

## Visualizations

The following visualizations are included in the project:

* Income distribution chart
* Age vs Income boxplot
* Correlation heatmap
* Confusion matrix
* Feature importance plot

These plots help in understanding the dataset and evaluating model performance.

---

## Applications

Employee salary prediction models can be useful for:

* HR analytics
* Workforce salary analysis
* Economic research
* Data-driven hiring insights

---

## Future Improvements

Possible improvements for this project include:

* Hyperparameter tuning for better accuracy
* Comparing multiple machine learning algorithms (Logistic Regression, SVM, XGBoost)
* Building a **web application using Flask or Streamlit**
* Deploying the model for real-time predictions

---

## Conclusion

This project demonstrates how machine learning techniques can be used to analyze employee data and predict salary categories. By combining **data preprocessing, visualization, and classification algorithms**, the model provides meaningful insights into income prediction.

---
