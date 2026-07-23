   # CYBER SECURITY ATTACK ANALYSIS DASHBOARD 

   ## PROJECT OVERVIEW
  **How can a Cybersecurity Attack happen to an organization whose purpose is to protect against cyber threats?** That was the first question i could think of when i got hold of this dataset. By the end of the analysis, i got to learn that, Cyberattacks can affect even organizations with strong security expertise.  This project analyzes network traffic data using Excel, Power BI, Python and SQL Server to identify attack patterns, compare different attack types, and understand how malicious activity differs from normal network behavior. The goal was to transform the raw data to uncover insights that can help firms and organizations improve and tighten their cybersecurity strategies.

  ## KEY METRICS

 | METRIC | VALUE |
 |---|---:|
 | **TOTAL RECORDS** | **99,999** |
 | **ATTACK RECORDS** | **75,123** |
 | **ATTACK RATE** | **75.12%** |
 | **NORMAL TRAFFIC** |**24,876** |
  
  
   ## KEY INSIGHTS — THE DATA STORY 
- **Attacks made up the clear majority of network activity** — 75.12% out of 99,999 records were classified as attacks , compared with 24.88% normal traffic. Meaning the dataset is heavily weighted toward malicious  activity. 
- **DDoS attacks generated the highest network activity** — they had the highest average packet count and the highest average source byte usage, making them the most significant attack type in terms of network volume. 
- **Normal traffic had the longest average duration** — it lasted significantly longer than the attack types in this dataset, while DDoS had the shortest average duration.
- **Brute Force attacks recorded the highest average number of failed logins** — which fits the nature of attack, as repeated login attempts are a key indicator of credential based attacks.
- **TCP and UDP traffic were almost evenly split** — the network traffic was not concentrated on a single protocol.


  ## RECOMMENDATIONS — WHAT DOES THIS MEAN FOR A SECURITY TEAM?
- **Prioritize DDoS detection and mitigation** — Since DDoS generated the highest packet and byte activity, monitoring sudden spike in network traffic could help identify and respond to these attacks faster. 
- **Monitor failed login patterns** — The high number of failed login attempts associated with Brute Force attacks suggests that login failure thresholds, accounts lockouts, and multi-factor authentification could help reduce the risk. 
- **Security monitoring should cover both TCP and UDP equally** — Since both protocols showed nearly equal usage, focusing heavily on one while ignoring the other could leave part of the network activity under monitored.
- **Normal traffic should be used as a baseline for anomaly detection** — Understanding what normal network behavior looks like can help seurity teams identify unusual patterns that may indicate an attack.
- **The high attack rate suggests that automated detection and real time monitoring are important** — With three out of every four records classified as attacks, relying only on manual investigation would be inefficent. 

## WHAT I BUILT IT IN AND WHY FOUR TIMES? 
- **Excel** — cleaned and explored the data, first pass at survival and outcome breakdowns and major charts and dasboard with slicers.
  
- **Power BI** — the main dashboard. Attack type and patterns all revealed. Solid charts and notable DAX and KPIs on display.
 
- **SQL** — same KPIs rebuilt as queries against the dataset.
 
- **Python** — same analysis again in a notebook, pandas and matplotlib doing the work.
 
Same reasoning as the rest of the portfolio — four tools, same questions, because the point isn't just the dashboard, it's proving the logic holds up across all of them. 
