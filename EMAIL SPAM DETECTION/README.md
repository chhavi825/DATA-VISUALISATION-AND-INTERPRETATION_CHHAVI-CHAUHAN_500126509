Email Spam Detection

📌 Project Overview
This project implements a **machine learning model** to classify emails as either **Spam** or **Not Spam (Ham)**.  
It uses **Natural Language Processing (NLP)** techniques to clean and preprocess the text, then trains models to predict the category of unseen emails.

📂 Features
- Text preprocessing (lowercasing, stopword removal, punctuation removal)
- Feature extraction using **Bag of Words (CountVectorizer)** or **TF-IDF**
- Model training with algorithms like:
  - Naive Bayes
  - Logistic Regression
  - Random Forest
- Model evaluation with accuracy, precision, recall, and F1-score

📊 Dataset
The dataset contains labeled emails, with columns:
- **Text** — The content of the email
- **Label** — `spam` or `ham`

🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
