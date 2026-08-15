# 🚚 Delhivery-Shipment-Exceptions-Analysis-Dashboard

A Power BI dashboard developed during my internship at Delhivery to analyze shipment exceptions, ageing, operational backlog, priority levels, and hub-wise exception patterns. The project focuses on using operational data to identify high-ageing and critical shipments and support data-driven decision-making.

## 🛠️ Tech Stack

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Microsoft Excel
- Data Cleaning & Transformation
- Data Visualization

## 📁 File Formats

- `.pbix` – Power BI Dashboard
- `.jpg` – Dashboard Screenshots
- `.xlsx` – Source/Prepared Dataset

---

## 🚨 Business Problem

In logistics operations, shipment exceptions such as **High Ageing, Short Received, Audit Missing, Finance Locked, Docs Missing, and Damaged shipments** can create operational backlogs and delay shipment movement.

A large exception dataset can make it difficult for operations teams to quickly identify:

- 🔎 Which shipments require immediate attention?
- 📊 How large is the ageing backlog?
- 📍 Which hubs have the highest exception volume?
- 🧩 Which exception categories contribute most to the backlog?
- 🚨 Where are critical/P0 shipments accumulating?
- ⏳ Which shipments have been stuck for an extended period?

The objective was to convert operational shipment data into an interactive dashboard that provides a consolidated view of these issues.

---

## 🎯 Project Goal

The primary goal of this project was to build an operational analytics dashboard that helps:

- 📦 Monitor overall shipment exceptions
- ⏳ Identify high-ageing shipments
- 🚨 Highlight critical backlog
- 📈 Analyze exception trends over time
- 📍 Compare exception volume across destination hubs
- 🏷️ Understand priority-wise distribution
- 🔎 Identify individual critical shipments requiring attention
- 💡 Support data-driven operational prioritization

---

# 📊 Dashboard Walkthrough

## 📌 Page 1: Shipments Exception Analysis Dashboard

The first page provides an executive-level overview of the shipment exception landscape through KPIs and interactive visualizations.

### 🔢 Key KPIs

- **8,790 Total Exceptions**
- **2,011 High-Ageing Shipments**
- **336 Critical Backlog**
- **7 Days Average Ageing**

### 📈 Key Visuals

#### 🧩 Exception Type Distribution

Breaks down exceptions into:

- High Ageing
- Short Received
- Audit Missing
- Finance Locked
- Docs Missing
- Damaged

This helps identify the major categories contributing to the operational exception workload.

#### 🚦 Priority Breakdown

Shows the distribution of exceptions across:

- P0 – Critical
- P1 – High
- P2 – Medium
- P3 – Low

The dashboard records **1,234 P0 Critical cases**, highlighting the importance of priority-based operational action.

#### 📅 Exception Trend by Week

Tracks exception volumes over time and helps identify sudden increases or unusual operational patterns.

The highest weekly exception volume shown is **5,413 exceptions in W23-2026**.

#### 📍 Shipments by Hub

Highlights the top destination hubs by exception volume.

The highest-volume destination hub shown in the dashboard records **4,571 exceptions**, indicating significant concentration of exceptions in specific locations.

### 🖼️ Page 1 Screenshot


![Dashboard Preview](https://github.com/iprateekpal/Delhivery-Shipment-Exceptions-Analysis-Dashboard/blob/main/Shipments%20Exceptions%20Analysis%20Dashboard.jpg)

---

## 📌 Page 2: Ageing Analysis

The second page focuses specifically on shipment ageing and critical shipment identification.

### 📈 Key Visuals

#### ⏳ Ageing Distribution

The dashboard categorizes shipments into:

- 0–1 Days: **3,261**
- 1–2 Days: **1,547**
- 2–3 Days: **940**
- 3–5 Days: **652**
- 5–7 Days: **379**
- 7+ Days: **2,011**

This provides a clear view of how the exception population is distributed by ageing.

#### 📍 Average Ageing by Hub

Compares average shipment ageing across the top-volume hubs.

This helps distinguish between hubs with high exception volumes and hubs where shipments are also remaining unresolved for longer periods.

#### 📊 Total Exceptions by Destination Hub

Provides another view of hub-level exception concentration and helps identify locations that may require deeper operational investigation.

#### 🚨 High-Ageing / Critical Shipment Detail

The detailed table provides shipment-level visibility into P0 critical cases using:

- AWB
- Client
- Exception Type
- Destination Hub
- Priority
- Average Ageing
- Agent

The dashboard highlights critical shipments with ageing values reaching **74 days**, allowing individual cases requiring immediate attention to be identified.

### 🖼️ Page 2 Screenshot


![Dashboard Preview](https://github.com/iprateekpal/Delhivery-Shipment-Exceptions-Analysis-Dashboard/blob/main/Shipments%20Ageing%20Analysis%20Dashboard.jpg)

---

## ❓ Key Business Questions Answered

### 📦 How many shipment exceptions are being analyzed?
**8,790 exceptions.**

### ⏳ How many shipments are highly aged?
**2,011 shipments are in the 7+ days ageing category.**

### 📅 What is the average ageing?
**7 days.**

### 🚨 How many critical backlog cases are present?
**336 critical backlog cases.**

### 🏷️ Which priority has the highest volume?
**P0 – Critical, with 1,234 cases.**

### 📈 When did exception volume reach its highest weekly level?
**W23-2026, with 5,413 exceptions.**

### 📍 Are exceptions concentrated across specific hubs?
Yes. The dashboard shows significant concentration, with the highest-volume destination hub recording **4,571 exceptions**.

### 🚨 Are there extremely aged critical shipments?
Yes. The detailed P0 table contains shipments with ageing values reaching **74 days**.

---

## 💼 Business Outcome

The dashboard converts a large operational exception dataset into a structured decision-support view.

Instead of reviewing exception records individually, users can quickly:

- 🔎 Identify critical and high-ageing shipments
- 🚨 Prioritize P0 cases
- 📈 Detect sudden changes in exception volume
- 📍 Identify high-volume destination hubs
- ⏳ Compare ageing patterns across hubs
- 🔍 Drill down from overall KPIs to individual shipment records

The key outcome is **better visibility and prioritization of operational exceptions**, helping teams focus their attention on shipments and hubs that require deeper investigation.

> **Note:** The dashboard demonstrates analytical visibility and prioritization. It does not claim a quantified reduction in ageing or backlog because the project data does not establish a before-versus-after performance comparison.

---

## 💡 Key Analytical Insights

- The dataset contains **8,790 shipment exceptions**.
- **2,011 shipments are aged 7+ days**, indicating a substantial long-pending population.
- Exception volume experienced a major spike in **W23-2026**.
- Exception volume is heavily concentrated in certain destination hubs.
- P0 critical cases form a major part of the priority breakdown.
- Individual critical shipments can remain unresolved for several weeks, with the highest displayed ageing reaching **74 days**.
- Combining volume, priority, hub, and ageing provides a more useful operational view than looking at exception counts alone.

---

## 🚀 Project Value

This project demonstrates the application of **Business Analytics to real-world logistics operations**, combining operational data analysis with interactive visualization to identify bottlenecks, prioritize exceptions, and support operational decision-making.

**Business Analytics | Operations Analytics | Power BI | Data Visualization | Logistics Analytics**

---
