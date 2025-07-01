# 🧠 Sentiment Analysis on IMDB Dataset using LSTM

## 📌 Project Overview
This project focuses on building a **sentiment classification model** using the **IMDB dataset** provided by TensorFlow. The model identifies whether a movie review expresses a **positive or negative sentiment**.

## 🚀 Tech Stack & Tools
- Python
- TensorFlow / Keras
- LSTM (Long Short-Term Memory)
- IMDB Dataset (Tokenized)
- Matplotlib (for visualization)

## 🧠 Key Features
- Preprocessed the IMDB review data and padded sequences
- Built a deep learning model using LSTM layers
- Achieved high accuracy through architecture optimization
- Visualized training performance with accuracy and loss plots
- Suitable for real-time review sentiment prediction

##  📊 Model Architecture
```python
Embedding → Dropout → LSTM → Dropout → Dense (sigmoid)

--> 📉 Training Summary
Optimizer: Adam

Loss Function: Binary Crossentropy

Accuracy: Over 87% (with LSTM)

--> 📈 Results
The model generalizes well to unseen data.

Validation accuracy remains stable across epochs.

--> 🔮 Future Improvements
Add pretrained GloVe embeddings

Build a Gradio / Streamlit web app interface

Test on multilingual sentiment datasets

--> 📁 Dataset
IMDB dataset: Inbuilt with TensorFlow

Pre-tokenized with a vocabulary size of 10,000 words
