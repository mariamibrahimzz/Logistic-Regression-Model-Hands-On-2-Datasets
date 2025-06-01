# Logistic Regression Classification Project

This project showcases the implementation of **logistic regression models** on two distinct datasets using a complete machine learning pipeline. It demonstrates how binary classification problems can be approached with clean, structured workflows, from data loading to evaluation and visualization.

---

## 🚀 Project Overview

Logistic regression is a fundamental algorithm in supervised learning used for binary classification tasks. In this project, the end-to-end process is performed twice—on two separate datasets—to reinforce the modeling workflow and highlight model evaluation techniques.

---

## 📁 Workflow

1. **Data Loading & Exploration**
   - Read the datasets using `pandas`.
   - Initial inspection of data shape, types, and basic statistics.

2. **Data Preprocessing**
   - Handle missing values.
   - Feature transformation if needed.
   - Convert categorical features into numerical (if applicable).

3. **Feature Definition & Train-Test Split**
   - Define feature matrix `X` and target vector `y`.
   - Use `train_test_split` from `sklearn` to split into training and testing datasets.

4. **Model Training**
   - Train a `LogisticRegression` model on training data.

5. **Model Prediction**
   - Make predictions on test data.
   - Evaluate model performance.

6. **Model Evaluation**
   - Generate and interpret:
     - **Confusion Matrix**
     - **Classification Report**
     - **AUC Score**
   - Plot ROC curve to visualize true positive rate vs. false positive rate.

7. **Visualization**
   - Plot confusion matrix with `seaborn.heatmap`.
   - Display AUC-ROC curve with `matplotlib`.

---

## 🛠️ Tech Stack & Tools

- **Languages & Libraries**:  
  `Python`, `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`

- **Algorithms**:  
  `Logistic Regression` from `sklearn.linear_model`

- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC Curve
  - AUC Score

---

## 📂 Project Structure

```plaintext
├── logistic_regression_model (1).ipynb
├── README.md
