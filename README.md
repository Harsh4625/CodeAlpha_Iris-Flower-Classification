Iris Flower Classification using Machine Learning
📌 Overview

This project implements a machine learning classification model to predict the species of an Iris flower based on its physical measurements.
The model classifies flowers into:

Iris Setosa

Iris Versicolor

Iris Virginica

The project is developed as part of a Data Science Internship task.

📂 Dataset

Dataset is provided as a ZIP file: Flower_Dataset.zip

Contains a CSV file with the following features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Species (target variable)

The dataset is extracted and loaded programmatically within the code.

🧠 Machine Learning Approach

Type: Supervised Learning

Algorithm Used: Logistic Regression

Problem Type: Multiclass Classification

Train-Test Split: 80% Training, 20% Testing

🛠️ Technologies & Libraries

Python

Pandas

Matplotlib

Seaborn

Scikit-learn

📁 Project Structure
iris-flower-classification/
│
├── iris_flower_classification.py
├── Flower_Dataset.zip
└── README.md

▶️ How to Run the Project
🔹 Google Colab

Upload both files:

iris_flower_classification.py

Flower_Dataset.zip

Run:

!python iris_flower_classification.py

🔹 Local Machine

Clone the repository or download files

Install dependencies:

pip install pandas matplotlib seaborn scikit-learn


Run the script:

python iris_flower_classification.py

📊 Output

Model accuracy score

Classification report (Precision, Recall, F1-score)

Confusion matrix visualization

Typical accuracy achieved: 96% – 100%

✅ Conclusion

The Logistic Regression model successfully classifies Iris flower species with high accuracy.
This project demonstrates the complete machine learning workflow including data handling, model training, evaluation, and visualization.

📌 Author

Harsh
Data Science Intern
