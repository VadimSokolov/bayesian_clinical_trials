# Chapter 9. Error Rates, Power, and Sample Size

<!-- cite:begin -->
From *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 9. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24141732. Book page: https://vsokolov.org/books/bayesian_clinical_trials_v1/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials_v1.
<!-- cite:end -->

This chapter turns to power and sample size. It gives the textbook calculation for binary, continuous and time to event endpoints, its sensitivity to the design alternative and the power curve, and what the regulator sees. It then shows that a conventional power calculation is assurance under a point mass prior, derives a closed form, states what assurance is not, and reviews Bayesian sample size criteria. A long section develops the moderate deviation sample size: the fixed n test has no memory of n, the power function and sample size equation, a surprising result about the saving, the role of prior odds in the constant, many parameters and endpoints, and a reading of SELECT against the formulas, with a candid statement of where the saving is and is not. It continues with sizing for the population in the sense of Anscombe and Colton. Cases: what a sample size costs, SELECT, why the phase 2 design alternative is too large, and platform arithmetic.

## From the literature

Sample size for survival (Freedman 1982, Schoenfeld 1981, 1983) and the SampleSizeProportions package (Joseph and colleagues 2023); trial size as a decision for the future population (Anscombe 1963, Colton 1963); assurance and Bayesian power (O'Hagan, Stevens and Campbell 2005, Spiegelhalter and Freedman 1986, Crisp and colleagues 2018, Kunzmann and colleagues 2021); Bayesian sample size (Adcock 1988, 1997, Joseph and colleagues 1995, 1997, Lindley 1997, Chaloner and Verdinelli 1995, Pezeshk 2003, Sahu and Smith 2006, Brutti and De Santis 2008, Joseph and colleagues 2019 consensus); the cost of trials (Moore and colleagues 2018, 2020, Saville and Berry 2016); SELECT (Ryan and colleagues 2020, Lincoff and colleagues 2023); the FDA Bayesian draft and ICH E9, E9(R1).

## New results

<!-- results:begin -->
- [Moderate deviation sample size equation](../RESULTS.md#moderate_deviation_sample_size) (Section 9.3.2, page 202; proved): A Bayes rule whose bar grows like the logarithm of the sample size has an implicit sample size equation, the textbook formula with the critical value replaced by the square root of log n plus a constant. First stated in Polson and Sokolov (2026), Bayesian versus Standard Clinical Trial Design: Theory, Evidence, and Protocol, working paper.
- [Moderate deviation and textbook sizes at the SELECT hazard ratio of 0.80 (not a prediction of SELECT's size)](../RESULTS.md#moderate_deviation_select_comparison) (Section 9.3.6, page 207; computed): At a hazard ratio of 0.80 and 90 per cent power the textbook formula gives 844 events and the moderate deviation formula more; SELECT was designed for a hazard ratio of 0.83, where the textbook formula gives about 1,211 events against the planned 1,225, so the formula does not predict SELECT's size. First stated in Polson and Sokolov (2026), Bayesian versus Standard Clinical Trial Design: Theory, Evidence, and Protocol, working paper.
<!-- results:end -->

## Key terms

sample size, power, power curve, design alternative, assurance, Bayesian power, expected power, Bayesian sample size criteria, moderate deviation, large deviation, prior odds, SELECT, trial cost, phase 2 to phase 3 optimism, platform arithmetic.
