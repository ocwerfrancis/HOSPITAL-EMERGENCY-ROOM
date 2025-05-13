# HOSPITAL-EMERGENCY-ROOM
This project is an end-to-end Business Intelligence solution for analyzing emergency room operations in a hospital setting. It uses Power BI to visualize key performance indicators (KPIs) and operational metrics, empowering healthcare administrators to make data-driven decisions
# HOSPITAL EMERGENCY SAMPLE DATA SET

  **Patient Admission Date:**
A unique alphanumeric code assigned to each patient. This serves as the primary identifier to distinguish one patient's records from another. It's essential for tracking individual cases while ensuring privacy in data analysis.

   **Patient Admission Date:**
The specific date and potentially time the patient was admitted to the emergency room. This field helps analyze patterns such as peak admission times, seasonal trends, or emergency response rates.

   **Patient First Initial:**
The first letter of the patient's first name, often used for anonymization purposes in datasets to comply with privacy regulations like HIPAA or GDPR.

   **Patient Last Name:**
The last name of the patient. If anonymized, this field could still be useful for identifying trends or grouping by familial or cultural naming conventions.

   **Patient Gender:**
The gender identity of the patient, typically recorded as Male, Female, or Other/Nonbinary. Useful for demographic studies and understanding healthcare disparities among different genders.

   **Patient Age:**
The numerical age of the patient at the time of admission. This field is crucial for age-group analysis, helping identify trends such as which age groups frequently visit the emergency room and for what reasons.

   **Patient Race:**
The racial or ethnic identity as self-reported by the patient. This is vital for studying healthcare access, outcomes, and disparities across different racial and ethnic groups.

   **Department Referral:**
Specifies the department the patient was referred to (e.g., Orthopedics, Cardiology, Pediatrics). Analyzing this helps understand which specialties see the highest ER referrals, enabling resource allocation.

   **Patient Admin Flag:**
A binary field that indicates whether a patient was officially admitted to the hospital during their visit to the Emergency Room (ER).
True: The patient was admitted to the hospital for further observation, treatment, or care beyond the ER visit. This could mean being assigned to a specific department, ward, or intensive care.
False: The patient was not admitted and was either discharged, referred to another facility, or given outpatient treatment.

   **Patient Satisfaction Score:**
A measure, often on a scale (e.g., 1 to 5 or 1 to 10), that captures the patient's evaluation of their ER experience. High scores indicate satisfaction, while low scores suggest areas needing improvement. It’s essential for service quality analysis.

   **Patient Wait Time:**
The time elapsed from the patient's arrival at the ER to when they were first attended to by medical staff. This is critical for analyzing operational efficiency and patient experience.

   **Patients CM (Case Manager):**
The individual or team responsible for coordinating the patient’s care during their visit. The case manager ensures timely treatment, proper documentation, and post-discharge follow-up. Analysis can reveal workload distribution and case outcomes.

# 📌 STEPS IN PROJECT
1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Layouting
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation

# 📊 DASHBOARDS (3 Views)
1. Monthly View
2. Consolidated View
3. Patient Details

# 📈 BUSINESS REQUIREMENTS
## ✅ KPIs to Track:
- **Number of Patients:**
Track daily ER visits using an area sparkline to understand patterns such as peak days or seasonal trends.
- **Average Wait Time:**
Show average time patients wait before seeing a medical professional. Use a sparkline to highlight days with longer wait times.
- **Patient Satisfaction Score:**
Monitor daily average satisfaction score to evaluate service quality. Use sparklines to find dips and correlate them with peak times.
- **Number of Patients Referred:**
Count of patients referred to various departments daily. Area sparkline identifies departments with high referral rates.
