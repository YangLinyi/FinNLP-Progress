# Paper with Finacial Event Prediction

* Sample Financial Events:
  * [Bankrupt](#bankrupt)
  * [Initial Public Offering (IPO)](#ipo)
  * [Mergers and Acquisitions (M&A)](#mergers-and-acquisitions)
  * Delisting


## Bankrupt
| Study | Paper | Data Source | Model | Time Period | Variable Type |
|-|-|-|-|-|-|
| Geng et al. (2015) | [Prediction of financial distress: An empirical study of listed Chinese companies using data mining](https://www.sciencedirect.com/science/article/abs/pii/S0377221714006511) | China, CSMAR | NN, DT, SVM, MV  | 2001–2008  | Accounting  |
| Liang et al. (2016)  | [Financial ratios and corporate governance indicators in bankruptcy prediction: A comprehensive study](https://www.sciencedirect.com/science/article/abs/pii/S0377221716000412) | Taiwan Economic Journal (TEJ)  | SVM, KNN, NB, CART, MLP  | 1999–2009  | Accounting, market, corporate governance  |
| Olson et al. (2012)  | [Comparative analysis of data mining methods for bankruptcy prediction](https://www.sciencedirect.com/science/article/abs/pii/S0167923611001709) | USA, Compustat | DT, logit, MLP, RBFN, SVM  | 2005–2009  | Accounting  |
| Ioannidis et al. (2010)  | [Assessing bank soundness with classification techniques](https://www.sciencedirect.com/science/article/abs/pii/S0305048309000796) | Bankscope, World Bank  | UTADIS, MLP, CART, KNN, Ordered logit, stacked models  | 2007–2008  | Accounting, country-level variables  |
| Boyacioglu et al. (2009) | [Predicting bank financial failures using neural networks, support vector machines and multivariate statistical methods: A comparative analysis in the sample of savings deposit insurance fund (SDIF) transferred banks in Turkey](https://www.sciencedirect.com/science/article/abs/pii/S095741740800078X) | Turkey, Banks Association of Turkey  | NN, SVM, MDA, K-means cluster analysis, logit  | 1997–2004  | Accounting  |
| Cecchini et al. (2010)  | [Making words work: Using financial text as a predictor of financial events](https://www.sciencedirect.com/science/article/abs/pii/S0167923610001181?via%3Dihub) | USA, Compustat, CRSP | SVM  | 1994–1999  | MD&A, Altman variables  |
| Kim et al. (2010)  | [Ensemble with neural networks for bankruptcy prediction](https://www.sciencedirect.com/science/article/abs/pii/S0957417409008781) | Korea | MLP + bagging, MLP + boosting  | 2002–2005  | Accounting  |
| Mai et al. (2018) | [Deep learning models for bankruptcy prediction using textual disclosures](https://www.sciencedirect.com/science/article/abs/pii/S0377221718308774) | USA, CRSP | CNN | 1994-2014 | Accounting  |
| Snow et al. (2020) | [Investigating Accounting Patterns for Bankruptcy and Filing Outcome Prediction using Machine Learning Models](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3481555) | USA, UCLA BRD | XGBClassifier | 1977-2016 | Accounting  |
| Snow et al. (2020) | [Predicting Global Restaurant Facility Closures](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3481555) | USA, Yelp | LightGBM | 2006-2017 | Accounting  |


## IPO
| Study | Paper | Data Source | Model | Time Period | Variables Type |
|-|-|-|-|-|-|
| Cristóbal et al. (2012) | [Predicting IPO Underpricing with Genetic Algorithms](https://core.ac.uk/download/pdf/288498268.pdf) | USA, AMEX, NASDAQ and NYSE IPOs | Genetic algorithms | 1999-2010 | Accounting  |
| Zhe et al. (2019)  | [Nlp Driven Large Scale Financial Data Analysis](https://www.ideals.illinois.edu/bitstream/handle/2142/104937/XU-THESIS-2019.pdf?sequence=1&isAllowed=y) | USA, Intrinio, The Reuters dataset | HAN | 2006-2013 | Accounting  |
| Jie et al. (2015)  | [Text Mining for Studying Management’s Confidence in IPO Prospectuses and IPO Valuations](https://aisel.aisnet.org/cgi/viewcontent.cgi?article=1163&context=amcis2015) | US SEC’s EDGA, CRSP | FOCAS-IE | 2003-2013 | Accounting  |

## Mergers and Acquisitions
| Study | Industry | Source of data | Sample size | Models | Time period | Variables Type |
|-|-|-|-|-|-|-|
| Adesoji  et al. (2015) | Firms | Securities Data Corporation (SDC)  | 150 | logit models | 1985–1995  | Food industry |
| Liu et al. (2016)  | Firms | China Securities Journal and the website  | 150 | Hopfield Network  | 2004-2006 | Accounting |
| Chin-Sheng (2012)  | Firms | SDC Platinum database | 689 | Ensemble | 1997–2008 | Accounting  |
| B. Shao (2018)  | Firms | UZABASE, Tokyo  | 3692 | Clustering | 2003-2016 | Accounting  |
| Ye Cai (2012) | Firms | Securities Data Company’s (SDC)  | 5055 | logit models | 1996–2008  | Accounting  |
| Ryan Moriarty et al. (2019) | Firms | EDGAR | 150,000 | Clustering | 1994-2018 | Accounting  |
