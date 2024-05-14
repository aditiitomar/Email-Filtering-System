# Email Filtering System

This Python script demonstrates email spam classification using Logistic Regression & TF-IDF vectorization. It imports necessary libraries, preprocesses the data, trains a Logistic Regression model, and evaluates its accuracy on both training and testing data. Finally, it predicts whether a given email is spam or not.

## Code Description
- **Libraries**: Numpy, Pandas, Scikit-learn
- **Data**: A [CSV file](https://www.kaggle.com/datasets/ashfakyeafi/spam-email-classification) containing email messages and their categories (spam/ham)
- **Preprocessing**: Conversion of text messages into numerical form using TF-IDF vectorization
- **Model**: Logistic Regression model is trained on the transformed features
- **Evaluation**: Accuracy scores are calculated for both training and testing data
- **Prediction**: The model predicts whether a given email message is spam or ham

## Dependencies
- Numpy
- Pandas
- Scikit-learn


