# 🧠 Research Framework

## Research Topic 1: A Semiparametric Effective Age Framework for Recurrent Event Modeling

### Problem Statement

Many real-world systems involve **recurrent events**, where the same unit experiences multiple events over time. Examples include repeated failures in engineering systems, disease recurrence in biomedical research, and repeated claims in insurance. In these settings, interventions such as maintenance actions, medical treatments, or claim-related processes can modify the timing of future events. Since these interventions are often imperfect, the future event process depends on the system's **effective age**, which captures the cumulative impact of previous events and interventions.

A key challenge across reliability engineering, biomedical research, and insurance is the lack of flexible statistical models that can simultaneously capture the effects of **covariates** and **interventions** on the **timing of recurrent events**. Existing approaches often rely on **relative risk models**, such as the Cox proportional hazards model, which focus on how predictors affect the risk of an event rather than how they accelerate or delay the occurrence of future events. Although effective age models incorporate intervention effects, many existing formulations remain hazard-based and do not provide a unified framework for modeling both covariate effects and intervention effects on event timing.

The inability to accurately characterize these dynamics can lead to significant practical consequences, including inefficient maintenance strategies, increased operational costs, limited treatment personalization, and inaccurate risk assessment. This research develops a **semiparametric effective age framework based on accelerated gap-time models** to directly model how covariates and interventions influence the acceleration or delay of recurrent event times. The proposed framework aims to improve prediction, reliability assessment, and decision-making in high-impact applications across engineering, healthcare, and insurance.
