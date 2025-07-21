Twitter Sentiment Analysis – NLP & Logistic Regression
A Natural Language Processing (NLP) project to perform sentiment analysis on Twitter data using classical machine learning techniques.
This project demonstrates the complete pipeline from data preprocessing to model training and deployment via Gradio.

<img width="869" height="341" alt="image" src="https://github.com/user-attachments/assets/c5f08297-fe56-410f-a7ea-1670d3b650f7" />
✅ Overview
This notebook solves a multi-class classification problem by analyzing tweets and classifying them into:

✅ Positive

❌ Negative

😐 Neutral

Using:

NLTK for tokenization & stopword removal

CountVectorizer for converting text into features

LogisticRegression for training the classifier

🗂 Dataset Description
We use two datasets:

twitter_training.csv

twitter_validation.csv

Each contains the following columns:

Column	Description
id	Unique identifier of tweet
information	Meta data (not used in training)
type	Sentiment label (Positive/Negative/Neutral)
comment	The actual tweet text

⚙️ Workflow
Data Loading

Text Cleaning

Feature Extraction

Model Training

Evaluation



🧪 Example Prediction
Input:
The service was really bad!
Output:
Predicted Sentiment: Negative

🧠 Tech Stack
Language: Python 3.x

Data Handling: pandas, numpy

NLP: nltk

ML Model: Logistic Regression (sklearn)

Visualization: matplotlib, seaborn

Deployment (UI): Gradio

👩‍💻 Author
Faryal Nimra
