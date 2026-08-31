# **Human Resources & Workforce Analytics**  
### **Workforce Intelligence Dashboard (Operational BI + Leadership) | Tracking Attrition, Diversity, Pay Equity & Performance | Top Strategic Recommendations to HR Manager/Director and Chief People Officer (CPO)**

<img width="1000" height="578" alt="image" src="https://github.com/user-attachments/assets/6be1bec2-8a11-4fb4-9ed5-3e1460c993ed" />


---

# **Quick Overview**

| **Section** | **Details** |
| :--- | :--- |
| **Business Problem** | HR teams struggle with high turnover (966 terminations vs. 8,950 hires), uneven workforce distribution, and pay gaps by gender and education. They lack clear data to spot problems and plan retention strategies. |
| **Objectives** | 1. Provide clear view of hiring, terminations, and active employees<br>2. Analyze workforce demographics (gender, age, education)<br>3. Identify salary gaps and performance patterns<br>4. Support better recruitment, retention, and diversity decisions |
| **Technical Stack** | **Dashboard:** Tableau (Dark Theme, 15+ visualizations)<br>**Data Generation:** Python (Faker library)<br>**Design:** Figma (mockups), draw.io (layout) |
| **Project Features** | • 3 dashboard sections: Overview, Demographics, Income Analysis<br>• Interactive filters and drill-through capabilities<br>• 15+ visualizations in a single, modern dark theme dashboard<br>• Geographic mapping of workforce distribution<br>• Performance vs. education analysis |
| **Start-to-End Pipeline** | **Requirement Gathering** → **Data Generation (Python/Faker)** → **Data Cleaning** → **Tableau Dashboard Design** → **Mockup Planning** → **Visualization Creation** → **Dashboard Optimization** → **Insight Generation** |


---


## **The Big Picture**
This project is a professional Tableau dashboard built for HR leaders. It visualizes hiring, demographics, performance, and salary data to support data-driven decisions. The dashboard features 15+ interactive visualizations in a modern dark theme, following a complete BI workflow from requirement gathering to final deployment.

The dashboard offers a **high-level summary**,**fully interactive**, **filterable**, **professionally designed** and **detailed breakdown** through three major sections:

1. **Overview**

   * Total hires, active employees, and terminations
   * Trends in hiring and attrition over years
   * Headcount by department and branch vs HQ distribution
   * Geographic representation via interactive maps

2. **Demographics**

   * Gender distribution
   * Age group vs education correlation
   * Employee count by age and education levels
   * Performance vs education analysis

3. **Income Analysis**

   * Salary comparisons by gender and education
   * Age vs salary scatter plot by department
   * Gap analysis visualized through parabola and scatter charts


---

**Theme**: Dark Mode | Professional Layout | Realistic HR Dataset  
**Skill Areas**: Data Visualization, Dashboard Design, Data Preparation, Insight Communication


