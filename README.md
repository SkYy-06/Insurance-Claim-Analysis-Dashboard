# 🚗 Insurance Risk & Claims Analysis Dashboard

<p align="center">
  <h1 align="center">INSURANCE RISKS & CLAIMS ANALYSIS</h1>
  <p align="center">
    <b>Interactive Power BI Dashboard | Insurance Analytics | Risk & Claims Analysis</b>
  </p>
</p>

---

## 📌 Project Overview

**Insurance Risk & Claims Analysis** is an interactive **Power BI Business Intelligence project** developed to analyze insurance policies, claims, customer demographics, vehicle characteristics, household driving behavior, and coverage zones.

The objective of this project is to transform insurance policy-level data into an interactive dashboard that helps users understand:

- Overall insurance policy volume
- Total financial claim exposure
- Claim frequency
- Average claim amount
- Customer demographics
- Vehicle characteristics
- Geographic coverage
- Household driving behavior
- Education and marital-status patterns

The dashboard provides two primary analytical perspectives through a dynamic **Select Measure** option:

- **Total Claim Amount**
- **Total Policies**

This allows the same dashboard to be used for both **claim analysis** and **policy analysis**.

---

# 🎯 Business Problem

Insurance companies need to understand both their **policyholder base** and **claim patterns** in order to make data-driven decisions.

The business requirements for this project call for a centralized interactive Power BI dashboard that provides an overview of:

- Total Policies
- Total Claim Amount
- Claim Frequency
- Average Claim Amount
- Gender-wise policy distribution

The dashboard also provides deeper analysis across:

- Car Use
- Car Make
- Coverage Zone
- Age Group
- Car Year
- Kids Driving
- Education
- Education & Marital Status

The goal is to move from raw insurance data to an interactive business intelligence solution.

---

# 🏢 Insurance Domain

The dataset contains detailed information about insurance policyholders, their vehicles, demographic characteristics, household characteristics, and claim history.

The major data areas are:

```text
Insurance Policy Data
│
├── Customer / Demographics
│   ├── Birthdate
│   ├── Gender
│   ├── Education
│   ├── Marital Status
│   ├── Household Income
│   └── Parent
│
├── Vehicle
│   ├── Car Make
│   ├── Car Model
│   ├── Car Color
│   ├── Car Year
│   └── Car Use
│
├── Geography
│   └── Coverage Zone
│
├── Claims
│   ├── Claim Amount
│   └── Claim Frequency
│
└── Household
    └── Kids Driving
```

This allows the project to analyze insurance performance from multiple business perspectives.

---

# 📊 Dashboard Preview

## 🔹 Total Claim Amount View

This view focuses on the **financial impact of insurance claims**.

![Insurance Dashboard - Total Claim Amount](Dashboard/Insurance%20Analysis%20Dashboard1.png)

### What this view analyzes

- Total claim amount
- Claim amount by car use
- Claim amount by car make
- Claim amount by coverage zone
- Claim amount by age group
- Claim amount by car year
- Claim amount by kids driving
- Claim amount by education
- Claim amount by education and marital status

---

## 🔹 Total Policies View

This view focuses on the **distribution of insurance policies**.

![Insurance Dashboard - Total Policies](Dashboard/Insurance%20Analysis%20Dashboard2.png)

### What this view analyzes

- Total policy count
- Policies by car use
- Policies by car make
- Policies by coverage zone
- Policies by age group
- Policies by car year
- Policies by kids driving
- Policies by education

---

# 🎛️ Interactive Measure Selection

One of the main interactive features of the dashboard is the **Select Measure** dropdown.

Users can switch between:

```text
Total Claim Amount
```

and

```text
Total Policies
```

The selected measure dynamically changes the analytical visuals.

### When Total Claim Amount is selected

The dashboard focuses on questions such as:

- Where are claims concentrated?
- Which car makes have higher claim exposure?
- Which age groups contribute more to claim amounts?
- Which coverage zones have higher claim exposure?
- How do claims vary across education groups?

### When Total Policies is selected

The dashboard focuses on questions such as:

- Where are policies concentrated?
- Which car makes have the most policies?
- Which age groups contain the most policies?
- How are policies distributed across coverage zones?
- Which education groups have more policyholders?

