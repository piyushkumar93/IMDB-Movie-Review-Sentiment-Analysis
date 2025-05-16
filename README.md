# 🎬 IMDB Movie Review Sentiment Analysis

![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Status](https://img.shields.io/badge/Deployed-Live-brightgreen)

A real-time NLP application that analyzes the **sentiment of IMDB movie reviews** using a custom-trained LSTM model. Users can input a movie review, and the app predicts whether the sentiment is **positive or negative**.

👉 **[Live Demo](https://imdb-movie-review-sentiment-analysiss.streamlit.app/)** on Streamlit Cloud

---

## 🚀 Features

- Trained on the official **IMDB Movie Review dataset**
- Built using a deep learning **LSTM (Long Short-Term Memory)** model
- Real-time **sentiment classification**
- Deployed using **Streamlit** for an interactive UI
- Fast and responsive with an intuitive user experience

---

## 🧠 Tech Stack

- 🐍 Python
- 🧠 TensorFlow / Keras
- 📊 Pandas, NumPy
- ✂️ NLP: Tokenizer, Padding, Stopwords Removal
- 🌐 Streamlit (Frontend & Hosting)
- 📦 Pickle (Tokenizer Serialization)

---

## 📂 Project Structure

IMDB-Movie-Review-Sentiment-Analysis/
├── app.py # Main Streamlit app
├── imdb_lstm_model.h5 # Trained LSTM model
├── tokenizer.pickle # Tokenizer used during training
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🛠️ How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/piyushkumar93/IMDB-Movie-Review-Sentiment-Analysis.git
cd IMDB-Movie-Review-Sentiment-Analysis
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py ```
📷 Sample Predictions
Review	Prediction
“This movie was a complete waste of time.”	❌ Negative
“An absolute masterpiece, totally loved it!”	✅ Positive
“Not bad, but it could've been better.”	🤔 Neutral-leaning (but classified as Pos/Neg)

✅ Future Improvements
Add confidence scores for predictions

Explore transformer-based models (like BERT)

Add model explainability with LIME/SHAP

Improve tokenizer generalization

Add multi-class sentiment (positive/neutral/negative)

🙋‍♂️ Author
Piyush Kumar
🎓 B.Tech (Instrumentation & Control Engineering), NSUT (2023–2027)
📧 piyushkumar-ug23@nsut.ac.in
🔗 LinkedIn | GitHub

⭐ If you liked this project, don’t forget to star it and share!
