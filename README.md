# March Madness
![](march_madness_header.png)

In this project, we analyze differences in performance metrics for collegiate basketball teams that have qualified for March Madness versus those that have not using a variety of Monte Carlo Simulation methods in R. 

## Medium Article
![Here you can find a more thorough and in-depth discussion about this work in a published Medium article.](https://github.com/DImsirovic/march_madness).

## Executive Overview
### Intro
The aim of this analyis is to identify if the *distributions* of collegiate basketball metrics differ in teams that qualify for March Madness versus those that do not.
This is done by employing a 2-sample permuational t-test with a difference of means test statistic (Welch's T-test). We justify it's use in *Simulations* and apply the test in *Analysis*.

### Data
Data used here comes from ![Kenpom](https://kenpom.com/) over the 2010-2019 seasons. The features are a collection of effeciency and miscellaneous stats over those seasons. Because these files were downloaded only as a result of a paid subscription, I don't find it appropriate to make them publicly available. Feel free to [contact me](mailto:dimsirov@umich.edu) regarding any questions about data or reproducibility.

### Simulation
In this section, we find that our test has at least 95% power with an observed mean difference of +/- 0.5 or greater. In other words, if the observed mean difference is at least 0.5 in magnitude, the probability of rejecting our null hypothesis when it is not true is approximately 95% or greater. Permutation tests also have size no greater than a given alpha level (in this case, 5%)

### Analysis

Finally, a very special thanks to Alex, Julian, and Elton for their help and feedback in making this possible.