---

# 🔢 Key Performance Indicators

The dashboard provides the following high-level KPIs:

| KPI | Value |
|---|---:|
| **Total Policies** | **37,542** |
| **Total Claim Amount** | **$187.8M** |
| **Average Claim Frequency** | **0.5** |
| **Average Claim Amount** | **$5.0K** |
| **Male Policies** | **18.7K** |
| **Female Policies** | **18.8K** |

These KPIs provide an executive-level summary before moving into detailed analysis.

---

# 📈 Dashboard Visualizations

## 1. 🚘 Total Claim Amount / Policies by Car Use

### Visualization

**Donut Chart**

### Dimension

**Car Use**

### Categories

- Personal
- Commercial

### Purpose

This visualization compares policy or claim distribution according to the primary use of the insured vehicle.

### Business Questions

- How are policies distributed between personal and commercial use?
- Which vehicle-use category contributes more to total claim exposure?
- Does policy distribution follow the same pattern as claim distribution?

### Business Value

Vehicle usage provides an additional dimension for understanding insurance exposure and customer segments.

---

# 2. 🚗 Total Claim Amount / Policies by Car Make

### Visualization

**Horizontal Bar Chart**

### Dimension

**Car Make**

The dashboard displays major manufacturers including:

- Ford
- Chevrolet
- Dodge
- Toyota
- GMC
- Mitsubishi
- Mazda
- Pontiac
- Mercedes-Benz
- Volkswagen

### Purpose

The chart ranks vehicle manufacturers based on the selected measure.

When **Total Claim Amount** is selected, it shows manufacturers with higher aggregate claim values.

When **Total Policies** is selected, it shows manufacturers with higher policy counts.

### Business Questions

- Which manufacturers have the highest policy volume?
- Which manufacturers have the highest total claim amount?
- Are manufacturers with high policy volume also associated with high claim exposure?

### Important Analytical Consideration

A high total claim amount does not automatically mean that a particular car make is riskier.

A manufacturer with more policies can naturally have a larger total claim amount.

For a more advanced comparison, metrics such as:

```text
Claim Amount per Policy
Claim Frequency per Policy
Average Claim Amount
```

would provide additional context.

---

# 3. 🌎 Total Claim Amount / Policies by Coverage Zone

### Visualization

**Donut Chart**

### Dimension

**Coverage Zone**

### Purpose

This visual compares policy or claim concentration across different coverage zones.

### Business Questions

- Which coverage zones have the highest policy counts?
- Which zones have the highest claim exposure?
- Are policy concentration and claim concentration similar?

### Business Value

Coverage zones provide a geographic perspective for insurance analysis.

They can be useful when investigating differences in accident exposure, theft risk, traffic conditions, and repair costs.

---

# 4. 👥 Total Claim Amount / Policies by Age Group

### Visualization

**Column Chart**

### Age Groups

```text
15–25
26–35
36–45
46–55
56–65
66–75
```

### Purpose

The chart compares insurance policies or total claim amounts across customer age groups.

### Business Questions

- Which age group has the largest policy population?
- Which age groups have higher claim exposure?
- Does policy distribution follow the same pattern as claim distribution?

### Business Value

Age-based segmentation can support:

- Customer profiling
- Risk analysis
- Insurance segmentation
- Pricing analysis

---

# 5. 🚘 Total Claim Amount / Policies by Car Year

### Visualization

**Area Chart**

### Dimension

**Car Year**

### Purpose

This visualization analyzes policy and claim trends across vehicle manufacturing years.

### Business Questions

- How does policy volume vary across vehicle years?
- How does claim amount vary across vehicle years?
- Are certain vehicle years associated with higher claim exposure?

### Business Value

Vehicle manufacturing year provides a way to analyze vehicle age and its relationship with policy and claim patterns.

---

# 6. 👨‍👩‍👧 Total Claim Amount / Policies by Kids Driving

### Visualization

**Ribbon / Area-style Chart**

### Dimension

**Kids Driving**

### Categories

```text
0
1
2
3
```

### Purpose

This visualization compares policy or claim values according to the number of licensed children driving in the household.

### Business Questions

