# lstm_sentiment_classification_template
lstm 和 bert的模板


lstm ... .ipynb这个文件是用lstm在pytorch1.3.1上实现的情感分类，运用起来比较简单，基本准备好数据集就行了（必备的：train训练集，test测试集），非必要文件unlabeledtrain（用作word2vec语料库训练）

因此只要保证切分数据成规范化的x和y即可复用代码了

数据可以参考kaggle的： https://www.kaggle.com/c/word2vec-nlp-tutorial/data
