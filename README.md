# Generic positive feedback does not aid leanring---power-analysis-and-visualizations

📌 Project Overview

This project investigates the effect of **enhanced expectancies (generic positive feedback)** on motor performance and learning in aerobic gymnastics.

Using a controlled experimental design, the analysis evaluates whether generic positive feedback can influence execution quality, perceived exertion, and intrinsic motivation dimensions.

---

❓ Research Question

Does enhanced expectancies (via generic positive feedback) improve motor performance and learning outcomes compared to a control condition?

---

📚 Background

Enhanced expectancies are considered an important psychological factor influencing motor learning and performance.

Previous research suggests:
- Positive feedback can improve performance outcomes
- Effects are often small and context-dependent
- Evidence in **aesthetic sports (e.g., gymnastics)** is limited

---

🧪 Study Design

- Sample size: N = 36 female gymnasts  
- Between-group design:  
  - Enhanced Expectancies (EE)  
  - Control (Con)  
- Task: Coordinative motor task  
- Phases:
  - Baseline (BT)
  - Practice (PT)
  - Retention (RT)

Measured outcomes:
- Execution quality (judged performance)
- Perceived exertion (Borg scale)
- Intrinsic motivation dimensions (IMI)

---

📊 Analysis Approach

Statistical model:
- Linear Mixed-Effects Models (LMM)

Fixed effects:
- group (EE vs Con)
- phase (BT, PT, RT)
- interaction (group × phase)

Random effects:
- participant ID

Additional analysis:
- Simulation-based power analysis (Monte Carlo approach)
- Sensitivity analysis across sample sizes (N = 20–120)

---

📈 Key Results

- No statistically discernible differences between groups
- Both groups improved over time
- EE group showed a **steeper improvement trend**

Performance change:
- EE: ~70% reduction in execution errors  
- Control: ~34% reduction  

---

🧠 Interpretation

Although no statistically significant group differences were observed:

- The EE group showed **practically meaningful improvement trends**
- Results suggest a **potential effect not detectable with given sample size**
- Findings highlight the importance of **statistical power in experimental designs**

---

⚠️ Sensitivity Analysis

Monte Carlo simulation (5,000 iterations) revealed:

- Extremely low power to detect interaction effects:
  - Power ≈ 0.006–0.012 across N = 20–120
- For N = 36:
  - Power ≈ 0.007

Effect sizes (Cohen’s d):
- BT: -0.10  
- PT: -1.08  
- RT: -0.95  

👉 Conclusion: The study was **severely underpowered**, limiting the ability to detect group differences.

---

🧰 Tools

- jamovi, R
- Linear Mixed-Effects Models (lme4)
- Monte Carlo simulation
- Data visualization (ggplot2)

See the preprint of the project: https://osf.io/preprints/psyarxiv/ufesa_v1
