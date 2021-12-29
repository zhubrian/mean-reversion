# mean-reversion

**Context:**

Senior Project (S&DS 491) for the B.S. in Statistics and Data Science at Yale University

**Title:**

Mean-reverting portfolio optimization: higher-order parametric models with regularization

**Abstract:**

In this paper, we frame the problem of finding a mean-reverting portfolio from a basket of
assets as maximizing the likelihood that the portfolio follows a stationary time series model. To
this end, we develop algorithms to optimize asset weights for autoregressive models of arbitrary
order for the portfolio value time series with unregularized, L1-regularized, and L2-regularized
objective functions. Using real-world asset price data to fit portfolios, we evaluate the effects
of model order and regularization with information criteria for model selection and proxies for
mean reversion. The results of our numerical experiments suggest that most metrics considered
show improvements in out-of-sample testing for models with moderate complexity and moderate
regularization, and that L1 regularization promotes sparse mean-reverting portfolios.

**Paper:**

See https://github.com/zhubrian/mean-reversion/blob/main/stat491-paper.pdf
