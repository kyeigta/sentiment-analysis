# Sentiment Analysis Deep Dive

This repository contains a collection of Jupyter Notebooks exploring different sentiment analysis techniques, ranging from lexicon-based approaches to advanced deep learning models, applied across various datasets.

---

## 🚀 Notebooks Overview

### 1. Lexicon & Rule-Based Approaches
*   **`Sentiment_Analysis_using_Text_Blob.ipynb`**
    *   **Library:** `TextBlob`
    *   **Description:** A quick and efficient baseline model utilizing TextBlob's built-in lexicon to calculate polarity and subjectivity scores on text datasets.

### 2. Deep Learning & Sequential Models (RNNs)
*   **`rnn_june_3.ipynb` & `rnn_appistd.ipynb`**
    *   **Library:** `TensorFlow` / `Keras`
    *   **Description:** Implementation of Recurrent Neural Networks (RNNs) to capture sequential dependencies in text for more nuanced sentiment classification.
*   **`sentiment_anlaysis.ipynb`**
    *   **Description:** Core deep learning workflow handling data preprocessing, tokenization, and model evaluation.

### 3. Transformer-Based Models (State-of-the-Art)
*   **`BERTipynb.ipynb`**
    *   **Library:** `Hugging Face Transformers` / `PyTorch` or `TensorFlow`
    *   **Description:** Fine-tuning a pre-trained BERT (Bidirectional Encoder Representations from Transformers) model to achieve high-accuracy sequence classification.

### 4. Data Collection
*   **`code_to_collect_tweets.ipynb`**
    *   **Description:** Scraper/API script used to gather real-world Twitter data for training and testing the sentiment models.

---

## 🛠️ Setup & Installation

To run these notebooks locally, clone the repository and install the required dependencies:

```bash
git clone [https://github.com/kyeigta/sentiment-analysis.git](https://github.com/kyeigta/sentiment-analysis.git)
cd sentiment-analysis
pip install -r requirements.txt
