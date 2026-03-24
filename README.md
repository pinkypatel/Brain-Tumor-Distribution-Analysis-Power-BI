## Brain Tumor Distribution Analysis (Power BI)
Healthcare Analytics | Data Visualization | Power BI Dashboard

### Project Overview
This project presents an interactive Power BI dashboard to analyze brain tumor patient data. The dashboard provides insights into tumor distribution, patient demographics, and diagnosis trends to support data-driven healthcare decisions.

### Tools and Technology Used
  * Power-BI

### Objective
  *	Analyze distribution of tumor types and grades
  *	Identify most affected age groups 
  *	Understand region-wise tumor occurrence 
  *	Track yearly diagnosis trends 
  *	Enable interactive exploration using filters

### Dataset Overview
  * Patient ID
  * Age
  * Gender
  * Tumor Type
  * Tumor Grade
  * Affected Brain Region
  * Tumor Size (cm)
  * Symptoms
  * Laterality
  * Histology Confirmation
  * Treatment Type
  * Date of Diagnosis

#### Sample Preview 

|Patient ID|Age|Gender|Tumor Type|Tumor Grade|Affected Brain Region|Tumor Size (cm)|Symptoms|Laterality|Histology Confirmation|Treatment Type|Date of Diagnosis|
|----------|----|-----|----------|-----------|---------------------|---------------|--------|----------|----------------------|--------------|-----------------|
|P00001|41|	Male|Glioma|Grade 1|Frontal|2.9|Weakness|Left|Confirmed|Observation|3/4/2022|
|P00002|	11|	Male|Ependymoma|Grade 3|Cerebellum|6.8|Balance issues, Dizziness, Coordination problems|Right|Confirmed|Radiation|4/1/2016|
|P00003|	23|	Male|Pituitary Tumor|Grade 1|Pituitary|1.6|Headache, Vision problems|Left|Confirmed|Observation|4/13/2015|

### Data Preparation (Power Query) and Data Transformation
  * Standardized date fields for accurate time-based analysis
  * Created a calculated column Age Group to segment patients into meaningful categories
  * Enabled better demographic analysis and visualization
   
### DAX Measures
  * Average Intake per Year
    → Calculated average number of patients diagnosed per year to normalize trends
  * Comparison vs Overall Average
    → Compared segment-level performance against overall average using visual indicators
  * Most Affected Age Group
    → Identified the age group with the highest number of patients
  * Most Affected Brain Region
    → Highlighted the most impacted brain region along with its percentage contribution
    
### Power BI Dashboard Features
* KPI Cards:
  - Total Patients
  - Average Age
  - Average Tumor Size
* Visualizations:
  - Donut Chart : Tumor Type Distribution
  - Bar Chart : Top Affected Brain Region
  - Line Chart : Annual Patient Diagnosed Chart
  - Bar Chart : Top Affected Age Group
* Filters:
  - Histology Confirmation (Confirmed / Unconfirmed)
* Extra Visuals added :
  - Chiclet Slicer and Image by CloudScope

### Power BI Dashboard Preview
<img width="1438" height="805" alt="image" src="https://github.com/user-attachments/assets/55b7fc7f-4c02-4f77-bada-4e59cce73855" />

### Key Insights

1. Overall Trends
  * The dataset includes 1500+ patients, with tumor cases distributed across multiple grades
  * The most affected age group across all grades is 41–60 years
  * Tumor size and severity tend to increase with higher tumor grades
  * Diagnosis trends show fluctuating patterns over the years, indicating variability in detection rates

2. Key Observations
  * Tumor severity increases with tumor size and spread
  * There is a shift in affected age group from middle-aged to older.
  * Certain brain regions like Cerebellum and Pituitary are frequently impacted
  * Early-stage detection could help reduce progression to higher-grade tumors

### Business Impact
  * Helps healthcare professionals identify high-risk age groups for early diagnosis
  * Provides insights into most affected brain regions, supporting targeted medical attention
  * Enables tracking of tumor trends over time, useful for hospital resource planning
  * Assists in understanding tumor progression across grades, aiding clinical decision-making
  * Supports data-driven strategies for early detection and treatment planning

### How to Use
  1. Download the `.pbix` file from this repository  
  2. Open it using Power BI Desktop  
  3. Use filters (Histology Confirmation, Tumor Grade) to explore insights
   
### Future Improvements
  * Integrate SQL or Python for deeper analysis
  * Add predictive modeling for tumor severity

### Credits
This project was inspired by a YouTube tutorial and used for learning and understanding Power BI concepts, including data transformation, DAX measures, and dashboard design.
