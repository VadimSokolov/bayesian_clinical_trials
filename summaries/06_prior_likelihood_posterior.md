# Chapter 6. Prior, Likelihood, Posterior

<!-- cite:begin -->
From *Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 6. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24564479. Book page: https://vsokolov.org/books/bayesian_clinical_trials/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials.
<!-- cite:end -->

This chapter introduces Bayesian inference through the kinds of trials used elsewhere in the book. It starts with a prior as a histogram on a grid, where Bayes' rule is prior times likelihood rescaled, shown with a coin and then a patient response rate, followed by a diagnostic test, exchangeability and de Finetti informally, and the Beta family. It shows the posterior mean as a weighted average and the prior's effective sample size. Conjugate pairs are worked in turn: the beta binomial for the 1965 duodenal ulcer surgery trial, using the real dumping syndrome counts, for the BNT162b2 vaccine efficacy success rule, and for the interval after one toxicity in six patients in 3+3 dose escalation; the gamma Poisson pair for event rates; and normal normal shrinkage, with a Chicago Bears example and the log hazard ratio. It redoes the two group comparison in traditional and Bayesian form, explains why the two nearly agree, compares credible and confidence intervals, and introduces the posterior predictive distribution. It explains what to do when no conjugate prior fits, computing the posterior by simulation (Markov chain Monte Carlo). It shows sequential updating, where the posterior today is the prior tomorrow, and that looking at the data does not change the posterior, and closes with what a protocol must say and two trials that stated their success rule as a posterior probability, BNT162b2 and REMAP-CAP.

## From the literature

Bayes' rule and the likelihood principle (Savage 1954, Edwards, Lindman and Savage 1963, Berger and Wolpert 1988, Berger 1985); exchangeability (de Finetti 1937); Novick and Grizzle (1965) on Bayesian analysis of a trial of four ulcer operations and the dumping syndrome counts of Grizzle, Starmer and Koch (1969); the BNT162b2 phase 3 trial (Polack and colleagues 2020, Pfizer statistical analysis plan, FDA EUA review 2021); REMAP-CAP (Gordon and colleagues 2021); Morita, Thall and Muller (2008) on effective sample size; ICH E9 and E20; the FDA draft guidance on Bayesian methodology (2026).

## New results

<!-- results:begin -->
- [Reproduction of the BNT162b2 beta binomial analysis](../RESULTS.md#bnt162b2_beta_binomial_reproduction) (Section 6.6, page 118; computed): The statistical analysis plan's beta binomial model with a Beta(0.700102, 1) prior, applied to 8 versus 162 cases, gives a posterior probability that vaccine efficacy exceeds 30 per cent of 1 minus 2e-28 and a point estimate of 95 per cent, matching the published interval within a tenth of a point. New in this book.
<!-- results:end -->

## Key terms

Bayes' rule, prior as a histogram on a grid, likelihood, posterior, exchangeability, de Finetti, Beta prior, beta binomial, conjugate prior, effective sample size, credible interval, posterior predictive distribution, gamma Poisson, normal normal model, shrinkage, log hazard ratio, no conjugate prior, Markov chain Monte Carlo, sequential updating, posterior probability success criterion, ulcer surgery trial, dumping syndrome, 3+3 dose escalation, vaccine efficacy, BNT162b2, REMAP-CAP.