- How are policies distributed across households with different numbers of young drivers?
- Does claim exposure change as the number of kids driving increases?
- Which household group represents the largest exposure?

### Business Value

Kids Driving provides another household-level dimension for analyzing insurance exposure.

---

# 7. 🎓 Total Claim Amount / Policies by Education

### Visualization

**Pie Chart**

### Education Groups

- Bachelors
- High School
- Masters
- PhD

### Purpose

The chart compares policy or claim distribution across education groups.

### Business Questions

- Which education group has the highest policy count?
- Which education group contributes the highest claim amount?
- Does policy distribution follow the same pattern as claim distribution?

### Business Value

Education can be used as a demographic segmentation variable when analyzing customer profiles.

---

# 8. 🎓💍 Claim Amount by Education & Marital Status

### Visualization

**Matrix / Heat Grid**

This visual combines:

### Education

- Bachelors
- High School
- Masters
- PhD

### Marital Status

- Divorced
- Married
- Separated
- Single

### Measure

**Claim Amount**

### Purpose

Instead of analyzing education and marital status separately, this matrix allows their combined relationship with claim amount to be explored.

For example:

```text
Education = Bachelors
Marital Status = Married
```

can be compared against:

```text
Education = Masters
Marital Status = Single
```

### Business Value

This creates more detailed customer segments and helps identify demographic combinations with different claim amounts.

---

# 📌 Dashboard Layout

The dashboard follows a structured analytical layout:

```text
┌─────────────────────────────────────────────────────────────┐
│                 INSURANCE RISKS & CLAIMS                    │
│                    SELECT MEASURE                           │
├──────────────┬─────────────────────────────┬───────────────┤
│              │ Car Use + Car Make           │ Coverage Zone │
│     KPI      │                             │               │
│   SUMMARY    ├─────────────────────────────┴───────────────┤
│              │ Age Group            │ Car Year             │
│              │                     │                       │
│              │ Kids Driving        │                       │
│              ├─────────────────────┼───────────────────────┤
│              │ Education           │ Education +           │
│              │                     │ Marital Status        │
└──────────────┴─────────────────────┴───────────────────────┘
```

The layout creates a flow from:

**Executive Summary → Category Analysis → Trend Analysis → Customer Segmentation**

---

# 🧩 Dataset Overview

The dataset contains information across several categories.

## 👤 Customer / Demographic Fields

| Field | Purpose |
|---|---|
| ID | Unique record identifier |
| Birthdate | Used for age analysis |
| Gender | Gender-based segmentation |
| Education | Education-based segmentation |
| Marital Status | Customer segmentation |
| Household Income | Income analysis |
| Parent | Household segmentation |

---

## 🚘 Vehicle Fields

| Field | Purpose |
|---|---|
| Car Make | Manufacturer-level analysis |
| Car Model | Model-level analysis |
| Car Color | Vehicle attribute |
| Car Year | Vehicle year analysis |
| Car Use | Usage-based analysis |

---

## 🌎 Geographic Field

| Field | Purpose |
|---|---|
| Coverage Zone | Geographic policy and claim analysis |

---

## 💰 Claims Fields

| Field | Purpose |
|---|---|
| Claim Amount | Financial claim exposure |
| Claim Frequency | Claim occurrence frequency |

---

## 👨‍👩‍👧 Household Field

| Field | Purpose |
|---|---|
| Kids Driving | Number of licensed young drivers |

---

# 📊 Data Profile

The dashboard represents:

### Total Policies

**37,542**

### Total Claim Amount

**$187.8M**

### Average Claim Frequency

**0.5**

### Average Claim Amount

**$5.0K**

### Gender Distribution

```text
Male       18.7K
Female     18.8K
```

---

# 🔍 Analytical Dimensions

The dashboard analyzes the insurance dataset from five major perspectives.

## 1. Customer

```text
Age
Gender
Education
Marital Status
```

## 2. Vehicle

```text
Car Make
Car Model
Car Year
Car Use
```

## 3. Geographic

```text
Coverage Zone
```

## 4. Household

```text
Parent
Kids Driving
```

## 5. Claims

```text
Claim Amount
Claim Frequency
```

---

# 🧠 Analytical Approach

The project follows a structured data analytics workflow:

