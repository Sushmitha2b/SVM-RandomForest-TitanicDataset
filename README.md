# Supervised-Learning
Survival rate prediction on titanic dataset using SVM and Random Forest
This project involves predicting the survival of passengers aboard the Titanic using various machine learning algorithms. The dataset includes passenger information, and the goal is to classify each passenger as either survived or not survived based on the features provided.

Project Overview

	1.	Data Preparation:
  	•	Load the training and testing datasets.
  	•	Handle missing values and preprocess the data by dropping irrelevant columns and filling in missing values.
  	•	Convert categorical variables to numerical values and create new features.
	2.	Exploratory Data Analysis (EDA):
  	•	Visualize the survival rate based on different features such as Sex, Pclass, SibSp, Parch, and AgeGroup.
	3.	Feature Engineering:
  	•	Convert continuous features into categorical bins.
  	•	Map categorical features to numerical values.
  	•	Create new features based on existing data.
	4.	Model Training and Evaluation:
  	•	Train and evaluate models using Random Forest and Support Vector Machine (SVM) classifiers.
  	•	Perform k-fold cross-validation to assess model performance.
  	•	Save predictions to CSV files.
	5.	Results:
  	•	Compare model accuracies and visualize results.

Files

	•	train.csv: The training dataset.
	•	test.csv: The testing dataset.
	•	RandomForest_Predictions.csv: Predictions made by the Random Forest model.
	•	SVM_Predictions.csv: Predictions made by the SVM model.
	•	titanic_prediction.ipynb: The main Python script for data processing, model training, and evaluation.

Requirements

Ensure you have the following Python packages installed:

	•	pandas
	•	numpy
	•	matplotlib
	•	seaborn
	•	scikit-learn

Results

	•	Model Performance: Evaluates accuracy across different models and k-fold values.
	•	Prediction Files: Outputs prediction results to RandomForest_Predictions.csv and SVM_Predictions.csv
 	•	SVM achieved a slightly higher average accuracy compared to Random Forest but may be less scalable and more complex to implement.
	•	Random Forest offers robustness to overfitting and better scalability, making it a viable choice for larger datasets despite its slightly lower accuracy.

The results highlight the trade-offs between model performance, interpretability, and scalability. Choosing the appropriate model depends on the specific requirements of the task and dataset.
