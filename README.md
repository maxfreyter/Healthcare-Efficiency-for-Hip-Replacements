[![Screenshot (47)](https://github.com/user-attachments/assets/cf8480eb-e70c-4039-b50b-fc4a4f7209b7)](https://public.tableau.com/app/profile/max.freyter/viz/HealthcareEfficiencyHipReplacementMetrics/CostOverview2#1)
Click [here](https://public.tableau.com/app/profile/max.freyter/viz/HealthcareEfficiencyHipReplacementMetrics/CostOverview2#1) to view my interactive dashboard on Tableau public!


# Case Study: Enhancing Hospital Efficiency in Elective Hip Replacement Surgeries

## Executive Summary
This project, conducted for HealthStat, a fictitious healthcare consulting firm, explores hospital efficiency in elective hip replacement surgeries across New York State. Using an anonymized 2016 hospital discharge dataset, analyzed in Tableau, the study uncovers insights into Length of Stay (LOS), discharge costs, and hospital performance.

Key findings indicate that certain hospitals significantly exceed industry norms in LOS and costs, while health status and diagnosis play critical roles in recovery time. This report provides actionable recommendations for optimizing hospital efficiency and improving patient outcomes.

## Healthcare Efficiency Framework
Efficiency in healthcare is minimizing waste, including equipment, supplies, ideas, and energy. A key efficiency indicator is Length of Stay (LOS)—the number of days a patient remains hospitalized.

Reducing LOS can:
- Lower costs for patients and hospitals
- Increase hospital capacity
- Improve patient throughput

Factors affecting LOS include:
- **Patient demographics:** Age, gender
- **Health status:** Severity of illness, pre-existing conditions
- **Hospital factors:** Hospital size, facility efficiency
- **Procedure risks:** Complications, post-surgical recovery

## Dataset Overview
- **Source:** DataCamp’s anonymized 2016 New York State hospital discharge data (https://app.datacamp.com/learn/courses/case-study-analyzing-healthcare-data-in-tableau)
- **Scope:** Patients undergoing elective hip replacement surgery
- **Size:** 30 columns, each row represents an individual inpatient stay
- **Tool Used:** Tableau for data visualization and analysis

## Key Metrics
- **Average LOS:** 2.65 days
- **Average Discharge Cost:** $20,910
- **Total Hospitals:** 151
- **Total Patients Discharged:** 26,286

## Key Findings & Visual Insights

### 1. Age and Gender Breakdown
![Screenshot (19)](https://github.com/user-attachments/assets/717d24da-721d-48de-b6a9-853f59c0f191)
- Patients 50+ make up the majority of hip replacement cases.


![Screenshot (20)](https://github.com/user-attachments/assets/e5d291e9-ae22-4bd8-afad-90fa0cebb6e2)
- Surprisingly, LOS is nearly identical for patients under 50 and over 50. Age does not seem to significantly impact recovery time.


### 2. Hospital Performance Comparison
![Screenshot (38)](https://github.com/user-attachments/assets/81879daa-11f6-4789-a3d9-cf38ea8e0349)

- Syosset Hospital had the highest LOS (3.22 days) among the top 15 hospitals, despite having 11 surgeons. One would think more surgeons means shorter hospital stays. This will be investigated further.


### 3. Identifying Outliers: LOS vs. Cost
![Screenshot (39)](https://github.com/user-attachments/assets/87e2e542-ff57-43e8-9dcf-d4ca718bca87)
- Kings County Hospital has an outlier LOS of 12.07 days—nearly 5× the average. While this seems quite high, a closer look using my interactive dashboard shows that one patient had a stay of 120 days, as well as a total cost of over $688k! This offers a valuable lesson on how a single outlier can skew average metrics and potentially misrepresent the overall performance of a facility.
- NYU Lutheran Medical Center has an outlier cost of $84.6K per discharge—over 4× the average. Interestingly, the average stay is just below the state average. I used my dashboard to investigate this further and what I found was interesting: 115 out of 124 total patients had osteoarthritis, with an average discharge cost of $86k. The state average for such patients is only 20k! It didn't seem to vary much between severity of illness either. Even minor cases averaged $85k. As we will discuss later, severity of illness is a strong contributer to high cost. NYU Lutheran's metrics aren't consistent with that trend.


### 4. NYC Hospitals: High Costs & Low Volume
![Screenshot (43)](https://github.com/user-attachments/assets/8879acce-0c01-49b7-a10a-6c07543d5319)
- Five hospitals in NYC have extremely high discharge costs but low patient volume, suggesting inefficiencies in resource utilization and potential overcharging.


### 5. Do More Surgeons Improve Efficiency?
![Screenshot (28)](https://github.com/user-attachments/assets/d15fc8e3-8169-4c99-8f1e-d2e95e86ea15)
- The trend line in the scatterplot is fairly close to being horizontal. This shows that there's no clear correlation between the number of surgeons and hospital efficiency. More surgeons do not necessarily lead to shorter LOS or lower costs. The efficiency of hospital workflows and care processes should be reviewed. 


### 6. Health Status: Major Factor in LOS & Costs
![Screenshot (33)](https://github.com/user-attachments/assets/17254461-4c7b-4805-a427-8c77b1fc9ea3)
- Extreme severity cases have 12.5-day LOS and $59.5K costs—nearly 3× longer and 2× higher costs than major severity cases. It's clear that severity of illness impacts length of stay and costs.

![Screenshot (44)](https://github.com/user-attachments/assets/99c911e8-415b-4ad7-be98-24241c583e3d)
- Cancer patients (bone/connective tissue) experience the longest LOS (12 days) and highest costs ($81.4K). 

## Actionable Recommendations

1. **Reduce Costs at High-Expense Hospitals**
   - Conduct financial audits to identify cost inefficiencies.
   - Implement standardized care pathways to streamline procedures and lower costs.

2. **Improve Performance at High-LOS Hospitals**
   - Review workflow inefficiencies at Kings County Hospital.
   - Enhance post-operative care plans to reduce LOS.

3. **Focus on High-Risk Patient Management**
   - Develop specialized care pathways for cancer and extreme severity patients to optimize recovery times.
   - Implement preventative osteoporosis programs to reduce surgical needs.

4. **Optimize Resource Utilization**
   - Reallocate resources in high-cost, low-volume NYC hospitals to improve efficiency.
   - Explore partnerships to share high-cost medical equipment between facilities.

5. **Implement Continuous Monitoring & Benchmarking**
   - Benchmark against top-performing hospitals to adopt best practices.

## Final Takeaways
- LOS and cost inefficiencies exist across several hospitals, with outliers significantly impacting averages. Even one case can skew the performance metrics of a facility.
- Health status—not age—is the primary driver of extended hospital stays and high costs for elective hip replacement patients.
- Number of surgeons does not affect efficiency, indicating that hospital workflows and care processes need greater attention.
- Targeted interventions can improve hospital efficiency, lower costs, and enhance patient outcomes.

