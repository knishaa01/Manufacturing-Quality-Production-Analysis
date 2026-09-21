# Manufacturing Quality & Production Intelligence

## 📌 Project Overview

**Manufacturing Quality & Production Intelligence** is a Python-based data analysis project designed to evaluate **manufacturing quality, production efficiency, operational performance, cost, and warranty risk**.

The project analyzes **10,000 manufacturing events and 23 original variables** covering plants, production lines, shifts, machines, operators, materials, process conditions, inspection methods, defects, rework, scrap, energy consumption, cost, and warranty claims.

The objective is to transform raw manufacturing data into **actionable quality and operational insights** that can support data-driven business decisions.

---

## 🎯 Business Problem

Manufacturing organizations need to continuously monitor production quality and operational efficiency to minimize defects, waste, rework, production costs, and customer-impacting quality issues.

This project focuses on identifying:

* **Defect Patterns**
* **Quality Issues**
* **High-Risk Production Lines**
* **Plant Performance Gaps**
* **Shift-Wise Quality Differences**
* **Material Quality Issues**
* **Scrap & Rework**
* **Cost Drivers**
* **Cycle Time Issues**
* **Warranty Claim Risk**

---

## 🎯 Project Objectives

* **Improve Product Quality**
* **Reduce Defects & Scrap**
* **Control Rework**
* **Identify Quality Drivers**
* **Optimize Production Performance**
* **Reduce Manufacturing Costs**
* **Monitor Warranty Risk**
* **Track Quality Trends**
* **Support Data-Driven Decisions**

---

## 📊 Dataset Overview

The dataset contains **10,000 manufacturing events** with **23 original columns**.

### Key Data Categories

| Category           | Examples                                |
| ------------------ | --------------------------------------- |
| Production         | Plant, Line, Shift                      |
| Machine            | Machine ID, Machine Age                 |
| Workforce          | Operator ID                             |
| Material           | Material Grade                          |
| Process            | Temperature, Humidity, Production Speed |
| Inspection         | Inspection Method                       |
| Quality            | Defect Type, Defect Severity            |
| Decision           | Rework Decision                         |
| Production Outcome | Final Pass, Scrap                       |
| Efficiency         | Cycle Time, Energy                      |
| Financial          | Cost                                    |
| Customer Impact    | 90-Day Warranty Claim                   |

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data loading, cleaning, transformation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Analysis and documentation

---

## 🔍 Data Preparation & Validation

The project begins with structured data validation to ensure the dataset is suitable for analysis.

### Performed Checks

* Dataset shape verification
* Column name validation
* Data type inspection
* Date conversion
* Missing value analysis
* Duplicate record detection
* Event ID uniqueness validation
* Binary column validation
* Defect severity validation

Additional analytical features were created:

* **Defect Flag**
* **Failure Flag**
* **Year**
* **Month**
* **Day of Week**
* **Hour**

These features enable deeper quality and time-based analysis.

---

## 📈 Key Manufacturing KPIs

The project calculates important operational and quality KPIs:

* **Total Manufacturing Events**
* **Defect Rate**
* **Final Pass Rate**
* **Scrap Rate**
* **Rework Rate**
* **Warranty Claim Rate**
* **Average Cycle Time**
* **Average Energy Consumption**
* **Average Manufacturing Cost**

These KPIs provide a high-level view of overall manufacturing performance.

---

## 🔎 Exploratory Data Analysis

### 1. Defect Analysis

Analyzes the frequency and distribution of different defect types to understand the major quality issues within the manufacturing process.

### 2. Plant Analysis

Compares plants based on:

* Defect Rate
* Pass Rate
* Scrap Rate
* Rework Rate
* Warranty Rate
* Average Cost
* Average Cycle Time

### 3. Production Line Analysis

Evaluates production lines to identify differences in quality, scrap, rework, cost, and operational efficiency.

### 4. Shift Analysis

Compares **Day, Swing, and Night shifts** based on manufacturing quality and operational KPIs.

### 5. Material Grade Analysis

