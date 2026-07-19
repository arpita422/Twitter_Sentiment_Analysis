# Twitter Sentiment Analysis

A **Twitter Sentiment Analysis** web application built using **Python**, **Machine Learning**, **Natural Language Processing (NLP)**, and **Streamlit**. The application predicts whether a given tweet or text expresses **Positive** or **Negative** sentiment using a trained machine learning model.

---

## 📌 Features

- Analyze sentiment of custom text
- Fetch tweets from a Twitter user *(requires a working tweet source)*
- Predict Positive or Negative sentiment
- Interactive Streamlit web interface
- Text preprocessing using NLTK
- TF-IDF Vectorization
- Machine Learning based sentiment classification

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Pickle

---

## 📂 Project Structure

```
Twitter-Sentiment-Analyzer/
│
├── app.py
├── train_model.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── dataset.csv
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Twitter-Sentiment-Analyzer.git
```

### 2. Open the project

```bash
cd Twitter-Sentiment-Analyzer
```

### 3. Create a virtual environment

Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📊 Machine Learning Workflow

1. Load dataset
2. Clean and preprocess text
3. Remove stopwords
4. Convert text into TF-IDF vectors
5. Train the machine learning model
6. Save the trained model
7. Predict sentiment on new text

---

## 📷 Application Features

- Text sentiment prediction
- Positive/Negative classification
- Interactive web interface
- Real-time prediction
- Fast processing

---

## 📈 Model Used

The project uses:

- TF-IDF Vectorizer
- Scikit-learn Classifier
- NLTK for text preprocessing

---

## 📦 Requirements

```
streamlit
scikit-learn
pandas
numpy
nltk
pickle-mixin
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Text Input
- Prediction Result

---

## 🔮 Future Improvements

- Neutral sentiment prediction
- Live Twitter/X API integration
- Sentiment visualization with charts
- Emoji sentiment detection
- Multi-language support
- Download prediction reports

---

## 👩‍💻 Author

**Arpita Sharma**

B.Tech CSE Student

Narula Institute of Technology

---

## ⭐ If you like this project

Please give this repository a ⭐ on GitHub