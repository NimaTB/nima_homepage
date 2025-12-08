---
title: "Event Identification via Modal & Spectral Analysis of PMU Data"
date: 2022-10-01
tags: ["PMU", "machine learning", "event identification", "modal analysis", "time-series"]
---

<div style="width:100%; display:flex; justify-content:center; margin:1.2rem 0;">
  <img src="/images/ss_n2p.png"
       alt="Global network visualization"
       style="width:400px; max-width:100%; border-radius:8px;">
</div>


This project develops a **real-time event identification framework** using modal and spectral features extracted from wide-area PMU streams.

## ▣ Problem

- PMUs produce extremely high-dimensional, high-rate data  
- Operators need rapid recognition of line trips, generator outages, and oscillations  
- SCADA-level alarms do not capture modal characteristics  

## ▣ Approach

- Extract **modal features** (frequency, damping, mode shapes)  
- Build a high-dimensional **spectral–temporal representation**  
- Apply feature selection (LASSO, MI ranking)  
- Train logistic regression and SVM classifiers  

## ▣ Validation

- Texas 2000-bus synthetic grid  
- Real utility dataset with ≈500 PMUs  
- Strong accuracy and robustness across conditions  

## ▣ Publication

**IEEE Transactions on Power Systems (2022):**  
https://ieeexplore.ieee.org/document/9911774
