# 📊 HR Workforce & Attrition Analytics Dashboard

## 🎯 Overview

The HR Workforce & Attrition Analytics Dashboard is an interactive Power BI solution designed to help HR leaders and business stakeholders to understand workforce composition, employee attrition, retention challenges, and training effectiveness.

The dashboard transforms raw HR data into actionable insights, enabling data-driven decisions related to employee retention, workforce planning, diversity, and learning & development.

---

# 🛠️ Technologies Used

* 📊 Microsoft Excel – Data cleaning and initial exploration
* 📈 Power BI – Dashboard development and visualization
* 🔄 Power Query – Data transformation and preparation
* 🧮 DAX (Data Analysis Expressions) – KPI calculations and business metrics
* 📁 PBIX File Format – Power BI project file

---

# 🚨 Business Problem

Organizations often struggle to understand what causes employee attrition, declining engagement, ineffective training investments, and future workforce risks.

This company faces challenges related to an aging workforce, concentration of employees in a single geographic region, high attrition within critical departments, and training programs that are delivering inconsistent outcomes.

Without data-driven intervention, these issues can lead to talent shortages, loss of institutional knowledge, and reduced organizational performance.

---

# 📂 Data Source

**Source:** Kaggle HR Analytics Dataset

The dataset contains employee-level information covering:

* Employee demographics (Gender, Age, Ethnicity, Marital Status)
* Employment details (Department, Business Unit, Division, Job Title)
* Attrition status
* Employee ratings and engagement scores
* Satisfaction and work-life balance scores
* Training participation and outcomes
* Training costs and pass rates
* Geographic employee distribution
* Retention and workforce metrics

The dataset enables analysis of workforce composition, employee behavior, training effectiveness, and organizational retention challenges.

---

# ❓ Key Business Questions Answered

## 👥 Workforce Demographics & Diversity

* What does the workforce look like across gender, age groups, and ethnicity?
* Are certain demographic groups experiencing higher attrition?
* Which employee segments require immediate retention focus?

## 📉 Attrition Analysis

* Which departments and business units have the highest attrition risk?
* Does work-life balance improve employee retention?
* How does attrition vary across age groups, race, engagement levels, and performance ratings?
* Which employee groups are most disengaged?

## 🎓 Training Program Effectiveness

* Which training programs provide the highest return on investment?
* Which programs have the lowest completion and pass rates?
* Are training investments translating into better employee performance and retention?

## 🏢 Workforce Planning

* Is the company prepared for future workforce transitions?
* Are succession planning and leadership development programs effective enough to support future growth?

---

# 🖥️ Dashboard Walkthrough

# 📄 Page 1: Workforce Overview

## 1️⃣ Workforce Metrics by Gender

**Visual Used:** KPI Cards + Stacked Percentage Bar

### Purpose:

Provides a quick comparison of workforce composition between male and female employees.

### Insights Delivered:

* Employee distribution by gender
* Active employee count
* Employees who left
* Average age
* Average engagement score

### Why This Visual?

KPIs enable instant comparison between demographic groups and highlight workforce imbalances.

---

## 2️⃣ Employee Demographics

### Ethnicity Distribution

**Visual Used:** Donut Chart

### Purpose:

Shows diversity distribution across different ethnic groups, highlights workforce age composition, displays concentration of employees by state.

### Why This Visual?

Donut charts effectively display proportional composition of a population.

---

## 3️⃣ Training Program Effectiveness

### Training Outcomes

**Visual Used:** Horizontal Bar Chart

### Purpose:

Compares completion, pass, fail, and incomplete training outcomes.

### Why This Visual?

Bar charts allow easy comparison of outcome categories and reveal hidden inefficiencies.

### Training Program Performance Table

**Visual Used:** Matrix/Table

### Purpose:

Evaluates each training program using:

* Enrollment
* Pass Rate
* Training Cost
* Average Performance Score

### Why This Visual?

Provides detailed program-level evaluation and supports ROI assessment.

---

# 📄 Page 2: Attrition Analysis

## 1️⃣ Executive KPIs

**Visual Used:** KPI Cards

### Metrics Included:

* Retention Rate
* Attrition Rate
* Employee Count
* Average Employee Rating

### Purpose:

Provides a high-level snapshot of organizational workforce health.

---

## 2️⃣ Attrition by Department / Business Unit

**Visual Used:** Column Chart

### Purpose:

Identifies organizational areas experiencing the highest employee turnover.

### Why This Visual?

Makes ranking and comparison across departments straight forward.

