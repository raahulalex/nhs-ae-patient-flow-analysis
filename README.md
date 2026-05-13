# NHS A&E Patient Flow Analysis (2025–2026)

## Project Overview

This project analyses NHS England Accident & Emergency (A&E) operational performance data from April 2025 to March 2026.

The analysis focuses on:
- Monthly A&E demand trends
- 4-hour A&E performance
- Decision-to-admit (DTA) waiting times
- Provider-level performance variation
- Indicators of wider patient-flow pressure across NHS hospitals

The project uses publicly available NHS England monthly A&E Attendances and Emergency Admissions data at provider organisation level.

---

## Project Objectives

The objectives of this project were to:

1. Analyse monthly trends in A&E attendances and 4-hour performance
2. Explore the relationship between emergency demand and operational performance
3. Identify provider organisations experiencing higher operational pressure
4. Investigate decision-to-admit waiting times as indicators of patient-flow challenges
5. Demonstrate healthcare operational analytics using real NHS England data

---

## Dataset Information

### Source
NHS England — A&E Attendances and Emergency Admissions Dataset

### Coverage
- April 2025 to March 2026
- Provider-level NHS England operational data
- Multiple A&E department types:
  - Type 1 A&E departments
  - Type 2 departments
  - Minor Injury Units and Walk-in Centres

### Key Variables Used
- Total A&E attendances
- Attendances over 4 hours
- 4-hour performance rate
- Decision-to-admit waits (4–12 hours and 12+ hours)
- Emergency admissions

---

## Project Structure

```text
nhs-ae-patient-flow-analysis
│
├── data_raw
├── data_cleaned
├── notebooks
├── outputs
└── report
```

---

## Tools and Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Healthcare Operational Analytics
- NHS England Open Data
- Patient Flow Analysis

---

## Analysis Performed

### 1. Monthly A&E Performance Analysis
- National attendance trends
- 4-hour performance trends
- Attendance versus performance relationship

### 2. Correlation Analysis
- Relationship between emergency demand and operational performance

### 3. Provider-Level Benchmarking
- Lowest-performing providers
- Comparison of operational variation across NHS organisations

### 4. Decision-to-Admit (DTA) Analysis
- Monthly DTA waiting trends
- 12+ hour waiting pressures
- Provider-level DTA benchmarking
- Adjusted DTA pressure rates

---

## Key Findings

- National A&E performance remained under operational pressure across the 12-month period.
- Higher attendance volumes showed a weak negative relationship with 4-hour performance.
- Significant variation existed between NHS providers in both performance and DTA waits.
- Several providers demonstrated high levels of prolonged decision-to-admit waiting times.
- The findings suggest wider inpatient flow pressures may contribute to operational strain beyond emergency demand alone.

---

## Limitations

- The analysis used aggregated provider-level operational data rather than patient-level records.
- The project was exploratory and does not establish causal relationships.
- Additional operational variables such as staffing levels, bed occupancy and discharge delays were not included.

---

## Future Improvements

Potential future extensions include:
- Power BI dashboard development
- Bed occupancy analysis
- Seasonal trend modelling
- Patient-level flow analysis
- Predictive modelling of operational pressure

---

## How to Run the Project

1. Clone the repository
2. Open the notebook inside the `notebooks` folder
3. Install required Python libraries:
   - pandas
   - matplotlib
4. Run the notebook cells sequentially

---

## Why This Project Matters

A&E waiting times and delayed admissions remain major operational challenges for the NHS.

This project demonstrates how healthcare operational data can be used to:
- investigate urgent care pressures
- analyse patient flow
- benchmark provider performance
- identify operational strain within healthcare systems

The project also demonstrates practical healthcare analytics skills including:
- data cleaning
- KPI development
- provider benchmarking
- healthcare data interpretation
- operational reporting
- visualisation
