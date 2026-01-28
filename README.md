Project Overview
This project is an NLP (Natural Language Processing) based machine learning project that works on text data and performs two major tasks:

1) Sentiment Analysis
In this part, the system reads a piece of text (like a review, feedback, or comment) and tries to understand the emotion or opinion behind it.
It predicts whether the text is:
Positive (happy / satisfied / good opinion)
Negative (angry / dissatisfied / bad opinion)
Neutral (normal statement, no strong emotion)
This is useful when we want to automatically analyze large amounts of customer reviews or feedback without reading them manually.

2) Spam Detection
In this part, the system checks whether a given message is spam or not.
It predicts whether the message is:
Spam (advertising, fake offers, suspicious links, unwanted messages)
Ham (normal, genuine message)

This is useful for filtering spam messages in SMS, emails, or chat systems.

What This Project Includes
Text Preprocessing

Before training, the text is cleaned and prepared so the machine can understand it properly. This includes steps like:
Removing extra spaces or symbols
Converting text to lowercase
Removing unnecessary words
Making the text more structured for the model

Feature Extraction
Since machine learning models cannot directly understand raw text, the project converts text into numerical form using vectorization methods like:

Count Vectorizer (word frequency based)
TF-IDF (importance based)
This creates a feature set that the model can learn from.

Model Training
After preprocessing and feature extraction, a machine learning model is trained on labeled data so it can learn patterns such as:
Words commonly found in spam messages (free, win, offer, click, etc.)
Words that indicate positive/negative tone in sentiment analysis

Model Evaluation
Once training is done, the performance of the model is tested using evaluation metrics like:

Accuracy
Confusion Matrix

Classification Report
This helps to verify how well the model is predicting correct results.

Final Predictions
After everything is trained and evaluated, the system can take new input text and provide output like:
Sentiment result (positive/negative/neutral)

Spam result (spam/ham)
What This Project Can Do in Real Life
This project can be applied in real-world scenarios such as:
Detecting fake or promotional messages automatically
Analyzing customer satisfaction from product reviews

Filtering spam emails or SMS
Understanding public opinion from social media comments
Improving customer support by categorizing feedback quickly
