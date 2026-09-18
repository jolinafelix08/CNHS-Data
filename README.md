# Cabiao National High School KPI-Based Strategic Dashboard

A web-based **KPI Strategic Dashboard** developed for **Cabiao National High School (CNHS)** as part of the capstone project:

> **Driving Institutional Performance Governance Through a KPI-Based Strategic Dashboard Model for Cabiao National High School**

The dashboard consolidates selected institutional indicators into one management-oriented view to support performance monitoring, trend analysis, gap identification, and evidence-based decision-making.

---

## Dashboard Overview

The dashboard organizes school performance into four major perspectives:

- **Student Outcomes**
  - Enrollment and Retention
  - Academic Performance
  - Student Attendance

- **Financial Management**
  - Budget Utilization
  - Procurement
  - Disbursement
  - Financial Reporting

- **Internal Operations**
  - Workforce
  - Personnel Attendance
  - Training Completion
  - Programs and Activities

- **Stakeholder Engagement**
  - Participation
  - Satisfaction
  - Partnerships
  - Stakeholder Support and Contributions

A dedicated **Priority Issues** page consolidates indicators requiring management attention using predefined thresholds.

---

## Key Features

- Executive Summary
- Interactive School Year / Fiscal Year filter
- Interactive Quarter filter
- Section-specific filters
- KPI cards and status indicators
- Trend and comparative charts
- Red / Gold / Green performance indicators
- Detailed data tables
- Priority Issues ranking
- Dashboard Guide
- **Update Data** function for operational use
- Automatic detection of newly added school years
- Local browser storage for imported datasets
- Blank Excel data-template generation
- Restore Demonstration Data option
- Offline-capable Excel workbook reading

---

## Demonstration vs. Operational Use

The public GitHub version contains a **synthetic presentation dataset** for dashboard demonstration, testing, and capstone presentation.

The displayed values **must not be interpreted as official or current Cabiao National High School performance records**.

For operational use, authorized CNHS personnel may load a validated institutional Excel workbook through the dashboard's **Update Data** function.

---

## How CNHS Can Update the Dashboard Data

1. Open the dashboard.
2. Click **Update Data**.
3. Select **Choose Excel Workbook**.
4. Choose the updated CNHS KPI workbook.
5. The dashboard validates the workbook structure.
6. If valid, the dashboard refreshes automatically using the selected data.
7. The imported data are stored locally in the browser/device being used.

No editing of the HTML source code is required for routine data updates.

---

## Excel Workbook Structure

For best compatibility, use the dashboard's **Download Blank Data Template** option.

The workbook should contain the following worksheets:

| Worksheet | Main Purpose |
|---|---|
| Enrollment Data | Enrollment, retention, promotion, graduation, dropout |
| Academic Performance | Subject performance, averages, passing rates |
| Attendance Raw Data | Student attendance by period |
| Annual Budget | Allocation, expenditure, utilization |
| Procurement Records | Procurement completion and delays |
| Disbursement Details | Fund-release timeliness |
| Financial Reporting | Financial-report compliance |
| Reporting Data | School-report submission compliance |
| Personnel Data | Staffing, attendance, training, workload |
| Program Activity | Program and activity completion |
| Stakeholder Data | Participation, satisfaction, partnerships, support |

### Important

- Keep worksheet names unchanged.
- Keep required column headers unchanged.
- Use `YYYY-YYYY` for School Year, e.g. `2026-2027`.
- Use `Q1`, `Q2`, `Q3`, or `Q4` for Quarter.
- Enter rates as Excel percentages or decimals, e.g. `92%` or `0.92`.

---

## Data Governance and Privacy

The dashboard is designed for **aggregate institutional performance data**.

Do not include unnecessary personal or sensitive information such as:

- Learner names
- Learner Reference Numbers (LRN)
- Employee numbers
- Home addresses
- Personal contact information
- Other personally identifiable information not required for KPI computation

For actual school implementation, institutional records should be validated and handled according to applicable school, DepEd, and data-privacy requirements.

---

## Priority Issues

The **Priority Issues** section summarizes performance concerns detected from KPI results and dashboard thresholds.

Examples may include:

- Late or incomplete reports
- Financial reports requiring follow-up
- Incomplete programs
- Underutilized budget categories
- Attendance below monitoring thresholds
- Academic areas below target
- Workforce or training gaps

Priority Issues are intended as a **decision-support view** and should be interpreted together with validated institutional records and management context.

---

## Repository Structure

```text
CNHS-Data/
│
├── index.html
└── README.md
```

`index.html` contains the dashboard application, interface, calculations, visualizations, demonstration dataset, and Excel-import functionality.

---

## Recommended Operational Workflow

```text
Authorized School Records
        ↓
Standardized CNHS Excel Workbook
        ↓
Data Validation
        ↓
Update Data
        ↓
KPI Dashboard
        ↓
KPI Cards / Trends / Priority Issues
        ↓
Management Review and Decision-Making
```

Suggested data ownership:

| Data Area | Suggested Responsible Office |
|---|---|
| Enrollment / Retention | Registrar |
| Academic Performance | Department Heads / Registrar |
| Student Attendance | Registrar / Academic Office |
| Budget / Disbursement | Bookkeeper |
| Procurement | Administrative Office |
| Programs / Reporting | Department Heads / Administrative Office |
| Workforce | Administrative Office |
| Stakeholder Engagement | School Administration |
| Dashboard Maintenance | ICT Coordinator / Authorized ICT Staff |
| Final Data Validation | School Principal / Authorized Personnel |

---

## Intended Use

The dashboard is intended to serve as a **supplementary management and decision-support tool**.

It does not replace:

- Official DepEd reports
- Official school records
- Required financial reports
- Existing institutional reporting mechanisms

Its purpose is to consolidate selected performance indicators into a more accessible and management-oriented view.

---

## Capstone Context

This dashboard was developed as the principal developmental output of the MBA capstone project at **Wesleyan University-Philippines Graduate School**.

The project focused on improving institutional performance governance through integrated KPI monitoring across:

- Student Outcomes
- Financial Management
- Internal Operations
- Stakeholder Engagement

---

## Author

**Jolina Felix Gripal**  
Master in Business Administration  
Wesleyan University-Philippines Graduate School

---

## Disclaimer

The demonstration dataset included in the public dashboard is synthetic and was developed solely for system development, testing, and academic presentation.

Actual operational use by Cabiao National High School should use authorized and validated institutional records and appropriate access-control, privacy, and data-governance procedures.