```text
Business Requirement
        ↓
Domain Understanding
        ↓
Dataset Understanding
        ↓
Identify KPIs
        ↓
Identify Dimensions
        ↓
Create Measures
        ↓
Select Visualizations
        ↓
Build Power BI Dashboard
        ↓
Add Interactivity
        ↓
Analyze Results
        ↓
Communicate Findings
```

---

# 💡 Important Analytical Concepts

## Claim Frequency

Claim frequency represents how often claims occur.

It provides a view of the occurrence of claims within the analyzed population.

---

## Claim Severity

Claim severity refers to the financial size of claims.

The **Average Claim Amount** provides a high-level indication of claim severity.

---

## Total Claim Amount

Total Claim Amount represents the aggregate financial exposure from claims.

However, it should be interpreted alongside policy volume.

---

# ⚠️ Important Analytical Consideration

One important lesson from this project is:

> **High total claims do not necessarily mean high risk.**

For example:

```text
Manufacturer A
10,000 policies
$20M total claims
```

versus:

```text
Manufacturer B
1,000 policies
$5M total claims
```

Manufacturer A has the higher total claim amount.

But:

```text
Manufacturer A

$20M / 10,000
= $2,000 per policy
```

while:

```text
Manufacturer B

$5M / 1,000
= $5,000 per policy
```

Therefore, Manufacturer B has a higher claim amount per policy despite having a lower total claim amount.

### Key Lesson

> Aggregate values should be interpreted together with the population size.

This is an important consideration when comparing insurance segments.

---

# 🧠 Frequency vs Severity

Insurance risk can be better understood by looking at both:

### Claim Frequency

How often claims occur.

### Claim Severity

How expensive those claims are.

These dimensions can produce different risk profiles:

```text
                    CLAIM SEVERITY
                   Low          High
                ┌──────────┬──────────┐
             Low│ Low       │ High     │
                │ Frequency │ Severity │
                ├──────────┼──────────┤
             High│ Frequent  │ High     │
                │ Claims    │ Risk     │
                └──────────┴──────────┘
                 CLAIM FREQUENCY
```

A future version of the dashboard could visualize this relationship directly.

---

# 📚 What I Learned

This project helped me develop practical skills across the complete data analytics workflow.

## 1. Business Requirement Analysis

I learned how to translate business requirements into:

- KPIs
- Dimensions
- Measures
- Visualizations
- Interactive dashboard components

---

## 2. Insurance Domain Understanding

I learned how to interpret insurance-specific fields such as:

- Claim Amount
- Claim Frequency
- Coverage Zone
- Car Use
- Car Year
- Kids Driving

Understanding the business meaning of each field is important before performing analysis.

---

## 3. KPI Development

I learned how to build an executive-level dashboard around meaningful KPIs instead of displaying every available field.

---

## 4. Data Visualization

I learned how to choose visualizations according to the analytical question.

| Requirement | Visualization |
|---|---|
| KPI Summary | Cards |
| Category Composition | Donut Chart |
| Ranking | Bar Chart |
| Group Comparison | Column Chart |
| Trend Analysis | Area Chart |
| Multidimensional Analysis | Matrix |

---

## 5. Dynamic Measures

I learned how to create an interactive dashboard where the user can switch between:

```text
Total Claim Amount
```

and:

```text
Total Policies
```

This allows one dashboard to provide multiple analytical perspectives.

---

## 6. Customer Segmentation

I learned how demographic attributes can be used to segment customers.

Examples:

- Age
- Gender
- Education
- Marital Status

---

## 7. Risk Analysis

This project helped me understand that insurance risk should not be evaluated using a single metric.

A more complete analysis considers:

```text
Policy Volume
+
Claim Frequency
+
Claim Amount
+
Average Claim Amount
```

---

## 8. Data Storytelling

I learned how to organize a dashboard so that users can move from high-level information to detailed analysis:

```text
KPI Summary
      ↓
Policy Distribution
      ↓
Vehicle Analysis
      ↓
Customer Analysis
      ↓
Geographic Analysis
      ↓
Claims Analysis
```

---

# 🛠️ Tools & Technologies

## Microsoft Power BI

Used for:

- Data visualization
- Dashboard development
- KPI reporting
- Interactive analysis
- Dynamic measure selection
- Business intelligence

