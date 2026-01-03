# Hospital Emergency Room Power BI Dashboard

## Project Overview

This project presents a Power BI dashboard designed to analyze and monitor **Emergency Room (ER) operations** in a hospital setting.  
The dashboard provides insights into patient volume, wait times, admissions, referrals, demographics, and satisfaction levels to support data-driven decision-making for healthcare administrators and operational teams.

The project demonstrates an end-to-end business intelligence workflow, from data preparation and modeling to visualization and insight generation.

---

## Business Objective

Emergency departments operate under high pressure and require continuous monitoring to ensure efficiency and patient satisfaction.  
The objective of this project is to address key operational and analytical challenges such as:

- Monitoring patient inflow and peak hours
- Reducing average patient wait time
- Understanding admission and referral patterns
- Analyzing patient demographics
- Measuring patient satisfaction levels

---

## Monthly View Dashboard

![Monthly View Dashboard](https://github.com/sagar201993/Hospital_Emergency_Room_Dashboard_PowerBI/blob/main/dash1.png)

### Business Questions Answered
- How many patients visited the ER in a specific month?
- What is the average wait time?
- How many patients were admitted or referred?

### Insights Delivered
- Total patients for the selected month
- Average wait time in minutes
- Patient satisfaction score
- Admission and referral counts
- Patient distribution by age group, gender, race, and department referral

### Business Value
Helps hospital staff monitor monthly ER performance and quickly identify operational bottlenecks.

---

## Consolidated View Dashboard

![Consolidated View Dashboard](https://raw.githubusercontent.com/sagar201993/Hospital-ER-PowerBI-Dashboard/main/assets/consolidated_view.png)

### Business Questions Answered
- What are the long-term trends in ER performance?
- How consistent are wait times and satisfaction levels?
- Which days and hours are busiest?

### Insights Delivered
- Total patient volume across the full date range
- Average wait time and satisfaction trends
- Admission status breakdown
- Peak days and hourly patient load

### Business Value
Supports long-term planning, staffing optimization, and performance benchmarking.

---

## Patient Details Dashboard

![Patient Details Dashboard](https://raw.githubusercontent.com/sagar201993/Hospital-ER-PowerBI-Dashboard/main/assets/patient_details.png)

### Business Questions Answered
- What are the details of individual patient visits?
- How do wait times vary across patients?
- Which departments receive the most referrals?

### Insights Delivered
- Patient-level details including age, gender, race
- Admission date and status
- Department referrals and wait times

### Business Value
Allows operational teams to drill down into individual records for detailed analysis and auditing.

---

## Key Takeaways Dashboard

![Key Takeaways Dashboard](https://raw.githubusercontent.com/sagar201993/Hospital-ER-PowerBI-Dashboard/main/assets/key_takeaways.png)

### Business Questions Answered
- What are the most important insights from the dataset?
- Where are the major operational challenges?

### Insights Delivered
- Summary of patient volume and demographics
- Identification of peak days and hours
- Admission and referral patterns
- Overall ER performance highlights

### Business Value
Provides decision-makers with a concise summary of findings to guide strategic improvements.

---

## Data Model Overview

![Data Model](https://raw.githubusercontent.com/sagar201993/Hospital-ER-PowerBI-Dashboard/main/assets/model.png)

### Tables Used
- Hospital_ER: Patient visits, admissions, referrals, wait times
- Calendar Table: Date, month, year, and time intelligence

### Modeling Approach
- Star schema design
- Dedicated calendar table for time-based analysis
- Optimized relationships for accurate filtering and performance

---

## Data Source and Assumptions

The dataset used in this project represents simulated hospital emergency room visit data.

Key assumptions:
- Each record represents a single ER visit
- Wait times are recorded in minutes
- Patient satisfaction scores are collected per visit
- All demographic attributes are self-reported or recorded at admission

These assumptions ensure analytical consistency while reflecting real-world ER operations.

---

## Key KPIs and Metrics

The dashboard tracks the following key performance indicators:

- Total Number of Patients
- Average Wait Time (minutes)
- Patient Satisfaction Score
- Number of Patients Admitted
- Number of Patients Referred
- Percentage of Patients Seen Within Target Time
- Patient Distribution by Age Group, Gender, and Race

Each KPI is aligned with operational efficiency and patient experience objectives.

---

## Technical Highlights

- Time intelligence using a dedicated calendar table
- Monthly and consolidated performance analysis
- KPI cards and trend analysis
- Structured Power Query transformations for data cleaning
- Optimized DAX measures for calculations and comparisons

---

## Performance and Best Practices

To ensure performance and maintainability:
- Star schema modeling was applied
- Unnecessary columns were removed during data preparation
- Measures were preferred over calculated columns
- Consistent naming conventions were used
- Relationships were optimized for clarity and efficiency

---

## Limitations and Future Improvements

Current limitations:
- Dataset represents a simulated hospital environment
- Real-time ER data integration is not implemented

Potential future enhancements:
- Real-time data ingestion from hospital systems
- Predictive modeling for patient inflow forecasting
- Advanced wait time optimization analysis
- Automated alerts for peak-hour congestion

---

## How to Use the Dashboard

1. Open the `.pbix` file in Power BI Desktop
2. Use slicers to filter by month, year, or date range
3. Navigate between dashboard pages using the menu
4. Hover over visuals for additional details
5. Drill down into patient-level data when required

---

## Tools and Technologies

- Power BI Desktop
- Power Query for data transformation
- DAX for KPI and time-based calculations
- Data modeling and relationship management

---

## Key Skills Demonstrated

- Healthcare data analytics
- Operational performance analysis
- KPI design and monitoring
- Data modeling best practices
- Dashboard storytelling and communication

---

## Repository Structure

