# Credit Approval Prediction

This project aims to develop a machine learning model for predicting credit approvals and rejections. The goal is to minimize the errors associated with rejecting good borrowers and approving bad ones, ensuring the bank's credit decisions are as accurate as possible.

## Dataset

The dataset consists of anonymized data with the following columns:

- **N (Numerical)**: Numerical features representing various borrower attributes.
- **C (Categorical)**: Categorical features that need to be encoded for model training.
- **C_enc**: Categorical features encoded with arbitrary numeric values (not following a consistent encoding scheme).
- **Target**: The target variable, where:
  - `Target = 1`: Credit is approved.
  - `Target = 0`: Credit is rejected.

## Goals

1. **Data Preprocessing**: Handle numerical and categorical features properly, with particular attention to the encoded categorical columns.
2. **Model Training**: Train a model that predicts whether a borrower should be approved or rejected based on the available features.
3. **Evaluation**: Focus on minimizing the **false positives** (approving bad borrowers) and **false negatives** (rejecting good borrowers).
4. **Model Optimization**: Use appropriate evaluation metrics to optimize the model for the bank's goals.

## Special Considerations

- **Categorical Encoding**: Ensure that categorical features, particularly those encoded arbitrarily (`C_enc`), are correctly handled to avoid introducing noise.
- **Class Imbalance**: Given that credit approvals (Target = 1) might be less frequent than rejections (Target = 0), consider techniques to handle class imbalance.
- **Model Robustness**: The model should be able to generalize well to new data while maintaining a low error rate for both types of mistakes (approving bad borrowers and rejecting good ones).

