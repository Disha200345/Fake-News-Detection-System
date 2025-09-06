# 📰 Fake News Detection using Machine Learning  

This project focuses on detecting fake news articles using machine learning techniques. The goal is to classify news as real or fake based on textual features extracted from the dataset.  

---

## 📌 Requirements  

Install the required Python libraries before running the notebook:  
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
---

## 📂 Dataset  

The dataset contains labeled news articles with two categories:  

- Fake News  
- Real News  

It is preprocessed and split into training and testing sets for evaluation.  

---

## ⚙️ Workflow  

1. Data Preprocessing  
   - Load dataset  
   - Handle missing values  
   - Text cleaning (stopword removal, tokenization, stemming/lemmatization)  

2. Feature Extraction  
   - Convert text into numerical form using TF-IDF Vectorizer  

3. Model Training  
   - Train machine learning models (e.g., LSTM, CNN-LSTM, DNN, BERT)  

4. Model Evaluation  
   - Evaluate models using metrics: Accuracy, Precision, Recall, F1-score  
   - Generate confusion matrix and classification report  

5. Prediction  
   - Predict whether a given news article is Fake or Real  

---

## 📊 Results  

- The trained models achieve good accuracy in detecting fake news.  
- BERT show strong performance.  
- Visualizations like confusion matrices and accuracy plots help compare models.  

---

## 🚀 Future Work  
  
- Implement a real-time fake news detection system using APIs.  
- Deploy the model as a web app or mobile application for end-users.  

---

## 👩‍💻 Author  

Developed as part of a project on Fake News Detection using Machine Learning in Python.  
