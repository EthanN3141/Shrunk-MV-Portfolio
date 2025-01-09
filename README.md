Author: Ethan Nanavati

Last Edited: 1/9/2025



This project proposes an optimal allocation of stocks in a portfolio and evaluates its performance. 

The work builds on the work of Ledoit et al 2003 to reduce estimation error in the sample covariance matrix by way of a "Shrinkage" estimator that weights the sample covariance to a more structured target.

The objective for the optimization is to maximize expected return subject to variance and simplex constraints (see (9) in the paper). This is a flipped version of the classic Markowitz portfolio.

The optimization problem is solved with and without shrinkage estimation, and the performance of these techniques is compared against a simple market average.


###############################FILES###############################

Shrunk MV Paper.pdf: Details the experiment, background, and results

Shrunk_MV.ipynb: performs the experiments detailed in the paper

tickers_etal.txt: contains information on the market used in this project (S&P 500 tickers and other data). Required for the data pull in Shrunk_MV.ipynb
