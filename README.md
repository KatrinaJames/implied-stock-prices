# Derive Risk Neutral Implied Probability of Stock Prices
Derive the risk-neutral probability of future stock prices using [Breeden and Litzenberger](/con_044169.pdf) method

$$
    call = C = e^{r(T-t)} \int_K^\infty f(S_T)(S_T-K)dS_T
$$
$$
    put = P = e^{r(T-t)} \int_{-\infty}^K f(S_T)(K-S_T)dS_T
$$ 
$$
    \frac{\partial C^2}{\partial K^2} = e^{-r(T-t)}f(K)
$$