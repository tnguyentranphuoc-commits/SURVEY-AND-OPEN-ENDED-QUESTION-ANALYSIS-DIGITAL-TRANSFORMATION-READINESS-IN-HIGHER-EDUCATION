# SURVEY-AND-OPEN-ENDED-QUESTION-ANALYSIS-DIGITAL-TRANSFORMATION-READINESS-IN-HIGHER-EDUCATION
Ministerial-level scientific research project  

🛠️ **Tech Stack**: R (tidyverse, psych, GPArotation, car, tm, tidytext, wordcloud)  
📊 **Data Types**: Survey (Likert-scale) + Open-ended Text Responses  
📐 **Methodological Framework**: Econometrics + Measurement Theory + Text Mining  

---

## (i). Overview

This project investigates **perceived training quality and digital transformation readiness in higher education** using a **mixed-method data analytics framework**.

Unlike purely numerical or purely NLP projects, this study integrates:

- **Structured survey data (Likert-based scales)**  
- **Unstructured text data (open-ended responses)**  

The objective is twofold:

1. Quantitatively measure latent constructs related to training quality and institutional readiness.  
2. Qualitatively extract thematic structures from textual feedback to contextualize statistical findings.  

This repository reflects an applied demonstration of:

> Measurement modeling  
> Cross-sectional econometric analysis  
> Text mining & thematic coding  
> Mixed-method integration  

---

## (ii). Data

### 1️⃣ Survey Data (Structured)

- Likert scale: 1–5  
- Multiple constructs:
  - Training Program (CT)
  - Lecturer Quality (GV)
  - Facilities (CS)
  - Training Management (QL)
  - Development Orientation (PH)
  - Proposed Solutions (GP)

Each construct consists of multiple observed items.

---

### 2️⃣ Open-ended Responses (Unstructured)

- Stakeholders: Students, Lecturers, Managers, Experts  
- Free-text feedback on:
  - Digital transformation  
  - Training improvements  
  - Institutional challenges  
  - Industry linkage  

---

## (iii). Quantitative Methodology (Econometrics Pipeline)

```text
Data Cleaning
→ Descriptive Statistics
→ Reliability Testing (Cronbach’s Alpha)
→ KMO & Bartlett’s Test
→ Exploratory Factor Analysis (EFA)
→ Construct Score Aggregation
→ Group Difference Testing (t-test, ANOVA)
→ Interpretation & Structural Implications
```

### Key Statistical Procedures

- **Reliability Analysis**
  - Cronbach’s Alpha per construct  

- **Construct Validity**
  - KMO Measure of Sampling Adequacy  
  - Bartlett’s Test of Sphericity  

- **Exploratory Factor Analysis**
  - Principal Axis Factoring  
  - Varimax rotation  

- **Group Comparison**
  - Gender-based tests  
  - Role-based ANOVA  

### Purpose

To evaluate whether perceived institutional readiness varies across stakeholder roles and demographic groups, while ensuring measurement robustness.

---

## (iv). Qualitative Methodology (Text Mining Pipeline)

```text
Text Cleaning & Normalization
→ Stopword Removal
→ Tokenization
→ Bigram Extraction
→ Frequency Analysis
→ Thematic Coding
→ Role-Based Theme Intensity Mapping
→ Integration with Quantitative Results
```

### Analytical Focus

- Bigram co-occurrence structures  
- Thematic dominance patterns  
- Role-based discourse intensity  
- Alignment between statistical and textual signals  

The qualitative layer provides interpretative depth to quantitative findings, reducing the risk of purely numerical inference without contextual understanding.

---

## (v). Key Findings

### Quantitative Insights

- Overall positive perception across constructs  
- Lecturer quality and strategic orientation receive high mean scores  
- Program content and facilities show relatively lower evaluation  
- Significant differences observed across stakeholder roles  
- No substantial gender-based perception gap  

---

### Qualitative Insights

Dominant themes:

- Practical application & industry linkage  
- Digital skill enhancement  
- Technology integration  
- Institutional constraints  

Textual data confirms:

- Strong demand for applied learning  
- Emphasis on digital capacity building  
- Structural interpretation of role-based perception gaps  

---

## (vi). Methodological Contribution

This project demonstrates how to:

- Handle **ordinal survey data** within an econometric framework  
- Measure **latent constructs** using reliability & factor analysis  
- Process **unstructured text data** using computational methods  
- Integrate qualitative and quantitative evidence coherently  

It bridges: Traditional social science methodology   ↔   Modern data science workflow  

---

## (vii). Why This Project Matters

As part of a broader Data & Econometrics Analytics trajectory, this project extends beyond financial time series modeling into:

- Measurement theory  
- Behavioral data analytics  
- Institutional evaluation  
- Mixed-method inference  
- Human-centered data modeling  

It reflects the ability to handle:

- Structured numerical data  
- Categorical demographic variables  
- Latent variable systems  
- Unstructured text corpora  
- Cross-method triangulation  

---

## (viii). Repository Contents

- `The R pipeline.pdf` – Full quantitative pipeline and NLP & thematic extraction pipeline  
- `Dataset.csv` – - `Dataset.csv` – Cleaned survey and text responses  dataset  
- `Report.pdf` – Final integrated results  
- `README.md` – Project documentation  

---

## (ix). Keywords

Data Analytics · Econometrics · Survey Analysis · Likert Scale · Reliability Testing · EFA · Mixed Methods · Text Mining · NLP · Institutional Evaluation · Digital Transformation · R Programming  
