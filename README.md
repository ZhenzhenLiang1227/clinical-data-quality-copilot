# Clinical Data Quality Copilot

An AI-assisted system for assessing data quality and investigating how data quality issues affect downstream machine learning using synthetic electronic health record (EHR) data.

## Overview

Electronic health record data are increasingly used for clinical research, healthcare analytics, and machine learning. However, routinely collected healthcare data may contain missing values, invalid values, duplicated records, temporal inconsistencies, and other quality issues.

These problems can influence not only statistical analysis but also the reliability of machine learning models.

This project aims to develop a reproducible data quality assessment system for synthetic EHR data and investigate how different types and levels of data quality degradation affect downstream machine learning performance.

## Research Question

**How do different dimensions of EHR data quality affect the reliability of downstream machine learning models?**

## Project Goals

The project will:

- assess multiple dimensions of EHR data quality
- detect potentially problematic records
- calculate interpretable data quality metrics
- simulate different types of data quality degradation
- evaluate their impact on machine learning performance
- visualize the results through an interactive dashboard
- explore LLM-based explanations of detected data quality issues

## Data Quality Dimensions

The initial implementation will focus on:

- Completeness
- Validity
- Consistency
- Uniqueness
- Timeliness

## Planned Workflow

```text
Synthetic EHR Data
        ↓
Data Profiling
        ↓
Data Quality Assessment
        ↓
Quality Metrics / Quality Score
        ↓
Controlled Data Corruption
        ↓
Machine Learning Experiments
        ↓
Performance Comparison
        ↓
Interactive Dashboard
        ↓
AI-assisted Explanation
```

## Tech Stack

Planned technologies include:

- Python
- Pandas
- NumPy
- scikit-learn
- Streamlit
- Plotly
- Pytest

Additional technologies such as FHIR, FastAPI, Docker, and LLM APIs may be introduced in later stages.

## Project Status

🚧 **Work in Progress**

Current stage: project design and initial data preparation.

## Disclaimer

This project uses synthetic healthcare data for educational and research purposes. No real patient data or personally identifiable health information is used.
