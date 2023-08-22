# HCAHPS_Dashboard

**Introduction**: 

American Hospital Association (AHA) is a national organization that represents hospitals and their patients, and acts as a source of information on healthcare issues and trends. The dataset consists of National & state-level results from 2013 to 2022 for the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey, including hospital-level completions and response rates.

**Objective**: 

To analyze the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey results for the last 9 years. The intent of the HCAHPS initiative is to provide a standardized survey instrument for measuring patients’ perspectives on hospital care, and one of its 3 main goals is to "create incentives for hospitals to improve their quality of care.

**Data Cleaning**:
1. I have cleaned the data in a way that all the tables are connected through their foreign keys and the relationships are well-defined.
2. For some data they didn't have a specific numeric value, rather they had ranges. I have used an average number for that data (Completed survey) so that it is easier to have an estimate about how many people completed the surveys. For example, I assigned the numbers like this: 300 or More to 350 |Fewer than 100 to "75" | Between 100 - 299 to "200". This might not be exactly accurate but this does give a direction to have a clear idea about this variable.


**Dashboard**

![HCAHPS_Patient](https://github.com/Anish127/HCAHPS_Dashboard/assets/77845356/64cc2be8-b835-4de9-8b6d-40a320fb456c)

![HCAHPS_Patient (1)](https://github.com/Anish127/HCAHPS_Dashboard/assets/77845356/d3c8dad3-37d9-4982-b539-4d372eceb517)



**Key Insights**:

 1. Highest patient satisfaction rates of 77% were recorded in South Dakota and Nebraska states.
 2. The District of Columbia recorded the lowest patient satisfaction rates, which were at 15%
 3. Least Satisfaction rate of 69% was observed in the year 2023
 4. The average response rate for the patient satisfaction surveys is 27%. This indicates that there is room for engaging and motivating patients to complete the survey. 
 5. The total number of completed surveys has decreased from 29.8 billion in 2016 to 21.6 billion in 2023, which suggests that there is a decline in patient participation and feedback 
    over time.
 6. Communication about medicine is the most declined measure over the years


**Recommendations**:

1. To increase the response rate, the hospitals should implement some strategies to encourage and incentivize patients to complete the surveys, such as providing reminders, rewards, or 
   feedback.
2. To improve the scores for other measures of patient satisfaction, the hospital should monitor and evaluate their performance and identify their strengths and weaknesses, such as 
   using benchmarks, audits, or feedback loops.
3. To learn from the best practices of the high-scoring hospitals, the hospitals should seek opportunities for collaboration and exchange with them, such as forming networks, 
   partnerships, or alliances.
4. Comprehensive training should be provided to all staff members.
