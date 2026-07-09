# 🧠 Research Framework

## Research Topic 1

**A Semiparametric Effective Age Framework for Recurrent Event Modeling**

### Problem Statement

Many real-world systems involve **recurrent events**, where the same unit experiences multiple events over time. Examples include repeated failures in engineering systems, disease recurrence in biomedical research, and repeated claims in insurance. In these settings, interventions such as maintenance actions, medical treatments, or claim-related processes can modify the timing of future events. Since these interventions are often imperfect, the future event process depends on the system's **effective age**, which captures the cumulative impact of previous events and interventions.

A key challenge across reliability engineering, biomedical research, and insurance is the lack of flexible statistical models that can simultaneously capture the effects of **covariates** and **interventions** on the **timing of recurrent events**. Existing approaches often rely on **relative risk models**, such as the Cox proportional hazards model, which focus on how predictors affect the risk of an event rather than how they accelerate or delay the occurrence of future events. Although effective age models incorporate intervention effects, many existing formulations remain hazard-based and do not provide a unified framework for modeling both covariate effects and intervention effects on event timing.

The inability to accurately characterize these dynamics can lead to significant practical consequences, including inefficient maintenance strategies, increased operational costs, limited treatment personalization, and inaccurate risk assessment. This research develops a **semiparametric effective age framework based on accelerated gap-time models** to directly model how covariates and interventions influence the acceleration or delay of recurrent event times. The proposed framework aims to improve prediction, reliability assessment, and decision-making in high-impact applications across engineering, healthcare, and insurance.

## Research Topic 2

**Integrating Deep Learning and Survival Analysis for Accurate and Interpretable Event Prediction**

### Problem Statement

Survival analysis provides a powerful framework for modeling time-to-event outcomes in applications such as biomedical research, reliability engineering, and insurance. However, modern datasets are increasingly high-dimensional, longitudinal, and complex, creating challenges for traditional survival models that often rely on restrictive assumptions about covariate effects and dependency structures. These limitations become more pronounced in recurrent event settings, where previous event histories contain important information about future outcomes.

Deep learning approaches offer powerful tools for capturing nonlinear relationships and complex temporal patterns from large-scale data. However, many existing deep survival models operate as black boxes, sacrificing interpretability for predictive performance. In contrast, traditional survival models provide statistical interpretability but may struggle to achieve competitive predictive accuracy in complex real-world applications.

This research explores the integration of **deep learning and survival analysis** to develop flexible and interpretable frameworks for time-to-event and recurrent event prediction. The goal is to identify effective approaches that balance **predictive performance, model transparency, and statistical reliability**, enabling trustworthy decision-making in high-impact domains including healthcare, reliability engineering, and insurance.

## Research Topic 3

**Variable Selection for High-Dimensional Survival Modeling Under Cross-Study Heterogeneity**

### Problem Statement

Large-scale biomedical studies increasingly rely on **individual-participant-data (IPD) meta-analysis** to integrate information from multiple cohorts and improve understanding of time-to-event outcomes. This is particularly important in **genomics and precision medicine**, where high-dimensional molecular data, such as gene expression profiles, contain thousands of potential predictors for identifying prognostic biomarkers and understanding disease progression. However, analyzing such data presents two major challenges: **between-study heterogeneity** and **reliable variable selection under high dimensionality and censoring**.

Existing penalized survival models often assume homogeneous covariate effects across studies or perform variable selection independently within each cohort. These approaches may fail to capture meaningful differences between populations while also missing important biomarkers that are consistently associated with outcomes across studies. In genomic applications, this limitation can lead to unstable gene selection, reduced reproducibility of discovered biomarkers, and limited generalizability of survival models across diverse patient populations.

This research develops a **hierarchical penalized survival modeling framework** that simultaneously captures shared and study-specific covariate effects in high-dimensional IPD meta-analysis. By integrating structured variable selection and advanced penalization techniques, the proposed framework aims to identify robust genes and prognostic biomarkers while accounting for biological and clinical heterogeneity across cohorts. The goal is to improve the reliability, interpretability, and generalizability of survival models for applications in **genomic biomarker discovery, precision medicine, clinical risk prediction, and multi-cohort biomedical research**.
