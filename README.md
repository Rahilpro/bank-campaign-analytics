# Bank Campaign Analytics
End-to-end data analysis on UCI Bank Marketing Dataset (11,162 customers)

## Project Overview
Analysed a Portuguese bank's telemarketing campaign to identify 
factors driving term deposit subscriptions.

## Tech Stack
- SQL — data exploration and EDA (7 phases, 30+ queries)
- Python/pandas — visualisation and statistical validation
- Power BI — interactive 4-page dashboard

## Key Findings
- Call duration is the strongest predictor (r=0.45, p<0.0001)
- Campaign fatigue starts after 3 calls (53% → 25% conversion)
- Students and retirees convert at 74.7% and 66.3%
- Re-contact window of 31-90 days converts at 81.7%

## Statistical Validation
- Chi-square tests: all 9 categorical features significant (p<0.05)
- T-tests: all 6 numeric features significant (p<0.05)
- Point-biserial correlation: duration r=0.45 (strongest predictor)

## Dashboard
- Live Power BI: https://app.powerbi.com/view?r=eyJrIjoiMTcxMjg3YzItYTJkYi00MTIwLWE1OGQtNTVmZjU1YTMyMTM2IiwidCI6Ijk2NDY0YThhLWY4ZWQtNDBiMS05OWUyLTVmNmI1MGEyMDI1MCIsImMiOjN9

## Dataset
UCI Bank Marketing Dataset — 11,162 rows, 17 columns
Source: https://archive.ics.uci.edu/ml/datasets/bank+marketing
