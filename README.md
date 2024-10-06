# SMS_Spam_Detector

## Introduction
This project implements a machine learning model to classify SMS messages as either spam or not spam. The model uses a pipeline of TF-IDF vectorization and Linear Support Vector Classification. The project also uses Gradio, an easy-to-use interface that allows users to input SMS messages and get predictions directly in a browser. I was provided assistance by Sean Morey, the instructor of the class. My classmate, Kyle Sellers, was a big help. I lastly could not have been able to finish this code without the help from the BCS Xpert Learning Assistant.

## Project Structure

1. Model Training: The model is trained on an SMS dataset containing labeled messages (spam or ham). The dataset is split into training and testing sets. A Pipeline is built with the following steps:

    - TF-IDF Vectorization: Converts the text data into numerical features.
    - Linear Support Vector Classification (SVC): A linear classifier for binary classification of the messages.
    - The training process is encapsulated in the function sms_classification.

2. SMS Spam Prediction: The sms_prediction function is designed to take user input (an SMS text) and predict whether the message is spam or not.

3. Gradio Interface: The project can be integrated with a Gradio interface for users to input their own SMS messages and view the spam classification results.