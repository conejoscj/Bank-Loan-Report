# Project Background & Overview
Lending is the core revenue driver for banks, but it is also the primary source of risk. This project analyzes a comprehensive loan dataset to monitor the health of the lending portfolio. By evaluating loan applications, funded amounts, and repayment patterns, the bank can identify "Good" vs. "Bad" loans, track seasonal trends, and adjust lending policies to ensure long-term profitability.

**Key Business Questions:**
* Which department and education field are experiencing the highest number of employees leaving?
* Is attrition higher among a specific age group or gender?
* Does a low job satisfaction rating in specific roles (like Sales or Lab Techs) directly lead to higher turnover?

# Data Structure Overview
The data tracks individual employee profiles and their current status within the company.

* **Source:** Kaggle Public Dataset
* **Employee Profile:** Age, Gender, Education Field, and Education Level.
* **Employment Details:** Job Role, Department, and Active/Inactive status.
* **Sentiment Data** Job Satisfaction Ratings (Scale of 1–4).

**Entity Relationship Diagram (ERD):**

![Data Model](images/hr.datamodel.png)

# Executive Summary
The organization currently has **1,470** employees with an overall **Attrition Rate of 16.12%** (237 people have left). The **R&D department** accounts for over half of all attrition (**56.12%**). Most employees who leave are in the **25–34** age bracket, and a significant number come from a **Life Sciences** education background. While the average age is **37**, the "Under 25" and "25–34" groups show the highest vulnerability to leaving.

**High-Level Metrics**
* **Overall Employees**: 1,470
* **Attrition**: 237
* **Attrition Rate**: 16.12%
* **Active Employees**: 1,233
* **Average Age**: 37

![Dashboard Overview](images/hr.dashboard2.png)

# Insights Deep Dive
### Department Analysis: R&D as the Primary Attrition Driver
* The R&D department has the highest attrition with **133** employees leaving, followed by Sales (**92**).
* R&D represents more than half of the total company turnover. HR needs to investigate if this is due to high-pressure environments or uncompetitive pay in technical roles.

![Dashboard Overview](images/hr.department2.png)

### Age Group Analysis: High Turnover in Young Professionals
  * The **25–34** age group has the highest number of departures (**112 employees**).
  * This group makes up nearly **47%** of total attrition. Younger employees are likely leaving for better career growth opportunities elsewhere.
![Dashboard Overview](images/hr.agegroup2.png)

### Education Analysis: Life Sciences and Medical Fields
* Employees with Life Sciences (**89**) and Medical (**63**) backgrounds are the most likely to leave.
* There is a high demand for these skills in the market. The company may be losing specialized talent to competitors.
  
![Dashboard Overview](images/hr.education2.png)

### Role & Satisfaction: Low Ratings in Laboratory and Sales
* Laboratory Technicians and Sales Executives have some of the highest counts of "Level 1" (lowest) satisfaction scores.
* These roles are high-stress. The data shows **56** Lab Techs gave the lowest satisfaction rating, which correlates with high attrition in the R&D department.

![Dashboard Overview](images/hr.satisfactionanalysis.png)

# Recommendations
* **R&D Retention Program**: Conduct "Stay Interviews" in the R&D department to understand why 56% of departures are happening there.
* **Career Pathing for 25–34 Year Olds**: Since this group leaves the most, implement a clear 2-year promotion track to keep them engaged.
* **Role-Specific Support**: Improve the working conditions for Laboratory Technicians and Sales Executives to raise their job satisfaction scores from Level 1 to Level 3.
