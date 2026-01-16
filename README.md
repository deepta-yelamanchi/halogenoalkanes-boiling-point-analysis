# Investigating the Influence of Halogen Type and Chain Length on Halogenoalkane Boiling Points

## Overview
This repository contains an **independent, data-driven chemistry research project** that investigates how **molecular structure variables**—specifically **halogen type** and **carbon chain length**—affect the **boiling points of halogenoalkanes**.

The project emphasizes **quantitative analysis, regression modeling, and data validation**, demonstrating skills applicable to **research, data science, chemical engineering, and applied STEM internships**.

---

## Problem Statement
Understanding how molecular features influence physical properties is critical in chemistry, materials science, and chemical engineering.

**Research Question:**  
*How do halogen type and carbon chain length quantitatively influence the boiling points of halogenoalkanes, and which factor is more significant?*

---

## Methodology & Tools
- **Data Sources**
  - CRC Handbook of Chemistry and Physics (experimental values)
  - ChemSpider and ACD/Labs (reference and predicted values)

- **Analysis Techniques**
  - Data cleaning and validation via relative/percent error
  - Linear regression (single-variable)
  - Multivariable regression (LINEST)
  - Categorical variable encoding using normalized dummy variables

- **Tools Used**
  - Google Sheets (data analysis, regression, visualization)
  - GitHub (version control, documentation)

---

## Key Results
- Both **halogen type** and **carbon chain length** increase boiling points
- **Carbon chain length** explains a larger portion of variance:
  - Chain length: **R² ≈ 0.661**
  - Halogen type: **R² ≈ 0.333**
- Final multivariable regression model:
  - **R² = 0.995**
  - **Prediction accuracy ≈ 88.65%**
- Conclusion: **Chain length is the dominant factor**, contradicting the initial dominance hypothesis

---

## Predictive Model
Final multivariable regression equation:

\[
y = -97.16 + 1.03x_1 + 31.01x_2
\]

Where:
- \( y \) = boiling point (°C)
- \( x_1 \) = halogen type (normalized categorical variable)
- \( x_2 \) = carbon chain length

This model demonstrates how **statistical methods can be applied to physical chemistry problems** to generate high-accuracy predictions.

---

## Repository Structure
- `paper/` – Full research paper (PDF)

---

## Skills Demonstrated
- Quantitative data analysis
- Regression modeling (linear & multivariable)
- Scientific research & experimental reasoning
- Data validation and error analysis
- Translating scientific questions into predictive models
- Technical documentation & GitHub best practices

---

## Applications & Relevance
This project reflects skills relevant to:
- Research & lab internships
- Data science / analytics roles
- Chemical & materials engineering
- Computational or modeling-focused STEM positions

---

## Author
**Deepta Yelamanchi**  
Independent Researcher | Chemistry & Data Analysis
