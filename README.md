# Patient-readmission-risk-prediction-Healthcare-data-analysis-
Patient readmission risk prediction

### Step 1 — Problem Statement

While repeat patient visits can increase revenue for the hospital, unplanned 30-day readmissions create operational strain, increased resource utilization, and potential penalties under quality regulations (e.g., CMS readmission penalties). The hospital wants to optimize patient care and resource allocation by understanding which patients are at higher risk of readmission, so it can improve care planning, reduce avoidable readmissions, and maintain compliance with quality standards.


### Key questions to answer

• What percentage of patients are readmitted within 30 days?

• How does readmission rate vary by age group?

• How does readmission rate differ between male and female patients?

• Are emergency admissions more likely to result in readmission than elective admissions?

• How does length of stay affect readmission likelihood?

• Does the number of previous admissions increase the risk of readmission?

• Which departments have the highest readmission rates?

• Does insurance type correlate with readmission patterns?

• Are there patient groups that might require more post-discharge support to reduce readmissions?

• Which combination of features best predicts 30-day readmission?

• Which combination of features best predicts 30-day readmission?




### Tools to use

•	Excel: Initial dataset inspection and quick validation

• MySQL:  Structured storage, cleaning, and querying

• Jupyter Notebook (Python): Exploration, analysis, and modeling prep

• Power BI: Dashboard and storytelling to stakeholders



## 📁 Patient Readmission Dataset

This dataset contains **2,000 synthetic patient records** for a readmission risk analysis project focused on understanding factors that contribute to 30‑day hospital readmissions.

📥 **Download the dataset:**  
https://github.com/CelesNeba/Patient-readmission-risk-prediction-Healthcare-data-analysis-/blob/main/patient_readmission_dataset_2000.csv

---

### 📊 Dataset Overview

Each row represents a unique patient hospitalization record. The dataset includes a mixture of demographic, clinical, and operational features used to analyze readmission patterns.

**Columns and Descriptions:**

| Column Name                | Description |
|---------------------------|-------------|
| `patient_id`              | Unique identifier for each patient |
| `age`                     | Patient age in years |
| `gender`                  | Patient gender (Male / Female) |
| `department`              | Hospital department of admission |
| `admission_type`          | Type of admission (Emergency / Elective) |
| `length_of_stay`          | Number of days hospitalized |
| `previous_admissions`     | Count of prior admissions for the patient |
| `comorbidity_index`       | Comorbidity score (higher = more conditions) |
| `primary_diagnosis`       | Primary reason for hospitalization |
| `discharge_disposition`   | Discharge status (e.g., Home, Rehab, Transfer, AMA) |
| `insurance_type`          | Patient insurance category |
| `readmission_30d`         | Target outcome (1 = readmitted within 30 days, 0 = not) |

---

### 🎯 Purpose

This dataset is designed for exploratory analysis, feature exploration, and predictive modeling (e.g., readmission risk prediction). It can be used to:

- Analyze patterns in readmissions
- Build visualizations and dashboards (Power BI, Tableau, etc.)
- Train and evaluate classification models in Python/R
- Identify high‑risk cohorts for targeted interventions

---

### 🧠 Key Questions You Can Answer

- What is the **overall 30‑day readmission rate**?
- How does readmission vary by **age, gender, admission type, or department**?
- Does clinical severity (e.g., comorbidity index) correlate with readmission?
- Do certain discharge dispositions have higher readmission rates?
- Can we build a **predictive model** to identify high‑risk patients?

---

### ⚙️ Recommended Tools

You can use this dataset with:

- **Excel** — initial data inspection
- **MySQL** — structured querying and cleaning
- **Jupyter Notebook (Python)** — exploratory analysis and modeling
- **Power BI / Tableau** — interactive dashboards and visual storytelling

---

Feel free to use and modify this dataset for your analysis, dashboard builds, or predictive modeling exercises. If you publish results or dashboards, linking back to this source dataset is encouraged.


