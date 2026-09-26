# Customer Churn Analysis & Prediction

An end-to-end **Customer Churn Analysis and Machine Learning** project
using the Telco Customer Churn dataset. The project explores customer
behavior through Exploratory Data Analysis (EDA) and builds a machine
learning model to predict whether a customer is likely to churn.

## 📌 Project Overview

Customer churn refers to customers discontinuing a service. Predicting
churn can help businesses identify customers who are at risk of leaving
and take preventive actions.

This project covers:

-   Data loading and preprocessing
-   Exploratory Data Analysis (EDA)
-   Customer behavior analysis
-   Feature engineering
-   Machine learning model building
-   Model evaluation
-   Churn prediction

## 📂 Project Structure

``` text
Customer_churn/
│
├── app.py
├── Churn Analysis - EDA.ipynb
├── Churn Analysis - Model Building.ipynb
├── first_telc.csv
├── tel_churn.csv
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── model.sav
└── README.md
```

### Files

  -----------------------------------------------------------------------------
  File                                      Description
  ----------------------------------------- -----------------------------------
  `app.py`                                  Application interface for using the
                                            churn prediction model

  `Churn Analysis - EDA.ipynb`              Exploratory data analysis and
                                            visualization

  `Churn Analysis - Model Building.ipynb`   Data preprocessing, model training
                                            and evaluation

  `WA_Fn-UseC_-Telco-Customer-Churn.csv`    Telco customer churn dataset

  `tel_churn.csv`                           Dataset used during the project
                                            workflow

  `first_telc.csv`                          Additional/processed dataset

  `model.sav`                               Saved trained machine learning
                                            model

  `README.md`                               Project documentation
  -----------------------------------------------------------------------------

## 🔍 Exploratory Data Analysis

The EDA notebook investigates patterns associated with customer churn,
including:

-   Churn distribution
-   Customer demographics
-   Contract type
-   Tenure
-   Monthly charges
-   Total charges
-   Payment methods
-   Internet and service subscriptions
-   Relationship between customer attributes and churn

Visualizations are used to identify trends and potential factors
associated with customer churn.

## 🤖 Machine Learning

The model-building notebook follows a typical machine learning pipeline:

1.  Load the dataset
2.  Clean and preprocess the data
3.  Handle categorical variables
4.  Prepare features and target variable
5.  Split data into training and testing sets
6.  Train the classification model
7.  Evaluate model performance
8.  Save the trained model as `model.sav`

**Target variable:** `Churn`

The model predicts whether a customer is likely to churn.

## 📊 Model Evaluation

The trained model can be evaluated using classification metrics such as:

-   Accuracy
-   Precision
-   Recall
-   F1-score
-   Confusion Matrix

> **Note:** Add the final model's actual evaluation metrics here after
> confirming them from the model-building notebook. Avoid putting
> estimated or assumed accuracy values in the README.

## 🚀 Running the Project

### 1. Clone the repository

``` bash
git clone <your-github-repository-url>
cd Customer_churn
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn streamlit
```

If your `app.py` uses additional libraries, install those as well.

### 3. Run the application

If the project uses Streamlit:

``` bash
streamlit run app.py
```

Otherwise, run the application according to the framework used in
`app.py`.

## 🛠️ Technologies Used

-   **Python**
-   **Pandas** -- Data manipulation
-   **NumPy** -- Numerical operations
-   **Matplotlib** -- Data visualization
-   **Seaborn** -- Statistical visualization
-   **Scikit-learn** -- Machine learning
-   **Jupyter Notebook** -- Analysis and experimentation
-   **Streamlit** -- Application interface (if used by `app.py`)

## 🎯 Key Objective

The main objective of this project is to use customer data to understand
churn behavior and develop a machine learning solution capable of
identifying customers who may be at risk of leaving a telecom service.

## 📈 Future Improvements

-   Compare multiple classification algorithms
-   Perform hyperparameter tuning
-   Address class imbalance if required
-   Add explainable AI techniques such as SHAP
-   Improve the prediction interface
-   Deploy the application online
-   Add automated model monitoring

## 👩‍💻 Author

**Aditi Ramola**

B.Tech --- Computer Science & Engineering (Artificial Intelligence &
Machine Learning)

------------------------------------------------------------------------

⭐ If you found this project useful, consider giving the repository a
star.
