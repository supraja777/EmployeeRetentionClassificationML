This repository contains a Python notebook aimed at predicting employee retention within a Human Resources department. The notebook is structured into several tasks, each focusing on different aspects of the problem, including data visualization, data cleaning, model training, and evaluation.

The goal is to predict employee retention using a dataset provided.We perform exploratory data analysis (EDA) by visualizing the dataset. We inspect features, handle missing data, and analyze various aspects of employee data to gain insights using sklearn, pandas, numpy and seaborn libraries.

We have trained the model using different classification models such as Logistic Regression, Artificial Neural Networks, and Random Forest Classifier.

The performance of the models are compared using KPIs such as accuracy, recall, precision and F1 score.

Result : 

Logistic Regression -

              precision    recall  f1-score   support

           0       0.90      0.99      0.94       304
           1       0.91      0.48      0.63        64

    accuracy                           0.90       368
   macro avg       0.91      0.74      0.79       368
weighted avg       0.90      0.90      0.89       368


RandomForestClassifier - 

              precision    recall  f1-score   support

           0       0.86      1.00      0.92       304
           1       0.93      0.22      0.35        64

    accuracy                           0.86       368
   macro avg       0.90      0.61      0.64       368
weighted avg       0.87      0.86      0.82       368


Artificial Neural Networks :


Number of epochs - 100
Number of Layers - 4
Number of Units - 500
Activation Function - ReLU
loss - Binary cross entropy
optimizer - Adam optimizer


           precision    recall  f1-score   support

           0       0.90      0.92      0.91       304
           1       0.58      0.52      0.55        64

    accuracy                           0.85       368
   macro avg       0.74      0.72      0.73       368
weighted avg       0.84      0.85      0.85       368


Conclusion -

Logistic Regression achieved the highest accuracy among the models, with an accuracy of 90%. 

Random Forest Classifier also performed reasonably well with an accuracy of 86%. It showed good performance in terms of precision for the positive class (employees who left), although the recall for this class was relatively low.

Artificial Neural Networks (ANN) exhibited an accuracy of 85%, with moderate precision and recall values for both classes. While ANN showed promising results, further fine-tuning or exploring more complex architectures might improve its performance.