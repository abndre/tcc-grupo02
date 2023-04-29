# tcc-grupo02

# 1. pacotes python necessarios

```
pip install -r requirements.txt
```

Crie uma conta no twitter, e crie um app: e preenche os dados no arquivo [config.ini](config.ini)

```
[twitter]
api_key=''
api_key_secret=''
bearer_token=''
access_token=''
access_token_secret=''
```

Portal do app do twitter: https://developer.twitter.com/en/portal/dashboard


# 2. Pasta Data

Na pasta [data/influencer_data](data/influencer_data/) temos os dados referentes a quantidade de seguires e twitter do influencer, que esta sendo executado pelo [notebook/coletando_tweets_influencer.ipynb](notebook/coletando_tweets_influencer.ipynb)

Na pasta [data/influencer_tweets](data/influencer_tweets/) temos os dados referentes aos tweets feitos pelos influencer [notebook/coletando_tweets_influencer.ipynb](notebook/coletando_tweets_influencer.ipynb)

Na pasta [data/tweet_iteracoes](data/tweet_iteracoes/) temos os dados as iteracoes sobre um tweeter.

# 3. Analise de dados

Na pasta [analise-de-dados](analise-de-dados), temos as principais analise do trabalho:

## 3.1 Analise dos influencer

[Arquivo](/analise-de-dados/Analise%20de%20dados%20dos%20Influencer.ipynb)

## 3.2 Analise dos tweets dos influencer

[Arquivo](/analise-de-dados/Analise%20de%20dados%20dos%20Twettes%20dos%20influencer.ipynb)

## 3.3 Analise da iteracao dos tweets dos influencer pela comunidade

[Arquivo](/analise-de-dados/Analise%20de%20dados%20das%20iteracoes%20dos%20tweets.ipynb)