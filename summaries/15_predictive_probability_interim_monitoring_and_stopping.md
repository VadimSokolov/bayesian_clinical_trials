# Chapter 15. Predictive Probability, Interim Monitoring, and Stopping

<!-- cite:begin -->
From *Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 15. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24147174. Book page: https://vsokolov.org/books/bayesian_clinical_trials/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials.
<!-- cite:end -->

This chapter asks when to stop for futility or success, and what the best rule is. It begins with the traditional interim: conditional power, futility rules, and sample size reestimation with the promising zone. It introduces predictive probability of success, from conditional power to the normal case, the exact beta binomial computation and a time to event example. It reviews the traditional phase 2 design (Simon's two stage design) where Bayesian monitoring started, predictive probability monitoring for phase 2, what that design is and is not, and the economic threshold. It describes the Goldilocks design with two predictive probabilities, then the Bayes optimal rule by backward induction: the decision problem, the sufficient statistic reduction, what backward induction does and does not do, and a single arm example. It compares designs, shows the protocol side by side and gives the regulatory reading. Cases: CALGB 49907, I-SPY 2, DAWN, BNT162b2 and GBM AGILE.

## From the literature

Conditional power and curtailment (Lan, Simon and Halperin 1982, Halperin and colleagues 1982, Lan and Wittes 1988, Proschan and Hunsberger 1995); predictive power (Herson 1979, Spiegelhalter, Freedman and Blackburn 1986, Johns and Anderson 1999); adaptive sample size (Bauer and Kohne 1994, Cui, Hung and Wang 1999, Lehmacher and Wassmer 1999, Chen, DeMets and Lan 2004, Mehta and Pocock 2011); two stage phase 2 designs (Gehan 1961, Fleming 1982, Simon 1989); Bayesian phase 2 monitoring (Thall and Simon 1994, Tan and Machin 2002, Lee and Liu 2008, Zhou and colleagues 2017); backward induction and optimal stopping (Bellman 1957, Arrow, Blackwell and Girshick 1949, Wald 1947, Anscombe 1963, Colton 1963, Berry and Ho 1988, Carlin, Kadane and Gelfand 1998); Goldilocks (Broglio and colleagues 2014); I-SPY 2 (Barker and colleagues 2009, Park and colleagues 2016); DAWN (Jovin and colleagues 2017); GBM AGILE (Alexander and colleagues 2018, Wen and colleagues 2026); CALGB 49907 (Muss and colleagues 2009).

## New results

<!-- results:begin -->
- [Exact backward induction for binary endpoints on a cubic lattice](../RESULTS.md#backward_induction_states) (Section 15.6.2, page 342; proved): For a two arm binary trial the Bayes optimal stopping rule depends only on the success counts and the stage, so backward induction is exact on a lattice of order T cubed states. First stated in Polson and Sokolov (2026), Bayesian Adaptive Clinical Trials: Priors, Thompson Sampling, Predictive Stopping and Backward Induction, manuscript submitted to Statistics in Medicine.
- [A utility only backward induction rule declares treatment better half the time under the null](../RESULTS.md#utility_only_rule_null_declaration) (Section 15.6.3, page 345; computed): A stopping loss that does not penalize false positives gives a good treatment choice rule and a useless confirmatory rule, because it declares treatment better in about half of null trials. First stated in Polson and Sokolov (2026), Bayesian Adaptive Clinical Trials: Priors, Thompson Sampling, Predictive Stopping and Backward Induction, manuscript submitted to Statistics in Medicine.
<!-- results:end -->

## Key terms

conditional power, futility, predictive probability of success, predictive power, promising zone, sample size re estimation, Simon two stage design, phase 2 monitoring, Goldilocks design, backward induction, optimal stopping, dynamic programming, CALGB 49907, I-SPY 2, DAWN, GBM AGILE.
