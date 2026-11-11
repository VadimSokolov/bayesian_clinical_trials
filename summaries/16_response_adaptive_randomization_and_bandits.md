# Chapter 16. Response-Adaptive Randomization and Bandits

<!-- cite:begin -->
From *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials* by Alexandra Sokolova, Vadim Sokolov and Nicholas G. Polson (2026), chapter 16. Cite as Sokolova, Sokolov and Polson (2026), *Bayesian Clinical Trials and Personalized Medicine: Volume I: Bayesian Clinical Trials*, edition 1, https://doi.org/10.5281/zenodo.24122876. Book page: https://vsokolov.org/books/bayesian_clinical_trials_v1/. Source: https://github.com/VadimSokolov/bayesian_clinical_trials_v1.
<!-- cite:end -->

This chapter asks when allocation should change as data accrue. It starts with the traditional default of fixed allocation (why one to one, and when unequal allocation is justified), then frames allocation as a bandit problem: exploring and exploiting, Thompson sampling, the Bellman equation, the Gittins index, regret and the Lai and Robbins bound, and why the analogy does not transfer as design advice. It tells the ECMO story (the Harvard two stage trial, the UK collaborative trial, how much the prior matters, what the rule did to information). It sets out the critiques of response adaptive randomization, the case against and the case for with the replies, and reproduces the critique. It explains time trends, the failure that matters most, with simulation and fixes, and when randomization helps with many arms, and gives what the regulators say and practical guidance. Cases: I-SPY 2, REMAP-CAP, BATTLE and SHINE with its Bayesian reanalysis.

## From the literature

Allocation by the probability of being better (Thompson 1933); sequential design of experiments (Robbins 1952); the Gittins index (Gittins 1974, Gittins and Jones, Whittle 1980); regret (Lai and Robbins 1985, Auer and colleagues 2002, Agrawal and Goyal 2013, Kaufmann and colleagues 2012, Russo and colleagues 2016); bandits in trials (Berry 1978, Berry and Fristedt 1985); play the winner (Zelen 1969, Wei 1978, Rosenberger 1993, Rosenberger and colleagues 2001, Hu and Zhang 2004, Hu and Rosenberger 2006); ECMO (Bartlett and colleagues 1985, O'Rourke and colleagues 1989, Ware 1989, Kass and Greenhouse 1989, Royall 1991, UK Collaborative ECMO Trial 1996); critiques and replies (Korn and Freidlin 2011, Thall, Fox and Wathen 2015, Proschan and Evans 2020, Villar, Bowden and Wason 2015, Villar and colleagues 2018, Hey and Kimmelman 2015, Robertson and colleagues 2023); I-SPY 2 (Park and colleagues 2016, Barker and colleagues 2009); REMAP-CAP (Angus and colleagues 2020, Gordon and colleagues 2021); BATTLE (Kim and colleagues 2011); SHINE (Johnston and colleagues 2019, with a Bayesian reanalysis); Trippa and colleagues (2012).

## New results

<!-- results:begin -->
No new results of this chapter are catalogued.
<!-- results:end -->

## Key terms

response adaptive randomization, multi armed bandit, Thompson sampling, Gittins index, regret, play the winner, ECMO, time trend bias, critiques of adaptive randomization, many arm trials, fixed allocation, I-SPY 2, REMAP-CAP, BATTLE, SHINE, patient benefit.
