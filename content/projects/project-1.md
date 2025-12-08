---
title: "Semi-Supervised Event Identification for Power Systems"
date: 2024-09-01
tags: ["PMU", "semi-supervised learning", "event identification", "time-series"]
---

[//]: # (<!-- Section with Background Image -->)

[//]: # (<div class="make_bg bg_blog">)

<div style="width:100%; display:flex; justify-content:center; margin:1.2rem 0;">
  <img src="/images/ss3.png"
       alt="Global network visualization"
       style="width:400px; max-width:100%; border-radius:8px;">
</div>

This project introduces a **semi-supervised learning framework** for classifying disturbance events using high-dimensional PMU data when labels are sparse. Real power-system PMU archives contain thousands of unlabeled snapshots and only a limited number of trusted labeled events.



## ▣ Problem

- PMU archives contain **very limited labeled data**, making supervised training unreliable  
- Grid conditions shift across time, seasons, and topology changes  
- Physics-based features alone cannot fully capture dynamic variability  

## ▣ Approach

- Combine **spectral/modal signatures** with **learned temporal embeddings**  
- Apply **self-training**, **pseudo-label refinement**, and **consistency constraints**  
- Leverage small labeled sets to guide structure in large unlabeled PMU corpora  

## ▣ Validation

- Strong generalization under low-label regimes  
- Robust identification across multiple utilities and operating conditions  
- Outperforms traditional supervised PMU classifiers in label-scarce settings  

## ▣ Publication

**arXiv preprint (2024):**  
https://arxiv.org/abs/2309.10095

[//]: # (</div>)