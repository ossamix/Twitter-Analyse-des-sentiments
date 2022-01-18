# Twitter Sentiment Analysis Using ELK Stack and Python
Analyse et calcule du sentiment de chaque tweet et créer un tableau de bord en temps réel à l'aide de la base de données Elasticsearch et de Kibana pour visualiser les résultats.

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
