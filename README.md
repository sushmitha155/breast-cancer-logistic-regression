🧠 Logistic Regression Classification - Breast Cancer Detection
📌 Objective
Build a binary classification model using Logistic Regression to predict whether a tumor is malignant (cancerous) or benign (non-cancerous) using the Breast Cancer Wisconsin dataset.

📂 Dataset
Source: Breast Cancer Wisconsin Dataset on Kaggle

Contains features computed from digitized images of a breast mass (mean radius, texture, perimeter, area, etc.)

🔧 Tools & Libraries
Python

Pandas – data manipulation

Matplotlib – data visualization

Scikit-learn – machine learning model and evaluation

✅ Steps Performed
Loaded and explored the dataset

Preprocessed the data:

Dropped irrelevant columns

Converted categorical labels (M, B) to binary (1, 0)

Split into training and test sets

Standardized the features

Trained a Logistic Regression model

Evaluated the model using:

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC-AUC Score & ROC Curve

Visualized the Sigmoid Function to understand how logistic regression works

📊 Results
High Accuracy in classifying malignant vs benign tumors

ROC-AUC score showed excellent separability

Sigmoid curve illustrated probability estimation from raw scores

📷 Screenshots 
Include plots of:

ROC Curve: ![image](https://github.com/user-attachments/assets/ef3dd67f-c87a-4527-84c8-73dda5f0fabb)


Confusion Matrix: Confusion Matrix:
 [[70  1]
 [ 2 41]]

Classification Report:
               precision    recall  f1-score   support

           0       0.97      0.99      0.98        71
           1       0.98      0.95      0.96        43

    accuracy                           0.97       114
   macro avg       0.97      0.97      0.97       114
weighted avg       0.97      0.97      0.97       114


ROC AUC Score: 0.99737962659679

Sigmoid function : ![image](https://github.com/user-attachments/assets/146513d8-fa18-49f7-b592-aa774d6bb33e)


📁 Files Included
logistic_regression.ipynb – Jupyter Notebook with all code and output

data.csv – Dataset used (or link)

README.md – This description file

🚀 How to Run
Clone the repo

Install required libraries (pip install -r requirements.txt)

Open the notebook and run all cells

📝 Submission
GitHub link submitted as part of internship Task 4 – Classification with Logistic Regression.

