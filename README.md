# Choosing-order-boosts-motor-performance---power-analysis-and-visualizations

## Abstract

This project investigates the effect of **enhanced expectancies** (induced via positive feedback) on motor performance and learning in aerobic gymnastics.

A total of 36 female gymnasts (mean age = 14.1 ± 3.48) were assigned to either an enhanced expectancies (EE) group or a control (Con) group. Participants performed a coordinative task across three phases: baseline (BT), practice (PT), and retention (RT). Performance was evaluated by certified judges, alongside perceived exertion (Borg scale) and intrinsic motivation (IMI).

Linear mixed-effects models showed **no statistically significant differences between groups** in performance, perceived exertion, or intrinsic motivation. However, both groups improved over time, with the EE group showing a **steeper improvement trend**. Execution errors decreased by approximately **70% in the EE group vs. 34% in the control group**.

Although between-group differences were not statistically significant, the results suggest a **potential practical effect** of enhanced expectancies and extend existing findings to aesthetic sports contexts.


---

## Sensitivity Analysis

To assess statistical sensitivity, a **simulation-based power analysis** was conducted following DeBruine & Barr (2021).

The analysis focused on detecting effects of:
- Group (EE vs. Control)
- Phase (BT, PT, RT)
- Group × Phase interaction

A linear mixed-effects model with participant ID as a random intercept was used.

Power was estimated using **5,000 Monte Carlo simulations**, defined as the proportion of 95% confidence intervals excluding zero, across sample sizes ranging from N = 20 to N = 120.

Results showed **extremely low statistical power** for detecting the Group × Phase interaction, ranging from:
- 0.006 to 0.012 across all tested sample sizes

For the observed sample (N = 36):
- Effect sizes (Cohen’s d):
  - BT: -0.10
  - PT: -1.08
  - RT: -0.95
- Estimated power: ~0.007 [0.005–0.01]

These findings indicate that the study was **severely underpowered** to detect interaction effects, highlighting the importance of adequate sample size planning in similar experimental designs.
