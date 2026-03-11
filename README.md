# Healthcare: Patient Readmission Risk Classifier

## Executive Summary
In the healthcare sector, 30-day patient readmissions are a critical metric. High readmission rates indicate poor initial care and result in heavy financial penalties from government bodies (like the NHS or CMS). This project implements a machine learning pipeline using Electronic Health Records (EHR) to predict which patients are at the highest risk of returning to the hospital within 30 days.

**Commercial & Clinical Objective:** Deploy a predictive triage system that flags high-risk patients at the time of discharge, allowing medical staff to allocate targeted follow-up care, thereby improving patient outcomes and minimising institutional financial penalties.

## Technical Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn (Gradient Boosting Classifier)
* **Data Processing & Visualisation:** Pandas, NumPy, Matplotlib, Seaborn

## Core Methodology
1. **EHR Data Simulation:** Dynamically generates a robust, fault-tolerant dataset mimicking tabular patient health records (e.g., time in hospital, number of medications, lab procedures, and diagnosis results).
2. **Exploratory Data Analysis (EDA):** Visualises clinical trends to identify baseline readmission rates across different demographic and clinical brackets.
3. **Predictive Modelling:** Utilises a **Gradient Boosting Classifier**, a powerful ensemble method that builds sequential decision trees to minimise prediction errors, highly suited for complex medical data.
4. **Clinical Interpretability:** Extracts feature importances to provide physicians with transparent insights into which clinical metrics (e.g., length of initial stay, polypharmacy) most strongly indicate a relapse in patient health.
