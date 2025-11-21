# 📧 Spam Email Classification

This project demonstrates a machine learning approach to classify emails as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)**.  
The email text is converted into numerical features using **TF-IDF Vectorization**, and a **Logistic Regression** model is trained to detect spam patterns with high accuracy.

---

## 📝 Description

The dataset contains thousands of email messages labeled as spam or ham.  
The text passes through an NLP pipeline that includes:

- Converting raw email text into numerical vectors using **TfidfVectorizer**
- Splitting the data into **training** and **testing** sets
- Training a **Logistic Regression** classifier
- Evaluating accuracy and predicting new email text


## 🛠 Technologies Used

- **Python** – Programming language  
- **Pandas / NumPy** – Data handling and preprocessing  
- **Scikit-learn**
  - `TfidfVectorizer` – Feature extraction  
  - `LogisticRegression` – Classification  
  - `train_test_split`, `accuracy_score` – Evaluation  
- **NLP (Natural Language Processing)** – Text conversion & feature extraction  

## ▶️ How to Run

python filename.py

