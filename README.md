# Healthcare Data Analytics Project

## 🏥 Project Overview

This project aims to perform analytical exploration and generate insights from a healthcare dataset. It utilizes a combination of Python-based data analysis (Pandas, Seaborn, Matplotlib) and an AI large language model (IBM Granite 3.3 8B via Replicate API) to interpret trends, derive findings, and assist in generating human-readable insights. The dataset includes patient demographics, admission/discharge dates, medical conditions, test results, insurance providers, and billing amounts.

## 📁 Dataset

- **Source**: [Healthcare Dataset — Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset/)
- **Columns Include**: Patient name, age, gender, date of admission, discharge date, medical condition, test results, insurance provider, billing amount.

## 🔍 Insights & Findings

- **Total Patients**: *(automatically counted from dataset)*
- **Average Age**: ~`X` years *(e.g., 46.75 — derived from mean of "Age")*
- **Most Common Medical Conditions**:
  - Example: Diabetes, Hypertension, Asthma
- **Test Result Distribution**: Breakdown of positive, negative, or inconclusive results.
- **Billing Patterns**:
  - Certain conditions such as **Condition A** had notably higher average billing.
  - There's a visible variance in billing across different age groups.
- **Length of Stay**: Calculated as the number of days between admission and discharge.
- **Top Insurance Providers**: Listed based on frequency.

> *Note: All insights above are generated using Python libraries such as `pandas`, `seaborn`, and `matplotlib`.*

## 🤖 AI Support Explanation

This project integrates the IBM Granite 3.3 8B language model through the **Replicate API**. It is used to:

- Generate analytical summaries from statistical output.
- Derive patterns and insights from grouped and aggregated data.
- Interpret complex relations such as correlations between age, billing, and test results.
- Enhance narrative reporting through natural language generation based on dataset summaries.

The AI was guided using structured prompts that included calculated statistics, enabling it to respond with paragraph-form analysis similar to that written by a data specialist.

---

> 🛠 Built with: Python, Pandas, Seaborn, Matplotlib, LangChain, IBM Granite 3.3 LLM
>© 2025 - IBM SkillsBuild x Hacktiv8 Capstone Project
