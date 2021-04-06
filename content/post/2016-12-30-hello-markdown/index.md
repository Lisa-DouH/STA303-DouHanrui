---
date: 2021-04-05T21:13:14-05:00
title: 3. Linear Mixed Model Structure
---

`$y = X\beta + Zb + \epsilon$`

`$b$` ~ `$N(0, \psi_\theta)$`, `$\epsilon$` ~ `$N(0, \Lambda_\theta)$`

- `$y$` is vector of outcomes for subject`$i$`.

- `$X$` and `$Z$` are model matrices for the **fixed** and **random** effects, respectively.

- The vector `$\beta$` describes the eect of covariates on the mean/expectation of the outcome, `$b$` is the random eects for the units (assumed to be normally distributed with mean zero).

- `$\epsilon$` is the residual errors, normally distributed with a given variance and the errors withinunits are mutually independent. In this course we won't deal with more complicatedsituations than a simple error vector that is distributed `$N(0, \sigma^2)$`