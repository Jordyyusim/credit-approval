# 🏦 Credit Approval
A machine learning classification project that predicts whether a credit card application should be approved or denied, based on applicant information such as age, income, credit history, employment status, and other indicators.

## 🌟 Features

- Predicts whether a credit application is approved (1) or not approved (0).
- Supports multiple models (Logistic Regression, Random Forest, KNN, and Decision Tree).
- Performs model tuning and best parameters for each model 
- Displays evaluation metrics and confusion matrix.
- Provides prediction for new user input.

## 🌟 Steps

- Import libraries
- Import and inspect datasets
- Handles missing and duplicate values
- Converts **birthdate** into **age** and **days of work** into **year**.
- Converts **Gender, Car and Realty Ownage** into **numerical values**
- Merges datasets
- Train-Test Split
- Encode Categorical Features with **OneHotEncoder**
- Scale Numerical Features with **MinMaxScaler**
- Data preprocessing 
- Creates model pipeline
- Model training
- Model Evaluation (classification report, confusion matrix)
- Save model


## 🛠️ Built With

- Python
- Scikit-learn
- Pandas and Numpy
- Matplotlib

## 📦 Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/jordyyusim/credit-approval.git
    cd credit-approval
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv yourenv
    source yourenv/bin/activate      # On Windows: yourenv\Scripts\activate
    ```

3. **Install the dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch Jupyter Notebook**:

    ```bash
    Jupyter notebook
    ```   

## 📬 Socials

[GitHub](https://github.com/jordyyusim) &nbsp;|&nbsp;
[LinkedIn](https://linkedin.com/in/jordyyusim) &nbsp;|&nbsp;
[X](https://x.com/jordyyusim)
