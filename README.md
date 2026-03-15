# 🏥 Hospital Emergency Room Analytics Dashboard

This **Power BI Capstone Project** provides actionable insights into **Hospital Emergency Room (ER) performance**.  
The dashboard focuses on monitoring **patient flow, reducing wait times, and improving service quality** through data-driven analysis.

By transforming raw hospital data into interactive visualizations, the dashboard helps healthcare administrators make **better operational decisions and optimize emergency room efficiency**.

---

# 📊 Key Performance Indicators (KPIs)

The dashboard tracks several important metrics to evaluate ER operational performance:

| KPI | Value |
|----|----|
| **Total Patients** | 431 visits during the reporting period |
| **Average Wait Time** | 36.7 minutes per patient |
| **Patient Satisfaction Score** | 4.72 / 5.00 |
| **Patients Referred** | 179 patients referred to specialized departments |

These KPIs help hospital administrators understand **service efficiency, patient experience, and referral patterns**.

---

# 🔄 Project Workflow

The project follows a structured **data analytics lifecycle**:

### 1️⃣ Requirement Gathering
- Identified key hospital performance metrics.
- Defined the objectives for ER operational analysis.

### 2️⃣ Data Cleaning & Processing
- Cleaned inconsistent or missing data.
- Standardized patient demographic information.
- Prepared datasets for analysis using **Power Query**.

### 3️⃣ Data Modeling
- Created relationships between:
  - Patient records
  - Hospital departments
  - Time-based data
- Designed a star-schema model for efficient querying.

### 4️⃣ DAX Calculations
Developed custom **DAX measures** for:

- Average wait time
- Patient satisfaction score
- Referral counts
- Percentage of patients treated within target time

### 5️⃣ Dashboard Development
Built an interactive **Power BI dashboard** including:

- KPI cards
- Trend charts
- Heatmaps
- Demographic visualizations

---

# 📈 Dashboard Views

The report includes four major analytical views designed for different stakeholders.

## 1. Monthly View
Provides a high-level overview of ER activity.

Includes:
- Patient trends by month
- Demographic breakdown (age, gender, race)
- Overall service metrics

## 2. Consolidated View
Offers a comprehensive summary of hospital performance with **customizable date filters**.

Useful for:
- Management reporting
- Operational monitoring

## 3. Patient Details
A **granular data grid** containing patient-level records.

Enables:
- Troubleshooting
- Operational auditing
- Detailed analysis

## 4. Key Takeaways
Provides descriptive insights and recommendations derived from the analysis.

---

# ⚙️ Technical Highlights

### ⏱ Timeliness Tracking
A custom algorithm calculates the **percentage of patients seen within the 30-minute target**.

- **Current Performance:** 65.66%

### 🔥 Peak Demand Analysis
A **time-based heatmap** identifies peak ER demand periods.

- Highest traffic occurs on **Thursday mornings (9 AM – 12 PM)**  
- Patient volume peaks at **77 patients**

### 🏥 Department Referral Analysis
Referral data reveals the most common departments receiving ER patients:

- **General Practice**
- **Orthopedics**

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|----|----|
| **Power BI** | Dashboard development and data visualization |
| **DAX** | Creating measures and KPI calculations |
| **Power Query** | Data cleaning and transformation |
