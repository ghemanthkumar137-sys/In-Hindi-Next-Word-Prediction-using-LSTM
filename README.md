# 🇮🇳 Hindi Next Word Prediction using NLP & LSTM

This project focuses on building a **Natural Language Processing (NLP)** model to predict the **next word in Hindi text** using deep learning techniques.

The goal is to understand language patterns and generate the most probable next word based on a given input sequence.

This is an **end-to-end NLP pipeline**, covering everything from data preprocessing to model training and prediction.

---

##  Objectives

- Perform text preprocessing and cleaning for Hindi language
- Convert text into numerical sequences
- Train a deep learning model (LSTM)
- Predict the next word in a sentence
- Build a reproducible NLP pipeline

---

##  Dataset

- Custom Hindi text dataset
- Cleaned and preprocessed sentences
- Used for sequence-based prediction

### Example:
- Input: "भारत एक"
- Output: "सुंदर"

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Removing special characters
- Keeping only Hindi Unicode characters
- Text normalization

### 2. Tokenization
- Converting words into sequences
- Creating vocabulary using tokenizer

### 3. Sequence Generation
- Generating n-gram sequences
- Padding sequences for uniform length

### 4. Model Building
- Embedding Layer
- LSTM Layer
- Dense Output Layer

### 5. Model Training
- Categorical crossentropy loss
- Adam optimizer
- Epoch-based training

### 6. Prediction
- Input sequence → model → next word prediction

---

##  Results

- Model successfully predicts next words in Hindi sentences
- Learns sequence patterns effectively

( You can add accuracy or sample outputs here)

---

##  Tech Stack

- Python 
- NumPy
- Pandas
- TensorFlow / Keras
- NLP Techniques

---

##  Future Improvements

- Use larger dataset (Wikipedia)
- Improve accuracy using GRU / BiLSTM
- Implement Transformer-based models
- Deploy using Streamlit
