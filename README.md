## Healthcare Operations & Patient Analytics Solutions – St. Augustine Hospital
![](./Images/hospital_pics.png)
## Overview
St. Augustine Hospital relied on a flat-file data structure, limiting its ability to analyse operational performance and identify trends.

To address this, the data was transformed into a structured star schema model, improving data quality, performance, and analytical flexibility. This enabled the development of interactive dashboards with real-time KPIs and drill-down capabilities.

The analysis revealed key challenges, including high readmission rates, capacity constraints in high-demand departments, and uneven workload distribution across doctors.

---
## Business Problem
St. Augustine Hospital lacked a structured data model and relied on flat-file datasets, making it difficult to analyse operational performance and patient outcomes effectively.

This resulted in:
- Limited visibility into key metrics such as patient flow, readmission rates, and department utilisation  
- Inability to identify capacity bottlenecks and workforce imbalances  
- Fragmented data that prevented meaningful analysis across patients, doctors, and treatments  
- Delayed and reactive decision-making due to lack of real-time insights  

As a result, the hospital struggled to optimise resource allocation, manage patient demand, and improve quality of care.

---
## Project Rationale
The hospital’s flat-file data structure limited its ability to generate accurate and timely insights due to data redundancy, poor performance, and lack of relational structure.

This project introduces a star schema model and an interactive analytics layer, enabling efficient data exploration, KPI monitoring, and multi-dimensional analysis.

The goal is to shift from reactive reporting to a proactive, insight-driven approach for improving operational efficiency and patient outcomes.

---
## Aim of the Project 
The aim of this project is to design a scalable analytics solution that provides clear visibility into hospital operations, patient outcomes, and resource utilisation. By transforming raw data into structured insights, the project supports data-driven decision-making to improve efficiency, optimise performance, and enhance quality of care.
 
---
## Key Business Questions 
The dashboard was designed to address the following core business questions, enabling stakeholders to gain deeper insight into hospital operations, patient behaviour, and treatment outcomes:
- How do patient visits trend month by month across the year?
- What is the age group distribution of patients?
- From which locations/cities are patients visiting the hospital?
- What percentage of cases are currently waiting vs admitted?
- Which department is the most occupied overall
- What is the admission status breakdown per department?
- On which days of the week and times do most patient visits occur?
- How are visits distributed among doctors (workload)
- For each doctor, what are the details of recovery outcomes, success rates, and average visits?
- How many treatment types are offered by the hospital?
- How does treatment success rate differ by department
- What is the trend of chronic illness cases over time?

---
## Project Scope (Step by Step Approach)
The project was executed through a structured and methodical approach, ensuring both data integrity and analytical value:
### 1. Data Acquisition & Understanding
Imported the hospital dataset into Power BI and performed an initial assessment to understand data structure, key fields, and business relevance.
### 2. Data Preparation & Transformation
Cleaned and standardised the dataset by handling missing values, correcting data types, and removing inconsistencies to ensure reliability for analysis.
### 3. Data Modelling
Designed and implemented a star schema by separating transactional data from descriptive attributes, and established relationships to enable efficient querying and filtering.
### 4. KPI Definition & Measure Development
Developed key business metrics using DAX, including patient counts, admission rates, treatment success rates, readmissions, and visit durations.
### 5. Exploratory Data Analysis
Analysed trends and patterns across time, departments, doctors, and patient demographics to uncover meaningful insights.
### 6. Dashboard Design & Visualisation
Built interactive dashboards with clear layouts, incorporating charts, KPIs, and slicers to allow users to explore data dynamically.
### 7. Insight Generation & Interpretation
Translated analytical findings into actionable insights, focusing on operational efficiency, patient outcomes, and resource utilisation.
### 8. Business Recommendations
Provided data-driven recommendations to support decision-making, including improvements in capacity planning, workforce allocation, and patient care strategies.

