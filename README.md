# IMDB-Sentiment-Explorer-From-Reviews-to-Insights
Classify IMDB movie reviews as positive or negative using Logistic Regression and TF-IDF. Achieves 88.87% accuracy with clean, modular code. Includes setup instructions and future ideas for improvement.
# IMDB Sentiment Explorer From Reviews to Insights
This project performs sentiment analysis on IMDB movie reviews using Logistic Regression and TF-IDF for feature extraction. The goal is to classify reviews as either positive or negative based on their text content.

## Features
- Text preprocessing (tokenization, lemmatization, stopwords removal)
- Feature extraction using TF-IDF
- Logistic Regression for sentiment prediction
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score

## Dataset
The dataset (`imdb_reviews.csv`) contains:
- **Review Text**: Raw text of movie reviews
- **Sentiment Labels**: Binary labels (`positive` or `negative`)

Download the dataset from [Kaggle](https://www.kaggle.com/datasets).

## Evaluation Metrics
Example output:

Accuracy: 0.8887

Classification Report:
               precision    recall  f1-score   support
           0       0.90      0.88      0.89      4961
           1       0.88      0.90      0.89      5039
    accuracy                           0.89     10000


## Project Structure
``` SentimentFlow/
├── data/ # Dataset folder
│ └── imdb_reviews.csv # Dataset file
├── src/ # Source code
│ └── sentiment_analysis.py
├── .gitignore # Ignore unnecessary files
├── README.md # Documentation
└── requirements.txt # Required libraries
```

## Future Improvements
- Experiment with advanced models (e.g., Naive Bayes, SVM, BERT)
- Use word embeddings like Word2Vec or GloVe
- Add visualizations (confusion matrix, ROC curve)
- Deploy as a web app using Flask or Streamlit
## Contributing
Contributions are welcome! Follow these steps:

- Fork the repository
- Create a new branch
- Commit your changes
- Open a pull request
## License
This project is licensed under the MIT License .
