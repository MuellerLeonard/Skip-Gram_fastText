# Sentiment analysis with word embeddings and Convolutional Neural Networks

## Datasets:
1. Item "Twitter" dataset
* 61529 different tweets and 300 feature dimensions, with a vocabulary of 73562
* Twitter hashtags crawled: 'ADBE', 'GOOGL', 'AMZN', 'AAPL', 'ADSK', 'BKNG', 'EXPE', 'INTC', 'MSFT', 'NFLX', 'NVDA', 'PYPL', 'SBUX', 'TSLA', 'XEL', 'positive', 'bad' and 'sad'
* 3 different sentiments: positive, negative or neutral
2. Item Pre-trained english word vectors trained with fastText on CommonCrawl and Wikipedia
* 300 Dimensions was reduced down to 200
* Source link: https://fasttext.cc/docs/en/crawl-vectors.html 
3. Item Pre-trained word vectors trained with GloVe on Twitter data
* 27B Tokens 200 Dimensions
* Source link: https://www.kaggle.com/fullmetal26/glovetwitter27b100dtxt

### How to run the code:
1. Item Written in Google Colab Notebook
2. Item Open the latest Notebook 
* Experiments: here the Experiments for the thesis were performed
* ft_text_classification: Demo file for sentiment analysis
3. Item Link the datasets needed to run the code
4. Item For Skip-gram sentence embedding use 1/4th of the "Twitter" dataset, to not overload the RAM
* can be found in Files
