# Fake News Detection Using Deep NLP

This project detects **Fake or Real News** using Deep Learning and Natural Language Processing (NLP).  
It processes text data (news headlines and content) and classifies it using an LSTM (Long Short-Term Memory) neural network.

---

## 🚀 Objective

To build a deep learning model that:
- Learns linguistic patterns in news articles.
- Identifies whether a given article is **Fake** or **Real**.
- Uses NLP preprocessing and deep learning (LSTM/Embedding layers).

---

## 🧠 Tech Stack

- Python 3.8+
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras
- NLTK (for text cleaning)
- Matplotlib, Seaborn (for visualization)

---

## 📊 Dataset

Dataset: `dataset.csv`  
Format:

| id | title | text | label |
|----|-------|------|-------|
| 1 | "Breaking: Major discovery in..." | "Scientists reveal new study..." | 1 (real) |
| 2 | "You won’t believe what happened..." | "Fake story spreading online..." | 0 (fake) |

You can use:
- [Kaggle: Fake News Dataset](https://www.kaggle.com/c/fake-news)
- or any custom dataset with similar columns.

---

## ⚙️ How It Works

1. **Data Preprocessing**
   - Lowercasing, removing punctuation, numbers, and stopwords.
   - Tokenization and padding sequences.

2. **Feature Extraction**
   - Using word embeddings (Keras Embedding layer).

3. **Model Training**
   - LSTM network trained to classify news.

4. **Evaluation**
   - Reports Accuracy, Precision, Recall, F1-score.

5. **Prediction**
   - Enter custom text and get result: `Fake` or `Real`.

---

## 🧩 Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/sathyag13/Fake-News-Detection-Using-Deep-NLP.git
cd Fake-News-Detection-Using-Deep-NLP
