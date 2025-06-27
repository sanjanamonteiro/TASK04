# Logistic Regression Binary Classification

This project demonstrates binary classification using logistic regression with Scikit-learn, Pandas, and Matplotlib.

## Objective

- Build and evaluate a binary classifier using logistic regression.
- Understand model evaluation metrics and the sigmoid function.
- Visualize ROC curve and sigmoid function.
- Experiment with decision thresholds.

## Dataset

The example uses the `Breast Cancer Wisconsin` dataset from scikit-learn. You can swap in your own binary classification dataset by changing the data loading section.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## How to Run

1. Clone this repository or download the script.
2. Install dependencies:
   ```
   pip install pandas numpy matplotlib scikit-learn
   ```
3. Run the script:
   ```
   python logistic_regression_task4.py
   ```

## Script Details

- **Data Preparation:** Loads and splits a binary classification dataset, standardizes features.
- **Model Training:** Uses `LogisticRegression` from scikit-learn.
- **Evaluation:** Outputs confusion matrix, precision, recall, and ROC-AUC score. Plots the ROC curve.
- **Threshold Tuning:** Shows the effect of changing the decision threshold.
- **Sigmoid Function:** Plots and explains the sigmoid function used in logistic regression.

## Customization

To use your own dataset:
1. Replace the data loading section with your CSV using `pd.read_csv`.
2. Ensure your target variable is binary (two unique values).

## Explanation

- **Confusion Matrix:** Shows counts of TP, FP, TN, and FN.
- **Precision & Recall:** Precision = TP / (TP + FP), Recall = TP / (TP + FN).
- **ROC-AUC:** Measures the model's ability to distinguish between classes.
- **Threshold Tuning:** Adjusts sensitivity/specificity by changing the probability threshold for classification.
- **Sigmoid Function:** Used in logistic regression to output probabilities between 0 and 1.

## License

This project is for educational purposes.
