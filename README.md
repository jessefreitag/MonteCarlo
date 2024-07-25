# An Exploration of Variance Reduction Techniques for Pricing European and Asian Options
## Department of Statistics, University of Chicago
### Jesse Freitag
#### jfreitag@uchicago.edu


## Abstract

In today’s dynamic financial landscape, options play a pivotal role in shaping investment strategies and managing risk. These unique and versatile financial instruments provide investors with the flexibility to hedge against adverse price movements, speculate on market trends, and optimize portfolio performance. Asian options, in particular, stand out for their unique characteristic of deriving their payoff from the average price of the underlying asset over a specified period, rather than relying on the asset’s price at a single point in time, like European options. However, the pricing of options in financial markets is very difficult and computationally complex, owing to the intricate interplay of various factors. Market volatility, time decay, interest rates, and the inherent stochastic nature of asset prices present formidable challenges to financial analysts and traders alike.

In this context, computational methods such as Monte Carlo simulations have emerged as indispensable tools for option pricing, offering a flexible and robust framework for estimating option values. Yet, the quest for efficient and accurate option pricing remains a perpetual endeavor, necessitating the exploration of innovative techniques to enhance computational efficiency and mitigate estimation errors.

This repository embarks on such a journey, delving into the realm of efficient Monte Carlo pricing methods for Asian and European options, with a particular focus on variance reduction techniques. We will introduce and implement some of the most common variance reduction techniques—namely Antithetic Variates and an array of Control Variates such as Delta-based, Gamma-based, and a combined antithetic-control variate algorithm which combines the three. Through a comprehensive analysis and empirical investigation, we seek to unveil novel strategies to address the complexities inherent in option pricing.
