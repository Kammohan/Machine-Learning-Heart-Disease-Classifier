# Machine-Learning-Heart-Disease-Classifier
This notebook utilizes real life medical data and various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.


## Features
- **Data Exploration**: Analyzing the dataset to uncover correlations and trends affecting heart disease.
- **Data Preprocessing**: Implementing data cleaning, normalization, and transformation.
- **Model Building**: Constructing a predictive model using `RandomForestClassifier`.
- **Evaluation**: Measuring model performance with metrics like accuracy, precision, recall, and F1-score.
- **ROC Curve Analysis**: Visualizing model effectiveness through ROC curves.

## Technologies Used
- **Python 3**
- **Pandas & NumPy**: For data manipulation
- **Matplotlib & Seaborn**: For data visualization
- **Scikit-learn**: For modeling and model evaluation

## Dataset
The project uses the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease), specifically focusing on a subset of 14 out of the 76 available attributes. The dataset helps in identifying the presence (value 1) and absence (value 0) of heart disease in clinical scenarios. 

## Model Training
The model uses RandomForestClassifier from scikit-learn, with hyperparameters optimized through GridSearchCV for the best performance.

## Evaluation
The model's efficacy is evaluated using various statistical metrics, including accuracy, precision, recall, and F1-score, alongside a ROC curve to assess its diagnostic ability.


