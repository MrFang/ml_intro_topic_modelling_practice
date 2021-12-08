При подготовке ноутбука использовались материалы:
1. [LDA topic modelling lenta Kaggle](https://www.kaggle.com/genyagree/lda-topic-modelling/notebook)
2. [LDA topic modelling visualization](https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0)
3. [LDA topic modelling](https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0)

# Установка окружения
```
conda create --name topic_modelling_2 python=3.7
conda activate topic_modelling_2
conda install -c conda-forge notebook
conda install pandas
conda install -c conda-forge wordcloud
conda install -c anaconda gensim
conda install -c anaconda nltk
conda install smart_open==2.0.0

pip install pyldavis
pip install pymorphy2
```
# Данные
## Корпус новостей с Lenta.Ru
  [Ссылка для скачивания](https://www.kaggle.com/yutkin/corpus-of-russian-news-articles-from-lenta)
  
  Распакуйте `lenta-ru-news.csv` файл в папку `data`
## Корпус постов про политику с Пикабу
[Ссылка для скачивания](https://www.kaggle.com/atomin/pikabu-politic-posts)
  
  Распакуйте `pikabu_posts.csv` файл в папку `data`
