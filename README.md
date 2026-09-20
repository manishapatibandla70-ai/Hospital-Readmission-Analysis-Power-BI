# Hospital Readmission Analysis – Power BI

## Project Overview

Hospital Readmission Analysis is a Power BI project built using healthcare data to analyze patient outcomes and hospital operations. The report brings together different healthcare metrics into interactive dashboards covering readmissions, revenue, blood bank activity, diagnostic errors, emergency delays, follow-up compliance, ICU mortality, patient satisfaction, and surgery cancellations.

The project uses a healthcare master dataset and Power BI measures and visualizations to organize the data into separate analytical views.

## Dataset

The main dataset used in the project is `Healthcare_Master`.

It contains 3,070 records and 33 fields covering patient, admission, treatment, hospital operation, and outcome-related information.

The dataset includes information such as:

- Patient ID
- Age
- Gender
- Disease
- Department
- Blood Group
- Admission Date
- Discharge Date
- Stay Days
- Waiting Time
- Diagnosis Delay
- Treatment Cost
- Satisfaction Score
- Follow-up information
- Surgery information
- Blood Units
- Readmission
- Mortality

A separate `Business_Cases` sheet contains healthcare-related business questions used as a reference for analysis.

## Power BI Report

The report contains the following pages:

### 1. Readmission Analysis

Focuses on hospital readmission data, including department-level analysis and readmission rate measures.

### 2. Revenue Analysis

Provides analysis of revenue and cost-related healthcare data.

### 3. Blood Bank

Presents analysis related to blood groups and blood unit information.

### 4. Diagnostic Error

Provides analysis of diagnostic error and diagnosis-related information.

### 5. Emergency Delay

Analyzes emergency waiting and delay-related hospital data.

### 6. Follow-up Compliance

Focuses on patient follow-up information and compliance.

### 7. ICU Mortality

Provides analysis of mortality-related information for ICU patients.

### 8. Patient Satisfaction

Analyzes patient satisfaction scores and related healthcare information.

### 9. Surgery Cancellation

Provides analysis of surgery cancellation-related data.

## Data Model and Analysis

The Power BI project is built around the `Healthcare_Master` dataset. The report includes Power BI measures and visualizations for analyzing healthcare metrics.

One of the measures used in the report is **Readmission Rate %**, which is used for department-wise readmission analysis.

The project also includes the Power BI model, report layout, diagram layout, metadata, settings, and related project configuration files.

## Tools Used

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX
- Data Visualization

## Key Areas Covered

- Healthcare data analysis
- Data preparation
- Data modeling
- DAX measures
- KPI analysis
- Interactive dashboards
- Patient outcome analysis
- Hospital operational analysis
- Department-wise analysis
- Data visualization

## Project Structure

```text
Hospital-Readmission-Analysis-Power-BI
│
├── Healthcare.xlsx
│
├── Power BI
│   ├── Report
│   ├── DataModel
│   ├── DiagramLayout
│   ├── Settings
│   ├── Metadata
│   ├── SecurityBindings
│   ├── Version
│   └── [Content_Types].xml
│
└── README.md
## Purpose of the Project

The purpose of this project is to work with healthcare data in Power BI and present different hospital-related metrics through structured and interactive report pages. It demonstrates the use of data preparation, modeling, measures, and visualization to organize healthcare information for analysis.

## Author

**Moksha Manisha**
