# Irish hospital Patient Waiting Time 2021-2023

## Dashboard 
Link: https://app.powerbi.com/view?r=eyJrIjoiOTI1MTU3YjYtYmEzNi00MDJiLWE1ZGYtODdhOGE0NmE5YzYzIiwidCI6IjVkMGFhNmVhLTY2MjAtNDg2My05ZTIxLTllY2IxNDAyMjJiYyIsImMiOjh9

## Overview

Irish Patient Waiting time dashboard provides insights into patient waiting times across various hospitals and specialties in Ireland, offering data representation from 2021 to 2023. It is designed to aid healthcare analysts in evaluating service efficiency, identifying high-demand areas, and optimizing patient care strategies.

## Data Sources

- Outpatient and Inpatient Waiting Lists (2021-2023): Sourced total counts of patients waiting for appointments across various time bands from eHealth Ireland.

- Irish Hospital Mapping: Created Geospatial data to identify regional hotspots.

- Irish Specialty Mapping: Categorized the relationship between medical specialties and patient needs.

## Data Transformation

- Season: Integrating a 'Season' column helps in identifying seasonal trends in patient volumes and wait times. Certain health issues may be more prevalent in specific seasons (e.g., respiratory infections in winter), and understanding these patterns allows for better staffing and resource planning.

- Long-term Stay (%) and Short-term Stay (%): These columns categorize patients based on the duration of their wait times. Differentiating patients by their wait time durations (like those waiting 0-6 months vs. 18+ months) helps in assessing the urgency of care needed and the efficiency of hospital service. It's also crucial for operational planning, ensuring that resources are allocated to reduce longer wait times effectively.

- Patient Contribution (%): This column provides insights into the workload contributed by each hospital or specialty. Calculating the percentage contribution of patients to each hospital or specialty helps identify high-demand areas and can guide decisions on resource reallocation to meet patient care demands more efficiently.

- Geospatial Analysis Preparation: Including latitude and longitude in the Irish Hospital Mapping dataset enhances the capability for geospatial analysis. This allows for visualizing data on maps, which can reveal geographic trends in patient distribution, hospital utilization, and regional healthcare needs.

- Categorization of Specialties: Grouping medical specialties in relation to specific body systems or types of care can help in analyzing the data more effectively. For instance, grouping similar specialties can simplify the analysis and highlight areas where certain types of specialists are in higher demand

## Dashboard Snapshot
![image](https://github.com/minhazulamin1/Irish-Hospital-Patient-Waiting-Dashboard-2021-2023/assets/168876236/78220fbf-ce51-41e6-9c4c-621960e8fc92)

![image](https://github.com/minhazulamin1/Irish-Hospital-Patient-Waiting-Dashboard-2021-2023/assets/168876236/7237ef62-5ab6-43ed-a4b2-7f60c347c575)

## Key Metrics 

#### Average Wait Times 

- Average time patients wait for medical care across different hospitals and specialties.
- Identifies bottlenecks in the system where wait times are excessively long and where improvements are necessary.

#### Average Patient per Hospital/Speciality 

- Typical patient volume in a hospital or specialty.
- Understanding patient distribution helps in resource and staffing planning. Hospitals or specialties with high patient volumes might need additional resources to handle the load effectively, ensuring that patient care does not suffer due to overcrowding.

#### Adult to Child Ratio

- Proportion of adult patients to child patients in each hospital or specialty.
- Aids in customizing healthcare services to demographic needs. Knowing the ratio can help allocate pediatric and adult specialists more effectively, ensuring that both demographics receive appropriate and timely care.

#### Average Short-term Wait Time (Hospital/Speciality)

- Waiting period for short-term care, focusing on those within the 0-6 month wait time category.
- Short-term wait times are critical for managing patient expectations and improving patient experience. This measure helps in prioritizing interventions in hospitals or specialties where short-term waits are longer than average.

#### Patient Contribution (%)

- Percentage contribution of the total number of patients for each hospital and specialty to the overall dataset.
- Identifies areas of high demand and potential growth within the healthcare system. It helps healthcare administrators understand where to focus their efforts to enhance capacity and improve services.

#### Long-term Stay and Short-term Stay (%)

- Grouped percentage of patients categorized by extended (12-18 months, 18 months+) and shorter (0-6 months, 6-12 months) hospital stays.
-  Differentiating between long-term and short-term patients allows for better allocation of resources. Long-term patients may require more intensive and sustained resources, while strategies to reduce short-term wait times can significantly improve overall efficiency and patient throughput.

## Key Insights

#### University hospitals have the highest average waiting times in Ireland for outpatients
- Possible Reasons: Mainly due to a wide range of specialized services and usually dealing with complex specialties which might require additional time for diagnosis and treatment planning, lead to longer wait times. 

![image](https://github.com/minhazulamin1/Irish-Hospital-Patient-Waiting-Dashboard-2021-2023/assets/168876236/f9c00ffe-9d61-4369-8d7a-28193969951d)

#### Bones/Joints and skin causing future risk of healthcare in Ireland
- Possible Reasons: Vitamin D deficiency due to lack of sufficient sunlight in July. Geographical locations of Ireland at high latitudes contribute to reduced UV. Additionally, cloudy weather and indoor lifestyle also could be potential reasons.

![image](https://github.com/minhazulamin1/Irish-Hospital-Patient-Waiting-Dashboard-2021-2023/assets/168876236/37fa2a6f-f9dd-4aa5-917f-1d601031c326)
