# Fake News Detection Project

This project focuses on detecting fake news using machine learning algorithms. The goal is to classify news articles as either *fake* or *real* based on their text content using Logistic Regression and Random Forest classifiers.

## Dataset

The dataset consists of news articles labeled as fake or real. It was preprocessed by cleaning text, removing stop words, and converting text into numerical features suitable for machine learning.

## Algorithms Used

- **Logistic Regression**
- **Random Forest**

## Performance Metrics

The models were evaluated using the following metrics:

| Metric    | Logistic Regression | Random Forest  |
|-----------|---------------------|----------------|
| Accuracy  | 0.9837              | 0.9918         |
| Precision | 0.9793              | 0.9897         |
| Recall    | 0.9867              | 0.9930         |
| F1-score  | 0.9830              | 0.9913         |

The Random Forest model performed best overall, showing very high accuracy and balanced precision and recall.

## How to Run

1. Clone the repository.
2. Install the required dependencies (e.g., scikit-learn, pandas, numpy).
3. Preprocess the dataset as per the preprocessing script.
4. Train and evaluate the models using the provided Jupyter notebook or scripts.

## Conclusion

Both Logistic Regression and Random Forest classifiers are effective for fake news detection, with Random Forest slightly outperforming Logistic Regression on this dataset.

## Contact

For questions or suggestions, please contact [manikanta] at [maddirala.23bai11066@vitbhopal.ac.in].

