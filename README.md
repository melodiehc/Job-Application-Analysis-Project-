# Job-Application-Analysis-Project-

#  Job Application Tracking & Analysis Project

##  Project Overview
This project is a data analytics portfolio project designed to track, analyze, and visualize my job application activity using **Excel, SQL (MySQL), and Tableau**. The goal is to simulate real-world analyst workflows while gaining insights into application funnels, interview conversion rates, and platform effectiveness during my current job search.

This project demonstrates skills in:
- Data cleaning & structuring
- SQL querying & analysis
- Funnel and conversion analysis
- Dashboard-ready data modeling


---

## Tools & Technologies
- **Excel** – Data entry, cleaning, and initial organization  
- **MySQL** – Database creation, querying, aggregation, and analysis  
- **Tableau** – Data visualization and dashboard creation  

---

## Dataset
The dataset currently includes **30 real job applications** (subset of 100+ applied roles) with the following fields:

| Column Name | Description |
|------------|-------------|
| ID_Number | Unique application identifier |
| Company_Name | Company applied to |
| Job_Title | Position title |
| Location | Job location |
| Application_Date | Date applied |
| Application_Status | Applied / Rejected / Viewed |
| Outcome | Applied, Rejected, Interviewed, Offer|

---

## 🧱 Database Schema (MySQL)
```sql
CREATE TABLE job_applications (
    ID_Number INT,
    Company_Name VARCHAR(100),
    Job_Title VARCHAR(100),
    Location VARCHAR(30),
    Application_Date DATE,
    Application_Status VARCHAR(30),
    platform VARCHAR(50),
    interview_stage VARCHAR(50),
    outcome VARCHAR(30)
);
