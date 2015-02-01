Bayesian Biostatistics - Conclusions
========================================================
author: Petr Keil
date: Feb 2014

You should now be able to use
========================================================
- likelihood, maximum likelihood, deviance.
- the basic prob. distributions.
- distinguish the deterministic and stoch. model parts
- posterior, prior, likelihood and their connection
- MCMC
- credible and prediction intervals
- elementary model specification in JAGS
- GLM, occupancy models, autoregression, random effects

Some really important advice
========================================================
- ALWAYS start with simple models.
- Make your models cool and complex only AFTER your simple models run.

Some really important advice
========================================================
- Copy other people's codes and models.

%#&$*! IT STILL DOES NOT RUN
========================================================

1. Your priors may be too wide. 
2. You may need to provide better initial values manually.
3. You have latent variabels - they need good inits.
4. You have mistaken ```~``` for ```<-```
5. You provide negative $\lambda$ to Poisson -> log link.
6. Same with Bernoulli -> logit link.
7. Standardize and center your variables, **especially for log link**.

And finally:
========================================================
 - If you have a hammer, every problem turns out to be a nail.
 - Do not forget the biology for all the stats.
 
THANK YOU!
========================================================

