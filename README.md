# 🧠 Research Framework

## Research Topic 1

**A Semiparametric Effective Age Framework for Recurrent Event Modeling**

### Problem Statement

Many real-world systems involve **recurrent events**, where the same unit experiences multiple events over time. Examples include repeated failures in engineering systems, disease recurrence in biomedical research, and repeated claims in insurance. In these settings, interventions such as maintenance actions, medical treatments, or claim-related processes can modify the timing of future events. Since these interventions are often imperfect, the future event process depends on the system's **effective age**, which captures the cumulative impact of previous events and interventions. A key challenge across reliability engineering, biomedical research, and insurance is the lack of flexible statistical models that can simultaneously capture the effects of **covariates** and **interventions** on the **timing of recurrent events**. Existing approaches often rely on **relative risk models**, such as the Cox proportional hazards model, which focus on how predictors affect the risk of an event rather than how they accelerate or delay the occurrence of future events. Although effective age models incorporate intervention effects, many existing formulations remain hazard-based and do not provide a unified framework for modeling both covariate and intervention effects on event timing. The inability to accurately characterize these dynamics can lead to inefficient maintenance strategies, increased operational costs, limited treatment personalization, and inaccurate risk assessment. This research develops a **semiparametric effective age framework based on accelerated gap-time models** to directly model how covariates and interventions influence the acceleration or delay of recurrent event times, with the goal of improving prediction, reliability assessment, and decision-making in high-impact applications across engineering, healthcare, and insurance.

**Keywords:**  
`Recurrent Event Analysis` · `Survival Analysis` · `Accelerated Failure Time Models` · `Accelerated Gap-Time Models` · `Effective Age Models` · `Repairable Systems` · `Reliability Engineering` · `Intervention Effects` · `Maintenance Optimization` · `Semiparametric Inference`


## Research Topic 2

**Integrating Deep Learning and Survival Analysis for Accurate and Interpretable Event Prediction**

### Problem Statement

Survival analysis provides a powerful framework for modeling **time-to-event outcomes** in applications such as biomedical research, reliability engineering, and insurance. However, modern datasets are increasingly **high-dimensional, longitudinal, and complex**, creating challenges for traditional survival models that often rely on restrictive assumptions about covariate effects, functional relationships, and dependency structures. These limitations become particularly pronounced in recurrent event settings, where the history and sequence of previous events contain critical information about future outcomes. Deep learning approaches offer powerful capabilities for capturing nonlinear relationships, complex temporal patterns, and high-dimensional representations from large-scale data. However, many existing deep survival models operate as black-box approaches, improving predictive performance at the expense of interpretability and statistical understanding. Conversely, traditional survival models provide strong interpretability and theoretical guarantees but may struggle to achieve competitive predictive performance in complex real-world applications. This research explores the integration of **deep learning and survival analysis** to develop flexible and interpretable frameworks for single and recurrent event prediction. The objective is to establish a balance between **predictive accuracy, model transparency, and statistical reliability**, enabling trustworthy decision-making in high-impact domains including healthcare, reliability engineering, and insurance.

**Keywords:**  
`Deep Learning` · `Survival Analysis` · `Deep Survival Models` · `Recurrent Event Prediction` · `Time-to-Event Modeling` · `Neural Networks` · `Representation Learning` · `Longitudinal Data` · `Explainable AI` · `Predictive Modeling`


## Research Topic 3

**Variable Selection for High-Dimensional Survival Modeling Under Cross-Study Heterogeneity**

### Problem Statement

Large-scale biomedical studies increasingly rely on **individual-participant-data (IPD) meta-analysis** to integrate information from multiple cohorts and improve the understanding of time-to-event outcomes. This is particularly important in **genomics and precision medicine**, where high-dimensional molecular data, such as gene expression profiles, contain thousands of potential predictors for identifying prognostic biomarkers and understanding disease progression. However, analyzing these data presents significant challenges due to **between-study heterogeneity**, high-dimensional predictor spaces, and reliable variable selection under right-censoring. Existing penalized survival models often assume homogeneous covariate effects across studies or perform variable selection independently within each cohort, limiting their ability to capture population-specific differences while identifying consistently important biomarkers. In genomic applications, these limitations can result in unstable gene selection, reduced reproducibility of biomarker discovery, and poor generalizability across diverse patient populations. This research develops a **hierarchical penalized survival modeling framework** that jointly captures shared and study-specific covariate effects in high-dimensional IPD meta-analysis. By integrating structured variable selection and advanced penalization techniques, the proposed framework aims to identify robust genes and prognostic biomarkers while accounting for biological and clinical heterogeneity across cohorts. The ultimate goal is to improve the reliability, interpretability, and generalizability of survival models for applications in **genomic biomarker discovery, precision medicine, clinical risk prediction, and multi-cohort biomedical research**.

**Keywords:**  
`IPD Meta-Analysis` · `Survival Analysis` · `High-Dimensional Statistics` · `Penalized Regression` · `Variable Selection` · `Cox Proportional Hazards Model` · `Hierarchical Modeling` · `Nonconvex Penalties` · `Genomic Data Analysis` · `Biomarker Discovery` · `Precision Medicine`

