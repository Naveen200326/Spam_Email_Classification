📧 Spam Email Classification

This project demonstrates a machine learning approach to classify emails as Spam or Ham (Not Spam) using Natural Language Processing (NLP). The email text is transformed into numerical features using TF-IDF Vectorization, and a Logistic Regression model is trained to detect spam patterns with high accuracy. This is a simple, effective implementation of text classification using classical machine learning techniques.

📄 Description

The dataset contains thousands of email messages labeled as spam or ham.
The text goes through an NLP pipeline that includes:

Converting raw email text into numerical vectors using TfidfVectorizer

Splitting the data into training and testing sets

Training a Logistic Regression classifier

Evaluating accuracy and predicting on new email text

The model learns common spam patterns such as promotional keywords, suspicious phrases, and unusual writing structure.

🛠 Technologies Used

Python – Programming language

Pandas / NumPy – Data handling and processing

Scikit-learn

TfidfVectorizer – Feature extraction

LogisticRegression – Classification

Train-test split, accuracy score

NLP (Natural Language Processing) – For text conversion & feature engineering
