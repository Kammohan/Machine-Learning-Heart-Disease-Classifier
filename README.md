# Machine-Learning-Heart-Disease-Classifier
This notebook utilizes real life medical data and various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.


Features
Data Exploration: Analysis of the dataset to identify correlations and patterns that affect heart disease.
Data Preprocessing: Data cleaning, normalization, and transformation to prepare data for modeling.
Model Building: Use of RandomForestClassifier to predict heart disease.
Evaluation: Assessing model accuracy, precision, recall, and F1-score.
ROC Curve Analysis: Visualization of model performance through ROC curves.
Technologies Used
Python 3
Pandas, NumPy - for data manipulation
Matplotlib, Seaborn - for data visualization
Scikit-learn - for building and evaluating the machine learning model
Dataset
The dataset used is the UCI Heart Disease Dataset, which contains 76 attributes, but all published experiments refer to using a subset of 14 of them. The goal is to distinguish the presence (value 1) from the absence (value 0) of heart disease.

Setup and Installation
Ensure that you have Python 3 installed on your machine. You can install the required packages using the following command:

bash
Copy code
pip install numpy pandas scikit-learn matplotlib seaborn
How to Run
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourgithubusername/heart-disease-classification.git
Navigate to the cloned repository.
Run the script using Python:
bash
Copy code
python heart_disease_classifier.py
Model Training
The model is trained using the RandomForestClassifier from scikit-learn. Hyperparameters were tuned using GridSearchCV to find the best model.

Evaluation
The model is evaluated using accuracy, precision, recall, and the F1 score. The ROC curve is plotted to visualize the model's performance.

