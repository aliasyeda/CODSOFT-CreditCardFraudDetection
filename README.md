# CODSOFT-CreditCardFraudDetection

🛡️ Credit Card Fraud Detection
This project focuses on detecting fraudulent credit card transactions using machine learning algorithms. The goal is to build and evaluate models that can classify transactions as either fraudulent or legitimate based on historical data.

📁 Dataset
The dataset contains real-world credit card transaction data. It includes features like transaction time, amount, location, and category of the transaction. The dataset is labeled to indicate whether a transaction is fraud or not fraud.

🔗 Download Dataset: Google Drive Link (https://drive.google.com/file/d/1flUaiLhnYIrRC65Wi3ABuw_GHir2wEFy/view?usp=sharing)
(Contains fraudTrain.csv and fraudTest.csv)


🎯 Project Objectives

Understand and explore the structure of credit card transaction data.

Preprocess the data (cleaning, encoding, feature selection).

Train multiple models:

Logistic Regression

Decision Tree

Random Forest

Evaluate model performance using:

Confusion Matrix

Accuracy, Precision, Recall, F1-score

Make predictions on test data to classify transactions.


🛠️ Tools & Technologies Used

Python

Pandas, NumPy – Data handling and analysis

Scikit-learn – Model building and evaluation

Matplotlib, Seaborn – Data visualization

Jupyter Notebook / Google Colab – Development environment


🧠 Key Learnings

How to handle imbalanced datasets.

Comparing performance of different classification algorithms.

Importance of metrics like Precision and Recall in fraud detection.


🚀 How to Run

Clone the repo or download the notebook.

Install required libraries:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn
Load the dataset (fraudTrain.csv and fraudTest.csv).

Run the notebook cell by cell to preprocess, train, and evaluate the models.


📊 Sample Output

Accuracy: ~0.96 (Random Forest)

Confusion Matrix showing high detection of fraud cases

Precision and Recall optimized for imbalance

