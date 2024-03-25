# **Fake News Detection using Machine Learning**
This project aims to combat the spread of misinformation by detecting fake n ews articles using machine learning techniques. 
The dataset utilized in this project is sourced from Kaggle. The dataset comprises two subsets: genuine news articles and fake news articles. 
The project involves several stages, including data loading and preprocessing, text processing, train-test splitting, text vectorization, model training, evaluation, and manual testing.

## **Dataset Obtained from:-**
https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection/data

## **Technical Stack**
The project relies on Python as the programming language. Key libraries utilized include:
- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical operations and array manipulation.
- **scikit-learn (sklearn)**: For implementing machine learning algorithms and evaluating model performance.
- **re**: For text processing tasks such as removing URLs, HTML tags, punctuation, digits, and newline characters.
  
The text data is preprocessed to remove noise, including URLs, HTML tags, punctuation, digits, and newline characters.
Text vectorization is performed using Term Frequency-Inverse Document Frequency (TF-IDF) vectorization to convert text data into numerical vectors suitable for machine learning models. 
The models used for classification include Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier.
