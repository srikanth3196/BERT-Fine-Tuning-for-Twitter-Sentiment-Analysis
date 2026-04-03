# BERT Fine-Tuning for Twitter Sentiment Analysis

## 📌 Project Overview
This repository contains a Python project where we fine-tune a pre-trained **BERT (bert-base-uncased)** model for **Twitter sentiment analysis** using the **Sentiment140 dataset**.  

The project covers:

- Data preprocessing (cleaning tweets, removing URLs, mentions, and special characters)
- Train/validation/test split
- Tokenization using Hugging Face `bert-base-uncased` tokenizer
- Fine-tuning BERT for text classification
- Model evaluation using **Accuracy, Precision, Recall, F1 Score**
- Confusion matrix visualization
- Experiments with freezing BERT layers or partial fine-tuning

---

## 🛠️ Tools & Technologies
- **Python 3.10+**
- **PyTorch**
- **Hugging Face Transformers**
- **scikit-learn**
- **pandas, numpy**
- **matplotlib, seaborn**
- **Jupyter Notebook / Google Colab**

---

## 📂 Dataset
The dataset used is **[Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)**.

- Contains ~1.6 million labeled tweets  
- Labels:  
  - `0` → Negative  
  - `4` → Positive (converted to `1` in preprocessing)  

> For faster experimentation, a smaller subset (50k samples) was used.


