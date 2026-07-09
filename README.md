<div align="center">

# 🧠 Research Framework
### Advanced Statistical & Machine Learning Methods for Time-to-Event Data

![Focus](https://img.shields.io/badge/Focus-Survival%20Analysis-2c5364?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Recurrent%20Events-0f3460?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Deep%20Learning-e94560?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Genomics-9d4edd?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active%20Research-brightgreen?style=flat-square)

*Three complementary research directions spanning reliability engineering, biomedicine, and insurance — unified by the goal of modeling time-to-event data more flexibly, interpretably, and reliably.*

</div>

---

## 📋 Table of Contents

| # | Topic | Domain Focus |
|---|-------|---------------|
| 1 | [Semiparametric Effective Age Framework for Recurrent Event Modeling](#-a-semiparametric-effective-age-framework-for-recurrent-event-modeling) | Reliability · Biomedicine |
| 2 | [Integrating Deep Learning and Survival Analysis](#-integrating-deep-learning-and-survival-analysis-for-reliable-event-prediction) | Healthcare · Engineering · Insurance |
| 3 | [Variable Selection for High-Dimensional Survival Modeling](#-variable-selection-for-high-dimensional-survival-data-under-cross-study-heterogeneity) | Genomics · Precision Medicine|

---

## 🔧 A Semiparametric Effective Age Framework for Recurrent Event Modeling

<img src="banner1.svg" alt="Recurrent Event Modeling Banner" width="100%">

### The Problem

Systems that experience **recurrent events** — repeated failures in machinery, disease recurrence in patients, repeated insurance claims — are everywhere. Interventions like maintenance, treatment, or claims processing can reset or partially reset the clock on future events. This "clock" is the system's **effective age**, and capturing it well is surprisingly hard.

> Most existing tools, like the Cox proportional hazards model, describe *how risky* an event is at a given moment — not *how much sooner or later* it will occur. Effective age models fill part of that gap but are still largely hazard-based, without a unified way to capture both covariate and intervention effects on timing directly.

**Why it matters:** getting this wrong leads to costly maintenance schedules, less personalized treatment plans, and inaccurate risk pricing.

### The Approach

This research builds a **semiparametric effective age framework grounded in accelerated gap-time models**, directly modeling how covariates and interventions *accelerate or delay* recurrent event timing — rather than just how they shift risk.

<details>
<summary><b>🏷️ Keywords</b></summary>
<br>

![Recurrent Event Analysis](https://img.shields.io/badge/-Recurrent%20Event%20Analysis-2c5364?style=flat-square)
![Survival Analysis](https://img.shields.io/badge/-Survival%20Analysis-2c5364?style=flat-square)
![AFT Models](https://img.shields.io/badge/-Accelerated%20Failure%20Time%20Models-2c5364?style=flat-square)
![Gap-Time Models](https://img.shields.io/badge/-Accelerated%20Gap--Time%20Models-2c5364?style=flat-square)
![Effective Age](https://img.shields.io/badge/-Effective%20Age%20Models-2c5364?style=flat-square)
![Repairable Systems](https://img.shields.io/badge/-Repairable%20Systems-2c5364?style=flat-square)
![Reliability Engineering](https://img.shields.io/badge/-Reliability%20Engineering-2c5364?style=flat-square)
![Intervention Effects](https://img.shields.io/badge/-Intervention%20Effects-2c5364?style=flat-square)
![Maintenance Optimization](https://img.shields.io/badge/-Maintenance%20Optimization-2c5364?style=flat-square)
![Semiparametric Inference](https://img.shields.io/badge/-Semiparametric%20Inference-2c5364?style=flat-square)

</details>

---

## 🤖 Integrating Deep Learning and Survival Analysis for Reliable Event Prediction

<img src="banner2.svg" alt="Deep Learning and Survival Analysis Banner" width="100%">

### The Problem

Modern time-to-event datasets are **high-dimensional, longitudinal, and complex** — and traditional survival models often rely on restrictive assumptions that don't hold up, especially for recurrent events where the *history and sequence* of prior events matters.

> Deep learning can capture nonlinear relationships and complex temporal patterns that classical models miss — but at a cost. Most deep survival models are **black boxes**: strong predictive performance, little statistical transparency. Classical models offer the opposite trade-off.

**Why it matters:** in healthcare, engineering, and insurance, decision-makers need models they can both *trust* and *understand* — not just ones that score well.

### The Approach

This research develops frameworks that **integrate deep learning with survival analysis**, aiming for a balance of predictive accuracy, interpretability, and statistical reliability across single-event and recurrent-event settings.

<details>
<summary><b>🏷️ Keywords</b></summary>
<br>

![Deep Learning](https://img.shields.io/badge/-Deep%20Learning-0f3460?style=flat-square)
![Survival Analysis](https://img.shields.io/badge/-Survival%20Analysis-0f3460?style=flat-square)
![Deep Survival Models](https://img.shields.io/badge/-Deep%20Survival%20Models-0f3460?style=flat-square)
![Recurrent Event Prediction](https://img.shields.io/badge/-Recurrent%20Event%20Prediction-0f3460?style=flat-square)
![Time-to-Event Modeling](https://img.shields.io/badge/-Time--to--Event%20Modeling-0f3460?style=flat-square)
![Neural Networks](https://img.shields.io/badge/-Neural%20Networks-0f3460?style=flat-square)
![Representation Learning](https://img.shields.io/badge/-Representation%20Learning-0f3460?style=flat-square)
![Longitudinal Data](https://img.shields.io/badge/-Longitudinal%20Data-0f3460?style=flat-square)
![Explainable AI](https://img.shields.io/badge/-Explainable%20AI-0f3460?style=flat-square)
![Predictive Modeling](https://img.shields.io/badge/-Predictive%20Modeling-0f3460?style=flat-square)

</details>

---

## 🧬 Variable Selection for High-Dimensional Survival Data Under Cross-Study Heterogeneity

<img src="banner3.svg" alt="Genomics and Biomarker Discovery Banner" width="100%">

### The Problem

**Individual-participant-data (IPD) meta-analysis** lets researchers combine multiple cohorts to better understand time-to-event outcomes — crucial in genomics, where gene expression data offers thousands of candidate biomarkers.

> The catch: cohorts differ. Existing penalized survival models often assume **homogeneous effects across studies**, or select variables independently within each one — missing the chance to capture population-specific differences while still finding biomarkers that hold up broadly.

**Why it matters:** in genomic research, this leads to unstable gene selection, poor reproducibility, and biomarkers that don't generalize across patient populations.

### The Approach

This research develops a **hierarchical penalized survival modeling framework** that jointly captures shared and study-specific covariate effects in high-dimensional IPD meta-analysis — combining structured variable selection with advanced penalization to identify robust, generalizable biomarkers.

<details>
<summary><b>🏷️ Keywords</b></summary>
<br>

![IPD Meta-Analysis](https://img.shields.io/badge/-IPD%20Meta--Analysis-9d4edd?style=flat-square)
![Survival Analysis](https://img.shields.io/badge/-Survival%20Analysis-9d4edd?style=flat-square)
![High-Dimensional Data](https://img.shields.io/badge/-High--Dimensional%20Survival%20Data-9d4edd?style=flat-square)
![Penalized Regression](https://img.shields.io/badge/-Penalized%20Regression-9d4edd?style=flat-square)
![Variable Selection](https://img.shields.io/badge/-Variable%20Selection-9d4edd?style=flat-square)
![Cox PH Model](https://img.shields.io/badge/-Cox%20Proportional%20Hazards%20Model-9d4edd?style=flat-square)
![Hierarchical Modeling](https://img.shields.io/badge/-Hierarchical%20Modeling-9d4edd?style=flat-square)
![Nonconvex Penalties](https://img.shields.io/badge/-Nonconvex%20Penalties-9d4edd?style=flat-square)
![Genomic Data Analysis](https://img.shields.io/badge/-Genomic%20Data%20Analysis-9d4edd?style=flat-square)
![Biomarker Discovery](https://img.shields.io/badge/-Biomarker%20Discovery-9d4edd?style=flat-square)
![Precision Medicine](https://img.shields.io/badge/-Precision%20Medicine-9d4edd?style=flat-square)

</details>

---

## 🔗 How the Topics Connect

```
Topic 1 (Effective Age / AFT Models)  ──┐
                                          ├──►  Unified goal: better time-to-event
Topic 2 (Deep Learning + Survival)    ──┤        modeling for engineering,
                                          │        healthcare & insurance
Topic 3 (High-Dim Variable Selection) ──┘
```

All three research lines push survival analysis beyond classical hazard-based assumptions — toward models that are more **flexible** (Topics 1 & 2), more **interpretable** (Topic 2), and more **robust across heterogeneous populations** (Topic 3).

<div align="center">

---

*Prepared as a research framework overview — reach out for full proposals, methodology details, or collaboration inquiries.*

</div>
