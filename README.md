# Tracking Progress in FinNLP

## News

FinNLP@EMNLP2021:
- [FinQA: A Dataset of Numerical Reasoning over Financial Data](https://arxiv.org/abs/2109.00122)
FinNLP@AAAI2021:
- [Coupling Macro-Sector-Micro Financial Indicators for Learning Stock Representations with Less Uncertainty](https://www.aaai.org/AAAI21Papers/AAAI-7228.WangG.pdf)
- [Modeling the Momentum Spillover Effect for Stock Prediction via Attribute-Driven Graph Attention Networks](https://www.aaai.org/AAAI21Papers/AAAI-5328.ChengR.pdf)
- [Stock Selection via Spatiotemporal Hypergraph Attention Network: A Learning to Rank Approach](http://34.94.61.102/paper_AAAI-7907.html)
- [DeepTrader: A Deep Reinforcement Learning Approach for Risk-Return Balanced Portfolio Management with Market Conditions Embedding](https://biweihuang.com/publications-2/)
- [Deep Portfolio Optimization via Distributional Prediction of Residual Factors](https://arxiv.org/pdf/2012.07245.pdf)
- [Commission Fee Is Not Enough: A Hierarchical Reinforced Framework for Portfolio Management](https://arxiv.org/pdf/2012.12620.pdf)

## Table of contents
- [Financial Index Forecasting](/NLP-based_Financial_Forecasting/README.md)
- [Financial Event Prediction](/Financial_Event_Prediction/README.md)
- [Financial Risk Analysis](/Financial_Risk_Analysis/README.md)
- [Financial Text Mining](/Financial_Text_Mining/README.md)
- [Fraud Detection](/Fraud_Detection/README.md)
- [Blockchain](/Blockchain/README.md)

## Open-source Datasets
- [Multi-modal Earnings Conference Call Datasets](/Earnings_Call_Datasets/README.md)
- [Pre-trained Word Embedding on Financial Communication Text](https://github.com/yya518/FinBERT)
- [Reuters TRC2 dataset](https://trec.nist.gov/data/reuters/reuters.html)
- [Financial Phrase Bank](https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10)

## Open-source Datasets (In Chinese)


| 数据名称  | 数据字段 | 样本量 | 总量 |  下载链接 |
| ----- |  ------ | ----- | ----- | ----- |
| 企业工商信息 | `名称`,`公司名称`,`公司介绍`,`工商`,`地址`,`工商注册id`,`成立时间`,`法人代表`,`注册资金`,`统一信用代码`,`网址` | 1万 | 50万 - (上市及中小型企业) |[下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E5%B7%A5%E5%95%86%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC10K.xlsx) | 
| 金融讯息新闻 | `title-新闻标题`,`content-新闻内容`,`pub_ts-发稿日期` | 2万 | 210万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E4%B8%93%E6%A0%8F%E8%B5%84%E8%AE%AF%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC10k.xlsx) |
| 专栏资讯 | `title-新闻标题`,`content-新闻内容`,`pub_ts-发稿日期` | 1万 | 58万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E4%B8%93%E6%A0%8F%E8%B5%84%E8%AE%AF%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC10k.xlsx) |
| 投资机构信息 | `机构名称`,`介绍`,`行业`,`规模`,`轮次`| 1K | 3万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E6%8A%95%E8%B5%84%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC1k.xlsx) |
| 投资事件 | `事件资讯`,`投资方`,`融资方`,`融资事件`,`轮次`,`金额` | 2K | 7万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E6%8A%95%E8%B5%84%E4%BA%8B%E4%BB%B6%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC2k.xlsx) |
|36氪新闻| `title-新闻标题`,`content-新闻内容`,`url-网址` |1万|11万|[下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP36kr新闻数据集10k.xlsx)

## Research Topics
### Financial Index Forecasting (Financial News/Social Media/Professional Documents/Earning Conference Call/10K-10Q Report)
Tasks:
1) Classification (Binary/Triple Classification)
2) Regression (MSE): Volatility Prediction; Return Prediction

### Financial Documents Analysis (Professional Documents)
Tasks:
Correlation (ACL-19: Financial Analysts Rating-Earning Conference Call)


### Investor Sentiment Analysis (Social Media/Financial News)
Tasks:
Sentiment Analysis (Binary Classification / Five-class Classification)


### Financial Event Prediction (Bankrupt/IPO/M&A)
Tasks:
Classification (Event Prediction)
Sentiment Analysis (Market Sentiment Prediction)

