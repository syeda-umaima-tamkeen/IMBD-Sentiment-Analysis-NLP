# 🎬 Sentiment Analysis on IMDB Movie Reviews

**Project by:** Syeda Umaima Tamkeen

---

## 📝 Summary

This project implements a **Sentiment Analysis** model on the **IMDB Movie Reviews Dataset** using **Natural Language Processing (NLP)** techniques and machine learning. The goal is to classify reviews as either **positive** or **negative**, helping to automate the analysis of public opinion in entertainment.

The project follows a complete machine learning pipeline—from data loading and preprocessing to model training, evaluation, and visualization—providing a foundational understanding of text classification tasks.

---

## 🔍 Key Steps

### 1. Dataset Loading & Exploration
- Imported the IMDB dataset containing labeled movie reviews.
- Examined dataset structure, class balance, and sample data.

### 2. Text Preprocessing
- Converted text to lowercase and removed punctuation, HTML tags, and stopwords.
- Tokenized the reviews and applied lemmatization for word normalization.

### 3. Feature Extraction (TF-IDF)
- Transformed processed text into numerical vectors using **TF-IDF Vectorization** to capture the importance of words in each review relative to the corpus.

### 4. Model Building
- Trained and tested multiple classification algorithms:
  - **Logistic Regression**
  - **Naive Bayes**
  - **Support Vector Machine (SVM)**
- Used train-test split to evaluate model performance.

### 5. Evaluation Metrics
- Evaluated models using:
  - **Accuracy**
  - **Precision, Recall, F1-Score**
  - **Confusion Matrix**
- Visualized model performance using confusion matrices and classification reports.

### 6. Prediction Testing
- Tested the best-performing model on custom input reviews to classify unseen data.

---

## ✅ Results

- The best-performing model achieved high **accuracy and balanced precision/recall** on test data.
- The pipeline successfully differentiated between positive and negative sentiment in text reviews.
- Visualization tools clearly illustrated the model’s effectiveness and potential for real-world application.

---

## 📌 Conclusion

This project demonstrates how **NLP techniques combined with machine learning** can be used to **analyze public sentiment** from large volumes of text data. It serves as a robust framework for developing AI-powered review systems in entertainment, e-commerce, and social platforms.


  

