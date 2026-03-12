# 🧠 Research by Emmanuel DJEGOU

I am a **Ph.D. candidate in Statistics** at **Missouri University of Science and Technology**, specializing in **deep learning methods for survival analysis**. This repository showcases my research projects, code, and findings.

##  🎯 Interests

Deep Learning; Survival Analysis; Joint Modeling; Mixed-Effects Models & Meta-Analysis

___

## 📜 Research Framework

![Presentation3](https://github.com/user-attachments/assets/f781631a-a0ff-4e02-bf4b-570645f406ec)

---

## 📝 Research Publications

**Manuscripts in Preparation**
1. Djegou, E., & Adekpedjou, A. (2026). *Efficient Estimation in Accelerated Gap-Time Models for Recurrent Events*.
2. Djegou, E., & Adekpedjou, A. (2026). *RNN-AGT: Recurrent Neural Networks for Accelerated Gap-Time Models via Gehan-Type Rank Loss*.

**Current Research**
2. Djegou, E. (2025). *A General Class of Virtual Age Models with Time-Dependent Covariates*.        


## 📂 Projects Description

### ☞ Efficient Estimation in Semiparametric Accelerated Gap-Time Models for Recurrent Events

The **Accelerated Failure Time (AFT)** model relates covariates to log-transformed event times under right censoring and extends naturally to recurrent events through the **Accelerated Gap-Time (AGT)** formulation, providing a meaningful alternative to the Cox model. In many applications, such as reliability engineering and biomedical research, interventions occurring between successive events may alter the timing of future events, motivating models that explicitly account for these effects.

- Proposed a **broad class of semiparametric accelerated gap-time models** for recurrent event data incorporating an **effective age process**, allowing diverse intervention mechanisms to be represented within a unified framework.
- Developed a **sample-based weighted efficient score function** using **parametric submodels** to address challenges arising from **infinite-dimensional baseline hazards** and **non-monotone score functions**.
- Established that the resulting estimators are **consistent and asymptotically normal**.
- Demonstrated the method through **simulation studies** and an **application to real biomedical data**.
  
---

### RNN-AGT: Recurrent Neural Networks for Accelerated Gap-Time Models via Gehan-Type Rank Loss

Recurrent event data arise in many fields such as medicine, reliability engineering, insurance, and economics. Classical **Accelerated Failure Time (AFT)** and **Accelerated Gap Time (AGT)** models provide interpretable alternatives to Cox models by modeling covariate effects directly on the event time scale. However, these models typically rely on linear predictors and cannot capture complex nonlinear relationships or temporal dependence between repeated events.

This project introduces **RNN-AGT**, a neural network–based extension of AGT models for predicting recurrent gap times.

- Uses **Gated Recurrent Units (GRUs)** to model temporal dependence across repeated events.
- Captures **nonlinear covariate effects and interactions** beyond traditional AFT models.
- Handles **right-censored gap times** using a **Gehan-type rank loss**.
- Implements a **subsampling strategy** to reduce the computational cost of pairwise comparisons while maintaining unbiased gradient estimates.

Simulation studies demonstrate strong predictive performance using:

- **Adjusted Mean Squared Error (AMSE)**
- **Inverse Probability of Censoring Weighted (IPCW) Concordance Index**

The method is validated on **real biomedical recurrent-event datasets** and benchmarked against state-of-the-art Cox-based models.

---

### ☞ A General Class of Virtual Age Models with Time-Dependent Covariates

Traditional virtual age models assume covariates affect only baseline hazard, overlooking their influence on the **virtual age** that reflects post-intervention condition. This ongoing project extends the framework to capture more realistic dynamics.  

- Formulate a **generalized class of virtual age models** where **time-varying covariates impact virtual age directly**  
- Provide flexibility for modeling recurrent events under censoring and imperfect interventions  
- Base inference on **semiparametric efficiency theory** with reparameterized baseline intensity and monotone estimating equations  
- Establish estimators that are **consistent and asymptotically normal**  
- Develop a **simulation algorithm** for generating recurrent failure times  
- Conduct empirical studies showing gains in **accuracy and applicability** on biomedical datasets  

---

## 📜 License

All papers are © by default unless stated otherwise. Contact me for collaboration or reuse.
