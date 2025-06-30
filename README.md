# Tata-GenAI-Powered-Data-Analytics-Job-Simulation

## Project Briefing 

**_Geldium_** - a financial services provider specializing in digital lending and consumer credit. The company has observed an increase in credit card delinquency rates, with more customers missing payments beyond the 30-day late payment threshold. To improve risk management and customer engagement, they have engaged Tata iQ to develop an AI-powered predictive solution that helps identify at-risk customers and recommend appropriate interventions.

The head of Geldium’s Collections team wants to improve how they assess repayment risk and prioritize outreach efforts. Currently, their approach relies on historical trends and manual case handling, which limits efficiency. They are looking for a solution that can:

- **Use AI-driven insights** to help predict which customers are likely to miss payments.
- **Support the Head of Collections with targeted intervention strategies** to reduce delinquency.
- **Ensure fairness and transparency in AI-driven risk assessments** while aligning with industry practices.
 
As an **AI transformation consultant**, your task is to:

- **Review available customer data** to identify patterns and risk factors.
- **Develop a predictive model logic using GenAI** to forecast delinquency likelihood.
- **Provide structured recommendations** on intervention strategies.
- **Prepare a PowerPoint presentation** outlining how Geldium can implement an AI-powered collections system, including ethical guardrails and expected business impact.

---

### ✅ Task 1: Exploratory Data Analysis (EDA)

Conducted an in-depth EDA on a 500-record financial dataset covering:

**Features analyzed:** Credit score, income, loan balance, credit utilization, payment history, employment status, credit card type, location.

**Missing Data:** Income (7.8%), Loan Balance (5.8%), Credit Score (0.4%)
 
Used MICE imputation for complex numerical gaps to preserve inter-variable relationships.

**Key Risk Indicators Identified:**
  
*	Business credit card holders – 21.29% delinquency rate
  
*	Unemployed individuals – 19.35%
  
*	Los Angeles residents – 19.62%

*	Customers with >4 missed payments + >50% credit utilization had 20.63% delinquency rate.

*	Insightful anomaly: Income and missed payments showed unexpected weak correlations with delinquency, hinting at non-linear or hidden interactions.

[Full EDA Report](https://github.com/ron0496/Tata-GenAI-Powered-Data-Analytics-Job-Simulation/blob/main/Task%201-%20EDA%20Summary%20Report.pdf)

---

### ✅ Task 2: Predictive Model Framework

Developed a no-code predictive model plan to identify high-risk customers using tabular data:

Chosen Algorithm: 

Gradient Boosting (XGBoost)

*	Outperforms logistic regression and decision trees on non-linear, high-variance datasets.

* Handles missing values, outliers, and imbalanced classes effectively.

*	Offers feature importance metrics for interpretability.

🛠 Model Pipeline:

* Preprocessing: Missing value handling, outlier treatment, categorical encoding

* Feature Engineering: Payment pattern aggregation, age/score binning, interaction terms

*	Bias mitigation: SMOTE, fairness-constrained training, adversarial debiasing

📊 Evaluation Metrics:

*	F1-score, ROC AUC, precision-recall trade-offs

*	Fairness Metrics: Demographic Parity, Equal Opportunity, Disparate Impact Rule (80%)

[Model Plan](https://github.com/ron0496/Tata-GenAI-Powered-Data-Analytics-Job-Simulation/blob/main/Task%202-%20Model%20Plan.pdf) 

---

### ✅ Task 3: Business Recommendations & Responsible AI

Designed a SMART business strategy based on model insights:

Insight:

Customers with high credit utilization (>50%) and missed payments (>2) are at elevated risk.

🎯 SMART Recommendation:
	
*	Specific: Launch proactive outreach (SMS/email) for high-risk users.
	
 *	Measurable: Target 10% delinquency reduction in this segment in 6 months.
	
 *	Achievable: Leverage Geldium’s existing CRM and monitoring infrastructure.

 *	Relevant: Addresses top predictors of delinquency.

 *	Time-bound: Campaign rollout within 2 weeks, monthly monitoring.

💡 Ethical Considerations:

 *	Bias Risk: Avoid over-penalizing customers by location or employment status.
	
 *	Explainability: Use SHAP values to visualize how customer features drive risk scoring.
	
 *	Responsible AI: Human-in-the-loop governance for sensitive decisions (e.g., loan restructuring).
   
[Business Summary Report](https://github.com/ron0496/Tata-GenAI-Powered-Data-Analytics-Job-Simulation/blob/main/Task%203-%20Updated%20Business%20Summary.pdf)

---

### ✅ Task 4: AI Collections System Design & Business Impact

Built a responsible, scalable AI system that automates collections while ensuring fairness and compliance.

🔁 How It Works:
*	Input: Real-time customer data (e.g., payments, credit usage, location)

*	Risk Engine: XGBoost model assigns delinquency risk scores

*	Autonomous Actions:

    * Triggers reminders, offers plans, or flags for support
      
    *	Self-learns from previous outcomes to optimize strategies
   
*	Human Oversight:
  
    * Reviews edge cases and high-value accounts
      
    *	Ensures compliance with FCRA, GDPR, ECOA

📊 Business KPIs:

| KPI | Target Impact |
|-----------------------|--------------------------|
| Delinquency Rate Reduction | 10–15% in high-risk group |
| Cost Efficiency | 25% lower call center load |
| Model Accuracy | F1 ≥ 0.80 |
| Action Speed | 50% faster interventions |

🤝 Customer Impact:

*	Personalized experience with timely nudges

*	Fairness via demographic checks

*	Higher engagement & transparency

[AI Collections Strategy Presentation](https://github.com/ron0496/Tata-GenAI-Powered-Data-Analytics-Job-Simulation/blob/main/Task%204-%20Presentation.pdf)

---

💼 Key Learnings & Impact

This project was a hands-on simulation of how AI, data science, and ethical design converge in real-world financial services:

*	Bridged raw data → insights → actionable AI-driven decisions

*	Balanced predictive power with fairness, transparency, and compliance

*	Applied advanced imputation, modeling, and evaluation techniques


