# Custom Text Sentiment Analysis using BERT

This project provides a comprehensive solution for sentiment analysis using BERT (Bidirectional Encoder Representations from Transformers). It classifies movie reviews into positive or negative sentiments and includes features for data preprocessing, model training, evaluation, and sentiment prediction.

## Features

- **Data Handling**: Automatically downloads and extracts the Stanford IMDB dataset.
- **Text Preprocessing**: Cleans and prepares text data by removing HTML tags and special characters.
- **Model Training**: Uses BERT for sequence classification to accurately predict sentiment.
- **Evaluation**: Assesses model performance with metrics such as accuracy and generates classification reports.
- **Visualization**: Includes sentiment distribution charts and word clouds for positive and negative reviews.
- **Sentiment Prediction**: Provides functionality to predict sentiment for custom text inputs.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ishaan2692/Custom-Text-Sentiment-Analysis-using-BERT-.git
   cd Custom_Text_Sentiment_Analysis
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare the Dataset**: The dataset is automatically downloaded and extracted.
2. **Run Analysis**: Open and run `BERT_sentiment_analysis.ipynb` in a Jupyter notebook environment to perform data preprocessing, model training, and evaluation.
3. **Predict Sentiments**: Use the `Get_sentiment` function to analyze and predict sentiments of new text reviews.

## Examples

```python
review = "The movie was fantastic!"
print(Get_sentiment(review))
```
