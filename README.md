This project focuses on binary classification of emails into spam and not spam categories using machine learning techniques. 
The dataset consists of word-count features extracted from emails, where the final column (Prediction) represents the target label (0 = not spam, 1 = spam).

Three models were implemented and compared: Logistic Regression, Complement Naive Bayes and Neural Network (Multilayer Perceptron – MLP).

The workflow follows a standard machine learning pipeline: data preprocessing, train-test split (80/20 with stratification), model training, and evaluation.
To ensure reliable results, all models were evaluated using 10-fold Stratified Cross-Validation. Performance was measured using accuracy, precision, recall, F1-score, and ROC-AUC. 
A final evaluation was performed on a separate test set, including a classification report, confusion matrix, and ROC curve visualization.
The results show that all models perform strongly on the dataset. Logistic Regression provides stable and well-balanced results, Complement Naive Bayes performs efficiently on text-based features, 
and the Neural Network achieves the highest overall performance in terms of F1-score and ROC-AUC.

This project demonstrates the comparison between classical machine learning models and a neural network
