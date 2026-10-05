# Green Destinations – HR Attrition Dashboard

![Green Destinations Logo](greendestination+logo.png)

## Overview

Green Destinations is a well-known travel agency. The HR Director noticed a rise in employee departures (attrition) and wanted a data-driven view of the problem. This project analyses survey data from **1,470 employees** to uncover the key trends and patterns behind staff leaving the company.

## Project Objective

The HR Director asked three core questions:

1. **What is the overall attrition rate?** (% of people who have left)
2. **Do factors like age, years at the company, and income influence whether someone leaves?**
3. **Which departments and job roles carry the highest risk?**

## Dashboard

The analysis is delivered as a fully self-contained interactive HTML dashboard:

**File:** `GreenDestinations_Attrition_Dashboard.html`

Open it in any modern web browser — no server or internet connection required.

### What the dashboard includes

| Section | Description |
|---|---|
| **KPI Strip** | Attrition rate, average income gap, average tenure gap, overtime impact |
| **Attrition by Department** | Sales (20.6%), HR (19%), R&D (13.8%) |
| **Attrition by Age Group** | Under-25s leave at 39.2% — the highest of any group |
| **Avg Monthly Income** | Employees who left earned $4,787 vs $6,833 for those who stayed |
| **Attrition by Tenure** | 29.8% of employees with ≤ 2 years leave — nearly 3× the company average |
| **Overtime Impact** | Overtime workers leave at 30.5% vs 10.4% for non-overtime staff |
| **Attrition by Gender** | Male 17% vs Female 14.8% |
| **Attrition by Job Role** | Sales Representatives highest at 39.8% |
| **Key Insights** | Five narrative findings summarising the main drivers |
| **About This Project** | Context on what the project is, why it was built, and how |

## Key Findings

- **16.1%** overall attrition rate (237 of 1,470 employees left)
- **Age** is the strongest predictor — under-25s are 4× more likely to leave than mid-career staff
- **Income gap** — a $2,046/month difference exists between those who left and those who stayed
- **Overtime** triples attrition risk (30.5% vs 10.4%)
- **Early tenure** is the danger zone — nearly 1 in 3 employees leave within their first 2 years

## Data Source

| File | Description |
|---|---|
| `greendestination (1).csv` | Raw employee survey data — 1,470 rows, 35 columns covering demographics, job details, satisfaction scores, and attrition status |
| `greendestination+logo.png` | Company logo embedded in the dashboard |
| `Project Objective.jpg` | Original project brief from the HR Director |

## How to Use

1. Clone or download this repository
2. Open `GreenDestinations_Attrition_Dashboard.html` in any browser
3. All charts and data are embedded — no setup needed

## Built With

- **Chart.js** — interactive charting library
- **HTML / CSS** — fully self-contained, no frameworks
- **IBM Bob** — AI-assisted development and analysis
