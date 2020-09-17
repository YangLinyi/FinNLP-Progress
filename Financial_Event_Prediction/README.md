# Paper with Finacial Event Prediction

* Sample Financial Events:
  * [Bankrupt](#bankrupt)
  * [Initial Public Offering (IPO)](#ipo)
  * Mergers and Acquisitions (M&A)
  * Delisting

## Bankrupt
| Study | Industry | Source of Data | Sample Size | Models | Time Period | Variable Type |
|-|-|-|-|-|-|-|
| Geng et al. (2015) | Firms | China, CSMAR | 214 | NN, DT, SVM, MV  | 2001–2008  | Accounting  |
| Liang et al. (2016) | Firms, manufacturing, service | Taiwan Economic Journal (TEJ) | 478 | SVM, KNN, NB, CART, MLP  | 1999–2009  | Accounting, market, corporate governance  |
| Olson, Delen, and Meng (2012) | Firms | USA, Compustat | 1321 | DT, logit, MLP, RBFN, SVM  | 2005–2009  | Accounting  |
| Ioannidis, Pasiouras, and Zopounidis (2010) | Banks | 78 countries, Bankscope, World Bank | 944 | UTADIS, MLP, CART, KNN, Ordered logit, stacked models  | 2007–2008  | Accounting, country-level variables  |
| Boyacioglu, Kara, and Baykan (2009) | Banks | Turkey, Banks Association of Turkey | 76 | NN, SVM, MDA, K-means cluster analysis, logit  | 1997–2004  | Accounting  |
| Cecchini et al. (2010) | Firms | USA, Compustat, CRSP | 156 | SVM  | 1994–1999  | MD&A, Altman variables  |
| Kim and Kang (2010) | Firms | Korea | 1458 | MLP + bagging, MLP + boosting  | 2002–2005  | Accounting  |
| Mai et al., (2019) | Firms | USA, CRSP | 11,827 | CNN | 1994-2014 | Accounting  |
| Snow et al. (2019) (1) | Firms | Aukland | 34466 | XGBClassifier | 1977-2016 | Accounting  |
| Snow et al. (2019) (2) | Firms | Aukland | 36544 | LightGBM | 2006-2017 | Accounting  |


## IPO
| Study | Industry | Source of data | Sample size | Models | Time period | Variables Type |
|-|-|-|-|-|-|-|
| Cristóbal Luque et al. (2012) | Firms | USA, AMEX, NASDAQ and NYSE IPOs | 866 | Genetic algorithms | 1999-2010 | Accounting  |
| ZHE XU et al. (2016)  | Firms | USA, intrinio, The Reuters dataset | 20200 | HAN | 2006-2013 | Accounting  |
| Jie et al. (2016)  | Firms | US SEC’s EDGA, CRSP | 513 | FOCAS-IE | 2003-2013 | Accounting  |


## M&A
| Study | Industry | Source of data | Sample size | Models | Time period | Variables Type |
|-|-|-|-|-|-|-|
| Adesoji  et al. (2015) | Firms | Securities Data Corporation (SDC)  | 150 | logit models | 1985–1995  | Food industry |
| Liu et al. (2016)  | Firms | China Securities Journal and the website  | 150 | Hopfield Network  | 2004-2006 | Accounting |
| Chin-Sheng (2012)  | Firms | SDC Platinum database | 689 | Ensemble | 1997–2008 | Accounting  |
| B. Shao (2018)  | Firms | UZABASE, Tokyo  | 3692 | Clustering | 2003-2016 | Accounting  |
| Ye Cai (2012) | Firms | Securities Data Company’s (SDC)  | 5055 | logit models | 1996–2008  | Accounting  |
| Ryan Moriarty et al. (2019) | Firms | EDGAR | 150,000 | Clustering | 1994-2018 | Accounting  |