---

## 3️⃣ Attrition by Race

**Visual Used:** Donut Chart

### Purpose:

Compares attrition distribution across ethnic groups, identifies age segments most vulnerable, examines whether training characteristics influence employee exits.

---

## 4️⃣ Attrition Trend Over Time

**Visual Used:** Line Chart

### Purpose:

Tracks changes in employee attrition over multiple Years, Quarters and Months.

### Why This Visual?

Line charts are ideal for identifying trends and long-term movement.

---

## 5️⃣ Employee Scores Vs Attrition

**Visual Used:** Horizontal Bar Chart

### Purpose:

Evaluates whether lower employee scores are associated with higher attrition.

### Metrics Included:

* Engagement Score
* Satisfaction Score
* Performance Score

### Why This Visual?

Allows quick identification of employee experience factors influencing attrition.

---

# 🔍 Key Insights & Findings

## Workforce Insights

### Gender Composition

* Females represent 55.8% of the workforce while males account for 44.2%.
* Female employee exits are substantially higher than male exits (significant loss).
* Female engagement scores are slightly lower, but not enough to fully explain the higher attrition.
* A targeted stay interview program for female employees is recommended to uncover underlying retention challenges.

---

### Employee Engagement

* Average engagement scores remain around 2.95 / 5 for both genders. This indicates a company-wide engagement concern.
* Low engagement is often associated with increased turnover risk and reduced productivity.

---

### Retention & Attrition

* Software Engineering and Production departments experience the highest attrition levels.
* Attrition is concentrated within technical and operational functions.
* BPC, NEL, and MSC business units represent the highest organizational risk.

---

### Aging Workforce Risk

* Nearly 47% of employees are aged 50 and above.
* Only 18.8% of employees are under 30.
* The organization faces risks including:

  * Knowledge loss through retirement
  * Succession planning challenges
  * Future talent shortages
  * Reduced workforce renewal

#### Recommended Actions:

* Launch knowledge transfer programs.
* Increase graduate and junior hiring.
* Strengthen succession planning initiatives.

---

### Diversity & Inclusion

* Ethnicity distribution is remarkably balanced across all five groups. However, demographic balance alone cannot determine whether pay equity or promotion equity exists.
* Additional compensation and promotion data would be required for deeper analysis.

---

### Geographic Concentration Risk

* 88.7% of employees are located in Massachusetts.
* Heavy concentration within a single state creates operational risk.

#### Potential risks include:

* Local labor shortages
* Economic downturns
* Regulatory changes
* Regional talent competition

#### Recommended Action:

* Diversify hiring across additional geographic regions.

---

### Training Completion Challenge

* Nearly 50% of training participants either fail or leave training incomplete.
* This represents a substantial hidden cost in training investment.

---

## 🏆 Best Performing Program

### Customer Service Training

* Highest average performance score (3.04)
* Third-lowest cost ($307.7K)
* Strong pass rate (53.5%)

This program delivers the strongest overall return on investment.

---

## ⚠️ Program Requiring Immediate Review

### Technical Skills Training

* Lowest pass rate (45.1%)
* Average performance gains remain limited.

This suggests potential issues with:

* Curriculum quality
* Training delivery
* Content relevance

---

## 💸 Potential Overspending Risk

### Communication Skills Program

* Highest training cost ($344.5K)
* Performance score lower than Customer Service Training

This indicates that spending may not be translating proportionally into employee outcomes.

---

## Age-Based Attrition

* Employees aged 31–40 show the highest attrition levels.
* This age segment typically represents experienced mid-career talent.
* Losing employees from this group may create leadership pipeline challenges.

---

## Work-Life Balance Impact

* Departments with stronger work-life balance generally demonstrate better retention outcomes.
* Employee experience initiatives may therefore play a meaningful role in reducing attrition.

---

## Employee Scores & Attrition

* Lower engagement, satisfaction, and performance scores are consistently associated with higher attrition.

---

# 💼 Business Impact

This dashboard enables HR leaders and business stakeholders to make evidence-based workforce decisions by identifying retention risks, workforce planning gaps, and ineffective training investments.

The analysis highlights three critical organizational concerns:

1. An aging workforce without a sufficient succession strategy
2. High attrition within key technical and operational departments
3. Training programs that consume substantial resources while failing nearly half of participants.

By addressing these challenges through targeted retention initiatives, improved employee engagement programs, succession planning, and optimization of training investments, the organization can reduce turnover costs, strengthen workforce stability, and improve long-term business performance.


