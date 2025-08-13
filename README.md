# OVC Preventive Dashboard – Sinovuyo Positive Parenting Program

## Overview
This Shiny application presents monitoring and analysis for the **Sinovuyo Positive Parenting Program** implemented under the **USAID 4TheChild** project. 

Sinovuyo is part of the Orphans and Vulnerable Children (OVC) program and targets **youth aged 10–14 years** for a structured **14-week series of sessions**. The aim is to improve positive parenting, communication, and resilience among young adolescents and their caregivers.

The app provides a visual and interactive interface for tracking program enrolment, session completion, and data quality issues, enabling project teams to make informed decisions and take corrective actions.

---

## Data Source
The dashboard uses the **Sinovuyo Registration List**, which contains:

- **Group Information:** Group name, facilitator name, and subcounty/ward location  
- **Participant Details:** Unique record ID, teen’s demographic information (sex, age, etc.), and caregiver details  
- **Data Entry Information:** User who entered the record and date of creation/update  
- **Session Tracking:** Number of sessions completed, skipped, or planned, including dates for each session  
- **Session Status:** Whether the teen completed all 14 sessions or is still active/incomplete  

The data is extracted from the latest available Excel file matching the naming pattern `Preventive_List-DD_MM_YYYY.xlsx`.

---

## About Sinovuyo
Sinovuyo is a **positive parenting program** developed to strengthen relationships between young adolescents and their caregivers, reduce abuse, and improve emotional wellbeing.  

Key characteristics:
- **Target group:** Youth aged **10–14 years**
- **Duration:** 14 weekly sessions
- **Focus:** Parenting skills, communication, problem-solving, and reducing risky behaviors
- **Implementation:** USAID 4TheChild through Moi University College for Health Sciences (MUCHS - AMPATH)
- **Approach:** Group-based interactive sessions with role-playing, discussions, and home activities

---

## Dashboard Components

### Filters
- **Subcounty / Ward / Facilitator / Created By / Group Name** – These allow users to focus the analysis on specific geographic areas, facilitators, data entry staff, or participant groups.
  
<img width="1825" height="422" alt="Screenshot 2025-08-13 083836" src="https://github.com/user-attachments/assets/36f27d8a-90ba-4b2e-b1d1-d642d271c3f6" />


---

### Summary Value Box
- **Enrolled vs Completed**
  - **Enrolled:** Number of unique participants registered
  - **Completed:** Number who have attended all 14 sessions
  - **Completion Rate:** Percentage of enrolled participants who have completed
<img width="887" height="242" alt="Screenshot 2025-08-13 083955" src="https://github.com/user-attachments/assets/fdaacfe1-1bdd-45d3-b666-854435be4b07" />

---

### Charts

1. **Teens Enrolled by Gender (Pie)**
   - Shows gender distribution of enrolled participants
   - Helps monitor gender balance and inclusivity in outreach

2. **Sinovuyo Completed Sessions by Gender (Pie)**
   - Shows gender breakdown of participants who have completed all sessions
   - Useful for identifying gender-specific dropout trends

3. **Sinovuyo Enrolment Trend (Line)**
   - Plots enrolment by quarter
   - Helps track programme reach over time and identify peak enrolment periods

4. **Sinovuyo Sessions Completion Trend (Line)**
   - Plots completion rates by quarter
   - Tracks whether completion is improving or declining

5. **Sinovuyo Sessions Status (Column)**
   - Shows the distribution of participants by the number of sessions completed
   - Helps identify where participants drop out

6. **Skipped Sessions (Column)**
   - Number of skipped sessions per participant
   - Useful for identifying engagement issues or scheduling conflicts
     
<img width="1820" height="726" alt="Screenshot 2025-08-13 084036" src="https://github.com/user-attachments/assets/4946a08f-b5cf-4774-9666-0be284c10663" />

---

### Data Quality Tables

1. **Duplicate Records**
   - Identifies participants appearing more than once in the registration list
   - Ensures accuracy and prevents double counting

2. **Future-Dated Sinovuyo Sessions**
   - Flags any session date set in the future
   - Helps correct data entry errors before reporting

3. **Inconsistent Session Dates**
   - Identifies records where session dates are out of logical sequence
   - Ensures session chronology is correct

4. **Sessions Done on the Same Date**
   - Flags participants recorded as attending multiple different sessions on the same day
   - Highlights possible attendance tracking errors
   - 
<img width="1820" height="660" alt="Screenshot 2025-08-13 084122" src="https://github.com/user-attachments/assets/a60fb12a-0ea4-42ea-9d5b-e02c47f3291d" />

---

## How to Use the Dashboard
1. The app is updated daily. Access it here: [https://usaid4thechild.shinyapps.io/ovc_preventive/](https://usaid4thechild.shinyapps.io/ovc_preventive/)  
2. Apply filters as needed to narrow the analysis.  
3. Review summaries, charts, and tables for program performance and data issues.  
4. Use findings to guide program improvement, staff feedback, and reporting.  

---

## Notes
- A **Google Form** is available for requesting the underlying dataset. Once approved, the data will be sent to your email.  
- Dashboard link: [https://usaid4thechild.shinyapps.io/ovc_preventive/](https://usaid4thechild.shinyapps.io/ovc_preventive/)  

---

