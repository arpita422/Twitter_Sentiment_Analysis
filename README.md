# Twitter Sentiment Analyzer

A simple **Twitter Sentiment Analyzer** built using **Python**, **Machine Learning**, and **Natural Language Processing (NLP)**. This project predicts whether a given tweet or text has a **Positive** or **Negative** sentiment using a pre-trained machine learning model.

The model was developed and trained in **Jupyter Notebook**, while the application is deployed using **Streamlit**.

---

## 📌 Features

- Analyze the sentiment of text or tweets.
- Predicts **Positive** or **Negative** sentiment.
- Interactive web interface built with Streamlit.
- Uses a trained Machine Learning model.
- Fast and easy to use.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Streamlit
- Scikit-learn
- NLTK
- Pickle

---

## 📂 Project Structure

```
Twitter-Sentiment-Analyzer/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Twitter-Sentiment-Analyzer.git
```

### 2. Open the project folder

```bash
cd Twitter-Sentiment-Analyzer
```

### 3. Install the required libraries

```bash
pip install streamlit scikit-learn nltk pandas numpy
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your default web browser.

---

## 📊 Working

1. Enter text or a tweet.
2. The text is preprocessed using NLP techniques.
3. The trained TF-IDF vectorizer converts the text into numerical features.
4. The Machine Learning model predicts the sentiment.
5. The result is displayed as **Positive** or **Negative**.

---

## 🤖 Machine Learning Model

- Text Preprocessing
- Stopword Removal
- TF-IDF Vectorization
- Trained Sentiment Classification Model
- Model stored as `model.pkl`
- Vectorizer stored as `vectorizer.pkl`

---

## 📷 Output

The application displays:

- Input Text
- Predicted Sentiment
- User-friendly Streamlit Interface

---

## 🔮 Future Improvements

- Neutral sentiment prediction
- Live Twitter/X API integration
- Sentiment visualization using charts
- Multi-language support
- Improved tweet fetching

---

## 👩‍💻 Author

**Arpita Sharma**

B.Tech CSE Student

Narula Institute of Technology

---

## ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star** on GitHub.
