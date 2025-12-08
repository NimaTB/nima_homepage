---
title: "Source Localization in Linear Dynamical Systems"
date: 2023-09-01
tags: ["dynamical systems", "source localization", "system identification", "control", "CCTA"]
---

This project studies the problem of **localizing unknown disturbance sources** in large linear dynamical systems using limited measurements. The work is motivated by oscillatory events, faults, and cyber-physical anomalies in power grids.

## ▣ Problem

- Disturbance inputs propagate through network dynamics  
- Only partial measurements of the system state are available  
- Need to infer **where** the excitation originated without full model knowledge  

## ▣ Approach

- Apply **subspace system identification** to recover reduced-order dynamics  
- Formulate a **source localization estimator** using Markov parameters  
- Use structured propagation patterns to recover the most probable source  

## ▣ Validation

- Demonstrated on synthetic linear networks and benchmark system models  
- Accurate localization under noise, limited sensors, and model uncertainty  
- Applicable to oscillation events and cyber-physical anomalies  

## ▣ Publication

**IEEE CCTA 2023:**  
https://ieeexplore.ieee.org/document/10252510
