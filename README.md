# Fake News Detection

This Python script is designed to classify a given text as either legitimate or fake news using a pre-trained machine learning model. The model is based on a logistic regression algorithm and is capable of predicting whether a piece of text is likely to be a legitimate or fake news article.

## Dataset

- **Dataset Name**: Fake News dataset
- **Data Source**: [upload on git]
- The dataset contains the following attributes:
  - Feature columns: Raw text data.
  - Target column: Binary variable (1 for legitimate, 0 for fake news).

## Project Structure

- **README.md**: Documentation of the project.
- **fake_news_detection.py**: Python script for detecting fake news.
- **nlppr.joblib**: Pre-trained logistic regression model for fake news detection.
- **tfidf_vectorizer.pkl**: Pre-trained TF-IDF vectorizer for text transformation.

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd fake-news-detection

2. Create a virtual environment (recommended) and install the required dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows, use: venv\Scripts\activate

## Usage
` Clone this repository to your local machine.

`Ensure you have the pre-trained model ('nlppr.joblib') and TF-IDF vectorizer ('tfidf_vectorizer.pkl') in the same directory as the script ('main.py').

`Open a command prompt or terminal and navigate to the directory where the script is located.

`Run the script with the -value argument followed by the news article text you want to classify.

## For example:
      ```
         python main.py -value "House Dem Aide: We Didn’t Even See Comey’s Letter Until Jason Chaffetz Tweeted It"

## Model Training
The project uses a natural language processing model for classifying news articles. The pre-trained model is saved as 'nlppr.joblib', and the TF-IDF vectorizer is saved as 'tfidf_vectorizer.pkl'.

## Results
The project provides predictions for the reliability of news articles based on the input text. The performance of the model may vary depending on the dataset used.

## Future Improvements
There are several ways to improve the model and the project:

-Explore more advanced natural language processing techniques.

-Fine-tune hyperparameters for better model performance.

-Gather more labeled data for improved accuracy.
## References

- Author: Mirza Salman
- Contact: salmansaluu661@gmail.com

Feel free to customize this README to include any additional information you want to provide about the project.

