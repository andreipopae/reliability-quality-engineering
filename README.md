> Statistical quality control of incoming lots and reliability characterization of electronic components.

## Overview

This project covers two sides of quality engineering: deciding whether to **accept or reject incoming
lots** of components using statistical sampling, and **characterizing how components fail over time**
from life-test data. It applies the MIL-STD-105E framework and standard reliability metrics end to end.

## Scope

| Topic | What was covered |
|-------|------------------|
| Acceptance sampling | Single / double / multiple plans, MIL-STD-105E (ANSI/ASQC Z1.4, ISO 2859) |
| AQL levels | 0.15 %, 0.65 %, 2.5 %, 10 % — inspection level II |
| Severity | Normal vs. tightened comparison |
| Defect classes | Critical, major, minor (type A / type B) |
| Reliability metrics | F(t), R(t), failure density f(t), failure rate z(t) |
| Distribution fitting | Exponential, Weibull, normal |

## Approach

- Built **single, double and multiple sampling plans** and derived the accept/reject criteria and switching rules.
- Compared **normal vs. tightened** inspection and analyzed how acceptance/rejection numbers (A, R) change with severity.
- Computed **reliability indicators** from a life test on 1000 transistors measured every 100 h, and from a separate truncated test on 200 transistors.
- Plotted **reliability R(t)** and **hazard-rate z(t)** curves and extracted quantiles.
- Identified the **failure-time distribution** with probability paper and **concordance tests** (Kolmogorov–Smirnov, Koziol–Byar) at several risk levels.

## Tools

Excel · MIL-STD-105E tables · reliability software · [sqconline](https://www.sqconline.com) acceptance-sampling calculator

## Skills Demonstrated

AQL acceptance sampling · OC/ASN curve interpretation · reliability metrics (R, F, hazard rate) ·
bathtub-curve reasoning · distribution fitting · statistical concordance testing.
