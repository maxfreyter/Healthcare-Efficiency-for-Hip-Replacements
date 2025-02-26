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
- **Hospital factors:** Number of surgeons, facility efficiency
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
![image](https://github.com/user-attachments/assets/bcb7d310-ffc4-4e43-a2d2-124b27caf431)
- Patients 50+ make up the majority of hip replacement cases.

![image](https://github.com/user-attachments/assets/37bfcb34-65d1-4e40-b4cc-73e81e405dfc)
- Unexpectedly, LOS is nearly identical for patients under 50 and over 50. Age does not seem to significantly impact recovery time.


### 2. Hospital Performance Comparison
![image](https://github.com/user-attachments/assets/fd30d0e9-4296-40da-9475-6d7d2d2b8ea3)
- Syosset Hospital had the highest LOS (3.22 days) among the top 15 hospitals, despite having 11 surgeons.


### 3. Identifying Outliers: LOS vs. Cost
![image](https://github.com/user-attachments/assets/31ee1da3-47b2-4c75-a80c-8393cecc0418)
- Kings County Hospital has an outlier LOS of 12.07 days—nearly 5× the average.
![image](https://github.com/user-attachments/assets/2ed9d7b3-d24a-4e17-a97f-563369fbd972)
- NYU Lutheran Medical Center has an outlier cost of $84.6K per discharge—over 4× the average.


### 4. NYC Hospitals: High Costs & Low Volume
![image](https://github.com/user-attachments/assets/1cf7f39c-59bb-47fd-a438-4e171c16bdd4)
- Five hospitals in NYC have extremely high discharge costs but low patient volume, suggesting inefficiencies in resource utilization and potential overcharging.


### 5. Do More Surgeons Improve Efficiency?
![image](https://github.com/user-attachments/assets/76e44884-62a4-42c1-b161-1d015916c392)
- There's no clear correlation between the number of surgeons and hospital efficiency. More surgeons do not necessarily lead to shorter LOS or lower costs.


### 6. Health Status: Major Factor in LOS & Costs
![image](https://github.com/user-attachments/assets/10b84a8f-fd43-4ebc-90dd-e821422cdc8e)
- Extreme severity cases have 12.5-day LOS and $59.5K costs—nearly 3× longer and 2× higher costs than major severity cases.

![image](https://github.com/user-attachments/assets/76b55d90-d321-4715-a41f-e67d1827e47d)
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
- LOS and cost inefficiencies exist across several hospitals, with outliers significantly impacting averages.
- Health status—not age—is the primary driver of extended hospital stays and high costs.
- Number of surgeons does not affect efficiency, indicating that hospital workflows and care processes need greater attention.
- Targeted interventions can improve hospital efficiency, lower costs, and enhance patient outcomes.