![HR_Workforce_Dashboard_Advance_Tableau](https://github.com/user-attachments/assets/12f7cbc5-60b1-49be-bc3b-0e865edadac4)

![image](https://github.com/user-attachments/assets/74501859-4530-4c23-b180-3986dbae842e)

![HR_Workforce_Dashboard_Shaik](https://github.com/user-attachments/assets/70b3dba6-6b12-4315-a773-fbc07e015ce6)



---

# Business Problem
HR teams struggle with high turnover (966 terminated vs. 8,950 hired), uneven workforce distribution across departments and locations, and salary gaps by gender/education, making it hard to retain talent and plan hiring without clear patterns.


# Objectives
Provide a clear view of employee stats—hiring, terminations, demographics, salaries, and performance—to spot trends, address imbalances, and support better recruitment, retention, and diversity efforts.


# Data Structure Overview

The dataset used was synthetically generated using Python’s Faker library to simulate realistic HR records. It consists of a **single CSV file** with fields including:

* **Employee Details**: ID, Name, Gender, Education, Department, Job Title
* **Employment History**: Hire Date, Termination Date
* **Location**: State, City (with HQ marked as New York)
* **Salary & Performance**: Monthly salary, Performance rating
* **Derived Fields**: Age, Age Groups, Location Type (HQ vs Branch), Status (Active vs Terminated)

These fields were cleaned, categorized (dimensions/measures), and formatted appropriately in Tableau to support advanced analysis.

Hover over the chart to see more information.
Click on the chart to filter the entire dashboard.
Click the switch icon on the top right corner to open the filter menu.

# Tools & Technologies

| Tool      | Purpose                                |
|-----------|----------------------------------------|
| **Tableau** | Data visualization and dashboarding    |
| **Python (Faker)** | Synthetic HR data generation         |
| **Figma**   | Dashboard layout design (mockups)     |
| **draw.io** | Container and layout planning          |



---
# Insights Deep Dive

#### This deep dive equips HR and leadership teams with actionable insights derived from real data patterns to drive strategic interventions in talent retention, pay equity, and performance alignment.

- **Overview Metrics:** Active employees (7,984), hired (8,950), terminated (966); trend line shows hiring peaks and drops.  
- **Departments Bar:** Operations tops at 2,429 active + 289 terminated; Sales next at 1,434 + 129.  
- **Gender Pie:** Males 54%, females 46%.  
- **Education & Age Bubbles:** Most employees 25-44; larger bubbles for bachelors/masters.  
- **Performance Matrix:** 50% "Good" for bachelors; PhDs excel more.  
- **Salary Bubbles by Education/Gender:** Males earn more (e.g., PhD males $93K vs. females $80K).  
- **Age & Salary Scatter:** Higher roles like Finance Manager at $120K+; clusters around 35-50 age.  
- **Location Map:** Bubbles in NY, MI, IL; bars for HQ/branch counts.  
- **Details Table:** Lists employees by ID, name, role, location, salary, status, tenure (e.g., Samuel Burgess, 7 years).

## **Department Distribution**:

  ![image](https://github.com/user-attachments/assets/a5549aad-e8e3-4d66-9b8c-209f642e182e)


  * **Operations** leads in headcount (2,429 active, 289 terminated), followed by **Sales** and **Customer Service**.
  * The departmental ranking bar chart clearly highlights team sizes and attrition side-by-side.

  ![image](https://github.com/user-attachments/assets/6f53437d-9751-431a-a984-088ec0547d2b)


## **Geographic Spread**:

  * **New York (HQ)** houses \~70% of the workforce.
  * Other branches across Michigan, Illinois, Pennsylvania, and Virginia contribute \~30%.
  * A U.S. map visually clusters staff density across states, with cities like Philadelphia and Chicago also highlighted.

  ![image](https://github.com/user-attachments/assets/9832d154-1d21-4493-a867-59801cf46b9b)


##  **Demographics Section**

* **Gender Balance**: Males represent **54%** of the workforce, females **46%**, shown via dual donut charts.
* **Education vs Age Correlation**:

  * The majority of employees fall within the **35–44 age bracket** and primarily hold **Bachelor's degrees**.
  * Age groups are evenly distributed above age 25, indicating a mature workforce.
 
  ![image](https://github.com/user-attachments/assets/76859c2b-3eaa-4766-81e6-f9dc7205e6ee)


## **Education vs Performance**:

  * **PhD holders** dominate the **'Excellent'** rating category.
  * **Bachelor’s degree** holders show the highest concentration in the **‘Good’** performance category (50%).
  * **High school graduates** are more likely to fall into **‘Needs Improvement’**—a flag for potential training needs.
    
    ![image](https://github.com/user-attachments/assets/c3a7defe-c777-4de4-aac0-516ed234d813)
    
    ![image](https://github.com/user-attachments/assets/c31f483d-cac8-43ee-a0c2-ec32c6375016)


##  **Income Analysis Section**

* **Gender Pay Gap by Education**:

  * At the **Bachelor level**, males earn **74K** while females earn **66K**, indicating a pay gap.
    <img width="674" height="312" alt="image" src="https://github.com/user-attachments/assets/98a19ce5-2424-4d88-a054-7c1889a0a654" />
    <img width="433" height="196" alt="image" src="https://github.com/user-attachments/assets/933422bd-3dc1-4bba-abf6-b846532a869a" />


  * Conversely, at the **PhD level**, females earn more (93K vs 80K), a reverse trend worth deeper exploration.
    <img width="689" height="322" alt="image" src="https://github.com/user-attachments/assets/daeebb09-efe7-4eaf-843d-96b4d13aeb4f" />
    <img width="433" height="334" alt="image" src="https://github.com/user-attachments/assets/6a66eb94-5fc7-44c4-99df-fae3722efa5c" />

  * Salary increases progressively with education level across both genders.
   
* **Age vs Salary (Scatter Plot)**:

  * **Finance Managers** and **IT Managers** earn the highest salaries and are generally older.
  * **HR Managers**, despite being younger, command relatively high salaries—an anomaly suggesting specialized skill or strategic importance.
    <img width="912" height="715" alt="image" src="https://github.com/user-attachments/assets/ffa3cd04-956d-4d9c-8a1c-087323b2a1c0" />

  * Roles like **HR Assistant** and **Sales Specialist** cluster at lower salary bands, aligned with expectations.
    
  <img width="692" height="309" alt="image" src="https://github.com/user-attachments/assets/1f84911d-58c9-4cd1-848a-ddca15cabe1e" />
  <img width="717" height="312" alt="image" src="https://github.com/user-attachments/assets/354da52b-27e3-45bf-b513-d4f6b3337631" />



---
# Top Strategic Recommendations to HR Manager/Director and Chief People Officer (CPO)


### 1. **Insight Summary: Strengthen Workforce Retention**

- **Observation**: Departments like **Operations** and **Sales** show **high attrition** relative to others, as indicated by termination volumes in the bar chart.
    -  **Implication**: Sustained attrition in these business-critical areas could impact delivery timelines, customer experience, and institutional knowledge.
      <img width="838" height="297" alt="image" src="https://github.com/user-attachments/assets/3be0dfa9-6704-4ae1-b67e-4fd16d60a60d" />


- **Suggested Actions**:
  - Conduct **regular pulse surveys** to gauge engagement and burnout risk
  - Implement **structured exit interviews** to identify root causes (e.g., lack of growth, workload imbalance, culture mismatch)
  - Re-evaluate **compensation, benefits, training, and team structures** in high-churn departments
  - Consider **mentorship programs** or **career path initiatives** to improve retention

### 2. **Improve Gender Pay Equity**

* The **Education & Gender** chart reveals a **gender-based pay gap** at the Bachelor's level (Male avg: 74K vs Female: 66K).
    - Conduct a compensation audit to address discrepancies and ensure equitable salary bands across all levels.
      <img width="1117" height="336" alt="image" src="https://github.com/user-attachments/assets/7dc3dcf8-0b0a-447d-880b-cf2a8235340b" />
      <img width="482" height="717" alt="image" src="https://github.com/user-attachments/assets/19904c4a-1d7e-4e8d-9315-ba5df2fa5d85" />



### 3. **Capitalize on HQ Talent Strength**

* With **70% of employees located at HQ (New York)**, the talent pool is centralized.
    - Consider **talent decentralization** or **hybrid staffing models** to expand reach and reduce HQ saturation risks.
      <img width="390" height="714" alt="image" src="https://github.com/user-attachments/assets/46100623-45da-4ed1-805a-9f2964adab13" />


### 4. **Targeted Upskilling Based on Performance**

* The **Education & Performance** heatmap shows employees with **lower education levels** (e.g., High School) are more likely to fall into **‘Needs Improvement’** ratings.
    - Implement **role-specific learning paths** to upskill this segment and boost overall performance.
      <img width="1111" height="731" alt="image" src="https://github.com/user-attachments/assets/b08119dc-f3df-4530-a88d-661c236d2fd7" />


### 5. **Recognize High-Performing Segments**

* **PhD holders** show high performance and draw higher salaries—particularly female employees.
    - Invest in **leadership development** for this high-performing segment to retain and promote them.
      <img width="857" height="401" alt="image" src="https://github.com/user-attachments/assets/c2c4d98a-d35f-4a8e-a7e1-8adf59f35a44" />
      <img width="861" height="347" alt="image" src="https://github.com/user-attachments/assets/ab24f15b-c51f-4179-b925-56e77ddb717d" />



### 6. **Align Compensation with Role and Age Trends**

* The **Age vs Salary** scatter plot shows some younger employees (e.g., HR Managers) drawing higher salaries.
    - Review compensation benchmarking to ensure it aligns with both **role seniority** and **market expectations**.
    <img width="580" height="345" alt="image" src="https://github.com/user-attachments/assets/aa4c5768-2241-4215-8830-98c4a9143411" />


### 7. **Departmental Capacity Planning**

* **Operations, Sales, and Customer Service** have the largest employee volumes.
    - HR should evaluate whether staffing levels match business needs and redistribute where inefficiencies are identified.
    
    <img width="391" height="212" alt="image" src="https://github.com/user-attachments/assets/4dbeb9d6-def9-438a-b2fa-f253577af535" />




---

# 👤 **Author**

### **Shaik Mayeenuddin**

#### Business Analyst | Data Analytics & AI/ML | Optimizing Processes to Drive Revenue & Retention

🔗https://www.linkedin.com/in/shaikmayeenuddin

---

This project demonstrates my complete end-to-end capability—from data ingestion and cleaning, through ETL pipelines, modeling, and dashboarding, 
to actionable business insights. I architected, modeled, validated, visualized, and strategically interpreted the data throughout.

This project is built upon the foundational work by **Baraa Khatib** 
I am grateful for the analytical tutorials


