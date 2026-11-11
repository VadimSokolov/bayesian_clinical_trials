# Chapter 6. Prior, Likelihood, Posterior

<!-- cite:begin -->
From *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 6. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24122876. Book page: https://vsokolov.org/books/bayesian_clinical_trials_v1/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials_v1.
<!-- cite:end -->

This chapter introduces Bayesian inference through the same kinds of trials as before. It starts with Bayes' rule on a diagnostic test, exchangeability and de Finetti informally, and the coin with the Beta family. It shows the posterior mean as a weighted average and the prior's effective sample size, then redoes the two group comparison in traditional and Bayesian form, side by side, and explains why the two nearly agree. It compares credible and confidence intervals, introduces the posterior predictive distribution, and works the normal normal model on the log hazard ratio. It shows sequential updating, where the posterior today is the prior tomorrow, and that looking at the data does not change the posterior. It closes with what a protocol must say. Two trials that stated their success rule as a posterior probability are discussed: Pfizer and BioNTech BNT162b2 and REMAP-CAP. The chapter proves nothing new.

## From the literature

Bayes' rule and the likelihood principle (Savage 1954, Edwards, Lindman and Savage 1963, Berger and Wolpert 1988, Berger 1985, Lindley 1985); Bayesian data analysis (Gelman and colleagues 2013); the BNT162b2 phase 3 trial (Polack and colleagues 2020, Pfizer statistical analysis plan 2020, FDA EUA review 2021); REMAP-CAP (Gordon and colleagues 2021); Morita, Thall and Muller (2008) on effective sample size; ICH E9 and E20; the FDA draft guidance on Bayesian methodology (2026).

## New results

<!-- results:begin -->
- [Reproduction of the BNT162b2 beta binomial analysis](../RESULTS.md#bnt162b2_beta_binomial_reproduction) (Section 6.12.1, page 132; computed): The statistical analysis plan's beta binomial model with a Beta(0.700102, 1) prior, applied to 8 versus 162 cases, gives a posterior probability that vaccine efficacy exceeds 30 per cent of 1 minus 2e-28 and a point estimate of 95 per cent, matching the published interval within a tenth of a point. New in this book.
<!-- results:end -->

## Key terms

Bayes' rule, prior, likelihood, posterior, exchangeability, de Finetti, Beta prior, conjugate prior, effective sample size, credible interval, posterior predictive distribution, normal normal model, log hazard ratio, sequential updating, posterior probability success criterion, BNT162b2, REMAP-CAP.
