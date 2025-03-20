# Textual Sentiment Analysis and Steganography Detection

**Unveiling Hidden Messages in Reviews**  
This project combines **Natural Language Processing (NLP)** and **Steganography** to analyze online textual reviews for sentiment and detect potential hidden (steganographic) messages embedded within them.

---

## 🧠 Project Overview

The notebook `NLP_STEGNORGRAPH_Final.ipynb` presents an experimental pipeline that:

1. Performs **sentiment analysis** on review texts using NLP techniques.
2. Applies **steganography detection** to uncover if any suspicious or hidden information is embedded within natural language reviews.

The aim is to explore how everyday-looking textual reviews could potentially be used as carriers for covert communication while still serving as valid user feedback.

---

## 🧹 NLP Preprocessing Steps

To prepare the text data for analysis, the following NLP preprocessing techniques were applied:

- **Lowercasing** – Normalize text for uniformity.
- **Tokenization** – Split reviews into individual words or tokens.
- **Stopword Removal** – Eliminate common words that don't add much meaning (like *is*, *the*, *and*).
- **Lemmatization** – Reduce words to their base or root form (e.g., *running* → *run*).
- **Punctuation Removal** – Clean unnecessary characters.
- **Vectorization** – Convert text into numerical format using methods like TF-IDF or CountVectorizer.

---

## 📁 Contents

- `NLP_STEGNORGRAPH_Final.ipynb` – Jupyter notebook containing the entire workflow:
  - Text preprocessing and cleaning
  - Feature extraction and transformation
  - Sentiment classification (using ML or deep learning models)
  - Steganographic message detection
  - Evaluation and visualization of results

---

## ⚙️ Requirements

Make sure to install the following Python libraries before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk
