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
1. Djegou, E., & Adekpedjou, A. (2025). *Efficient Estimation in Semiparametric Accelerated Life Models for Recurrent Events*.
2. Djegou, E., & Adekpedjou, A. (2025). *Efficient Semiparametric Methods for Generalized Virtual Age Models with Time-Varying Covariates*.  
3. Djegou, E. (2025). *Deep Survival Learning: A Modern Statistical Framework for Recurrent Event Data*.  

**Current Research**
1. Djegou, E., & Adekpedjou, A. *Modeling Recurrent Events with Deep Neural Networks in Accelerated Failure Time Models*.    
2. Boamah, E., Kafle, A., & Djegou, E. *Neural Network-Based Prediction of Incurred but Not Reported Claims*.  


## 📂 Projects Description

### ☞ Efficient Estimation in Semiparametric Accelerated Life Models for Recurrent Events

Accelerated life models, such as the Accelerated Failure Time (AFT) model, relate covariates to log event times under right-censoring and extend naturally to recurrent events via the Accelerated Gap Time (AGT) model. While they provide intuitive interpretations and serve as meaningful alternatives to the Cox model, they often overlook the effects of interventions occurring between events—common in fields like reliability engineering and biomedical research.

- Proposed a broader class of **semiparametric accelerated life models** incorporating an **effective age process** to capture intervention effects.
- Developed a **sample-based weighted efficient score function** using parametric submodels to address infinite-dimensional baseline hazards and non-monotone score functions.
- Estimators are **consistent and asymptotically normal**.
- Validated via simulations and application to real biomedical data.

---

### ☞ Efficient Semiparametric Methods for Generalized Virtual Age Models with Time-Varying Covariates

Traditional virtual age models assume covariates influence only baseline hazard of initial failure times, ignoring their effect on the virtual age reflecting post-intervention condition.

- Introduce a **general class of virtual age models** where **time-varying covariates directly influence virtual age**.
- Offers flexible modeling of recurrent events (e.g., post-surgical readmissions), accounting for censoring and imperfect interventions.
- Inference based on **semiparametric efficiency theory** via reparameterization of baseline intensity and monotone estimating equations.
- Estimators are **consistent and asymptotically normal**.
- Proposed a **novel failure time simulation algorithm**.
- Demonstrated improved accuracy on biomedical datasets.

---

### ☞ Deep Learning Methods in Survival Analysis for Recurrent Events: A Review

Recurrent event data extend traditional survival analysis beyond the first event, capturing repeated occurrences across healthcare, engineering, and social sciences. This review focuses on **deep learning methods** specifically designed for recurrent event survival analysis.

- Provide a **theoretical foundation** for modeling recurrent events using deep learning techniques.  
- Survey **state-of-the-art deep survival methods**, including RNNs, LSTMs, attention mechanisms, and deep hazard/intensity estimators.  
- Discuss key challenges such as **censoring**, **time-varying covariates**, and **irregular event sequences** in recurrent event data.  
- Highlight **practical applications** in hospital readmissions, chronic disease progression, system reliability, and behavioral event modeling.  
- Demonstrate how deep survival learning improves **predictive performance** and **interpretability** compared to traditional recurrent event models.

---


### ☞ Modeling Recurrent Events with DNNs in Accelerated Failure Time Models

Recurrent event data commonly arise in biomedical and reliability studies, with multiple failures per subject.

- Extend **DeepR-AFT** framework to recurrent events via **DeepR-AGT-Recur**, a DNN model with **Gehan-type rank loss**.
- Capture nonlinear relationships between covariates and event times over multiple occurrences.
- Include a **subject-level frailty term** for within-subject dependence.
- Employ **stratified subsampling** for stable learning amid censored and irregularly spaced events.
- Perform simulation studies and real-world data applications to show that DeepR-AGT-Recur outperforms traditional AFT and Cox models in accuracy and interpretability.


---

### ☞ Neural Network-Based Prediction of Incurred but Not Reported Claims 

Claims reserving in insurance requires accurate prediction of both Reported But Not Settled (RBNS) and Incurred But Not Reported (IBNR) claims. While recent hybrid neural network approaches have advanced RBNS modeling, IBNR claims pose unique challenges due to the absence of detailed claim-level features and the presence of large-loss risks.  

- Extended **hybrid neural network models** to explicitly handle IBNR reserves.  
- Investigated the use of **predictive indicators** and **ensemble techniques** to improve accuracy.  
- Proposed a **dual-framework** separating RBNS and IBNR modeling for improved reserve allocation.  
- Results show potential for **enhanced prediction** and **nuanced treatment of large-loss claims** in actuarial practice.  

---

## 📜 License

All papers are © by default unless stated otherwise. Contact me for collaboration or reuse.
