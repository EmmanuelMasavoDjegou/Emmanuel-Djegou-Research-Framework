# 🧠 Research by Emmanuel DJEGOU

I am a **Ph.D. candidate in Statistics** at **Missouri University of Science and Technology**, specializing in **deep learning methods for survival analysis**. This repository showcases my research projects, code, and findings.

##  🎯 Interests

- Neural Networks
- Recurrent Events
- Accelerated Life Models


___

## 📜 Research Framework

![Presentation3](https://github.com/user-attachments/assets/f781631a-a0ff-4e02-bf4b-570645f406ec)

---

## 📝 Research Publications

**Manuscripts in Preparation**
1. Djegou, E., & Adekpedjou, A. (2025). *Efficient Estimation in Accelerated Life Models for Recurrent Events*.
2. Djegou, E., & Adekpedjou, A. (2025). *RNN-AFT: Recurrent Neural Networks for Censored Gap Time Prediction*.

**Current Research**
1. Djegou, E. (2025). *Deep Survival Learning: A Modern Statistical Framework for Recurrent Event Data*.
2. Djegou, E. (2025). *A General Class of Virtual Age Models with Time-Dependent Covariates*.        



## 📂 Projects Description

### ☞ Efficient Estimation in Accelerated Life Models for Recurrent Events

Accelerated life models, such as the Accelerated Failure Time (AFT) model, relate covariates to log event times under right-censoring and extend naturally to recurrent events via the Accelerated Gap Time (AGT) model. While they provide intuitive interpretations and serve as meaningful alternatives to the Cox model, they often overlook the effects of interventions occurring between events—common in fields like reliability engineering and biomedical research.

- Proposed a broader class of **semiparametric accelerated life models** incorporating an **effective age process** to capture intervention effects.
- Developed a **sample-based weighted efficient score function** using parametric submodels to address infinite-dimensional baseline hazards and non-monotone score functions.
- Estimators are **consistent and asymptotically normal**.
- Validated via simulations and application to real biomedical data.

---

### ☞ RNN-AFT: Recurrent Neural Networks for Censored Gap Time Prediction

Recurrent event data frequently arise in biomedical and reliability studies, where subjects may experience multiple failures over time.  

- Introduce **RNN-AFT**, a recurrent neural network framework based on the **Gated Recurrent Unit (GRU)** to model recurrent events within the Accelerated Failure Time paradigm.  
- Capture complex, nonlinear relationships between covariates and event times across multiple occurrences.  
- Address censoring through a comparative study of **four loss functions**:  
  - Naive loss  
  - Imputation-based loss conditioning on covariates (inspired by Buckley–James)  
  - Inverse Probability of Censoring Weighting (IPCW) loss  
  - Gehan-type rank loss  
  - Unbiased transformation of censored survival times  
- Validate the approach through extensive simulations and real-world applications, showing that **RNN-AFT outperforms traditional AFT and Cox models** in both predictive accuracy and interpretability.  

---


### ☞ Deep Survival Learning: A Modern Statistical Framework for Recurrent Event Data

Recurrent event data extend survival analysis beyond the first event, capturing repeated occurrences in healthcare, engineering, and social sciences. This ongoing project explores how **deep learning methods** can advance recurrent event survival modeling.  

- Develop a **theoretical framework** for recurrent event analysis with deep learning  
- Investigate **state-of-the-art deep survival approaches**: RNNs, LSTMs, GRUs, attention-based models, deep hazard/intensity estimators  
- Examine challenges such as **censoring**, **time-varying covariates**, and **irregular event sequences**
- Explore **applications** in hospital readmissions, chronic disease progression, system reliability and actuarial science.
- Aim to show improvements in **predictive accuracy** and **interpretability** over traditional recurrent event models  


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