## Microsoft Excel

Used as the source data format.

## GitHub

Used for:

- Project version control
- Documentation
- Portfolio presentation
- Dashboard image hosting

---

# 💼 Skills Demonstrated

## Technical Skills

```text
Power BI
Microsoft Excel
Data Visualization
Dashboard Development
Interactive Reporting
KPI Development
Business Intelligence
```

## Analytical Skills

```text
Exploratory Data Analysis
Customer Segmentation
Claims Analysis
Risk Analysis
Demographic Analysis
Vehicle Analysis
Geographic Analysis
Comparative Analysis
```

## Business Skills

```text
Business Requirement Analysis
KPI Selection
Business Question Development
Data Storytelling
Decision Support
Stakeholder-Oriented Reporting
```

---

# 📂 Repository Structure

The current repository is organized as follows:

```text
Insurance-Claim-Analysis-Dashboard/
│
├── 📁 Dashboard/
│   ├── Insurance Analysis Dashboard1.png
│   └── Insurance Analysis Dashboard2.png
│
├── 📄 Business Requirements.docx
│
├── 📄 Domain Doc.docx
│
├── 📊 Insurance Claim Analysis Report.pbix
│
├── 📄 README.md
│
└── 📊 insurance_policies_data.xlsx
```

> **Note:** Make sure the `.pbix` filename in this section exactly matches the filename in your GitHub repository.

---

# 🖼️ Dashboard Files

The `Dashboard` folder contains the two screenshots used in this README.

```text
Dashboard/
│
├── Insurance Analysis Dashboard1.png
│
└── Insurance Analysis Dashboard2.png
```

### Dashboard 1

**Total Claim Amount**

```text
Dashboard/Insurance Analysis Dashboard1.png
```

### Dashboard 2

**Total Policies**

```text
Dashboard/Insurance Analysis Dashboard2.png
```

---

# 📄 Project Documentation

The repository contains supporting documentation.

## Business Requirements.docx

Contains the business requirements used to determine:

- KPIs
- Dynamic measures
- Required charts
- Business questions

## Domain Doc.docx

Contains the domain-level description of the insurance dataset, including:

- Field definitions
- Data types
- Business meaning
- Potential business applications

## Power BI Report

The `.pbix` file contains the interactive Power BI dashboard.

---

# 🔄 Complete Project Workflow

### Step 1 — Business Requirement

Understand the problem and identify what stakeholders need from the dashboard.

### Step 2 — Domain Understanding

Understand the insurance terminology and business meaning of the fields.

### Step 3 — Data Understanding

Classify fields into:

- Customer
- Vehicle
- Geographic
- Household
- Claims

### Step 4 — KPI Identification

Define:

- Total Policies
- Total Claim Amount
- Average Claim Frequency
- Average Claim Amount
- Gender-wise Policies

### Step 5 — Visualization Development

Build visuals for:

- Car Use
- Car Make
- Coverage Zone
- Age Group
- Car Year
- Kids Driving
- Education
- Education & Marital Status

### Step 6 — Interactivity

Add the dynamic measure selector:

```text
Total Claim Amount
        ↕
Total Policies
```

### Step 7 — Dashboard Design

Arrange the visuals into a structured single-page dashboard.

### Step 8 — Analysis

Interpret the data while considering both aggregate values and population size.

---

# 🚀 Future Improvements

The current dashboard provides a broad overview, but several improvements could make the analysis more advanced.

## 1. Claim Amount per Policy

Add:

```text
Total Claim Amount
------------------
Total Policies
```

This would provide better comparisons between segments of different sizes.

---

## 2. Claim Frequency Rate

Create a standardized frequency metric to compare customer and vehicle segments more effectively.

---

## 3. Risk Matrix

Create a matrix comparing:

```text
Claim Frequency
        vs
Average Claim Amount
```

This could identify:

- Low Frequency / Low Severity
- Low Frequency / High Severity
- High Frequency / Low Severity
- High Frequency / High Severity

---

## 4. Vehicle Drill-Down

Create:

```text
Car Make
   ↓
Car Model
```

to provide more detailed vehicle analysis.

---

## 5. Geographic Mapping

