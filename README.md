# 📝 Bilingual Sentiment Analysis (Urdu & English)

This project performs **sentiment analysis** on Urdu and English text using **TF-IDF vectorization** and **Logistic Regression**.  
It can classify text into sentiment categories (e.g., Positive, Negative, Neutral) and supports **interactive testing** via Jupyter Notebook widgets.

---

## 📌 Project Overview
- **Languages Supported**: Urdu and English
- **Models Used**: Logistic Regression (TF-IDF features)
- **Dataset**: Urdu and English sentiment dataset from Pakistani drama scripts and translations
- **Interactive Testing**: Uses IPython widgets for real-time input and prediction
- **Output**: Classification report, confusion matrix, saved model & predictions file

---

## ✨ Features
- 🧹 **Text Preprocessing** – Removes Urdu punctuation, stopwords, and normalizes text
- 🔤 **TF-IDF Vectorization** – Supports unigrams and bigrams
- 🧠 **Model Training** – Logistic Regression for high accuracy
- 📊 **Evaluation** – Classification report + confusion matrix visualization
- 💾 **Model Saving** – Save and reload trained models for later use
- 🖥️ **Interactive UI** – Enter Urdu or English text to get instant sentiment prediction

---

## 🛠️ Tech Stack
- **Python** 3.x
- **Pandas**
- **NLTK** (tokenization & stopwords)
- **scikit-learn**
- **Matplotlib** & **Seaborn**
- **ipywidgets** (interactive testing)
- **Pickle** (model saving/loading)

---

## 📂 Dataset
Your dataset must have at least the following columns:
- `Urdu Sentiment` → Urdu text
- `Sentiment` → Sentiment label (Positive, Negative, Neutral)

Example:
| Urdu Sentiment           | Sentiment   |
|--------------------------|-------------|
| یہ فلم بہت اچھی ہے        | Positive    |
| یہ کہانی بورنگ تھی       | Negative    |

📌 **Dataset Available on Kaggle**: [Urdu-English Drama Dataset](https://www.kaggle.com/code/mzaid990447)

---

## ⚙️ Installation

```bash
pip install pandas nltk scikit-learn matplotlib seaborn ipywidgets
