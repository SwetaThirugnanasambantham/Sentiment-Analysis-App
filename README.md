# Product Sentiment Analysis

## 📌 Project Overview

This project focuses on performing **sentiment analysis on product reviews** using Natural Language Processing (NLP) techniques. The goal is to classify reviews into **Positive, Negative, or Neutral** categories based on the textual content.

---

## 🎯 Objectives

* Analyze product reviews and determine sentiment
* Build a machine learning model for classification
* Preprocess and clean textual data
* Evaluate model performance using standard metrics

---

## 📂 Dataset

The dataset consists of product reviews in a **PDF format**, where each review is structured as:

```
1. [Positive] This product exceeded my expectations...
2. [Negative] Very disappointed with the quality...
```

### Features:

* **Review Text** → Input feature
* **Sentiment Label** → Target variable (Positive / Negative / Neutral)

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK / TextBlob
* Scikit-learn
* Streamlit (for deployment, optional)

---

## 🔄 Workflow

### 1. Data Extraction

* Extract text from PDF using PyPDF2

### 2. Data Preprocessing

* Lowercasing
* Removing punctuation
* Tokenization
* Stopword removal

### 3. Feature Engineering

* Bag of Words (BoW)
* TF-IDF Vectorization

### 4. Model Building

* Logistic Regression
* Naive Bayes
* Support Vector Machine (optional)

### 5. Evaluation

* Accuracy
* Precision
* Recall
* F1-score

---

## 🚀 How to Run

### Step 1: Clone the repository

```
git clone <your-repo-link>
cd sentiment-analysis
```

### Step 2: Install dependencies

```
pip install -r requirements.txt
```

### Step 3: Run the project

```
python main.py
```

### (Optional) Run Streamlit App

```
streamlit run app.py
```

---

## 📊 Example Output

| Review                              | Predicted Sentiment |
| ----------------------------------- | ------------------- |
| "Amazing product, works perfectly!" | Positive            |
| "Waste of money"                    | Negative            |
| "It's okay, not great"              | Neutral             |

---

## 📈 Future Enhancements

* Use deep learning models (LSTM, BERT)
* Increase dataset size for better accuracy
* Add real-time sentiment prediction UI
* Deploy using cloud platforms

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is for educational purposes and is open-source.

---

## 👤 Author

Sweta Thirugnanasambantham


