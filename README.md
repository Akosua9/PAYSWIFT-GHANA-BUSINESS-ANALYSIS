#  Pay Swift Ghana – Financial Insights Dashboard

![Dashboard Preview](![Screenshot 2025-04-16 075013](https://github.com/user-attachments/assets/ec27f447-e3fd-46ee-bbf5-81e38e927c90)


##  Overview

This Power BI dashboard presents a comprehensive view of user behavior, loan distribution, and feature utilization for **Pay Swift Ghana**, a digital financial service platform. It is designed to help stakeholders understand key financial and customer engagement metrics.

---

##  Business Challenge

1. **Low adoption rates for new features** 
2. **High loan default rates** 
3. **Customer churn** 

---

##  Key Business Questions

- **What customer behavior patterns** can be observed in feature usage, transaction frequency, and loan repayments?  
- **What trends and drivers** are associated with customer churn? Why are users leaving the platform?  
- **Which user segments** (age group, usage level, repayment history) are at higher risk of **loan defaults**?

---

##  Data Cleaning & Preparation

- Removed duplicate entries and irrelevant fields  
- Handled missing values through imputation and exclusion  
- Standardized date formats and calculated derived columns (e.g., monthly transactions per user)   
- Created new categorical fields such as age groups and churn indicators  

---

##  Tools & Techniques Used

- **Power BI** – For data modeling, dashboard design, and visualization  
- **Power Query Editor** – For data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – For custom calculations and KPIs  
- **Filters & Slicers** – For dynamic data exploration (churn, repayment status, etc.)  
- **Data Visualization Best Practices** – To ensure clarity, accessibility, and usability

---

##  Key Insights

- **Feature Engagement:** Only 3 features—**Investment Advice**, **Budgeting Tools**, and **Savings Tracker**—show high user engagement.  
- **Behavioral Correlation:** Users who borrow higher loan amounts tend to have more monthly transactions, indicating a positive link between borrowing behavior and overall financial activity.  
- **User Segment Trends:** **Mid-aged users (36–45)** account for the highest loan amounts, suggesting they are the most financially engaged segment.  
- **Churn Rate:** The churn rate stands at **34%**, meaning roughly 1 in every 3 users is leaving the platform.  
- **Default Risk:** The average **default risk score is 3.28**, which may be associated with limited financial literacy or underuse of available support features like Budgeting Tools and Investment Advice.

---

##  Dashboard Breakdown

### 1. Loan Amount by Age Group  
Displays the distribution of total loan amounts across different age categories:
- **36–45 (Mid-Age):** GHS 137K  
- **26–35 (Young Adults):** GHS 102K  
- **46–55 (Mature):** GHS 79K  
- **18–25 (Youth):** GHS 25K  

### 2. Loan vs Monthly Transactions  
A scatter plot showing the correlation between loan amounts and monthly transactions, highlighting behavioral trends.

### 3. Churn Analysis  
A donut chart illustrating that **34% of users have churned**, providing insight into customer retention.

### 4. Feature Usage by Monthly Transactions  
Bar chart of most-used features by transaction count:
- **Investment Advice:** 384  
- **Budgeting Tool:** 308  
- **Savings Tracker:** 267  
- **Mobile Payments:** 168  
- **Loan Services:** 127  

---

---

## ✅ Recommendations

1. **Promote Underused Features**  
   Launch awareness campaigns or in-app nudges to encourage the use of features like **Mobile Payments** and **Loan Services**, which currently show low adoption.

2. **Targeted Financial Education**  
   Provide personalized financial education and tooltips within the app to help users better understand budgeting, saving, and repayment strategies—especially for segments with higher default risks.

3. **Strengthen Retention Strategies**  
   Identify reasons for churn through exit surveys and usage pattern analysis. Introduce loyalty programs, referral bonuses, or re-engagement campaigns for users showing signs of inactivity.

4. **Segmented Loan Risk Models**  
   Refine credit scoring models by incorporating behavior data (e.g., feature usage, transaction frequency) to better assess and predict default risk at a granular level.

5. **Engage Mid-Aged Users as Champions**  
   Leverage the 36–45 age group, who are highly engaged borrowers, for feedback loops, beta testing new features, or word-of-mouth promotion campaigns.


---

##  Filters Included

- **Churn Status:** Show data for churned vs. active users  
- **Repayment Status:** Filter by repayment behavior  

---

## 📁 File Info

- **Data Source:** Simulated/anonymized data for demonstration  

---

## 📬 Contact

Questions or feedback? Open an issue on [Email](roseakarimanga@gmail.com) or reach out directly.  
