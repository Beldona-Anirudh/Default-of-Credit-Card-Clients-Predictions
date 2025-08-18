
# Default of Credit Card Clients Predictions

Credit card default is a major risk for banks and financial institutions. Predicting whether a client will default on their credit card payment helps in reducing financial losses and in building stronger risk management strategies.

This project applies machine learning techniques to predict whether a customer will default on their next payment using demographic, financial, and payment history data.



## What I Did

Explored the dataset – 

    Checked demographic information, past payment records, and bill amounts.

Performed EDA (Exploratory Data Analysis) – 

    Visualized default patterns across age, gender, education, and payment history.

Preprocessed the data – 

    Encoded categorical variables, normalized numerical features, and handled missing data.

Trained a Machine Learning Model – 

    Implemented Random Forest Classifier (main model).

Evaluated performance – 

    Compared model results using accuracy, confusion matrix, precision, recall, and F1-score.

Interpreted results – 

    Identified which features have the strongest impact on default prediction.
## Machine Learning Approach

Data Preprocessing

    Encoded categorical variables (e.g., education, marriage, payment status).

    Scaled numerical values like bill amounts and payment history.

    Split into train and test sets for fair evaluation.

Modeling

    Random Forest Classifier used as the main prediction model.

    Can also be extended to Logistic Regression, Decision Tree, or Gradient Boosting for comparison.

Evaluation Metrics

    Accuracy → Overall correctness of predictions.

    Precision, Recall, and F1-score → Important due to class imbalance.

    Confusion Matrix → To check false positives vs false negatives.

    Feature Importance → To identify strongest predictors of default.
## Key Insights

Clients with a history of delayed payments are far more likely to default.

High credit limit clients tend to default less often.

Younger clients (age < 30) showed slightly higher default risk.

Payment history (PAY_0, PAY_2, PAY_3, …) is the strongest predictor in the Random Forest model.
## Tech Stack

-> Python

-> Pandas, NumPy 

    Data wrangling and analysis

->Matplotlib, Seaborn 

    Trend and correlation visualization

-> Scikit-learn 

    Random Forest Classifier, train/test split, evaluation metrics
## How to Run It

Clone the repo

    git clone https://github.com/Beldona-Anirudh/Stock-Price-Movement-Prediction
    


Install the Streamlit

    pip install Streamlit.

Change the Directory

    Switch the cmd directory to the directory where your file is located.

Run 

    Now run the app file with the extension .py .
## Results & Conclusion

The Random Forest Classifier achieved high accuracy and provided reliable results.

Payment history and bill amounts were the most important predictors of default.

This model can help financial institutions detect high-risk clients early and design preventive strategies such as credit counseling, flexible repayment plans, or stricter approval policies.
