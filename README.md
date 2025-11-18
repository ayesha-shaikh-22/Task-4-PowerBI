**HR Attrition Dashboard – Power BI Project**

A comprehensive HR analytics dashboard built using **Power BI**, focused on understanding employee attrition patterns, identifying risk factors, and helping HR teams make data-driven decisions to reduce turnover.

---

 **Project Overview**

Employee attrition is a critical challenge for organizations. This project analyzes employee data from the **IBM HR Analytics Attrition Dataset** and provides insights through interactive dashboards.

The dashboard uncovers **why employees leave**, which groups are most at risk, and what factors significantly influence turnover.


---

### **Key Attributes Include:**

* Age
* Gender
* Education Field
* Department
* Job Role
* Monthly Income
* Years at Company
* DistanceFromHome
* Overtime
* Attrition (Yes/No)
* Job Satisfaction
* Work-Life Balance
* Marital Status

---

 **Project Objectives**

* Identify patterns behind employee attrition
* Analyze demographic factors affecting turnover
* Understand department- and job role–specific attrition
* Explore the impact of income, overtime, and tenure
* Build an interactive Power BI dashboard for HR decision-making

---

## ⭐ **Key KPIs (Displayed on Dashboard)**

* **Total Employees**
* **Total Attrition**
* **Attrition Rate (%)**
* **Average Age**
* **Average Monthly Income**
* **Average Years at Company**

---

**Dashboard Visuals**

The dashboard includes multiple charts designed for HR insights:

### **1. Attrition by Department**

Shows which departments have the highest turnover.

### **2. Attrition by Job Role**

Highlights roles with the greatest resignation rate.

### **3. Attrition by Gender (Donut Chart)**

Male vs Female attrition distribution.

### **4. Attrition by Age Group**

Reveals which age groups are most likely to leave.

### **5. Attrition by Education Field**

Shows attrition trends based on education background.

### **6. Age vs Attrition (Line Chart)**

Trendline that identifies attrition patterns across different ages.

### **7. Overtime vs Attrition**

Higher attrition among overtime workers.

### **8. Monthly Income vs Attrition **

Relationship between salary and turnover.

---

## 🏗️ **Data Preparation & Cleaning**

Done using **Power Query** in Power BI:

### ✔ Removed unnecessary columns

* EmployeeCount
* Over18
* StandardHours

### ✔ Converted incorrect data types

* Age → Whole Number
* MonthlyIncome → Whole Number
* Attrition → Text
* Overtime → Text


### ✔ Created DAX Measures

* Total Attrition
* Attrition Rate
* Average Monthly Income
* Average Tenure
* Attrition by department/role/gender

---

## 🧠 **Key Insights**

* Overtime workers are at significantly higher risk
* Lowest salaries correlate strongly with higher attrition
* Sales and Laboratory Technician job roles show higher turnover
* Employees with Life Science & Medical backgrounds show higher attrition
* Early-stage tenure (0–3 years) has the highest exit rate

---

## 💡 **Recommendations**

* Improve onboarding and engagement during early tenure
* Adjust compensation for low-income roles
* Reduce overtime dependency through resource planning
* Provide clearer career progression and skill development
* Strengthen HR policies for high-risk departments
* Invest in employee well-being programs

---

## 🛠️ **Tools & Technologies Used**

| Tool                 | Usage                             |
| -------------------- | --------------------------------- |
| **Power BI Desktop** | Data modeling, dashboard creation |
| **Power Query**      | Data cleaning & transformation    |
| **DAX**              | Calculations & measures           |
| **Excel / CSV**      | Dataset source                    |

---

## 📝 **Future Enhancements**

* Predictive model for attrition risk scoring
* Machine learning integration (Python / Power BI)
* HR insights automation through Power Automate
* Department-wise detailed dashboards
* Employee satisfaction index creation

---

## 👩‍💻 **Author**

**Ayesha Shaikh**

Feel free to reach out for collaboration or improvements!

---

