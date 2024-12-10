# Introduction

In today's digital era, the widespread use of mobile communication has led to an increase in unsolicited and malicious messages, commonly referred to as spam. These spam messages can range from harmless advertisements to fraudulent schemes, posing a significant threat to users. To address this issue, the "SMS Spam Classification" project aims to build a robust machine learning model capable of distinguishing between legitimate (ham) messages and spam.

# Project Synopsis: SMS Spam Classification

## Objective:
The primary goal of this project is to build an interactive SMS spam classification application that identifies and categorizes SMS messages as either "Spam" or "Ham" (not spam).

## Framework and Algorithm Used:

Framework: Streamlit – A Python-based framework for creating interactive web applications.
Algorithm: Multinomial Naive Bayes (Multinomial NB) – A probabilistic machine learning algorithm suitable for text classification tasks, leveraging the frequency of words for prediction.

# Features of the Application:

## User-friendly Interface:

Developed using Streamlit, the application offers a clean and interactive user interface.
Users can input text messages directly into the app for real-time classification.
## Real-time Classification:

The app processes the input SMS and classifies it as "Spam" or "Ham" based on the trained model.

# Implementation Details:

## Data Preprocessing:

Data cleaning to remove noise (e.g., punctuation, stop words).
Tokenization and conversion of text to lowercase.
Transformation into a Bag of Words (BoW) or TF-IDF representation for numerical representation of the text.
## Model Training:

A Multinomial Naive Bayes classifier was trained on a labeled dataset of SMS messages.
The dataset was split into training and testing subsets to evaluate the model's performance.
## Deployment:

The model was integrated into a Streamlit application to enable real-time predictions.
# Key Outcomes:

Achieved high classification accuracy, indicating the model's ability to effectively distinguish between spam and ham messages.
The application provides a practical and scalable solution for SMS spam filtering.
# Future Scope:

Integration with APIs to classify live SMS feeds.
Enhancements in the user interface for better visualization of classification probabilities.
Incorporation of additional models or techniques to improve accuracy further.

# Thoughts

The project is simple, we work on some dataset and try to find out what are the trends and what is is the pattern, after finding out the pattern one can get idea of what I've uploaded using the dataset.
Also you explore various dataset on kaggle because this one I've downloaded from there. 
We first do EDA and I have written comments for everything in the jupyter notebook you can refer it. 
After that we checked for various algorithms which gave accuracy and precison score and which was having great score we used that. 
Then we trained the mode and pickled the model and used it.
For the website part I've used streamlit.

# Setup

Step1: Download the zip file of the project.

Step2: Open PyCharm and create new project and name it.

Step3: After the project is created copy the files - app.py, model.pkl, vectorizer.pkl and paste it in the PyCharm project.

Step4: Go in the PyCharm terminal and install Streamlit Python framework - pip install streamlit

Step5: Also install nltk by 'pip install nltk' and sklearn by 'pip install scikit-learn'

Step6: Atlast write "streamlit run app.py" on the terminal the project will be implemented.



# Output

![Screenshot 2024-09-09 141548](https://github.com/user-attachments/assets/83c9c252-08a3-4ce0-9258-b6694abe9779)

![Screenshot 2024-09-09 141702](https://github.com/user-attachments/assets/64ca4683-ce29-49b9-8f4f-292010913fc9)

![Screenshot 2024-09-09 141801](https://github.com/user-attachments/assets/a91832b0-51ce-425a-96fd-042a1db8bb10)

