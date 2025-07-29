# Diabetes-SVM-Classifier
A Support Vector Machine model for diabetes prediction using Python”

steps and packages used 
Python 3.8+
scikit-learn
pandas
numpy
matplotlib
seaborn

 Methods 

- Data loading and inspection
- Train-test split
- Feature scaling (StandardScaler)
- SVM classifier from `sklearn.svm`
- Evaluation using confusion matrix and accuracy score

 Key Findings

- The SVM model was trained to classify diabetes with promising accuracy.
- Feature scaling significantly impacted performance.
- Model evaluation showed balanced prediction with a reasonable confusion matrix outcome.

Projet Description 

In this project, I built a machine learning model to predict the likelihood of a person having diabetes using a Support Vector Machine (SVM) classifier. The dataset used consists of various medical predictor variables such as glucose level, BMI, and insulin level, along with the target variable indicating whether the patient is diabetic.

I began by loading and exploring the dataset to understand the distribution and identify any inconsistencies. The data was then split into training and testing sets using an 80:20 ratio. Since SVM models are sensitive to the scale of features, I applied feature scaling using StandardScaler from scikit-learn to normalize the data.

Next, I implemented an SVM classifier using the sklearn.svm.SVC module and trained it on the scaled training data. After training, the model was tested on unseen data, and its performance was evaluated using accuracy score and confusion matrix. Visualizations were generated to better understand the distribution of predictions and model performance.

The results showed that the SVM model provided a decent level of accuracy and balanced classification for both diabetic and non-diabetic cases. This project demonstrates how preprocessing steps like scaling and splitting, followed by model training and evaluation, can be combined to build an effective classifier in Python.




 Key Results

- Accuracy: 78%
- Balanced predictions between positive and negative classes
- Scaling the data significantly improved model performance

  
 Motivation

The rise in diabetes cases worldwide calls for early prediction tools. This project aims to build a simple, interpretable machine learning model that can help flag potential diabetes risk using structured data.
