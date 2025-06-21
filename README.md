"Fighting fake news is not just a technical challenge — it's a national responsibility."

A model that detects fake News and misinformation using the Machine Learning

Overview

This projects help in building a machine learning model that detects fake news or any misinformation spreading in the country. 
Here the user simply has to insert the headline or a snippet of any article and the model would predict if the news is real or fake.
In the age of information overload, it's vital to detect and filter misinformation for  national security and psychological warfare, as they are deeply affected by propaganda and fake content.

Tech Stack 
1. Language : Python
2. Platform : Google Colab
3. Libraries :
               pandas - For data collection and manipulation
               scikit-learn - For using machine learning models
               TfidfVectorizer - For conversion of text into numbers
               LogisticRegression - For classification

Dataset

fake.csv and true.csv
Source: Kaggle Fake News Dataset
Due to Github's 25 MB file upload limit, I couldn't upload the dataset.
Dataset was uploaded in Google Colab and then used to train and test data

Model Details

Achieved 98% accuracy on the data.
Used the news headlines of the year 2016-17, it may not predict latest news accurately, for latest news prediction BERT and XGBoost is used 
(I don't have a command on these yet but I would be making a model using both of the technologies)

✍️ Developed By

Anshika Singh
4th Semester,
B.Tech CSE (AIML)
