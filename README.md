# CYBER SECURITY ATTACK ANALYSIS DASHBOARD 

## Project Overview
  - This project analyzes cyber attack data using Microsoft Excel, Power BI, Python (Pandas, Matplotlib) and SQL Server to identify attack types, attack patterns and network protocol. The goal was to transform the raw data to uncover insights that can help firms and organizations improve and tighten their cybersecurity strategies.
  
  ## Project Objectives
  - Performed same Analysis across different tools, solving same Questions
  - Cleaned and prepared the cyber attack Dataset with microsoft Excel
  - Identified the most common cyber attack types
  - Analyzed cyber attack patterns across different networks
  - Created visualizations to support cybersecurity decision making

  ## Tools Used
- **Excel** — Data cleaning, Data exploration, Pivot Tables, Dashboard
- **Power BI** — Interactive dashboard with KPI cards
- **SQL (SSMS)** — Data querying and aggregation
- **Python** — Data analysis and visualization (Pandas, Matplotlib, Seaborn)

 ## Key Metrics

 | Metric | Value |
 |---|---:|
 | **Total Records** | **99,999** |
 | **Attack Records** | **75,123** |
 | **Attack Rate** | **75.12%** |
 | **Normal Traffic** |**24,876** |

## Key Insights
- After cleaning and preparing the Dataset which originally had 100,000 rows, 99,999 valid rows were found
  - By the end of this analysis, 75.12% of records were attacks, while 24,876 were normal traffic and Attack rate was also 75.12%
  - DDoS had the highest average packet count and byte usage
  - Normal traffic showed the highest average duration compared to attack types
  - BruteForce attacks had the highest failed login attempts
  - TCP and UDP usage were nearly equal.

  ## Recommendations
  - Prioritize DDoS detection and mitigation.
  - Monitor failed login patterns.
  - Strengthen authentification records.
  - Security monitoring should cover both TCP and UDP Traffic equally.
  - Lastly, Establish normal traffic baselines, using the characteristics of normal traffic to improve anomaly detection.
