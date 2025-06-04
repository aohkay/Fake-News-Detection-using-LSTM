Fake News Detection using LSTM

This project demonstrates a deep learning approach to detect fake news using an LSTM model built with TensorFlow and Keras.

Dataset
- [Kaggle Dataset](https://www.kaggle.com/datasets/sahideseker/fake-news-detection)
- 1000 samples labeled as "real" or "fake"

Process
1. Data Preprocessing (stopwords, lemmatization)
2. Tokenization and Padding
3. Model Architecture: Embedding + LSTM + Dropout + Dense
4. Evaluation with Accuracy, F1-Score, and Confusion Matrix

Results
- Accuracy: 56.5%
- F1 Score: 72%
- All predictions biased toward "real"

Future Work
- Improve model with more data
- Try BERT, RoBERTa, or BiLSTM
- Use oversampling or class weighting

Built with
- TensorFlow / Keras
- NLTK
- Scikit-learn
- Matplotlib / Seaborn

Alican Ohkay
