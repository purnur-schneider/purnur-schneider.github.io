### With Insch Capital Management

#### Asymmetric Deviation as a risk measure for a managed portfolio or strategy

- Asymmetric deviation was introduced by Insch Capital Management as a better measure of risk than standard deviation. Asymmetric Deviation multiplies standard deviation by the ratio between the downside deviation and the upside deviation of returns.
["A New Way to Measure Risk", Insch CM, Jan.2017](webdocs/Non-StandardDeviation_17_01.pdf)

- Asymmetric Deviation can replace standard deviation in building optimal minimum risk portfolios. 
["The True Deviation of Returns and Portfolio Optimization, Insch CM, Feb.2017"](webdocs/TDandMinRiskPortfolios17_02.pdf)


#### Omega measure based on the Kernel Distribution

The Omega measure provides as a way to describe the holistic disribution of performance across strategies or benchmarks. At Insch, we used Omega in logarithmic form and in combination with the kernel distribution of returns, for smoother and more general results. In addition, by inverting the axes of the Omega versus returns graph we obtain a more intuitive view of the performance domain, which makes it easier to make comparisons bewtween various investments' performances.

<img src="../img/LogOmega.png" width=350px;/>



#### Volatility Drag

It is the negative impact of compounding volatile returns on the total return of a strategy. 

Consider two investments, one risk-free and one risky, over two time periods. Say the risky investment yields returns $r_1$ in the first period and a different $r_2$ in the second period. Also assume the risk-free investment yields a
constant return $r$ equal to the average of the risky investment returns. 
The difference in the total returns between the risky and the riskless investments is the volatility drag: 

$(1+r_1)(1+r_2) - (1+r)^2 = -(1/4)(r_1-r_2)^2$, always negative. 

For Geometric Brownian Motions, expected total return has the
expression $E(R) = \mu - \sigma^2/2$, where $-\sigma^2/2$ is the volatility drag. 

If leverage is applied, so exposure is increased by a factor $n$, the volatility drag term increases by the factor $n^2$. 

A trading strategy could aim to minimize the volatility drag by decreasing exposures when high volatility is expected and
vice versa.


### With DL Investment Partners 

- I have performed Returns-Based-Style-Analysis, to track eventual style drift by individual foreign exchange managers. The results are however strongly affected by the choice of benchmarks for style. 

- I have decomposed total portfolio variance to assess the individual contributions risk of individual asset managers. This decomposition leads to an easy and straightforward portfolio allocation among managers in a minimum risk portfolio, by equalizing the risk contributions across managers. 

- I have written practical guides for using statistical measures such as Omega, Ljung-Box and Jarque-Bera, and F-tests.