# Smart-Beta-Optimisation
Building a smart beta portfolio against an index and optimising it using quadratic programming


**1. Project scope**

Smart beta has a broad meaning, but we can say in practice that when we use the universe of stocks from an index, and then apply some weighting scheme other than market cap weighting, it can be considered a type of smart beta fund.  A Smart Beta portfolio generally gives investors exposure or "beta" to one or more types of market characteristics (or factors) that are believed to predict prices while giving investors a diversified broad exposure to a particular market. Smart Beta portfolios generally target momentum, earnings quality, low volatility, and dividends or some combination. Smart Beta Portfolios are generally rebalanced infrequently and follow relatively simple rules or algorithms that are passively managed.  Model changes to these types of funds are also rare requiring prospectus filings with US Security and Exchange Commission in the case of US focused mutual funds or ETFs. Smart Beta portfolios are generally long-only, they do not short stocks.

Hence, the purpose of this project is to build a smart beta portfolio and compare it to a benchmark index. To find out how well the smart beta portfolio did, we are calculating the tracking error against the index. We are then building a portfolio by using quadratic programming to optimize the weights. The code in this project rebalances this portfolio and calculates turnover to evaluate the performance. This metric is used to find the optimal rebalancing frequency. 


**2. Datasets used**

The end of day data from Quotemedia has been used for this project.

**3. Initial requirements**

In order to make use of the project, the user should have a Python- version 3.5.2 installed on their PC, so that they can compile and run the codes included in the current repository.

**4. Repository constituents**

- `smart_beta.ipynb` - This Jupyter Notebook contains all of the functions needed to complete the project as well as explanatory comments which are aimed at guiding the user along the way
- `README.md` - the file that you are currently reading

**5. Authors**

Svetlozar Stoev as a project assignment from the Udacity 'AI for Trading' Nanodegree Program

**6. Resources Used**
- Udacity 'AI for Trading' Nanodegree Program. Can be found at: https://in.udacity.com/course/ai-for-trading--nd880

