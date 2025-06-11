# 🗞️ News Topic Classification using NLP

This project implements a machine learning pipeline for classifying news articles into categories using fundamental **Natural Language Processing (NLP)** techniques including **tokenization**, **stopword removal**, and **TF-IDF vectorization**.

---

## 🧠 Project Objective

Automatically categorize news articles (e.g., politics, sports, business, technology) by processing their titles and descriptions using traditional NLP methods and training a text classification model.

---

## 📌 Features

- ✂️ Tokenization of news content
- 🚫 Removal of stopwords
- 📊 TF-IDF vectorization for feature extraction
- 🧪 Classification model using Naive Bayes
- 📈 Evaluation using classification report

---

## 🧰 Tech Stack

- Python 3.x  
- Libraries: `pandas`, `nltk`, `scikit-learn`, `matplotlib`, `seaborn`

---

## 🚀 How to Run

1. **Clone the repository**

git clone project repository
cd news-topic-classification
Install dependencies
pip install -r requirements.txt
Run the notebook
Open news_classifier.ipynb in Jupyter Notebook and execute all cells.

📊 Sample Categories
🏛️ politics

⚽ sports

💼 business

💻 technology

🌍 environment

📝 Example Output

              precision    recall  f1-score   support

   business       0.80      0.75      0.77        20
   sports         0.85      0.90      0.87        20
   politics       0.78      0.82      0.80        20
   technology     0.90      0.85      0.87        20

   accuracy                          0.83        80

📄 License

This project is licensed under the MIT License.

