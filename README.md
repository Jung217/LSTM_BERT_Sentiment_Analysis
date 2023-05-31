## Network Sentiment Analysis Based on LSTM & BERT Machine Learning
### 基於 LSTM &amp; BERT 機器學習之網路輿情分析

> 「縱浪大化中，不喜亦不懼。應盡便須盡，無復獨多慮。」－陶淵明〈神釋〉

> 「AI科技發展快速，其無非是世界一道不可阻攔的洪流，人們應保持開放樂見的心態面對，在一波波的浪潮中，尋等機會，一舉站上AI的浪頭上，盡享AI帶來的便利及紅利。」－CCJ
<hr/>

### Introduction
* [Detail Report](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/blob/main/Network%20Sentiment%20Analysis%20Based%20on%20LSTM%20%26%20BERT%20Machine%20Learning_By_CCJ.pdf) : All the details about this project
* [LSTM Model](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/LSTM)
    * [LSTM.ipynb](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/blob/main/LSTM/LSTM.ipynb) : Main training and testing program 
    * [input](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/LSTM/input)
        * [apply-jieba-tokenizer](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/LSTM/input/apply-jieba-tokenizer) : Tokenizer and testing data 
        * [fake-news-pair-classification-challenge](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/LSTM/input/fake-news-pair-classification-challenge) : Origin training data
* [BERT Model](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/BERT)
    * [BERT.ipynb](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/blob/main/BERT/BERT.ipynb) : Main training and testing program
    * [commentss.csv](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/blob/main/BERT/commentss.csv) : Training, Testing and validation data
* [Shopee Crawler(蝦皮爬蟲程式)](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/Shopee%20Crawler) 
    * [shopee.ipynb](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/blob/main/Shopee%20Crawler/shopee.ipynb) : Crawler program to get data from [Shopee](https://shopee.tw/)
    * [Data](https://github.com/Jung217/LSTM_BERT_Sentiment_Analysis/tree/main/Shopee%20Crawler/Data) : Commodity data from shopee

<hr/>

### Reference
[Kaggle-WSDM - Fake News Classification](https://www.kaggle.com/competitions/fake-news-pair-classification-challenge)

[LeeMeng:進擊的 BERT：NLP 界的巨人之力與遷移學習](https://leemeng.tw/attack_on_bert_transfer_learning_in_nlp.html)

[Evaluation Metrics : 分類模型](https://medium.com/ai%E5%8F%8D%E6%96%97%E5%9F%8E/evaluation-metrics-%E5%88%86%E9%A1%9E%E6%A8%A1%E5%9E%8B-ba17ad826599)

[「蝦皮爬蟲」｜商品資料＋留言評論](https://marketingliveincode.com/classification/crawler_king/110)