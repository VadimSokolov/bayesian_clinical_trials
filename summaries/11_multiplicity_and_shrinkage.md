# Chapter 11. Multiplicity and Shrinkage

<!-- cite:begin -->
From *Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 11. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24564479. Book page: https://vsokolov.org/books/bayesian_clinical_trials/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials.
<!-- cite:end -->

This chapter asks what multiplicity costs and how to pay for it. It starts with many chances for luck, what counts as the family, and what keeping the option to look costs in patients. It sets out the traditional toolbox: Bonferroni, Holm, Hochberg, closed testing, fixed sequence and graphical procedures, and what the FDA multiple endpoints guidance asks for. It treats subgroups and forking paths, and how the result was chosen. The Bayesian alternative is shrinkage instead of threshold inflation: Stein, Efron and Morris and the batting averages, a numerical illustration of the winner's curse, and what shrinkage does not do. It treats false discovery rate and prior probabilities. It uses the hierarchical model rather than developing it, pointing to the separate chapter on hierarchical pooling, and applies it to the RECOVERY subgroups and to a four operation ulcer trial, which contrasts the traditional and hierarchical readings, shows structure a correction cannot see, and compares the two ways to pay for looking. It covers comparisons across arms and drugs in platforms, including the June 2026 FDA draft position on master protocols, then multiplicity handled by modeling in I-SPY 2 and REMAP-CAP (the trials themselves are told in the chapter of landmark trials), and reviewer expectations.

## From the literature

Bonferroni and Dunn (1961); Dunnett (1955); Holm (1979); Hochberg (1988); Hommel (1988); Simes (1986); closed testing (Marcus, Peritz and Gabriel 1976); gatekeeping (Dmitrienko and colleagues 2003); graphical procedures (Bretz and colleagues 2009, 2011, Burman and colleagues 2009, Maurer and Bretz 2013); false discovery rate (Benjamini and Hochberg 1995, Benjamini and Yekutieli 2001); shrinkage (Stein 1956, James and Stein 1961, Efron and Morris 1975); empirical Bayes and large scale inference (Efron 2008); Bayesian multiplicity (Berry and Berry 2004, Scott and Berger 2006, 2010, Berry and Hochberg 1999, Gelman and colleagues 2012); type S and M errors (Gelman and Tuerlinckx 2000); subgroups (Wang and colleagues 2007, Rothman 1990, Mehrotra and colleagues 2012); whether to adjust (Rothman 1990, Proschan and Waclawiw 2000); the ulcer data (Grizzle, Starmer and Koch 1969); I-SPY 2 (Park and colleagues 2016); REMAP-CAP (Gordon and colleagues 2021); the FDA multiple endpoints guidance (2022).

## New results

<!-- results:begin -->
- [Four operation ulcer trial, adjusted p value against posterior probability](../RESULTS.md#ulcer_bonferroni_vs_posterior) (Section 11.5.2, page 236; computed): In the dumping syndrome data of the four operation ulcer trial, the Bonferroni adjusted one sided p value for 75 per cent resection against drainage is 0.1362, while a hierarchical model gives posterior probability 0.92 that 75 per cent resection has the higher dumping rate, on a contrast shrunk from 0.574 to 0.28. New in this book.
<!-- results:end -->

## Key terms

multiplicity, familywise error rate, false discovery rate, Bonferroni, Holm, Hochberg, closed testing, fixed sequence, graphical procedure, subgroup analysis, forking paths, winner's curse, shrinkage, Stein estimator, empirical Bayes, ulcer trial, multiplicity across arms and drugs, master protocol multiplicity, I-SPY 2, REMAP-CAP.
