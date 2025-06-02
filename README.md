# 🧠 Naive Bayes Classification on User Data

This project demonstrates the use of the **Naive Bayes algorithm** for classification tasks using a user dataset. The goal is to classify users into categories (e.g., purchase vs. no purchase) based on features such as age, salary, gender, or other demographic information.

## 📁 Files in this Repository

- `User_Data (1).csv` – The dataset containing user demographic information and the target label.
- `Naive_Bayes_Classification.ipynb` – Jupyter notebook with a step-by-step implementation of the Naive Bayes classifier.
- `README.md` – Documentation and overview of the project.

## 🚀 Features Covered

- Loading and preprocessing user data
- Feature selection and train/test splitting
- Data visualization (optional)
- Applying **Gaussian Naive Bayes** classification
- Evaluating model performance:
  - Confusion matrix
  - Accuracy, precision, recall
  - Decision boundary visualization

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🔧 How to Run

1. Clone the repository or download the files.
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Launch the notebook:
   jupyter notebook Naive_Bayes_Classification.ipynb

Dataset Overview
Typical columns in the dataset:

Age

EstimatedSalary

Gender (if present)

Purchased (target variable – binary classification)

📈 Model Summary
Naive Bayes is used due to its simplicity, performance on small datasets, and suitability for probabilistic classification.

📌 Next Steps
Try different Naive Bayes variants (e.g., Multinomial, Bernoulli)

Apply cross-validation

Tune features or preprocessing methods

Use this as a baseline for comparison with more complex models
