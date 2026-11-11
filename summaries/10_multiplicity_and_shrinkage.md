# Chapter 10. Multiplicity and Shrinkage

<!-- cite:begin -->
From *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 10. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24139858. Book page: https://vsokolov.org/books/bayesian_clinical_trials_v1/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials_v1.
<!-- cite:end -->

This chapter asks what multiplicity is and how to pay for it. It starts with many chances for luck and what counts as the family, then the traditional toolbox: Bonferroni, Holm, Hochberg, closed testing, fixed sequence and graphical procedures, and what the FDA multiple endpoints guidance asks for. It discusses subgroups and forking paths, and why a Bayesian must also ask how the result was chosen. The Bayesian alternative is shrinkage instead of threshold inflation: the idea, Stein, Efron and Morris and the batting averages, a numerical illustration of the winner's curse, and what shrinkage does not do. It treats false discovery rate (Benjamini and Hochberg) and prior probabilities, where familywise control is not the target, and the Bayesian view of multiplicity, then a large trial with many subgroups (RECOVERY). It works through the four operation ulcer trial, compares the two ways to pay for looking, and extends to platforms across arms and drugs. Cases: I-SPY 2, REMAP-CAP and the FDA master protocol position.

## From the literature

Bonferroni and Dunn (1961); Holm (1979); Hochberg (1988); Hommel (1988); Simes (1986); closed testing (Marcus, Peritz and Gabriel 1976); gatekeeping (Dmitrienko and colleagues 2003); graphical procedures (Bretz and colleagues 2009, 2011, Burman and colleagues 2009, Maurer and Bretz 2013); false discovery rate (Benjamini and Hochberg 1995, Benjamini and Yekutieli 2001); shrinkage (Stein 1956, James and Stein 1961, Efron and Morris 1975, 1977); empirical Bayes and large scale inference (Efron 2008); Bayesian multiplicity (Berry and Berry 2004, Scott and Berger 2006, 2010, Berry and Hochberg 1999, Gelman and colleagues 2012); type S and M errors (Gelman and Tuerlinckx 2000); subgroups (Wang and colleagues 2007, Rothman 1990, Mehrotra and colleagues 2012); ISIS 2 (1988); I-SPY 2 (Park and colleagues 2016); REMAP-CAP (Gordon and colleagues 2021); the FDA multiple endpoints guidance (2022).

## New results

<!-- results:begin -->
- [Four operation ulcer example, adjusted p value against posterior probability](../RESULTS.md#ulcer_bonferroni_vs_posterior) (Section 10.5.3, page 232; computed): In the four operation ulcer example the Bonferroni adjusted p value for best against worst is 0.0855, while the hierarchical posterior probability that drainage is worse than 75 per cent resection is 0.952 on a contrast shrunk from 1.053 to 0.464. First stated in Polson and Sokolov (2026), Bayesian versus Standard Clinical Trial Design: Theory, Evidence, and Protocol, working paper.
<!-- results:end -->

## Key terms

multiplicity, familywise error rate, false discovery rate, Bonferroni, Holm, Hochberg, closed testing, fixed sequence, graphical procedure, subgroup analysis, forking paths, winner's curse, shrinkage, hierarchical model, Stein estimator, empirical Bayes, I-SPY 2, REMAP-CAP, master protocol multiplicity.
