# Projects: Derivatives Pricing - Machine Learning - Algorithmic Trading



Binomial Tree (Excel): 
This was made to price American options for the S&P 100 index. I used OEX and VIX data from the Chicago Board Options Exchange, the dividend yield comes from Bloomberg. The time to maturity is represented in years. For this example I used a 42 day maturity.

K-means (Python): 
This project uses PWT.11 data. I was inspired to use a k-means clustering for my econometrics project after reading 'Advanced Statistics for Researchers'. This algorithm is part of 4500-word econometric analysis on the determinants of economic growth. We used a linear regression model based on an augmented Solow growth model (includes human capital). The purpose of this algorithm was to identify outliers for robustness checks with regards to the regression models. Which it did successfully, clustering India, China and the United States together. However the results overall were underwhelming, I believe this was due schewed data which will be taken into account for the final specification. 

Trading Algorithm (Python): 
This algorithm was one of about a dozen gradually evolving to ustilize an autoregressive integrated moving average model. The reason these more complex algorithms are not included in this repository is due to my increasing reliance on AI generated code and thus they became increasingly removed from my actual capabilities (also some of the bugs are horrendous especially with MCMC) 

To use this, you need to:  

1: Test for positive autocorrelation. I used a Durbin-Watson test. 

2: If the time series exhibits properties of positive autocorrelation, you can apply it through interactive brokers API.

3: As this algorithm has a tick rate of about 1 second the gains are very minor so you would need huge liquidity, admittedly I used a paper trading account as I am a university student. 

Overall: The biggest short coming of the algorithm is that it uses yahoo finance data which has a 20-minute delay. Meaning 
that all the gains that I did manage to get were from pure luck.

Finally: This algorithm was built out of academic curiosity NOT because I thought I could compete with firms like Hudson-river trading. 

Note on Methadology: 

All projects ustilized AI, mainly claude's sonnet 4.6. However, each project is accositated with around 50 - 200 prompts.
