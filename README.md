# 🎬 IMDB-Sentiment-Analysis

A web-based sentiment analysis app that classifies IMDB movie reviews as **positive** or **negative** using a Recurrent Neural Network (RNN). The model is trained on the IMDB dataset and deployed using **Streamlit**.

---

## 🚀 Features

- 🧠 **Recurrent Neural Network (RNN)** trained on IMDB movie reviews
- 🔠 Accepts raw review text input
- 📊 Outputs real-time sentiment classification and confidence score
- 🌐 Interactive front-end powered by **Streamlit**
- 🛠️ Easily deployable locally or on the cloud

---

## 🧠 Model Details

- **Architecture:** Simple RNN with ReLU activation
- **Input:** Tokenized and padded text reviews
- **Output:** Sigmoid score indicating review sentiment
- **Training Dataset:** [IMDB Movie Review Dataset]([https://ai.stanford.edu/~amaas/data/sentiment/](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/imdb))

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Streamlit** (for UI)
- **NumPy, h5py, JSON** (utilities)

---

## 📦 Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/IMDB-Sentiment-Analysis.git
cd IMDB-Sentiment-Analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run main.py
```

---

## 📁 Project Structure

```
├── main.py                # Streamlit web app
├── simple_rnn_imdb.h5     # Pre-trained RNN model
├── README.md              # This file
├── requirements.txt       # Required Python libraries
```

---

## 📊 Sample Prediction

```
Review: "The movie was absolutely wonderful, I loved it!"
Prediction: Positive
Confidence: 0.87
```

---

## 📌 Notes

- If you encounter a `time_major` error while loading the model, it is automatically patched via code.
- You can save the fixed model after first load to skip the patch in future runs.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests for improvements.

---

## 🙌 Acknowledgements

- [Stanford IMDB Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- TensorFlow / Keras team
- Streamlit for effortless web apps
