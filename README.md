# 🧠 Text Emotion Detection

This project aims to detect emotions from raw text using Natural Language Processing (NLP) and Machine Learning techniques. It is capable of identifying emotions like joy, **anger, **fear, **love, **sadness, and **surprise based on textual input.

---

## 📊 Dataset Used

- Name: emotion_dataset_raw.csv
- Description: A labeled dataset containing text samples annotated with emotional categories.
- Format: CSV file with columns like text and emotion.

---

## 🧠 Approach Summary

### 🔧 1. Data Preprocessing
- Cleaned and tokenized the text.
- Removed stopwords and punctuation.
- Applied text normalization techniques like stemming or lemmatization.

### 🤖 2. Model Building
- Vectorized the text using TF-IDF.
- Trained a Multinomial Naive Bayes / Logistic Regression / SVM classifier.
- Tuned hyperparameters for optimal accuracy.

### 📈 3. Evaluation
- Accuracy and F1-score metrics were used.
- Achieved high precision across major emotion classes.

### 🧩 4. Deployment
- Developed a front-end using Streamlit for easy user interaction.
- Integrated trained model (text_emotion.pkl) with app.py.

---

## 🧩 Dependencies

Make sure to install these before running the project:

```bash
pip install -r requirements.txt
