# Insurance Claims Dashboard | Power BI

## Project Overview

An interactive insurance claims dashboard developed using Microsoft Power BI and DAX to analyze claim costs, product-level risk, regional patterns, and claim trends over time.

The project uses a synthetic insurance dataset and demonstrates how data can be transformed into interactive business insights for insurance decision-making.

## Dataset

The dataset contains four related tables:

| Table | Records |
|---|---:|
| Customers | 500 |
| Policies | 800 |
| Claims | 320 |
| Payments | 1,000 |

## Tools & Technologies

- Microsoft Power BI
- DAX
- Google BigQuery
- SQL
- Data Modelling
- Data Visualization

## Dashboard

![Insurance Claims Dashboard](Insurance%20Claim%20Dashboard%20Picture.png)

## Key Metrics

- **Total Policies:** 800
- **Total Claims:** 320
- **Total Claim Cost:** RM1.88M
- **Overall Claim-to-Premium Ratio:** 95.08%

## Key Insights

### Product Risk

- **Motor** has the highest total claim cost at approximately **RM0.86M**.
- **Travel** has the highest claim-to-premium ratio at **427.84%**.
- **Health** has the lowest claim-to-premium ratio at **41.98%**.

### Regional Analysis

- **North** has the highest total claim cost at approximately **RM0.53M**.
- **East** follows closely at approximately **RM0.52M**.
- **West** and **South** have lower total claim costs compared with North and East.

## Dashboard Features

- KPI cards for key insurance metrics
- Claim cost by insurance product
- Claim cost by region
- Claim cost trend over time
- Product risk summary
- Interactive policy-type slicer
- Conditional formatting for claim-to-premium ratios

## Insurance Analysis

The dashboard provides a high-level view of claim performance across insurance products and regions.

The claim-to-premium ratio is used as a comparative indicator in this project to highlight products where approved claim costs are high relative to premium. Since this is a synthetic portfolio and does not calculate earned premium or actuarial incurred claims, the ratio should not be interpreted as a formal actuarial loss ratio.

## Skills Demonstrated

- Insurance claims analysis
- Data modelling
- DAX measures
- Interactive dashboard development
- Data visualization
- Business intelligence
- Risk analysis
- Communicating analytical findings

## Project Structure

```text
insurance-claims-dashboard-powerbi/
│
├── Insurance Claims Dashboard.pbix
├── Insurance Claim Dashboard Picture.png
└── README.md
Author

Muhammad Aiman bin Azaman

Actuarial Science Student
Focus: Insurance Data Analytics
