# Business-Driven Snowflake ELT Practice Project

**Platform:** Snowflake  
**Target Audience:** Freshers (0–1 year experience)  
**Duration:** 5 Working Days (Monday–Friday)  
**Daily Time Commitment:** 30–60 minutes  

---

## Why Are We Building This Project?

This project was created to help you **understand data engineering from a business perspective**, not just a technical one.

Many early-career data engineers learn tools, syntax, and features but struggle to answer simple questions such as:

- Why are we building this pipeline?
- What business problem does this solve?
- Who benefits from this data?
- What happens if this data is wrong or insecure?

This project is designed to **build that understanding step by step**.

You are not expected to write perfect SQL.  
You *are* expected to think about **why you are doing what you are doing**.

---

## The Required Mindset Shift

You should move from thinking:

> “I am creating tables, warehouses, and roles.”

to thinking:

> **“I am helping a business trust, use, and safely share its data.”**

Every task in this project exists because of a **real business need**.

---

## Business Context and Scenario

You are working as a data engineering team for a **mid-sized digital commerce company**.

The company:

- Has customers across multiple regions  
- Processes online orders  
- Tracks user behavior through application events  
- Works with external partners who need analytics data  

The company wants to become **data-driven**, but is facing several challenges.

---

## Business Problems We Are Trying to Solve

### 1. Lack of Trust in Data

- Different teams report different numbers  
- Raw data is modified too early  
- No clear data ownership  

**Business impact:** Leadership does not trust reports.

---

### 2. Messy and Inconsistent Data

- Missing values  
- Duplicates  
- Invalid records  
- Inconsistent formats  

**Business impact:** Analysts spend time cleaning data instead of analyzing it.

---

### 3. Poor Governance and Security

- Too much access to sensitive data  
- No clear access boundaries  
- High compliance risk  

**Business impact:** Analytics adoption is limited due to fear of misuse.

---

### 4. No Safe Way to Share Data

- Partners ask for data extracts  
- Manual exports are risky  
- Sharing does not scale  

**Business impact:** Collaboration is slow and unsafe.

---

## What This Project Delivers

By the end of this project, you will have built:

- A **governed ELT pipeline**  
- A **trusted analytics layer**  
- A **cost-aware compute setup**  
- A **secure data share** for external consumers  

At the same time, you will understand **why each piece exists**.

---

## How This Repository Is Used

1. Clone or fork this repository  
2. Create a personal branch using:

   ```bash
   feature/<your-name>



---



# Day-by-Day Execution Plan



Each day answers four questions:



1. What business problem are we solving?  
2. What are you expected to do?  
3. What does success look like for the business?  
4. How will learning be evaluated?  



---



## Day 1 – Access, Roles, and Ownership



### Business Problem



The business does not trust the platform because **access and ownership are unclear**.



**Business question:**  
**“Who owns the data, and who is allowed to use it?”**



### What You Are Expected to Do



- Design role-based access aligned to responsibilities  
- Separate ingestion, transformation, and analytics access  
- Avoid using default admin roles  
- Assign ownership intentionally  



### Expected Outcome (Business View)



- Clear ownership of data layers  
- Minimal and intentional access  
- Reduced risk before analytics begins  



### Evaluation Focus



- Can you explain why access separation matters?  
- Do your roles reflect business responsibilities?  



### Quiz / Reflection (Mandatory)



👉 [https://forms.office.com/r/L3MJje7egr](https://forms.office.com/r/L3MJje7egr)



---



## Day 2 – Raw Data and Ingestion



### Business Problem



The business cannot trace where data came from or recover from failures.



**Business question:**  
**“Can we trust raw data and trace it back to the source?”**



### What You Are Expected to Do



- Load structured and semi-structured data as-is  
- Preserve file metadata  
- Keep raw data unchanged  
- Design for reprocessing  



### Expected Outcome (Business View)



- Raw data can be audited  
- Errors can be investigated  
- Pipelines can be re-run safely  



### Evaluation Focus



- Do you understand why raw data should remain untouched?  
- Can you explain auditability in simple terms?  



### Quiz / Reflection (Mandatory)



👉 [https://forms.office.com/r/n1XE52bC4X](https://forms.office.com/r/n1XE52bC4X)



---



## Day 3 – Transformations and Data Quality



### Business Problem



Teams calculate metrics differently and do not trust each other’s data.



**Business question:**  
**“Can we create consistent meaning from messy data?”**



### What You Are Expected to Do



- Identify data quality issues  
- Clean and standardize where required  
- Apply simple, consistent business rules  
- Decide what *not* to fix  



### Expected Outcome (Business View)



- Metrics mean the same across teams  
- Analysts spend less time cleaning data  
- Event data becomes usable  



### Evaluation Focus



- Can you justify your transformation decisions?  
- Do you understand trade-offs in data cleaning?  



### Quiz / Reflection (Mandatory)



👉 [https://forms.office.com/r/FbFmjpurgF](https://forms.office.com/r/FbFmjpurgF)



---



## Day 4 – Analytics, Performance, and Compute



### Business Problem



Insights are slow and compute costs are unclear.



**Business question:**  
**“Can leaders get answers quickly without overspending?”**



### What You Are Expected to Do



- Build analytics-ready datasets  
- Choose warehouse sizes consciously  
- Observe performance differences  
- Think about cost vs value  



### Expected Outcome (Business View)



- Faster insights  
- Predictable performance  
- Controlled compute usage  



### Evaluation Focus



- Do you understand why warehouse size matters?  
- Can you explain compute decisions in business terms?  



### Quiz / Reflection (Mandatory)



👉 [https://forms.office.com/r/ZpJVcKDPuq](https://forms.office.com/r/ZpJVcKDPuq)
👉 [https://forms.office.com/r/sHzHJTmUr0](https://forms.office.com/r/sHzHJTmUr0)



---



## Day 5 – Data Sharing, Governance, and Delivery



### Business Problem



The business needs to share analytics data with partners safely and at scale.



**Business question:**  
**“Can we share trusted data without copying or manual work?”**



### What You Are Expected to Do



- Create a secure data share  
- Share only analytics-ready data  
- Configure future grants  
- Prevent exposure of raw or sensitive data  



### Expected Outcome (Business View)



- Partners access trusted data directly  
- New analytics tables are shared automatically  
- Governance scales with growth  



### Evaluation Focus



- Do you understand why data sharing is better than exports?  
- Can you explain future grants clearly?  



### Quiz / Reflection (Mandatory)



👉 [https://forms.office.com/r/Bya7XWubPL](https://forms.office.com/r/Bya7XWubPL)



---



# Final Project Evaluation



You will be evaluated on:



| Area | Focus |
|-----|------|
| Business understanding | Why decisions were made |
| Fundamentals | Raw → Transform → Analytics |
| Governance awareness | Access, security, sharing |
| Clarity of explanation | Simple, clear reasoning |



This is **not an exam**.  
There are **no right or wrong answers**.



A Reflection for yourself.
👉 [https://forms.office.com/r/gYYx2N3sSh](https://forms.office.com/r/gYYx2N3sShL)



---



## Final Note



This project is designed to help you understand:



- Why data engineering exists  
- How technical decisions affect businesses  
- Why governance and sharing matter  
- How to explain your work confidently  



If you can clearly explain **what you built and why**,  
you are building the right foundation for your career.



---
 
