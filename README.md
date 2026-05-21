# 📊 Global Freelancers Analytics Dashboard

![Status](https://img.shields.io/badge/status-completed-success)
![Python](https://img.shields.io/badge/Python-Data%20Analytics-blue)
![BI](https://img.shields.io/badge/BI-Looker%20Studio-orange)
![Tools](https://img.shields.io/badge/tools-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-informational)
![Dataset](https://img.shields.io/badge/dataset-1000%20Freelancers-lightgrey)

---

## 📌 Project Overview

This project analyzes a global freelance marketplace dataset containing **1,000 freelancer profiles** with intentionally messy and inconsistent data.

The objective was to simulate a real-world business intelligence workflow by transforming raw data into a clean, analytics-ready dataset and building an interactive **Looker Studio dashboard** for stakeholder-oriented insights and decision-making.

The project covers:
- Data cleaning & preprocessing
- Feature engineering
- Exploratory data analysis (EDA)
- KPI development
- Business intelligence dashboarding
- Strategic insight generation

---

## 🎯 Business Objectives

The dashboard was designed to help stakeholders:

- Understand freelancer distribution across countries and skill domains
- Analyze pricing behavior across technical and creative categories
- Measure freelancer quality using ratings and satisfaction metrics
- Detect platform engagement inefficiencies
- Identify opportunities for pricing optimization and marketplace growth

---

## 🧹 Data Cleaning & Preprocessing

Several real-world data quality issues were addressed during preprocessing.

### ✔️ Cleaning Tasks Performed

- Standardized inconsistent categorical values:
  - gender
  - country
  - language
  - primary_skill

- Cleaned mixed-format numeric values:
  - `$40`
  - `USD 40`
  - `40/hr`

- Converted percentage-based satisfaction values into numeric format

- Unified `is_active` representations into binary values:
  - `1` → Active
  - `0` → Inactive

- Handled missing values using:
  - Median imputation for numerical features
  - Mode imputation for categorical features

- Removed unrealistic outliers and invalid records

---

## ⚙️ Feature Engineering

Additional analytical features were created to improve dashboard usability and business analysis.

### 📊 Generated Features

- **Age Groups**
  - 20–30
  - 31–40
  - 41–50
  - 51–60

- **Experience Levels**
  - Junior
  - Mid
  - Senior
  - Expert

- **Hourly Rate Log Transformation**
  - Used for smoother pricing distribution analysis

- **Business KPI Fields**
  - Estimated income indicators
  - Engagement metrics
  - Skill-level segmentation

---

## 📈 Dashboard Structure (Looker Studio)

### 🟦 Executive Overview

High-level KPIs and platform health indicators:

- Total Freelancers
- Average Hourly Rate
- Average Rating
- Active Freelancer Percentage
- Average Experience

---

## 🧠 Skills Intelligence

Marketplace supply and pricing analysis:

- Top Skills by Freelancer Count
- Average Hourly Rate by Skill

### Focus:
Understanding skill demand concentration and pricing behavior across domains.

---

## 📊 Performance Analysis

Freelancer quality and engagement analysis:

- Rating Distribution
- Experience vs Rating Scatter Plot

### Focus:
Evaluating whether experience translates into client satisfaction and platform success.

---

## 🌍 Geography Insights

Global workforce distribution analysis:

- Average Rating by Country

### Focus:
Understanding regional marketplace representation and quality consistency.

---

## 🖼️ Dashboard Preview

### Executive Overview
<img width="677" height="440" alt="image" src="https://github.com/user-attachments/assets/330c0ffa-648d-4330-8e4c-94a4433c2a4c" />

## Skills Intelligence
<img width="1002" height="760" alt="image" src="https://github.com/user-attachments/assets/84c7d285-267e-4115-a390-68a36bdd48ef" />

## Performance Analysis
<img width="1037" height="718" alt="image" src="https://github.com/user-attachments/assets/33b4db24-bcdc-4d59-8cd7-761d9aa7d9ff" />

## Geography Insights
<img width="1143" height="727" alt="image" src="https://github.com/user-attachments/assets/596fb4d1-ace4-4df2-979d-9f7adf428df3" />

---

## 🔥 Key Insights

### 💰 Pricing & Market Structure

- Average freelancer hourly rate is approximately **\$51/hour**
- Pricing across skills is relatively flat
- Specialized technical skills such as:
  - AI
  - Machine Learning
  - Blockchain

  are not receiving strong premium pricing despite niche demand

---

### 👥 Workforce Composition

- Average freelancer experience exceeds **11 years**
- Platform talent is heavily concentrated in senior-level professionals
- Very limited representation of junior or mid-level freelancers

---

### ⚠️ Platform Health Indicators

- Average platform rating is approximately **2.5 / 5**
- Rating distribution reveals strong inconsistency in freelancer quality
- Significant imbalance exists between active and inactive users

---

### 🌍 Geographic Distribution

- Talent is distributed across more than **20 countries**
- No specific region significantly outperforms others in quality metrics
- Low ratings appear to be a platform-wide issue rather than a regional one

---

## 📌 Strategic Recommendations

Based on the analysis, several operational improvements are recommended:

### ✔️ Improve Onboarding & Vetting
Introduce stricter technical and communication assessments before freelancer activation.

### ✔️ Introduce Skill-Based Pricing
Specialized domains such as AI and Blockchain should be premium-positioned for enterprise clients.

### ✔️ Investigate Engagement Issues
Analyze why large portions of the platform remain inactive.

### ✔️ Improve Matching Algorithms
Enhance client-freelancer recommendation quality to improve successful engagements.

### ✔️ Expand Mid-Level Talent Acquisition
The platform could benefit from onboarding motivated mid-level professionals.

---

## 🛠️ Tech Stack

### Data Processing & Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Business Intelligence
- Looker Studio

### Workflow
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- KPI Design
- Dashboard Storytelling

---

## 🔗 Live Dashboard

[View Interactive Dashboard](https://datastudio.google.com/reporting/427c6557-770c-4db1-b452-3ee09d302e6f)

---

## 🚀 Project Outcome

This project demonstrates a complete end-to-end analytics workflow commonly used in modern BI environments:

- Raw data ingestion
- Data quality assessment
- Cleaning & preprocessing
- Feature engineering
- KPI development
- Interactive dashboard creation
- Business insight extraction

The final result is a stakeholder-oriented analytics dashboard designed to support strategic decision-making in a freelance marketplace ecosystem.

---

## 👩‍💻 Author

**Maryam Skaik**  
Computer Science Graduate | Data Analytics & BI Enthusiast
