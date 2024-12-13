# stock
# Stock Market News Analysis

This project analyzes stock market news articles by processing their headlines and publication data. The goal is to uncover publication trends, perform sentiment analysis, and extract key topics or events related to stock market movements.

## Tasks Completed

### 1. **Data Preprocessing**
- Loaded the dataset containing stock market news articles.
- Cleaned and formatted the `publication_date` column to ensure it is in `datetime` format.
- Set the `publication_date` as the index to enable time-series analysis.

### 2. **Publication Frequency Analysis**
- Resampled the data by day to track the number of articles published on each specific date.
- Visualized publication frequency to identify trends, periodicity, and potential spikes related to market events.

### 3. **Sentiment Analysis**
- Preprocessed article headlines by tokenizing text, converting it to lowercase, and removing stopwords.
- Applied sentiment analysis to classify headlines into **positive**, **negative**, or **neutral** categories.
- Visualized sentiment distribution over time to understand shifts in market sentiment.

### 4. **Keyword and Topic Extraction**
- Used Natural Language Processing (NLP) techniques to tokenize and clean text, removing stopwords.
- Identified the most common words in the headlines to uncover significant keywords, such as "FDA approval" or "price target," that could indicate key market events.

### 5. **Handling Large Files**
- Managed large datasets by using **Git Large File Storage (LFS)** to handle files exceeding GitHub’s file size limits.

### 6. **Visualization**
- Created various visualizations, including time series charts for publication frequency and sentiment distributions.
  


