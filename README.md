# Sentiment Classifier

A deep learning–based sentiment analysis model built with TensorFlow and Keras. This project trains a binary classifier on the IMDB dataset to predict whether a given text expresses positive or negative sentiment. The model architecture leverages tokenization, padding, and a Bidirectional LSTM layer to capture the context of natural language inputs.

Although trained on movie reviews, the model is easily adaptable to customer feedback, product reviews, or support ticket classification in real-world applications.

## Key Features

- Binary sentiment classification (positive or negative)
- Built with TensorFlow 2 and Keras
- Uses Bidirectional LSTM for sequence modeling
- Trained on 50,000 IMDB reviews from `tensorflow_datasets`
- Easily extendable to other text datasets and business domains

## Project Contents

- `customer-sentiment-analyser.ipynb` – Jupyter notebook with full training, evaluation, and inference code
- `README.md` – Project overview and usage information

## Requirements

- Python 3.7+
- TensorFlow 2.x
- TensorFlow Datasets
- NumPy

Install dependencies:

```
pip install tensorflow tensorflow-datasets numpy
```

## Author

Oshoumya Verma  
Final-year Computer Science student, MIT Manipal  
[GitHub](https://github.com/oshov) • [LinkedIn](www.linkedin.com/in/osho-verma) • oshoverma26@gmail.com
