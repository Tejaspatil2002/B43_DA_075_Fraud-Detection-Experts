# 🚀 Social Media Trend Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/40cf779e-1214-4126-9e45-b41545f9ac85" width="300" height="300">
</p>

## 📌 Project Overview
This project aims to track and analyze trending keywords, topics, and engagement levels on Reddit. The goal is to understand how trends evolve and predict future engagement levels using machine learning models.

## ✨ Features
- 📊 Data collection from Reddit
- 📝 Text preprocessing and feature extraction (TF-IDF, title length, word count)
- ⚖️ Handling class imbalance with SMOTE
- 🤖 Model training using XGBoost for trend prediction
- 📈 Evaluation metrics for model performance

## 🛠️ Technologies Used
- 🐍 Python  
- 🗄️ Pandas  
- 🎯 Scikit-learn  
- 🚀 XGBoost  
- 🔤 TfidfVectorizer  
- ⚖️ SMOTE (imbalanced-learn) 

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/reddit-trend-analysis.git
   cd reddit-trend-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place your dataset (`reddit_historical_data.csv`) in the project directory.
4. Run the analysis script:
   ```bash
   python analysis.py
   ```

## Dataset Details
The dataset includes:
- **Title**: Post title
- **Content-Type**: Type of content (text, image, link, etc.)
- **Subreddit**: Community where the post was shared
- **Keyword**: Extracted keywords
- **Engagement Level**: Categorized as Low, Medium, or High


## Future Enhancements
- Expand data collection to Twitter and Instagram
- Improve trend correlation with global events
- Enhance visualization with interactive dashboards

## Contribution
Feel free to fork the repo and submit pull requests for improvements.



