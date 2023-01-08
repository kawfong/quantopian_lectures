# quantopian_lectures
Quantopian was shut down back in 2020 and the [lectures from the quantopian repo](https://github.com/quantopian/research_public/tree/e183ecd093efbebce9b0febdc7d0253159c04061/notebooks/lectures) are no longer maintained. Reworking with the past lectures in python3, so people who're interested in getting into Quant in 2023 don't have to work with Python2

## Contents
The course content is copied from [quantrocket](https://www.quantrocket.com/codeload/quant-finance-lectures/quant_finance_lectures/Introduction.ipynb.html). Will update the `.ipynb` file as I go through the lectures. 
### Intro To Python
|Progress|Lecture # | Title | Description |
|-----|----------|-------|-------------|
| <ul><li>- [x] </li></ul> | [Lecture 2](https://github.com/kawfong/quantopian_lectures/tree/main/Introduction_to_Python)  | Introduction to Python                                       | Basic introduction to Python semantics and data structures      
| <ul><li>- [x] </li></ul> | [Lecture 3](https://github.com/kawfong/quantopian_lectures/tree/main/Introduction_to_Numpy)  | Introduction to NumPy                                        | Introduction to NumPy, a data computation library                                                      |
| <ul><li>- [ ] </li></ul> | Lecture 4  | Introduction to pandas                                       | Introduction to pandas, a library for managing and analyzing data                                      |
| <ul><li>- [ ] </li></ul> | Lecture 5  | Plotting Data                                                | How to plot data with matplotlib                                                                       |
| <ul><li>- [ ] </li></ul> | Lecture 6  | Means                                                        | Understanding and calculating different types of means                                                 |
| <ul><li>- [ ] </li></ul> | Lecture 7  | Variance                                                     | Understanding and calculating measures of dispersion                                                   |
| <ul><li>- [ ] </li></ul> | Lecture 8  | Statistical Moments                                          | Understanding skewness and kurtosis                                                                    |
| <ul><li>- [ ] </li></ul> | Lecture 9  | Linear Correlation Analysis                                  | Understanding correlation and its relation to variance                                                 |
| <ul><li>- [ ] </li></ul> | Lecture 10 | Instability of Estimates                                     | How estimates can change with new data observations                                                    |
| <ul><li>- [ ] </li></ul> | Lecture 11 | Random Variables                                             | Understanding discrete and continuous random variables and probability distributions                   |
| <ul><li>- [ ] </li></ul> | Lecture 12 | Linear Regression                                            | Using linear regression to understand the relationship between two variables                           |
| <ul><li>- [ ] </li></ul> | Lecture 13 | Maximum Likelihood Estimation                                | Basic introduction to maximum likelihood estimation, a method of estimating a probability distribution |
| <ul><li>- [ ] </li></ul> | Lecture 14 | Regression Model Instability                                 | Why regression coeffecients can change due to factors like regime change and multicollinearity         |
| <ul><li>- [ ] </li></ul> | Lecture 15 | Multiple Linear Regression                                   | Multiple linear regression generalizes linear regression to multiple variables                         |
| <ul><li>- [ ] </li></ul> | Lecture 16 | Violations of Regression Models                              | Different scenarios that can violate regression assumptions                                            |
| <ul><li>- [ ] </li></ul> | Lecture 17 | Model Misspecification                                       | What can cause a bad model to look good                                                                |
| <ul><li>- [ ] </li></ul> | Lecture 18 | Residual Analysis                                            | How to analyze residuals to build healthier models                                                     |
| <ul><li>- [ ] </li></ul> | Lecture 19 | Dangers of Overfitting                                       | How overfitting can make a bad model seem attractive                                                   |
| <ul><li>- [ ] </li></ul> | Lecture 20 | Hypothesis Testing                                           | Statistical techniques for rejecting the null hypothesis                                               |
| <ul><li>- [ ] </li></ul> | Lecture 21 | Confidence Intervals                                         | How to measure and interpret confidence intervals                                                      |
| <ul><li>- [ ] </li></ul> | Lecture 22 | Spearman Rank Correlation                                    | How to measure monotonic but non-linear relationships                                                  |
| <ul><li>- [ ] </li></ul> | Lecture 23 | p-Hacking and Multiple Comparisons Bias                      | How to avoid getting tricked by false positives                                                        |
| <ul><li>- [ ] </li></ul> | Lecture 24 | Leverage                                                     | Using borrowed money to amplify returns                                                                |
| <ul><li>- [ ] </li></ul> | Lecture 25 | Position Concentration Risk                                  | The riskiness of investing in a small number of assets                                                 |
| <ul><li>- [ ] </li></ul> | Lecture 26 | Estimating Covariance Matrices                               | Using covariance matrices to model portfolio volatility                                                |
| <ul><li>- [ ] </li></ul> | Lecture 27 | Introduction to Volume, Slippage, and Liquidity              | An overview of liquidity and how it can affect your trading strategies                                 |
| <ul><li>- [ ] </li></ul> | Lecture 28 | Market Impact Models                                         | Understanding how your own trading activity moves the market price                                     |
| <ul><li>- [ ] </li></ul> | Lecture 29 | Universe Selection                                           | Defining a trading universe                                                                            |
| <ul><li>- [ ] </li></ul> | Lecture 30 | The Capital Asset Pricing Model and Arbitrage Pricing Theory | Using CAPM and Arbitrage Pricing Theory to evaluate risk                                               |
| <ul><li>- [ ] </li></ul> | Lecture 31 | Beta Hedging                                                 | Hedging your algorithm's market risk                                                                   |
| <ul><li>- [ ] </li></ul> | Lecture 32 | Fundamental Factor Models                                    | Using fundamental data in factor models                                                                |
| <ul><li>- [ ] </li></ul> | Lecture 33 | Portfolio Analysis with pyfolio                              | Evaluating backtest performance using pyfolio                                                          |
| <ul><li>- [ ] </li></ul> | Lecture 34 | Factor Risk Exposure                                         | Understanding and measuring your algorithm's exposure to common risk factors                           |
| <ul><li>- [ ] </li></ul> | Lecture 35 | Risk-Constrained Portfolio Optimization                      | Managing risk factor exposure                                                                          |
| <ul><li>- [ ] </li></ul> | Lecture 36 | Principal Component Analysis                                 | Using PCA to understand the key drivers of portfolio returns                                           |
| <ul><li>- [ ] </li></ul> | Lecture 37 | Long-Short Equity                                            | Introduction to market-neutral strategies                                                              |
| <ul><li>- [ ] </li></ul> | Lecture 38 | Factor Analysis with Alphalens                               | Using Alphalens to evaluate alpha factors                                                              |
| <ul><li>- [ ] </li></ul> | Lecture 39 | Why You Should Hedge Beta and Sector Exposures               | How hedging common risk exposures can improve portfolio performance                                    |
| <ul><li>- [ ] </li></ul> | Lecture 40 | VaR and CVaR                                                 | Using Value at Risk to estimate potential loss                                                         |
| <ul><li>- [ ] </li></ul> | Lecture 41 | Integration, Cointegration, and Stationarity                 | Introduction to stationarity and cointegration, which underpins pairs trading                          |
| <ul><li>- [ ] </li></ul> | Lecture 42 | Introduction to Pairs Trading                                | A theoretical and practical introduction to pairs trading                                              |
| <ul><li>- [ ] </li></ul> | Lecture 43 | Autocorrelation and AR Models                                | Understanding how autocorrelation creates tail risk                                                    |
| <ul><li>- [ ] </li></ul> | Lecture 44 | ARCH, GARCH, and GMM                                         | Introduction to volatility forecasting models                                                          |
| <ul><li>- [ ] </li></ul> | Lecture 45 | Kalman Filters                                               | Using Kalman filters to extract signals from noisy data                                                |
| <ul><li>- [ ] </li></ul> 