## Project Images
### 1. Patients Analysis
![patients](./Images/dashboard_1.png)
### 2. Department Analysis
![](./Images/dashboard_2.png)
### 3. Doctors Analysis
![](./Images/dashboard_3.png)
### 4. Treatment Analysis
![](./Images/dashboard_4.png)
### 5. Data Model (Star Schema)
![](./Images/data_model.png)

---
## Interactive Power BI Dashboard
Click below to explore the live dashboard

[Dashboard](./Pbix/Health_care.pbix)

---
## Dataset
[Find the Dataset here](./Dataset/St.%20Augustine's%20Hospital%20Visits.csv)

---
## Key Insights

- **High Readmission Risk:**  
  Approximately 35% of patients are readmitted, particularly in Cardiology and Pediatrics, indicating potential gaps in post-discharge care and treatment effectiveness.

- **Capacity Imbalance:**  
  Pediatrics operates at ~91% capacity, creating bottlenecks, while the Emergency department is underutilised (~29%), highlighting inefficient resource allocation.

- **Workforce Imbalance:**  
  Patient load is unevenly distributed across doctors, with some handling significantly higher volumes, which may impact service quality and efficiency.

- **Treatment Performance Variation:**  
  Overall treatment success rate is ~78%, but varies significantly between routine procedures (high success) and complex treatments (lower success).

- **Patient Demographics:**  
  Majority of patients fall within the 18–35 age group, with a secondary concentration in older populations, influencing demand patterns.

- **Chronic Illness Growth:**  
  Chronic illness cases show a consistent upward trend, increasing long-term pressure on hospital resources.

---
## Strategic Recommendation
### 1. Improve Readmission Rates
**Recommendation:** Strengthen post-discharge care and patient follow-up processes.

**Action:**
- Introduce structured follow-up programmes (calls, check-ins within 7–30 days)
- Implement discharge planning protocols for high-risk patients
- Use data to flag patients with high likelihood of readmission
### 2. Optimise Department Capacity
**Recommendation:** Address capacity pressure in high-demand departments and improve utilisation of underused units.

**Action:**

- Increase bed capacity and staffing in Pediatrics
- Redirect non-critical cases to underutilised departments (e.g., Emergency)
- Implement real-time bed and resource tracking dashboards
### 3. Balance Workforce Distribution
**Recommendation:** Ensure equitable workload distribution across medical staff to improve efficiency and outcomes.

**Action:**

- Introduce workload balancing systems based on patient volume
- Monitor doctor performance metrics regularly
- Share best practices from high-performing doctors
## 4. Enhance Treatment Effectiveness
**Recommendation:** Improve outcomes for complex and high-risk treatments.

**Action:**

- Review treatment protocols for lower-performing procedures
- Invest in specialised training and equipment
- Track treatment performance continuously using KPIs
## 5. Expand Patient Reach 
**Recommendation:** Reduce dependency on a single geographic region and broaden patient base.

**Action:**

- Develop outreach programmes in underrepresented regions
- Partner with local clinics and referral networks
- Use targeted awareness campaigns to attract new patients
## 6. Strengthen Chronic Illness Management
**Recommendation:** Shift towards preventive and long-term care strategies for chronic conditions.

**Action:**

- Implement chronic disease management programmes
- Schedule regular monitoring and follow-up appointments
- Educate patients on early intervention and lifestyle management

---
## Business Impact

This solution provides a scalable analytical foundation for improving hospital operations and patient outcomes.

By identifying key issues such as high readmission rates, capacity imbalances, and uneven workload distribution, the hospital can implement targeted interventions to improve efficiency and quality of care.

The dashboard enables real-time monitoring of critical KPIs, supporting:
- Reduced readmission rates through proactive patient follow-up
- Improved resource allocation across departments
- Better workforce management and performance tracking
- Enhanced treatment effectiveness through data-driven evaluation

Overall, the project supports more efficient operations, improved patient outcomes, and better long-term resource planning.

---
## Tech Stack

|Power BI       | Data visualisation & dashboarding|
|---            | ---                              |
|DAX            |KPI and measure creation          |
|Power Query    | Data cleaning and transformation |
|Data Modelling | Star schema design               |







