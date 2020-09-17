# Paper with respect to stock price movement

**Table 1** Type of financial texts leveraged and how are they processed
|Reference       | Text Type     |  Coverage    | Frequency Level  |   Time span   |  Processing   |
| --------------- | :-----------: | :-----------: | :--------------: | :-----------: | :-----------: |
|Picasso（2019)   | Financial News | Stock market  | Minutes  | 03/07/2017-14/06/2018| L&Mc, AffectiveSpace|
|Frank Z. X. (2018)|Social Media   |	Stock market  |	\  | 	08/14/2017-16/11/2017 | Sentic Computing  |
| Kelly (2018)  |  Financial News, Social Media (blogs) |  Equity market,Crude oil market | Days | 18/02/1998-31/07/2015 |  Vectorize with GI dictionary, the Platts glossary and Oil and Gas glossary |
|Malandri(2018) |  Social Media,Article | Stock market | Days | 24/01/2012-02/06/2017 |  \ (Download vectorized sentiment data) |
|Merello(2018) | Financial News | Stock market | Days |	-/08/2017--/03/2018 | L&Mc dictionary |

***


|Reference       | Feature Formatting     |  Model Type     | Implementation  |
| --------------- | :-----------: | :-----------: | :--------------: |
|Picasso（2019） |	Sentiment vectors |	RF, SVM, feed forward NN |	RF with Gini impurity matric,Gaussian kernel SVM, 4 layer NN |
|Frank Z. X. (2018) | Lexicon based sentiment score |	Recurrent Neural Network |	Knowledge-based polarity inference, LSTM |
|Kelly (2018) |	Sentiment vectors |	Rolling window regression,Vector autoregression |	VAR: Financial return is calculated by returns, sentiment, trading volume, VIX return, etc. |
|Malandri(2018) |	7-dimensional vector: closing price, trading volume, number positive, neutral, negative reviews, the change value and the sentiment score |	Random forest classifier, Multi-layer Perceptron, LSTM |	MLP: Three layer network with BP,Stateful LSTM |
|Merello(2018) |	Categories of words: positive, negative, litigious, uncertainty, etc. |	Attention model + LSTM + Dense |	\ |

***

|Reference       | Measurement      |  Performance      | Trading Strategy  |
| --------------- | :-----------: | :-----------: | :--------------: |
|Picasso（2019） |	Trading simulation (20 stocks) |	Maximum 85.2% Annualized Return |	Buy or Sell when the prediction is greater or less than a threshold |
|Frank Z. X. (2018) |	Trading simulation of one period portfolio asset allocation (5 stocks) |	Improve Annualized Return 10% on average |	Reinvest whole capital daily to the fastest-growing asset in the next time period |
|Kelly (2018) |	Trading simulation |	Stock market: AR increased by 4.2%, MD decreased by 4.4%, Crude oil market: AR increased by 25.6%, MD decreased by 28.8% |	Buy or sell according to the sentiment prediction result |
|Malandri (2018) |	Trading simulation | Outperforms the benchmark portfolio: EW portfolio. LSTM is better than others. |	Daily re-allocation according to the prediction for the following day |
|Merello(2018) |	Matthews correlation coefficient (MCC), Accuracy |	Accuracy 62.8%, MCC 0.18 |	Buy or sell according to the prediction |





 
