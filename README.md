# Mithi Jain

**7987426086** · [mithijain220405@gmail.com](mailto:mithijain220405@gmail.com) · [LinkedIn](https://www.linkedin.com/in/mithi-jain-856825330) · [GitHub](https://github.com/Mithijain22)

---

## EDUCATION

**VIT Bhopal University — School of Computer Science Engineering**  
B.Tech in Computer Science and Engineering, CGPA: 8.23/10.0 ·        2023 – 2027

**St. Joseph's Convent Sr. Sec. School**  
10th Standard: 94.6% · 2021

## TECHNICAL SKILLS

**Languages:** Python, SQL

**Product Analytics:** A/B Testing, Cohort & Funnel Analysis, RICE Prioritization, Causal Inference (DiD), Experiment Design

**Data Science & ML:** LightGBM, Conformal Prediction, Reinforcement Learning (PPO), Statistical Validation (Bootstrap CI)

**Tools & Platforms:** BigQuery, Looker Studio, Stable-Baselines3

## PROJECTS

### [Nexus — Product Funnel, Cohort & Experimentation Analysis](https://github.com/Mithijain22/Nexus)
*May – Jun 2026*

- Analyzed ~903K e-commerce sessions (13 months of BigQuery GA360 data) using window-function funnel queries and self-join cohort analysis, uncovering a 1.7x checkout-to-purchase gap between desktop (54.5%) and mobile (32.0%).
- Pre-registered a north-star metric and stop-loss rule, then validated a real A/B test (90,189 users) with a Sample Ratio Mismatch check, confirming a statistically significant +4.5% relative lift in week-1 retention (95% CI [0.31pp, 1.33pp], p=0.0016).
- Scored 4 candidate interventions with a RICE prioritization framework and shipped a Looker Studio dashboard (funnel, cohort heatmap, A/B results) filterable by device, traffic source, and cohort month.
- **Tech Stack:** SQL (BigQuery), RICE Prioritization, A/B Testing, Cohort & Funnel Analysis, Looker Studio

### [1-Star Review Root-Cause Analysis — Executive Memo & Experiment Design](https://github.com/Mithijain22/Causea)
*Apr 2026*

- Diagnosed the leading drivers of 1-star reviews across a marketplace dataset: late delivery (38.2% of categorized complaints; 55.2% 1-star rate on 30+ day orders vs. 5.0% on-time) and product-quality issues (~20.9%).
- Applied difference-in-differences causal inference on a natural experiment (2017–18 regional delivery slowdown) against 3 pre-committed robustness checks, transparently reporting a failed check (2 of 3) rather than overstating a causal claim.
- Recommended an expedited-fulfillment SLA for the slowest-delivery quartile of 52 high-volume sellers (12.9% 1-star rate vs. 9.8% platform average) and designed a seller-randomized A/B test (~3,271 orders/arm) to validate impact pre-rollout.
- **Tech Stack:** Causal Inference (DiD), Robustness/Placebo Testing, Experiment Design, Stakeholder Communication

### [Delphi — Demand Forecasting & Inventory Decision Optimization](https://github.com/Mithijain22/Delphi)
*Feb – Mar 2026*

- Developed a forecasting-to-decision pipeline on 2,260 Walmart M5 item-store series, comparing point forecasts against full predictive distributions (quantile LightGBM, conformal, CQR) scored through a newsvendor ordering model.
- Quantified a $38,736.57 (7.81%) reduction in simulated inventory cost from using calibrated predictive distributions over point forecasts (95% bootstrap CI [$35,884, $41,829]), positive across all 6 backtest windows, departments, and stores.
- Uncovered a hidden per-segment calibration failure in split-conformal intervals (54.1% actual coverage vs. 90% target on high-volume series) masked by an overall pooled metric, directly informing a per-segment calibration fix.
- **Tech Stack:** Python, LightGBM, Conformal Prediction, Rolling-Origin Backtesting, Cost-Based Decision Modeling

### [RL-Based Kubernetes Autoscaling vs. Baseline HPA](https://github.com/Mithijain22/rl-kubernetes-autoscaler)
*Dec 2025 – Jan 2026*

- Engineered a reinforcement-learning autoscaler (PPO via Stable-Baselines3) benchmarked against a baseline modeled on Kubernetes' real HPA, across synthetic and real-world (Alibaba Cluster Trace) traffic.
- Ran a full multi-seed statistical audit (8 seeds/distribution, bootstrap confidence intervals), catching and fixing 2 critical bugs (train/eval seed leakage, real-data sampling bias) that had produced false "clean win" results.
- Reframed an initial "PPO can't generalize" conclusion into a precise, evidence-backed diagnosis via failure-mode analysis: PPO's learned cost-reliability tradeoff, not its behavior, fails to transfer across traffic distributions.
- **Tech Stack:** Python, PPO (Stable-Baselines3), Statistical Validation, Experiment Design, Reinforcement Learning

## CERTIFICATIONS

**Mastering Data Structures & Algorithms (FACE Prep)** · **DP-900: Microsoft Azure Data Fundamentals** · **The Bits and Bytes of Computer Networking (Google, Coursera)** · **Introduction to Machine Learning (NPTEL)**
