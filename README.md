
# Data Analytics Portfolio: UK Labour Markets 

This repository contains data visualisation projects developed in Tableau to analyse regional economic shifts in the United Kingdom 

## 📈 Project 1: UK Industrial Employment Trends (EMSI)

**Live Dashboards:** [Dashboard 1](https://public.tableau.com/views/Change_17711741128970/Dashboard12?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
[Dashboard 2](https://public.tableau.com/views/Change_17711741128970/Dashboard3?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Situation:**  
Economic fluctuations between 2011 and 2014 significantly impacted various UK regions. There was a need to identify which industries were thriving and which were contracting to help inform regional development strategies.

**Task:**  
Create an interactive dashboard that allows stakeholders to compare job growth and decline across major UK cities using SIC (Standard Industrial Classification) codes.

**Action:**  
- **Data Structure:** Processed a complex dataset organised into two primary sheets: 1-digit (Broad Industries) for high-level sector overviews and 2-digit (Detailed Sub-industries) for granular analysis.  
- **Calculated Fields:** Created custom formulas in Tableau to determine the % Change in jobs, ensuring consistency between aggregation levels.  
- **Regional Analysis:** Focused on Swansea as a primary case study. Using the 1-digit data, identified growth in Arts & Entertainment (+42.7%). Using the 2-digit data, drilled down to see that while Public Administration remained stable, specific sub-sectors like Professional Services faced significant contraction (-21.9%).

**Result:**  
The dashboard successfully visualises the "two-speed" economy, allowing users to see the big picture while investigating the specific sub-industries driving those trends and how the differ from city to city.

### 💡 Insights

To understand the UK economy, we often look at the "average" trend, but the sources suggest that the most extreme data points—the outliers—provide the most critical lessons. To be clear, we are not suggesting that national trends are "hiding" inside these anomalies. Instead, we pay attention to outliers because they serve as essential signals for organizations to either encourage or prevent specific economic shifts.

First, outliers act as "Success Blueprints." For example, while professional services grew in many places, Nottingham-Derby saw a massive 47.9% surge. By studying the driving forces behind this specific success, other cities can learn how to replicate that growth.

Second, outliers are "Early Warning Signs." The sharp -27.0% drop in Public Administration in Cardiff-Newport and -26.7% in Swansea are localized shocks. If an organization wants to prevent such declines from spreading, it must understand the forces—such as budget shifts or relocation—behind these specific extremes.

Finally, outliers help us distinguish between speed and magnitude. The public should understand that an outlier in percentage can be different from an outlier in actual jobs.Swansea’s 53.2% growth in Real Estate is a high-speed outlier but represents only 1,241 jobs. In contrast, London’s 19.4% growth in the Professional sector added over 100,000 jobs, showing massive scale. 

By watching how these extremes evolve, the public can better understand where the economy is "tilting" and prepare for the future. 
