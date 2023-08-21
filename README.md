# HCAHPS_Dashboard

**Introduction**: American Hospital Association (AHA) is a national organization that represents hospitals and their patients, and acts as a source of information on healthcare issues and trends. The dataset consists of National & state-level results from 2013 to 2022 for the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey, including hospital-level completions and response rates.

**Objective**: To analyze the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey results for the last 9 years. The intent of the HCAHPS initiative is to provide a standardized survey instrument for measuring patients’ perspectives on hospital care, and one of its 3 main goals is to "create incentives for hospitals to improve their quality of care.

**Data Cleaning**:
1. I have cleaned the data in a way that all the tables are connected through their foreign keys and the relationships are well-defined.
2. For some data they didn't have a specific numeric value, rather they had ranges. I have used an average number for that data (Completed survey) so that its easier to have an estimate about how many people completed the surveys. For example, I assigned the numbers like this: 300 or More to 350 |Fewer than 100 to "75" | Between 100 - 299 to "200". This might not be exactly accurate but this does give a direction to have a clear idea about this variable.

**Key Insights**:
 1. **States with the Most and least satisfied patients**
 **>** South Dakota and Nebraska states have the most satisfied patients.
 **>** District of Columbia has the least satisfied patients
