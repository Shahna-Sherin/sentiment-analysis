# 🧠 Sentiment Analysis with Gradio Web App

This project uses a machine learning model to classify text (like tweets, reviews, or messages) as **Positive** or **Negative**.

Built during an internship to demonstrate:
- Text preprocessing (NLTK)
- TF-IDF vectorization
- Logistic Regression model
- Live prediction using **Gradio**

## 🚀 Features
- Clean user interface using Gradio
- Real-time text classification
- Model trained using `LogisticRegression`
- Deployed from Google Colab

## 📂 Files
| File | Description |
|------|-------------|
| `Sentiment_Analysis_Final.ipynb` | Colab notebook for training and testing |
| `app.py` | Gradio web app code |
| `requirements.txt` | Python libraries needed |
| `sentiment_model.pkl` | Trained sentiment model |
| `tfidf_vectorizer.pkl` | Fitted TF-IDF vectorizer |

## 📦 How to Run the App (Locally)
```bash
pip install -r requirements.txt
python app.py
