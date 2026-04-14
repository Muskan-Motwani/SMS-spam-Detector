# SMS Spam Detection using Machine Learning

##  Overview

This project focuses on building a machine learning model to classify SMS messages as **Spam or Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

The model helps in filtering unwanted messages and is widely used in real-world applications like messaging platforms and email systems.

---

##  Features

* Text preprocessing (cleaning, tokenization, stopword removal)
* Feature extraction using TF-IDF
* Spam classification using Machine Learning
* Saved trained model (`model.pkl`)
* Real-time prediction capability

---

## Tech Stack

* Python
* Scikit-learn
* Pandas & NumPy
* NLTK

---

##  Workflow

1. Data Collection (SMS dataset)
2. Data Cleaning & Preprocessing
3. Feature Extraction (TF-IDF)
4. Model Training (Naive Bayes / Logistic Regression)
5. Model Saving using Pickle
6. Prediction on new messages

---

##  Dataset

* Contains SMS messages labeled as spam or ham
* Used for training and testing the model

---

##  Results

(Add your accuracy here)
Example:
Accuracy: 96%

---

##  How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run prediction:

```bash
python src/predict.py
```

---

##  Example

Input:
"Congratulations! You have won a lottery"

Output:
Spam

---

##  Use Cases

* SMS filtering
* Email spam detection
* Fraud message detection

---

##  Future Improvements

* Deploy as web app (Streamlit)
* Use deep learning models
* Improve dataset size

---

## 👩‍💻 Author

Muskan Motwani
