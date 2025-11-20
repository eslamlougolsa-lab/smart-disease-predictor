Disease Detection Project 🩺💻



This Python notebook implements a disease detection project combining rule mining (Apriori) with supervised machine learning models.



📁 Dataset



Download the dataset from Kaggle and place it in the same folder as the notebook (data/ folder recommended):



Disease Prediction Using Machine Learning (kaushil268)



Disease Diagnosis Dataset (s3programmer)



Example filenames: disease.csv or Training.csv



🚀 Features



Extract frequent symptom patterns with Apriori



Train supervised models: Random Forest, Logistic Regression, SVM, XGBoost



Handle Yes/No symptoms, missing values, and categorical data



Evaluate with accuracy, cross-validation, and classification reports



Save the best model for future predictions (disease\_model.pkl)



⚡ Quick Start



Download the dataset from Kaggle and put it in the data/ folder.



Open the notebook and run the code step by step.



Preprocess the data, train models, evaluate performance, and save the best model.



joblib.dump({'model': best\_model, 'scaler': scaler, 'columns': X\_train.columns}, 'disease\_model.pkl')



📊 Results



Frequent symptom patterns using Apriori



Model accuracy \& classification reports



Cross-validation scores

