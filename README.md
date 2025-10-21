# sms-spam-detection
# 📱 SMS Spam Detection using Machine Learning

This project classifies SMS messages as **Spam (unwanted)** or **Normal (genuine)** using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
Developed as part of the *Naan Mudhalvan* initiative, it runs fully in **Google Colab**, making it easy to use even from a mobile device.

---

## 🚀 Features
- ✅ Clean and preprocess SMS text (remove URLs, symbols, etc.)
- ✅ TF-IDF feature extraction
- ✅ Machine Learning models:
  - Multinomial Naive Bayes
  - Logistic Regression (balanced)
- ✅ Confusion Matrix & WordCloud visualizations
- ✅ Interactive real-time chat predictor
- ✅ Mobile-friendly design (no manual dataset upload needed)

---

## 🧠 Methodology

1. **Data Collection:**  
   Used the public *SMS Spam Collection Dataset* (UCI Repository).

2. **Data Preprocessing:**  
   - Convert to lowercase  
   - Remove URLs, special characters  
   - Keep important spam words like “free”, “win”, “offer”

3. **Feature Extraction:**  
   TF-IDF Vectorization with unigrams and bigrams.

4. **Model Training:**  
   Logistic Regression with `class_weight='balanced'` for better spam recall.

5. **Evaluation Metrics:**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix (visualized with Seaborn)

---

## 📊 Results
| Metric | Score |
|--------|--------|
| Accuracy | ~98% |
| Precision (Spam) | ~0.95 |
| Recall (Spam) | ~0.93 |
| F1-score | ~0.94 |

Spam keywords like **“win”, “free”, “claim”, “offer”** were successfully detected, while personal messages like **“See you in class”** were classified as *Normal*.

---

## 🖼️ Visualizations
- **Confusion Matrix Heatmap**  
- **WordClouds** for Spam vs Normal  
- **Interactive chat output examples**

---

## 💬 Example Output
