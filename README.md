# credit-risk-classification

# Loan Default Prediction

This project aims to predict loan default risk based on financial information using machine learning techniques. The goal is to develop models that can accurately classify loans as either healthy (0) or at risk of default (1).

## Data

The dataset used in this project is stored in the `lending_data.csv` file, which contains various financial variables for each loan applicant. The target variable is `loan_status`, which indicates whether a loan is classified as a default (1) or not (0).

## Requirements

The project requires the following dependencies:

- Python 3.x
- NumPy
- Pandas
- scikit-learn
- imbalanced-learn

Install the dependencies using pip:

```
pip install numpy pandas scikit-learn imbalanced-learn
```

## Usage

1. Clone the repository:

```
git clone https://github.com/birdipa2/credit-risk-classification.git
cd loan-default-prediction
```

2. Run the `loan_default_prediction.ipynb` notebook to train and evaluate the machine learning models.

## Results

The project utilizes two machine learning models: Logistic Regression with Original Data and Logistic Regression with Resampled Data.

The Logistic Regression model with Original Data achieved an accuracy score of 0.952 and exhibited good precision, recall, and F1-scores for both healthy loans and loan defaults.

The Logistic Regression model with Resampled Data achieved an accuracy score of 0.994 and demonstrated improved precision, recall, and F1-scores, especially for loan defaults.

## Conclusion

Based on the evaluation results, the Logistic Regression model with Resampled Data outperformed the model trained on the original data. It showed higher accuracy and better performance in capturing loan defaults. Therefore, it is recommended to use the Logistic Regression model with Resampled Data for loan default prediction.

## Contact

Please contact param.birdi@utoronto.ca in case of any clarifications or suggestions.