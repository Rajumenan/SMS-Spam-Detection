# 📩 SMS Spam Detection Using Machine Learning

This project focuses on detecting spam messages from SMS text data using **Machine Learning** and **Natural Language Processing (NLP)**.  
By leveraging text preprocessing, TF-IDF vectorization, and classification algorithms, the system accurately distinguishes between **Spam** and **Ham (Non-Spam)** messages to improve digital communication safety.

---

## 📊 Project Objectives

- Classify SMS messages as **Spam** or **Ham** automatically  
- Preprocess and clean text for model readiness  
- Compare multiple ML algorithms (Naive Bayes, Logistic Regression, SVM)  
- Evaluate model performance with precision, recall, and F1-score  
- Build a reusable and deployable ML pipeline  

---

## 🗂 Dataset Description

- **File:** spam.csv  
- **Source:** [UCI SMS Spam Collection Dataset (Kaggle)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- **Columns include:**  
  - `label` → Message category (`spam` or `ham`)  
  - `message` → SMS text content  

**Dataset Characteristics:**  
- ~5,500 messages total  
- Approx. 13% spam, 87% ham  
- Texts contain informal language, abbreviations, and punctuation

---

## 🔧 Tools & Technologies

- **Programming Language:** Python 3.x  
- **Libraries:**  
  - `pandas`, `numpy` → Data handling  
  - `nltk`, `re` → Text preprocessing  
  - `scikit-learn` → ML models, TF-IDF  
  - `matplotlib`, `seaborn` → Visualization  
- **Environment:** Jupyter Notebook / Google Colab  
- **Version Control:** GitHub  

---

## 🔍 Key Insights

- TF-IDF features improve model accuracy compared to raw word counts  
- **Multinomial Naive Bayes** achieves >95% accuracy with fast performance  
- Logistic Regression and SVM provide comparable results with more computation  
- Frequent spam keywords include “win”, “free”, “claim”, “urgent”  
- Text preprocessing (stopword removal, stemming) improves classification consistency  

---

## 📈 Sample Visualizations

- **Word Clouds** of spam vs. ham messages  
- **Bar Charts** of word frequency distribution  
- **Confusion Matrix** and **ROC Curve** for model evaluation  
- **EDA Visuals:** Spam vs. Ham message counts, length distributions  

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rajumenan/SMS-Spam-Detection.git
