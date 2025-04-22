# Sentiment Analysis with RNN - IMDB Dataset

## Project Information

- **Title**: Sentiment Analysis with RNN on IMDB Dataset  
- **Students**:  
  - Abhijeet (055002)  
  - Jhalki Kulshrestha (055017)  
- **Group Number**: 19  

---

## 1. Introduction

This project focuses on building a deep learning pipeline to classify movie reviews as **positive**, **negative**, or **neutral** using the **IMDB dataset**. It leverages a Recurrent Neural Network (RNN) architecture with LSTM layers to effectively capture sentiment in sequential text data.

---

## 2. Dataset Description

The dataset used is the IMDB movie review dataset provided by Keras:

- **Total Reviews**: 50,000  
- **Training Set**: 25,000 reviews  
- **Testing Set**: 25,000 reviews  
- **Labels**: Binary (1 = Positive, 0 = Negative)  
- **Vocabulary Size**: Top 10,000 most frequent words  
- **Data Format**: Each review is encoded as a list of word indices

---

## 3. Project Objectives

- Build an end-to-end NLP pipeline for sentiment classification.
- Implement an LSTM-based RNN model for handling sequential text data.
- Apply proper text preprocessing and transformation techniques.
- Evaluate model performance using metrics like accuracy.
- Create an intuitive sentiment score and emoji output for user-friendliness.

---

## 4. Model Architecture

- **Embedding Layer**: Converts word indices into dense vector representations.
- **Bidirectional LSTM Layer**: Captures contextual dependencies in both forward and backward directions.
- **Dense Output Layer**: Uses sigmoid activation for binary classification.

---

## 5. Implementation Steps

1. **Load IMDB Dataset**: Preprocessed movie reviews with word indices.
2. **Preprocess Data**: Pad sequences to a fixed length for uniform input.
3. **Build and Train Model**: Implement Bidirectional LSTM with embedding layer.
4. **Evaluate Performance**: Test the model with validation data.
5. **Custom Predictions**: Encode new reviews, predict sentiment, and classify into positive, negative, or neutral categories.

---

## 6. Requirements

To run the project, install the required dependencies:

```bash
pip install tensorflow numpy pandas
```

---

## 7. How to Run

1. **Train the model**: Run the Python script to train and save the model.
2. **Predict Sentiment**: Load the saved model and run it on custom reviews.
3. **Review Output**: Sentiment scores and emoji representation.

---

## 8. Results & Performance

- **Evaluation Metric**: Binary accuracy
- **Accuracy Achieved**: ~85% (varies with training settings)
- **Sentiment Categories**:
  - **Positive** (>65% score) 😄
  - **Neutral** (35%-65% score) 😐
  - **Negative** (<35% score) 😞

---

## 9. Conclusion

This project successfully demonstrates sentiment analysis using RNN with LSTM on IMDB reviews. The model captures text sentiment effectively and provides a user-friendly interpretation with sentiment scores and emojis.

---

## 10. Future Improvements

- Fine-tuning hyperparameters for better accuracy.
- Using a pre-trained word embedding like GloVe.
- Expanding to multi-class sentiment analysis.
- Deploying as a web application using Flask or Streamlit.

---

## 11. Authors

- **Abhijeet**  
- **Jhalki Kulshrestha**

Code - Abhijeet
Project Report - Abhijeet & Jhalki
---
