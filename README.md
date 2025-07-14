
# 🎬 IMDB Reviews Sentiment Analysis using LSTM

## 📝 Project Overview

This project uses a Long Short-Term Memory (LSTM) neural network to perform sentiment analysis on IMDB movie reviews.  
The model predicts whether a review expresses a **positive** or **negative** sentiment based on its textual content.

---

## 📁 Dataset

- **Source**: [IMDB Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- The dataset contains 50,000 reviews:
  - 25,000 labeled for training (balanced between positive and negative)
  - 25,000 for testing

---

## ⚙️ Technologies Used

- **Python 3.9+**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **NLTK** (for tokenization and preprocessing)

---

## 🔄 Workflow

1. **Text Preprocessing**
   - Lowercasing
   - Removing HTML tags and punctuation
   - Tokenization and padding sequences

2. **Model Building**
   - Embedding Layer
   - LSTM Layer
   - Dense Output Layer (Sigmoid activation for binary classification)

3. **Model Training**
   - Trained with binary cross-entropy loss and Adam optimizer
   - Evaluation on test dataset

4. **Performance Metrics**
   - Accuracy
   - Loss curves (training vs. validation)

---

## 📊 Results

- Achieved **87% accuracy** on the test set.
- LSTM model successfully learned sentiment patterns from review texts.

---
