# Customer Retention Analysis

A project to predict **customer churn** for a telecommunications company using **Logistic Regression**. The goal is to identify customers likely to leave the service and provide insights to improve retention strategies.

---

## Dataset

The dataset contains **200 rows** and **10 columns**, including customer demographics, account details, and service usage. Key features:
- `tenure`: Duration of customer retention.
- `age`: Customer age.
- `income`: Annual income.
- `churn`: Target variable (1 = Churn, 0 = No Churn).

---

## Workflow

1. **Data Preprocessing**:
   - Feature scaling with `StandardScaler`.
   - Splitting into training (80%) and testing (20%) datasets.
2. **Model Training**:
   - Logistic Regression with hyperparameter tuning (`C` and solver).
3. **Evaluation**:
   - Confusion Matrix, Precision, Recall, F1 Score, Log Loss.

---

## Results

- **Churn = 1**: F1 Score = 0.55
- **Churn = 0**: F1 Score = 0.83
- **Log Loss**: 0.5919
- The model performs well for non-churners but requires improvement for predicting churners.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/IpsitMohanty/CustomerRetentionAnalysis.git
   cd CustomerRetentionAnalysis
