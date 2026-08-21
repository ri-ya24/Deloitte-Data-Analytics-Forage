# Deloitte Data Analytics Job Simulation

A data analytics project completed as part of the **Deloitte Data Analytics Job Simulation on Forage**, focused on data analysis, visualization, and business-oriented interpretation using **Tableau and Microsoft Excel**.

## 📌 Project Overview

This simulation involved analysing operational telemetry data from **Daikibo** and evaluating employee compensation equality data.

The project consisted of two tasks:

* **Task 1:** Telemetry Data Analysis & Tableau Dashboard
* **Task 2:** Employee Compensation Equality Classification

---

## 🛠️ Tools & Technologies

* Tableau
* Microsoft Excel
* Data Analysis
* Data Visualization
* Calculated Fields
* Dashboard Development
* Data Classification

---

# 📊 Task 1 — Telemetry Data Analysis

### Objective

Analyse telemetry data collected by Daikibo to identify factories and device types experiencing the highest potential downtime.

### Dataset

The provided telemetry dataset contained machine/device status information collected across Daikibo factories.

### Work Performed

* Imported the `daikibo-telemetry-data.json` dataset into Tableau.
* Included all available schema levels during data import.
* Created a calculated measure named **Unhealthy**.
* Assigned a value of **10 minutes** to each unhealthy status to represent potential downtime since the previous telemetry message.
* Created a bar chart showing **Down Time per Factory**.
* Created a second bar chart showing **Down Time per Device Type**.
* Combined both visualizations into an interactive Tableau dashboard.
* Configured the factory chart as a filter for the device-type chart.
* Identified the factory with the highest downtime and analysed its device-level downtime.

### Dashboard

The final dashboard allows users to select a factory and dynamically view the downtime distribution across its device types.

### Key Learning

This task provided practical experience in:

* Working with telemetry data
* Creating calculated measures in Tableau
* Building interactive dashboards
* Using filters and dashboard actions
* Translating operational data into business insights

---

# 📈 Task 2 — Employee Compensation Equality Analysis

### Objective

Classify employee compensation equality scores into meaningful categories to identify potential fairness and discrimination concerns.

### Dataset

The provided Excel file contained:

| Column         | Description                     |
| -------------- | ------------------------------- |
| Factory        | Factory location                |
| Job Role       | Employee job role               |
| Equality Score | Score ranging from -100 to +100 |

A fourth column, **Equality Class**, was created based on the equality score.

### Classification Logic

| Equality Score                    | Equality Class        |
| --------------------------------- | --------------------- |
| -10 to +10                        | Fair                  |
| Less than -10 or greater than +10 | Unfair                |
| Less than -20 or greater than +20 | Highly Discriminative |

### Examples

* `10 → Fair`
* `-9 → Unfair`
* `-30 → Highly Discriminative`

### Work Performed

* Analysed the provided equality scores.
* Created the **Equality Class** column.
* Applied the required classification criteria.
* Categorised records into Fair, Unfair, and Highly Discriminative groups.
* Saved the edited Excel dataset for submission.

---

# 🎯 Skills Demonstrated

Through this simulation, I gained practical experience in:

* Data cleaning and preparation
* Data classification
* Tableau calculated fields
* Data visualization
* Interactive dashboard creation
* Excel-based analysis
* Identifying operational patterns
* Translating data into business-relevant insights

---

## 📂 Project Deliverables

### Task 1

* Tableau telemetry analysis
* Down Time per Factory visualization
* Down Time per Device Type visualization
* Interactive Tableau dashboard

### Task 2

* Processed Equality Table
* Equality Class categorization

---

## 🏢 Simulation

**Deloitte — Data Analytics Job Simulation**
Completed through **Forage**

This project was completed as a practical simulation to develop real-world data analytics and visualization skills.
