Author: Ethan Nanavati
Last Edited: 1/9/2025

This project proposes an optimal allocation of stocks in a portfolio and evaluates its performance. 

The work builds on the work of Ledoit et al 2003 to reduce estimation error in the sample covariance matrix by way of a "Shrinkage" estimator that weights the sample covariance to a more structured target.

The objective for the optimization is to maximize expected return subject to variance and simplex constraints (see (9) in the paper). This is a flipped version of the classic Markowitz portfolio.

The optimization problem is solved with and without shrinkage estimation, and the performance of these techniques is compared against a simple market average.
