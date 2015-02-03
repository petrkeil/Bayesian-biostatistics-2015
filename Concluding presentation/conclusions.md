Bayesian Biostatistics - Conclusions
========================================================
author: Petr Keil
date: February 2015

You should now be able to use
========================================================
- Likelihood, maximum likelihood, deviance.
- The basic prob. distributions.
- Distinguish the deterministic and stoch. model parts.
- Posterior, prior, likelihood and their connection.
- MCMC
- Credible and prediction intervals.
- Elementary model specification in JAGS.
- GLM, occupancy models, autoregression, random effects.

Some advice
========================================================
- ALWAYS start with simple models.
- Make your models cool and complex only AFTER your simple models run.

Some advice
========================================================
Learn your probability distributions. The useful ones
are: 
* Normal, Poisson, Binomial, Uniform
* Beta, Gamma, Exponential, Negative Binomial, Lognormal
* Categoriacal, Multinomial, Double exponential
* Truncated and censored distributions

Some advice
========================================================
- Copy other people's codes and models.
- Copy your own codes and models.

%#&$*! IT STILL DOES NOT RUN
========================================================

1. Your priors may be too wide. 
2. You may need to provide better initial values manually.
3. You have latent variabels - they need good inits.
4. You have mistaken ```~``` for ```<-```
5. You provide negative $\lambda$ to Poisson -> log link.
6. Same with Bernoulli -> logit link.
7. Standardize and center your variables, **especially for log link**.

And finally
========================================================
 - If you have a hammer, every problem turns out to be a nail.
 - Do not forget the biology for all the stats.
 
THANK YOU!
========================================================

