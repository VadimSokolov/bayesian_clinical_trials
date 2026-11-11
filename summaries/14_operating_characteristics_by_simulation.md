# Chapter 14. Operating Characteristics by Simulation

<!-- cite:begin -->
From *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 14. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24141732. Book page: https://vsokolov.org/books/bayesian_clinical_trials_v1/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials_v1.
<!-- cite:end -->

This chapter asks how a Bayesian design earns an error rate. It first describes what a traditional design computes and what goes in the SAP (the fixed sample design and the group sequential design), then the Bayesian success rule and why it has no error rate until calibrated, and why the uncalibrated rule inflates the error. It gives the calibration of the threshold and the interim boundary by simulation, with the algorithm and how to choose them, and a worked two arm binary trial with four looks: type I error across the null space, the null boundary, power, expected sample size, early stopping and bias, and the sources of calibration noise. It covers scenario grids and the worst case, the Goldilocks design, what the simulation report must contain, and software, reproducibility and what to submit. Cases: BNT162b2, REBYOTA, DAWN and Superion.

## From the literature

Bayesian designs calibrated to frequentist operating characteristics (Spiegelhalter, Freedman and Parmar 1994, Lewis and Berry 1994, Thall and Simon 1994, Rubin 1984, Little 2006); simulation for design (Muller and colleagues 2007, Berry and colleagues 2010, Morris, White and Crowther 2019, Mayer and colleagues 2019); group sequential theory (Jennison and Turnbull 2000, Wassmer and Brannath 2016, O'Brien and Fleming 1979); the Goldilocks design (Broglio and colleagues 2014); adaptive design reporting (Dimairo and colleagues 2020); FDA guidance on adaptive designs (2019), Bayesian statistics in device trials (2010) and the Bayesian draft (2026); ICH E20; BNT162b2 (Polack and colleagues 2020, Pfizer statistical analysis plan); REBYOTA (FDA briefing 2022); DAWN (Nogueira and colleagues 2018, Stryker statistical analysis plan); Superion (FDA summary of safety and effectiveness 2015, Pennello and Thompson).

## New results

<!-- results:begin -->
- [Calibration of a posterior probability rule by the null maximum](../RESULTS.md#null_maximum_calibration) (Section 14.4.1, page 309; proved): The smallest threshold that holds a monitored posterior probability rule to level alpha is the (1 minus alpha) quantile of the largest posterior probability reached over the looks in null simulations, so one simulation serves every threshold. New in this book.
<!-- results:end -->

## Key terms

operating characteristics, calibration, type I error rate, simulation, success threshold, posterior probability threshold, interim boundary, scenario grid, expected sample size, Goldilocks design, statistical analysis plan, simulation report, reproducibility, BNT162b2, REBYOTA, DAWN, Superion.
