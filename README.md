# PCA.R
R script performing a PCA on the correlation matrix of stock market returns. 
The starting portfolio is composed of 22 English equities, whose geometric returns were calculated in the specified time frame. 
Once the "principal portfolios" were defined, we evaluated their absolute and relative performance against an equally weighted benchmark portfolio.
The asset allocation strategy that steams from PCA is based on the coefficients of each eigenvector of the correlation matrix. Each of them indeed identifies the position vector of a principal portfolio.
The backtesting was performed using the whole study.
