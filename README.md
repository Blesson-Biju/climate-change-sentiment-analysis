# climate-change-sentiment-analysis

🌍 Climate Change Social Media Sentiment Analysis
📌 Project Overview

This project analyzes social media discussions related to climate change using Natural Language Processing (NLP) and Machine Learning techniques.

The objective is to classify posts into Positive, Neutral, and Negative sentiment categories and analyze engagement patterns using a Power BI dashboard.

This project demonstrates an end-to-end pipeline from data preprocessing to visualization.

🎯 Objectives

Perform sentiment classification on climate-related posts

Analyze engagement metrics (likes & comments)

Identify dominant public opinion trends

Visualize insights using Power BI

📂 Dataset Information

File: Climate_change.csv

Features:

date – Date of the post

text – Post content

text_length – Length of the text

likesCount – Number of likes

commentsCount – Number of comments

sentiment_score – Sentiment polarity score

sentiment – Sentiment label (Positive / Neutral / Negative)

Total Records: 504

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

NLP (Text Preprocessing & TF-IDF)

Jupyter Notebook (Colab)

Power BI

⚙️ Project Workflow
1️⃣ Data Preprocessing

Removed missing values

Converted date column to datetime

Cleaned text data

Generated text length feature

Applied TF-IDF vectorization

2️⃣ Model Building

Split dataset into training and testing sets

Trained Machine Learning model for sentiment classification

Evaluated model using:

Accuracy

Precision

Recall

F1-score

3️⃣ Dashboard Development

Created a Power BI dashboard including:

Total Posts

Total Likes

Total Comments

Average Sentiment Score

Sentiment Distribution

Engagement by Sentiment

Sentiment Trend Over Time

Text Length vs Sentiment Score

📊 Key Insights

Identified dominant sentiment category in climate discussions

Analyzed engagement differences across sentiment types

Observed sentiment trends over time

Explored relationship between text length and sentiment

🚀 Future Improvements

Use real-time social media API data

Deploy model as a web application

Improve classification using deep learning models

Expand dataset size for better generalization
