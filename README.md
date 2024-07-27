
# Sentiment Analysis

This project focuses on sentiment analysis of tweets using various machine learning models. The goal is to classify the sentiment of the tweets as positive or negative.


## Project Structure

The project is structured as follows:

- Data Loading and Exploration
- Data Preprocessing
- Model Training and Evaluation


# Sentiment Analysis

This project focuses on sentiment analysis of tweets using various machine learning models. The goal is to classify the sentiment of the tweets as positive or negative.


## Usage

- Data Loading and Exploration
  - Load the dataset and explore its structure.
  - Check for null values and data distribution

```python
import pandas as pd

DATASET_COLUMNS = ['target', 'ids', 'date', 'flag', 'user', 'text']
DATASET_ENCODING = "ISO-8859-1"
df = pd.read_csv('path/to/dataset.csv', encoding=DATASET_ENCODING, names=DATASET_COLUMNS)

```
- Data Preprocessing
  - Clean and preprocess the text data.
  - Perform tokenization, lemmatization, and vectorization.
- Model Training and Evaluation
  - Train different models such as LinearSVC, BernoulliNB, and LogisticRegression.
  - Evaluate the models using confusion matrix and classification report.




## Model Results:
The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score.



![Logo](https://pics.io/preview/66a4e727fbc934f629bf2f49/thumbnail)

![Logo](https://pics.io/preview/66a4e954fbc934f629bf2f4f/thumbnail)
## Conclusion

The project demonstrates the process of building a sentiment analysis model using machine learning techniques. The provided code can be further optimized and expanded for more complex sentiment analysis tasks.

