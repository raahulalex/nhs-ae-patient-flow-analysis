# NHS A&E Patient Flow Analysis (2025–2026)

## Project Overview

This project analyses NHS England Accident & Emergency (A&E) operational performance data between April 2025 and March 2026.

The analysis explores national urgent and emergency care pressures using provider-level operational data, with a particular focus on:

- A&E attendance trends
- 4-hour operational performance
- Decision-to-admit (DTA) waiting pressures
- Provider-level performance variation
- Indicators of wider patient-flow and inpatient pressure across NHS organisations

The project combines Python-based healthcare operational analytics with an interactive Tableau dashboard to investigate trends in NHS urgent care performance.

---

## Project Objectives

The objectives of this project were to:

- Analyse monthly trends in NHS A&E attendances and operational performance
- Investigate the relationship between emergency demand and 4-hour performance
- Identify providers experiencing higher operational pressure
- Explore prolonged decision-to-admit waits as indicators of patient-flow challenges
- Demonstrate healthcare operational analytics using real NHS England data
- Develop an interactive operational dashboard for performance monitoring and benchmarking

---

## Dataset Information

### Source

NHS England — A&E Attendances and Emergency Admissions Dataset

### Coverage

- April 2025 to March 2026
- Provider-level NHS England operational data
- Multiple urgent care settings including:
  - Type 1 A&E departments
  - Type 2 departments
  - Minor Injury Units
  - Walk-in Centres

### Key Variables Used

- Total A&E attendances
- Attendances over 4 hours
- 4-hour performance rate
- Decision-to-admit waits (4–12 hours and 12+ hours)
- Emergency admissions

---

## Tools and Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Tableau Public
- Healthcare Operational Analytics
- NHS England Open Data

---

## Project Structure

```text
nhs-ae-patient-flow-analysis
│
├── data_raw
├── data_cleaned
├── notebooks
├── outputs
├── dashboard
└── report
```

---

## Analysis Performed

### 1. Monthly A&E Performance Analysis

- National attendance trends
- 4-hour performance trends
- Attendance versus performance analysis

### 2. Provider-Level Benchmarking

- Lowest-performing providers
- Operational variation across NHS organisations
- Comparative provider analysis

### 3. Decision-to-Admit (DTA) Analysis

- Monthly DTA waiting trends
- 12+ hour waiting pressures
- Provider-level DTA benchmarking

### 4. Operational Pressure Analysis

- Relationship between emergency demand and performance
- Indicators of wider inpatient flow pressure
- System-level operational strain analysis

---

## Interactive Tableau Dashboard

An interactive Tableau Public dashboard was developed to visualise:

- National A&E attendance trends
- 4-hour operational performance
- Decision-to-admit waiting pressures
- Provider-level benchmarking
- Indicators of operational and patient-flow pressure

### Tableau Dashboard Link

https://public.tableau.com/views/NHSAEPatientFlowandOperationalPerformanceDashboard/NHSAEPatientFlowDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Key Findings

- National A&E performance remained under sustained operational pressure across the 12-month period.
- Winter months demonstrated worsening 4-hour performance and increased prolonged waiting pressures.
- Significant variation existed between NHS providers in both operational performance and DTA waits.
- Higher attendance volumes showed a weak negative relationship with 4-hour performance.
- Several providers demonstrated particularly high levels of prolonged decision-to-admit waits, suggesting wider inpatient flow challenges beyond emergency demand alone.

---

## Limitations

- The analysis used aggregated provider-level operational data rather than patient-level records.
- The project was exploratory and does not establish causal relationships.
- Additional operational variables such as bed occupancy, staffing levels, delayed discharges, and inpatient capacity were not included.
- Some provider organisations represented smaller urgent care settings which required filtering during benchmarking analysis.

---

## Future Improvements

Potential future extensions include:

- Bed occupancy and inpatient capacity analysis
- Delayed discharge and patient-flow modelling
- Seasonal trend forecasting
- Predictive modelling of operational pressure
- Expanded healthcare operational dashboarding
- Integration of additional NHS urgent care datasets

---

## How to Run the Project

1. Clone the repository
2. Open the notebook inside the `notebooks` folder
3. Install required Python libraries:

```text
pandas
matplotlib
```

4. Run notebook cells sequentially

---

## Why This Project Matters

A&E waiting times and delayed admissions remain major operational challenges for the NHS.

This project demonstrates how healthcare operational data can be used to:

- investigate urgent care pressures
- analyse patient flow
- benchmark provider performance
- identify operational strain within healthcare systems
- support operational performance monitoring

The project also demonstrates practical healthcare analytics skills including:

- data cleaning and preprocessing
- KPI engineering
- provider benchmarking
- healthcare data interpretation
- operational reporting
- dashboard development
- data visualisation
