# 🫀 Cardiac Arrest Analysis | Power BI Dashboard

> An interactive healthcare analytics dashboard designed to analyze cardiac arrest patient outcomes, survival patterns, hospital performance, treatment costs, and key patient risk indicators.

---

## 📊 Project Overview

This project uses Microsoft Power BI to analyze cardiac arrest patient data and transform healthcare information into meaningful visual insights.
The dashboard focuses on patient survival, mortality, hospital performance, treatment costs, admission types, blood pressure, diabetes, heart rate, and oxygen levels.

The objective is to provide a centralized analytical view that can help stakeholders understand patient outcomes and identify important patterns within the available data.

---

# 🎯 Business Problem

Healthcare organizations need to understand patient outcomes and operational performance to improve decision-making.
This project explores questions such as:

- What is the overall survival rate?
- How many patients survived versus deceased?
- Which hospitals have higher survival counts?
- Which treatment areas have the highest costs?
- How does survival vary by region?
- What is the average length of stay by admission type?
- How is high blood pressure distributed by gender?
- How does diabetes relate to patient survival?
- What are the overall patient heart rate and oxygen-level indicators?

---

# 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| 👥 Patient Count | **80K** |
| ⚠️ Deceased Count | **34K** |
| 💚 Survival Count | **46K** |
| 📈 Survival Rate | **58%** |
| 🫀 Avg Heart Rate | **94** |
| 🫁 Avg Oxygen Level | **92** |
| 💰 ICU Treatment Cost | **3.6bn** |
| 💰 Emergency Treatment Cost | **2.4bn** |

---

# 🔍 Key Dashboard Insights

## 1. Patient Outcomes

The dashboard reports approximately:

- **80K patients**
- **46K survived**
- **34K deceased**
- **58% survival rate**

This provides a high-level overview of patient outcomes in the analyzed dataset.

---

## 2. Hospital Survival Analysis

The dashboard compares survival and deceased patient counts across:

- Fortis Hospital
- AIIMS
- Apollo Hospital
- Metro Hospital

Fortis Hospital shows the highest displayed survival count, while the dashboard allows comparison of outcomes across hospitals.

---

## 3. Treatment Cost Analysis

Treatment costs are analyzed across:

- ICU
- Emergency
- General Ward

ICU has the highest treatment cost at approximately **3.6bn**, followed by Emergency at approximately **2.4bn**.
This provides an overview of how treatment costs are distributed across admission/treatment areas.

---

## 4. Regional Analysis

The dashboard provides a region-wise breakdown of cardiac arrest cases.
The displayed regions have relatively similar proportions, allowing stakeholders to compare patient distribution across geographical areas.

---

## 5. Blood Pressure by Gender

The dashboard analyzes high blood pressure cases by gender.
The visualization shows approximately:

- Female: **44.24%**
- Male: **55.76%**

This allows comparison of high blood pressure patterns across gender groups within the dataset.

---

## 6. Average Length of Stay

Average length of stay is analyzed by admission type:

| Admission Type | Average Stay |
|---|---:|
| ICU | **11.03 days** |
| General Ward | **4.56 days** |
| Emergency | **4.54 days** |

ICU patients have a significantly higher average length of stay compared with Emergency and General Ward patients.

---

## 7. Diabetes & Survival

The dashboard compares survival outcomes for patients with and without diabetes.
This allows analysts to investigate whether survival outcomes differ between the two groups.

---

# 📊 Dashboard Components

The dashboard includes:

- Patient Count
- Deceased Count
- Survival Count
- Survival Rate
- High Cholesterol Indicator
- High Blood Pressure Risk
- Average Heart Rate
- Average Oxygen Level
- Region-wise Cardiac Arrest Analysis
- Hospital Survival Analysis
- Treatment Cost Analysis
- Blood Pressure by Gender
- Average Length of Stay
- Diabetes vs Survival Analysis

---

# 🛠️ Tools & Technologies

### Power BI
Used to create the interactive healthcare analytics dashboard.

### Power Query
Used for:

- Data cleaning
- Data transformation
- Data preparation
- Data type management

### DAX
Used for:

- KPI calculations
- Survival metrics
- Aggregations
- Analytical measures

### Data Visualization

Visuals used include:

- KPI Cards
- Donut Charts
- Bar Charts
- Tables
- Interactive Filters

---

# 🔄 Data Analytics Workflow

```text
Raw Healthcare Data
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Patient Outcome Analysis
        ↓
Dashboard Development
        ↓
Business Insights
