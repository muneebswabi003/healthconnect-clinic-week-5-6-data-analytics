# HealthConnect Clinic — Week 5–6 Data Analytics Project

## Improving Patient Appointment Attendance and Healthcare Support Using Data and AI

**Programme:** AnalystLab Africa Experience Lab Internship Programme
**Track:** Data Analytics
**Project:** HealthConnect Clinic
**Assignment:** Week 5–6 | Data Analytics
**Tools:** Power BI, Microsoft Excel

---

## Project Overview

The HealthConnect Clinic project focuses on improving patient appointment attendance and healthcare support through data-driven analysis.

The project investigates appointment patterns and identifies factors associated with attended, missed, and cancelled appointments. The analysis combines **Exploratory Data Analysis (EDA), KPI development, interactive Power BI dashboarding, and advanced booking lead-time analysis**.

### Business Question

> **How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?**

---

## Project Objectives

* Analyze appointment attendance and no-show patterns.
* Identify factors associated with missed appointments.
* Develop meaningful KPIs for monitoring appointment performance.
* Build an interactive Power BI dashboard.
* Conduct advanced analysis of booking lead time and no-show behavior.
* Generate evidence-based business insights and recommendations.
* Provide analytical findings that can support future Data Science modelling.

---

## Dataset

The HealthConnect appointment dataset contains **5,000 appointment records** and **18 variables**, representing **1,696 unique patients**.

| Attribute          | Details               |
| ------------------ | --------------------- |
| Total Appointments | 5,000                 |
| Variables          | 18                    |
| Unique Patients    | 1,696                 |
| Primary Key        | `appointment_id`      |
| Outcome Variable   | `appointment_outcome` |
| Attended           | 2,314                 |
| No-Show            | 2,423                 |
| Cancelled          | 263                   |

The dataset includes patient characteristics, appointment information, booking lead time, previous appointment history, reminder information, distance to the clinic, waiting time, and appointment outcomes.

---

## Week 5 — Data Analytics

Week 5 focused on preparing the data, conducting Exploratory Data Analysis, developing KPIs, and creating an interactive Power BI dashboard.

### Analysis Areas

The analysis examined:

* Appointment outcomes
* Patient age groups
* Appointment types
* Booking lead time
* Previous no-show history
* Reminder status and channel
* Distance to the clinic
* Waiting time

### Key KPIs

| KPI                    | Result |
| ---------------------- | -----: |
| Total Appointments     |  5,000 |
| Attended Appointments  |  2,314 |
| No-Show Appointments   |  2,423 |
| No-Show Rate           |  48.5% |
| Attendance Rate        |  46.3% |
| Cancellation Rate      |   5.3% |
| Reminder Effectiveness |  47.6% |

### Week 5 Key Findings

The analysis identified a substantial no-show burden, with **48.5% of appointments recorded as no-shows**.

Other important patterns were observed across appointment type, booking lead time, previous no-show history, reminder engagement, distance to the clinic, and waiting time.

---

## Week 6 — Advanced Analysis

Week 6 extended the Week 5 analysis by investigating the relationship between **booking lead time and no-show behavior**.

Appointments were grouped into four meaningful booking lead-time categories:

| Booking Lead Time | No-Show Rate |
| ----------------- | -----------: |
| 0–7 days          |        27.8% |
| 8–14 days         |        33.6% |
| 15–30 days        |        43.2% |
| 31–60 days        |        60.5% |

The no-show rate increased from **27.8%** for appointments booked 0–7 days in advance to **60.5%** for appointments booked 31–60 days in advance.

This represents a **32.7 percentage-point difference** between the shortest and longest lead-time groups.

The finding indicates a strong observed association between longer booking lead times and higher no-show rates. However, the analysis is observational and **does not establish causation**.

---

## Key Business Insight

### Booking Lead Time and No-Show Rate

No-show rates increased consistently as booking lead time increased.

Appointments booked **31–60 days in advance had the highest observed no-show rate at 60.5%**, compared with 27.8% for appointments booked 0–7 days in advance.

This identifies longer booking lead times as an important segmentation factor for further investigation and appointment-support planning.

---

## Recommendation

HealthConnect Clinic should consider **additional reminder and confirmation follow-ups for appointments booked more than 30 days in advance**.

Timely follow-up closer to the appointment date could help the clinic address the higher observed no-show rate among longer-lead appointments.

This recommendation should be monitored and validated through future testing rather than treated as evidence of causation.

---

## Power BI Dashboard

The interactive Power BI dashboard provides a consolidated view of appointment performance and allows users to explore appointment outcomes across different patient and appointment characteristics.

The dashboard includes:

* Appointment outcome KPIs
* Attendance and no-show rates
* Cancellation rate
* Reminder effectiveness
* Average waiting time
* Age-group analysis
* Appointment-type analysis
* Booking lead-time analysis
* Previous no-show analysis
* Reminder analysis
* Distance-to-clinic analysis
* Waiting-time analysis
* Interactive filters and slicers

During Week 6, the booking lead-time visualization was refined to display **No-Show Rate by Booking Lead Time Group**, providing a clearer view of the observed relationship.

---

## Cross-Track Integration

The Data Analytics findings provide an analytical input for the **Data Science** track.

Booking lead time can be considered as a potential feature for future predictive modelling of appointment no-show behavior.

The Week 6 analysis provides:

* Validated KPI results
* Appointment outcome patterns
* Booking lead-time segmentation
* Evidence of varying no-show rates
* Potential modelling features
* Business-relevant findings for future testing

Formal Data Science implementation or feedback was not available at the current reporting stage and has therefore not been presented as completed.

---

## Limitations

* The analysis identifies associations and does not establish causation.
* The dataset represents a defined set of historical HealthConnect appointments.
* Some factors influencing appointment attendance may not be captured.
* Future patient behavior may differ from historical patterns.
* Booking lead-time groups may hide variation within individual categories.
* Further statistical testing is required to validate the Week 6 finding.

---

## Future Analysis

The next stage of the project should focus on:

* Statistical validation of the booking lead-time relationship.
* Testing whether the pattern remains consistent across different patient and appointment segments.
* Investigating additional factors associated with no-show behavior.
* Supporting Data Science feature selection and predictive modelling.
* Evaluating whether targeted reminder strategies are associated with improved attendance.

---

## Project Deliverables

* **Data Analytics Report:** `HealthConnect_Clinic_Week_5-6_Data_Analytics_Report_Muneeb_Tareen.docx`
* **Power BI Dashboard:** `HealthConnect_Clinic_Week_5-6_Data_Analytics.pbix`

---

## Tools Used

* **Microsoft Power BI** — Data analysis, KPI development, visualization, and dashboarding
* **Microsoft Excel** — Data review and preparation

---

## Conclusion

The Week 5–6 HealthConnect Clinic project demonstrates how data analytics can be used to identify appointment attendance patterns and support operational decision-making.

The analysis identified a substantial no-show rate and revealed a clear observed increase in no-show rates across longer booking lead-time groups. The refined Week 6 analysis provides a stronger analytical foundation for targeted appointment-support strategies and future predictive modelling.

The findings should be further tested and validated before being used to make causal or predic