Examines whether different material grades are associated with differences in defects, scrap, rework, cost, and quality outcomes.

### 6. Inspection Method Analysis

Compares available inspection methods against manufacturing quality and operational outcomes.

### 7. Defect Severity Analysis

Studies how defect severity levels relate to:

* Final Pass Rate
* Scrap Rate
* Warranty Claims
* Manufacturing Cost
* Cycle Time

### 8. Monthly Quality Trend

Tracks manufacturing performance over time to identify changes in:

* Defect Rate
* Pass Rate
* Scrap Rate
* Rework Rate
* Warranty Rate
* Average Cost

---

## 📊 Correlation Analysis

Correlation analysis is performed across important numerical variables including:

* Machine Age
* Temperature
* Humidity
* Production Speed
* Defect Severity
* Rework
* Final Pass
* Scrap
* Cycle Time
* Energy Consumption
* Cost
* Warranty Claims

Special correlation analysis is performed for:

* **Scrap**
* **Warranty Claims**

> Correlation indicates statistical association between variables and does not establish causation.

---

## 📉 Data Visualizations

The project includes business-focused visualizations such as:

* **Defect Type Distribution**
* **Monthly Defect Rate Trend**
* **Scrap Rate by Production Line**
* **Defect Rate by Material Grade**
* **Final Pass Rate by Shift**
* **Average Cost by Defect Severity**
* **Manufacturing Correlation Heatmap**

These visualizations make quality and operational patterns easier to identify.

---

## 💡 Business Value

The analysis can help manufacturing teams monitor and investigate:

* **Quality Performance**
* **Production Efficiency**
* **Defect Reduction Opportunities**
* **Scrap & Rework**
* **Cost Optimization**
* **Process Performance**
* **Warranty Risk**
* **Operational Trends**

The results can support quality, production, and operations teams in identifying areas that require further investigation and improvement.

---

## 📂 Project Structure

```text
Manufacturing-Quality-Analysis/
│
├── manufacturing_quality_decisions.csv
│
├── Manufacturing_Quality_Analysis.ipynb
│
├── plant_quality_analysis.csv
├── line_quality_analysis.csv
├── shift_quality_analysis.csv
├── material_quality_analysis.csv
├── inspection_quality_analysis.csv
├── severity_analysis.csv
├── monthly_quality_analysis.csv
├── correlation_matrix.csv
│
└── README.md
```

---

## 🚀 Project Workflow

```text
Raw Manufacturing Data
          ↓
Data Validation
          ↓
Data Preparation
          ↓
Feature Engineering
          ↓
KPI Calculation
          ↓
Exploratory Data Analysis
          ↓
Quality & Operational Analysis
          ↓
Correlation Analysis
          ↓
Business Insights
          ↓
Exported Analysis Results
```

---

## 📌 Key Skills Demonstrated

### Python

* Data Loading
* Data Cleaning
* Data Transformation
* Feature Engineering
* GroupBy Analysis
* Aggregation
* Statistical Analysis

### Data Analysis

* KPI Development
* Quality Analysis
* Trend Analysis
* Correlation Analysis
* Business Problem Analysis

### Data Visualization

* Bar Charts
* Line Charts
* Count Plots
* Heatmaps
* Comparative Analysis

---

## 📤 Output Files

The project exports major analytical results into separate CSV files for further use in **Excel, Power BI, reporting, or business analysis**.

Generated outputs include:

* Plant Quality Analysis
* Production Line Analysis
* Shift Analysis
* Material Analysis
* Inspection Analysis
* Severity Analysis
* Monthly Quality Analysis
* Correlation Matrix

---

## 🏁 Conclusion

This project demonstrates an end-to-end **Python Data Analysis workflow for manufacturing operations**, starting from raw data validation and feature engineering to KPI development, exploratory analysis, visualization, correlation analysis, and business-oriented insights.

It showcases how manufacturing data can be transformed into structured information for monitoring **quality, efficiency, cost, production performance, and warranty-related risks**.

---

## 👩‍💻 Author

**Nisha Kumari**

**Focus:** Data Analysis | Python 

