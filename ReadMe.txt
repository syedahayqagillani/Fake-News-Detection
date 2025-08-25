# 📰 Fake News Detection using Machine Learning  

## 📌 Project Overview  
This project aims to detect whether a news article is **Fake** or **Real** using Natural Language Processing (NLP) and Machine Learning techniques.  
By applying preprocessing steps and training different classifiers, the project evaluates which model performs best for fake news detection.  

---

## 🎯 Goal  
- Build a machine learning model to classify news articles as **fake** or **real**.  
- Apply **text preprocessing** techniques to clean the dataset.  
- Evaluate multiple classifiers and compare their performance.  

---

## 📊 Dataset  
The dataset used in this project is the **Fake and Real News Dataset** from Kaggle:  
👉 [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)  

- `True.csv` → Contains real news articles.  
- `Fake.csv` → Contains fake news articles.  

---

## 🔄 Data Preprocessing  
- Text cleaning (lowercasing, removing punctuation & numbers).  
- Tokenization.  
- Removal of stopwords.  
- Lemmatization / Stemming.  
- Vectorization using **TF-IDF**.  

---

## 🤖 Models Used  
The following machine learning classifiers were applied:  
- Logistic Regression  
- Naïve Bayes  
- Random Forest  

---

## 📈 Model Evaluation  
Models were evaluated on the basis of:  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-score**  

### ✅ Example Results   
- Logistic Regression Accuracy: **99%**  
- Naïve Bayes Accuracy: **96%**  
- Gradirent Boasting Accuracy: **99%**  

---

## 📌 How to Run  

1. Clone this repository:
   ```bash
   git clone https://github.com/syedahayqagillani/Fake-News-Detection
   cd Fake-News-Detection
