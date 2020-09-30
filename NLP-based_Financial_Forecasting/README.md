# Paper with respect to NLP-based Financial Forecasting

* Sample Financial Events:
  * [Stock Price Movement Prediction](#stock-price-movement-prediction)
  * [Stock Return Forecasting](#stock-return-forecasting)
  * [Portfolio Managament](#portfolio-management)
  * [Trading Strategy Analysis](#trading-strategy-analysis)


## Stock Price Movement Predicion
| Reference | Paper | Data Source | Model | Evaluation Metric(s) | Time Period | Contributions | Venue |
|-|-|-|-|-|-|-|-|
| Merello(2018) | [Investigating Timing and Impact of News on the Stock Market](https://ieeexplore.ieee.org/document/8637369) | Financial News | 	Attention model + LSTM + Dense | Accuracy, MCC | -/08/2017- -/03/2018 | Accuracy 62.8%, MCC 0.18 | ICDM Workshops 2018 |

## Stock Return Forecasting
| Reference | Paper | Data Source | Model | Evaluation Metric(s) | Time Period | Contributions | Venue |
|-|-|-|-|-|-|-|-|
| Kelly (2018)  | [Estimating the impact of domain-specific news sentiment on financial assets](https://www.sciencedirect.com/science/article/abs/pii/S0950705118301230) | Dow Jones Industrial Average and West Texas Intermediate crude oil | Rolling window regression,Vector autoregression | Stock market: AR increased by 4.2%, MD decreased by 4.4%, Crude oil market: AR increased by 25.6%, MD decreased by 28.8% | 18/02/1998-31/07/2015 | present a method and implementation that analyses the content of news using multiple dictionaries that accounts for the specific use of terminology in a given domain | Knowledge-Based Systems |


## Portfolio Management
| Reference | Paper | Data Source | Model | Evaluation Metric(s) | Time Period | Contributions | Venue |
|-|-|-|-|-|-|-|-|
|Malandri(2018) | [Public Mood–Driven Asset Allocation: the Importance of Financial Sentiment in Portfolio Management](https://link.springer.com/article/10.1007/s12559-018-9609-2)| NYSE companies | Random forest classifier, Multi-layer Perceptron, LSTM | Trading simulation | 24/01/2012-02/06/2017 | Discuss how public mood affect portfolio management | Cognitive Computation | 
|Frank Z. X. (2018)|[Intelligent Asset Allocation via Market Sentiment Views](https://ieeexplore.ieee.org/document/8492384) |  StockTwits | Recurrent Neural Network | Trading simulation of one period portfolio asset allocation (5 stocks) | 08/14/2017-16/11/2017 | A novel neural network design, built upon an ensemble of evolving clustering and long short-term memory, is used to formalize sentiment information into market views.These views are later integrated into modern portfolio theory through a Bayesian approach. | IEEE Computational Intelligence Magazine | 
|Picasso（2019)   | [Technical analysis and sentiment embeddings for market trend prediction](https://www.sciencedirect.com/science/article/abs/pii/S0957417419304142)| NASDAQ 100 companies | RF, SVM, feed forward NN | Trading simulation (20 stocks) | 03/07/2017-14/06/2018 | Maximum 85.2% Annualized Return | Expert Systems with Applications | 


## Trading Strategy Analysis
| Reference | Paper | Data Source | Model | Evaluation Metric(s) | Time Period | Contributions | Venue |
|-|-|-|-|-|-|-|-|
