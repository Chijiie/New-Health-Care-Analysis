# Health Care Performance and Patient Analytics Dashboard

## Project Overview
This project contains the Heath Care Performance and Patient Analytics Potfolio.

The goal was to transform raw datasets into an interactive Power BI dashboard that helps management understand the organizations performance and make data driven decisions.

## Business Problem

Management requires a clear and interactive way to monitor health care performance and identify areas that need attention. 

The dashboard was designed to answer questions such as:
- How the healthcare organization is performing?
- What are patients experiencing?
- Where are the major areas that require attention?
- Which age group represents the largest number of patients?
- Which diagnoses are most common?
- Which state have the highest patient volume?
- How many patients are returning?
- What are the most common patient outcomes?
- Which department receives the most patients?
- Which department has the longest waiting time?
- Which branch handles the most visits?
- Which department has the lowest satisfaction score?
- Are there operational areas management should investigate?
- Which sate generates the most revenue?
- Which department generates the most profit?
- Which services generates the most revenue?
- Are states meeting their revenue targets?
- Which areas require further financial investigation?
- Which department has the highest satisfaction?
- Which branch has the lowest satisfaction?
- What is the relationship between waiting time and satisfaction?
- Which patient outcome occurs most frequently?

## Dataset Description 

The dataset contains information about health care analysis.

Key fields include:
- Patient ID
- Age
- Gender
- Department
- State
- Branch
- Visit Date
- Diagnosis
- Insurance Type
- Payment Method
- Revenue
- Satisfaction Score
- Waiting Time Min

## Tools Used 

The following tools were used for the project:
- Power Query
- Data Cleaning
- Data Transformation
- Data Modelling
- Relationships
- Date Table
- Dax Measures
- Slicers
- Conditional Formating
- Drill-through
- Tooltips
- Page Navigation
- Interactive Visuals

## Data Cleaning Process

The data was cleaned and processed using Power Query. Process included:
- Importing the raw data
- Cleaning missing values
- Removing duplicates
- Correcting data types
- Standardizing text values
- Creating calculated values where necessary

## Data Model

The following were the models used for the project:

 - Date Table (Date, Month, Year)
 - Patient Visits (Age, Branch, Cost, Department, Diagnosis, Gender, Insurance Type, Outcome, Payment ID, Payment Method, Revenue, Satisfaction Score, Service, State, Visit Date)
 - State Target (Annual Revenue Target, State)

## Dax Measures

Key measures created include:
- Total Patients
- Total Visits
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Average Revenue Per Patient
- Average Waiting Time
- Average Satisfaction
- Previous Month Revenue
- MoM Revenue Growth %
- Previous Year Revenue
- YoY Revenue Growth %
- Revenue Target
- Revenue Variance
- Achievement %
- Top Department
- Top Department by Patient Visit
- Top Department by Profit
- Top Month by Revenue
- Top Month by Patient Visit
- Top State
- Top State by Revenue
- Top Service
- Longest Waiting Time
- Lowest Satisfaction by Branch

## Key Insights

Key Insights Include:
- Rivers State has the highest patient volume
- The adult age group has the highest number of patients
- The most common diagnosis is Malaria
- The most common outcome is recovered
- The number of returning patients are eight hundred and eighty nine (889)
- Rivers state generates the most revenue
- Pediatrics department generates the most profit
- The month of April generates the most revenue

## Recommendations
 Key Recommendations include:
 - Laboratory department requires further financial investigation as they are struggling financially
 - Investigate staffing levels in the department with longest waiting time
 - Implement appointment scheduling to reduce peak-time congestion
 - The Lekki branch should be looked into by the management as the level of satisfaction by patients is not up to standard

 ## Conclusion 

 Analysis of the patient visits data shows that Recovered is the most common patient outcome, indicating effective clinical care and discharge process. However, waiting time remains a key issue. The longest waiting time was recorded in Pediatrics department with wait times exceeding minutes, This suggests a need for improved triage, staffing, or process optimization in that unit. Overall, while clinical outcomes are positive, operational efficiency, particularly in reducing patient waiting time should be the primary focus for quality improvement.  

