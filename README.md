# Twitter Sentiment Analysis Using ELK Stack and Python
Analyze and calculate the sentiment of each tweet and create a real-time dashboard using the Elasticsearch database and Kibana to visualize the results.

## Prerequisites
* Install and setup [ELK Stack](https://www.elastic.co/products/elasticsearch)
    * Elasticsearch
    * Kibana
* Python packages
    * Tweepy
        ```
        pip install tweepy
        ```
    * TextBlob
        ```
        pip install -U textblob
        python -m textblob.download_corpora
        ```
    * Elasticsearch-py
        ```
        pip install elasticsearch
        ```
* Set up [Twitter streaming API](https://developer.twitter.com/en/docs)
