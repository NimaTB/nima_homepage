---
title: "Forced Oscillation Localization via Complex-LASSO"
date: 2022-07-01
tags: ["forced oscillations", "complex LASSO", "PMU", "oscillation analysis"]
---

This project develops a **Complex-LASSO framework** for identifying the sources of forced oscillations (FOs) in wide-area power systems.

## ▣ Problem

- Forced oscillations degrade stability and can spread across large systems  
- Source location is often unknown and difficult to estimate  
- PMU measurements are noisy and distributed  

## ▣ Approach

- Represent unknown FO inputs as sums of sinusoids in the frequency domain  
- Estimate candidate frequencies via empirical spectrum analysis  
- Formulate and solve a **complex-valued ℓ₁-regularized** least-squares problem  
- Use coordinate descent for efficient optimization  

## ▣ Validation

- IEEE 68-bus and WECC 179-bus systems  
- Correctly identifies FO locations and amplitudes  
- Scalable to multiple sources and noisy measurements  

## ▣ Publication

**IEEE PES General Meeting (2022):**  
https://ieeexplore.ieee.org/document/9916993
