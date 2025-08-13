Input Data Directly from Kaggle
- This guide explains how to fetch and load a dataset from Kaggle directly into your code using the Kaggle API.
Example dataset: 🏅 120 years of Olympic history: athletes and results.

🔑 Install Kaggle API
!pip install kaggle

🔑 Set Up Kaggle API Credentials 
- Go to your Kaggle Account Settings
- Scroll to API → click Create New API Token
- Download kaggle.json
- Move it to the Kaggle API folder and set correct permissions:
!mkdir -p ~/.kaggle
!mv kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json

📥 Download the Dataset 
- !kaggle datasets download -d heesoo37/120-years-of-olympic-history-athletes-and-results

📂 Unzip the Dataset 
- !unzip 120-years-of-olympic-history-athletes-and-results.zip

📂 Load the Dataset into Python 
- import pandas as pd
df = pd.read_csv('athlete_events.csv')
df.head()

ℹ️ Dataset Info
- Name: 120 years of Olympic history: athletes and results
- Source: Kaggle Link
