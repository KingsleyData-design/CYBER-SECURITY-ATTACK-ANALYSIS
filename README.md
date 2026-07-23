   # CYBER SECURITY ATTACK ANALYSIS DASHBOARD 

   ## Project Overview
  **How can a Cybersecurity Attack happen to an organization whose purpose is to protect against cyber threats?** Cyberattacks can affect even organizations with strong security expertise.  This project analyzes network traffic data using Excel, Power BI, Python and SQL Server to identify attack patterns, compare different attack types, and understand how malicious activity differs from normal network behavior. The goal was to transform the raw data to uncover insights that can help firms and organizations improve and tighten their cybersecurity strategies.

  ## Key Metrics

 | Metric | Value |
 |---|---:|
 | **Total Records** | **99,999** |
 | **Attack Records** | **75,123** |
 | **Attack Rate** | **75.12%** |
 | **Normal Traffic** |**24,876** |
  
  
   ## Insights — What the data actually says 
**Attacks made up the clear majority of network activity** — 75.12% out of 99,999 records were classified as attacks , compared with 24.88% normal traffic. Meaning the dataset is heavily weighted toward malicious  activity. 
**DDoS attacks generated the highest network activity** — they had the highest average packet count and the highest average source byte usage, making them the most significant attack type in terms of network volume. 
**Normal traffic had the longest average duration** — it lasted significantly longer than the attack types in this dataset, while DDoS had the shortest average duration.
-**Brute Force attacks recorded the highest average number of failed logins** — which fits the nature of attack, as repeated login attempts are a key indicator of credential based attacks.
**TCP and UDP traffic were almost evenly split** — the network traffic was not concentrated on a single protocol.


  ## Recommendations — What does this mean for a security team?
-**Prioritize DDoS detection and mitigation** — Since DDoS generated the highest packet and byte activity, monitoring sudden spike in network traffic could help identify and respond to these attacks faster. 
-**Monitor failed login patterns** — The high number of failed login attempts associated with Brute Force attacks suggests that login failure thresholds, accounts lockouts, and multi-factor authentification could help reduce the risk. 
-**Security monitoring should cover both TCP and UDP equally** — Since both protocols showed nearly equal usage, focusing heavily on one while ignoring the other could leave part of the network activity under monitored.
-**Normal traffic should be used as a baseline for anomaly detection** — Understanding what normal network behavior looks like can help seurity teams identify unusual patterns that may indicate an attack.
-**The high attack rate suggests that automated detection and real time monitoring are important** — With three out of every four records classified as attacks, relying only on manual investigation would be inefficent. 

## What I built it in, and why four times  
-**Excel** — cleaned and explored the data, first pass at survival and outcome breakdowns and major charts and dasboard with slicers. 
-**Power BI** — the main dashboard. Cancer Type and Gender as slicers, with charts covering survival by cancer type, survival months by treatment, age group, outcomes by stage, and a map of patients across Indian states. 
-**SQL** — same KPIs rebuilt as queries against the dataset. 
-**Python** — same analysis again in a notebook, pandas and matplotlib doing the work.  
Same reasoning as the rest of the portfolio — four tools, same questions, because the point isn't just the dashboard, it's proving the logic holds up across all of them. 
