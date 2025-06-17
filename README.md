
# Social Media Sentiment Analysis

This project performs sentiment analysis on social media text data using natural language processing techniques. It classifies user posts or tweets as positive, negative, or neutral based on their content.

## Features

- Text preprocessing and cleaning (stopwords, punctuation, tokenization)
- Sentiment classification using machine learning models
- Real-time prediction interface using Gradio
- Visualization of sentiment distribution (optional if included)

## Technologies Used

- Python
- NLTK / TextBlob / VaderSentiment (depending on implementation)
- Scikit-learn
- Pandas, NumPy
- Gradio (for UI)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Cnu12224/Social_media_sentiment_analysis.git
   cd Social_media_sentiment_analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python app.py
   ```

4. Access the Gradio UI in your browser to test sentiment predictions.

## Note

Ensure you have an active internet connection if you're using pretrained models or online resources.
