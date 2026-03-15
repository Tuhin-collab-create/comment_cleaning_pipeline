# Twitter Sentiment Analysis & Text Preprocessing

## Project Overview
This project implements an advanced Natural Language Processing (NLP) pipeline specifically designed for social media data. It focuses on transforming noisy Twitter text into a standardized format by handling HTML entities, emojis, contractions, and slang. The pipeline prepares the data for high-performance machine learning models through rigorous tokenization and lemmatization.

## Dataset
**Twitter Sentiments Dataset**: A CSV file containing raw tweets and their corresponding sentiment labels.

## Technologies Used
* **Language:** Python
* **NLP Libraries:** NLTK (WordNetLemmatizer, Tokenization)
* **Data Handling:** Pandas, NumPy
* **Text Processing:** Regex, Emoji, HTML
* **Visualization:** Matplotlib

## Key Features
* **Noise Cleaning:** Removes HTML tags, URLs, and special characters.
* **Contraction Mapping:** Expands words like "can't" to "cannot" to preserve sentiment meaning.
* **Lemmatization:** Reduces words to their base dictionary form.
* **Visual Analytics:** Generates frequency distributions of top emotional tokens.

## How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
