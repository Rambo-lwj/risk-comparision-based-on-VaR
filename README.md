Assume that NASDAQ-100 and S&P 500 is both geometric brownian motion,  then log daily return follow a normal distribution.

Log daily return of day t is  $log r_t=ln S_t - lnS_{t-1}$

Assume that the expectation of log daily return = 0, then 

$$VaR(10d,0.01)_t= Z_{0.01}\sqrt{10} \sigma_t $$

where $Z_{0.01}$ is (1-99%) one-side quantile for standard normal distribution N(0,1), $\sigma_t$ is standard deviation from 21 realized log daily return (from $log r_t-20$ to $log r_t$) .

realized 10-days log return $log r_{t+10}=ln S_{t+10} - lnS_t$.

breach occur when $log r_{t+10}<VaR(10d,0.01)_t$
