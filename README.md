# Sentiment analysis with word embeddings and Convolutional Neural Networks

## Datasets:
1. "Twitter" dataset
  * 61529 different tweets and 300 feature dimensions, with a vocabulary of 73562
  * Twitter hashtags crawled: 'ADBE', 'GOOGL', 'AMZN', 'AAPL', 'ADSK', 'BKNG', 'EXPE', 'INTC', 'MSFT', 'NFLX', 'NVDA', 'PYPL', 'SBUX', 'TSLA', 'XEL', 'positive', 'bad' and 'sad'
  * 3 different sentiments: positive, negative or neutral
2. Pre-trained english word vectors trained with fastText on CommonCrawl and Wikipedia
   * 300 Dimensions was reduced down to 200
  * Source link: https://fasttext.cc/docs/en/crawl-vectors.html 
3. Pre-trained word vectors trained with GloVe on Twitter data
  * 27B Tokens 200 Dimensions
  * Source link: https://www.kaggle.com/fullmetal26/glovetwitter27b100dtxt

### How to run the code:
1. Written in Google Colab Notebook
2. Download the following files:
  * "Twitter" dataset, found in the folder **files** 
  * FastText word vectors (see link, needs to be reduced to 200 dimensions)
  * GloVe word vectors (see link)
  * sentqs_dataset.npz link: https://cloud.fhws.de/index.php/s/8BwgMykHEf9BwAd
2. Open the latest Notebook 
  * Experiments: here the Experiments for the thesis were performed
  * ft_text_classification: Demo file for sentiment analysis
3. Link the datasets needed to run the code
4. For Skip-gram sentence embedding use 1/4th of the "Twitter" dataset, to not overload the RAM
  * can be found in the folder **files**
