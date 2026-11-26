# Chapter 7. Hierarchical Models: How Much to Pool

<!-- cite:begin -->
From *Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 7. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24163054. Book page: https://vsokolov.org/books/bayesian_clinical_trials/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials.
<!-- cite:end -->

This chapter asks how much each group in a set of related groups should borrow from the others. It develops the normal hierarchical model with exchangeable group effects, a common mean and a between group standard deviation tau, and shows that tau is the single control that decides the amount of partial pooling: near zero every group gets the same estimate (complete pooling), large gives each group its own (no pooling), and in between each estimate shrinks part of the way to the overall mean, with noisy groups shrinking most. The objects are the shrinkage weight, the marginal posterior of tau, a half Cauchy prior for tau, and the effect of tau on each group estimate. Worked examples are the baseball batting averages (James Stein shrinkage, empirical Bayes), the eight schools SAT coaching experiments, four operations for duodenal ulcer compared on dumping syndrome, and a basket trial with ten tumor types in which one basket disagrees. The chapter explains when exchangeability is justified and when it fails, and three ways to settle tau: estimate it, fix it by design, or calibrate it by simulation. It shows that with few groups the data say little about tau and that borrowing can raise the false positive rate for a group that differs.

## From the literature

Efron and Morris (1975) supply the batting data and Stein estimation. Rubin (1981) analyzed the eight schools coaching experiments as parallel randomized experiments. Novick and Grizzle (1965) gave an early Bayesian analysis of a clinical trial of four duodenal ulcer operations, using the dumping syndrome counts of Grizzle, Starmer and Koch (1969). The FDA Bayesian draft guidance (2026) is cited for hierarchical borrowing across groups.

## New results

<!-- results:begin -->
No new results of this chapter are catalogued.
<!-- results:end -->

## Key terms

hierarchical model, partial pooling, shrinkage, between group standard deviation, tau, half Cauchy prior, exchangeability, empirical Bayes, James Stein estimator, eight schools, Efron and Morris, baseball batting averages, ulcer surgery, dumping syndrome, basket trial, borrowing, dynamic borrowing, false positive rate, marginal likelihood, Bayesian borrowing