If suitable geographic information is available, add a map visual for regional analysis.

---

## 6. Drill-through Pages

Potential drill-through pages:

```text
Customer Analysis
Vehicle Analysis
Claims Analysis
Geographic Analysis
```

---

## 7. Additional DAX Measures

Potential future measures include:

- Claim Amount per Policy
- Average Claim Amount
- Claim Frequency Rate
- Segment Contribution %
- Policy Contribution %
- Year-over-Year Change
- Claim Amount Growth %

---

# 📈 Future Dashboard Structure

A future version could be expanded into multiple pages:

```text
Page 1
Executive Overview
│
├── Total Policies
├── Total Claim Amount
├── Average Claim Amount
└── Claim Frequency

Page 2
Customer Risk Analysis
│
├── Age
├── Gender
├── Education
└── Marital Status

Page 3
Vehicle Risk Analysis
│
├── Car Make
├── Car Model
├── Car Year
└── Car Use

Page 4
Geographic Analysis
│
└── Coverage Zone

Page 5
Claims Analysis
│
├── Claim Frequency
├── Claim Severity
└── Risk Segmentation
```

---

# 🎯 Project Outcome

The final Power BI dashboard provides a centralized interactive view of the insurance portfolio.

It allows users to analyze:

### Customer

- Age
- Gender
- Education
- Marital Status

### Vehicle

- Car Make
- Car Model
- Car Year
- Car Use

### Geographic

- Coverage Zone

### Household

- Parent
- Kids Driving

### Claims

- Claim Amount
- Claim Frequency

The result is a business intelligence dashboard that converts structured insurance data into an interactive analytical solution.

---

# 📌 Key Takeaways

The most important lesson from this project is that a good BI dashboard is not only about creating attractive visuals.

A useful dashboard connects:

```text
Business Problem
       ↓
Business Requirement
       ↓
Data Understanding
       ↓
KPI Development
       ↓
Visualization
       ↓
Interactivity
       ↓
Analysis
       ↓
Business Decision
```

This project allowed me to practice the complete process using an insurance analytics use case.

---

# 👨‍💻 About Me

## Aakash Diwakar

**Aspiring Data Analyst | Power BI | SQL | Excel | Python**

I am building practical Data Analytics and Business Intelligence projects to strengthen my skills in:

- Data Analysis
- Power BI
- SQL
- Excel
- Python
- Data Visualization
- Business Intelligence

This project represents my practical experience in converting a business requirement and structured dataset into an interactive Power BI dashboard.

---

# 🔗 Connect With Me

### LinkedIn

Add your LinkedIn profile:

```text
https://www.linkedin.com/in/YOUR-USERNAME/
```

### GitHub

Add your GitHub profile:

```text
https://github.com/YOUR-USERNAME
```

---

# ⭐ Project Highlights

| Area | Demonstrated |
|---|---|
| Business Requirement Analysis | ✅ |
| Insurance Domain Understanding | ✅ |
| Data Understanding | ✅ |
| KPI Development | ✅ |
| Power BI Dashboard | ✅ |
| Dynamic Measure Selection | ✅ |
| Data Visualization | ✅ |
| Customer Segmentation | ✅ |
| Claims Analysis | ✅ |
| Risk Analysis | ✅ |
| Vehicle Analysis | ✅ |
| Geographic Analysis | ✅ |
| Business Storytelling | ✅ |

---

# 🏷️ Technologies & Topics

`Power BI` `Excel` `Data Analysis` `Data Visualization` `Business Intelligence` `Insurance Analytics` `Claims Analysis` `Risk Analysis` `Customer Segmentation` `Dashboard Development` `KPI Analysis`

---

# ⚠️ Disclaimer

This project is intended for **learning, portfolio, and demonstration purposes**.

The dashboard should not be interpreted as a professional insurance pricing, underwriting, actuarial, or financial model.

The analysis is descriptive and is based on the available dataset and defined business requirements.

---

# ⭐ Thank You

Thank you for visiting this project.

If you are a recruiter, hiring manager, or fellow data enthusiast, I hope this project demonstrates my ability to transform structured data and business requirements into an interactive and business-focused analytical dashboard.

### Business Requirement → Data → Analysis → Visualization → Insight
