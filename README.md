# health-analytics-based-on-power-bi
# 🌟 **Healthcare Analytics Dashboard – Power BI Project**

<div align="center">

### 🏥 **Transforming Healthcare Data Into Actionable Insights**

🚀 *A premium-quality Power BI project designed to analyze patient records, hospital trends, treatment effectiveness, and cost patterns.*

📊 **Interactive Dashboards | Advanced Data Modeling | Clinical & Operational Insights**

</div>

---

# 🎯 **Project Overview**

Healthcare organizations generate large volumes of patient and treatment data, but turning that data into meaningful insights requires powerful visualization and analytics. This project leverages **Power BI** to create a comprehensive, visually rich dashboard covering:

* Patient admission trends
* Treatment effectiveness analysis
* Cost behavior by month & diagnosis
* Hospital-level performance
* Recovery insights across demographics

This dashboard is designed for **hospital administrators, analysts, and clinicians** to make informed decisions that improve efficiency, patient experience, and resource management.

---

# 🏆 **Project Highlights**

* ✔️ Professionally designed Power BI dashboards
* ✔️ Multi‑page analysis with slicers and filters
* ✔️ Time‑series trends & forecasting‑ready visuals
* ✔️ Deep-dive treatment and diagnosis insights
* ✔️ High-quality visual storytelling
* ✔️ Clean, optimized data model for smooth performance

---

# 📊 **Dashboard Output Screenshots**

Each visual below represents a key analysis component of the project.

### **1️⃣ Patient Admission Trends Over Time**

Shows monthly fluctuations in patient admissions using line & bar charts.

![Patient Admission Trends](1.jpg)

---

### **2️⃣ Treatment Effectiveness Analysis**

Evaluates how different treatments perform using LOS (Length of Stay) & Recovery Rating.

![Treatment Effectiveness](2.jpg)

---

### **3️⃣ Time-Based Analysis Overview**

A combined page for cost trends, patient volume, LOS, and hospital-wise metrics.

![Time Based Analysis](3.jpg)

---

### **4️⃣ Main Healthcare Dashboard**

The hero dashboard page capturing KPIs, demographics, cost, diagnosis distribution, and recovery analytics.

![Health Dashboard](4.jpg)

---

# 🧬 **Data Sources & Schema**

### **Datasets Used:**

1. **Patient Medical Records**

   * PatientID, Age, Gender, Diagnosis, BloodType
   * Admission & Discharge Dates
   * TotalCost, RecoveryRating

2. **Hospital Treatment Details**

   * TreatmentID, TreatmentName
   * Length of Stay (LOS)
   * Treatment Cost

### **Cleaning & Transformations Performed:**

* Removed nulls & duplicates
* Standardized date formats
* Created custom calculated columns
* Built DAX measures for KPIs
* Normalized categories for consistency

---

# 📈 **Key Dashboard Pages & Insights**

### **1️⃣ Overview & KPIs**

* Avg Recovery Rating
* Avg LOS
* Avg Patients Per Room
* Avg Total Cost

### **2️⃣ Demographics Analysis**

* Patient age distribution
* Blood type proportions
* Diagnosis frequency

### **3️⃣ Treatment Intelligence**

* LOS vs Recovery performance
* Cost comparison by treatment

### **4️⃣ Time-Series Analytics**

* Admissions per month
* Cost patterns by month

### **5️⃣ Hospital Performance Comparison**

* Avg patients per room
* Recovery by hospital
* Hospital-wise cost insights

---

# 🧮 **Key DAX Measures Used**

```DAX
Total Patients = DISTINCTCOUNT(Patients[PatientID])

Average Length of Stay = AVERAGE(Patients[LengthOfStay])

Average Total Cost = AVERAGE(Patients[TotalCost])

Recovery Rating Avg = AVERAGE(Patients[RecoveryRating])

Admissions per Month = COUNT(Patients[PatientID])
```

> More measures included inside PBIX (KPIs, Time Intelligence, Aggregations).

---

# 🔍 **Major Insights & Findings**

⭐ **Seasonal Fluctuations:** Patient admissions vary noticeably across months, with certain months showing sharp drops.

⭐ **Treatment Efficiency:** Therapy shows a balanced combination of lower LOS and higher recovery.

⭐ **Cost Behavior:** Certain diagnoses (such as Covid-19 & Hypertension) contribute heavily to overall costs.

⭐ **Demographic Patterns:** Children (0–12) appear more frequently in patient admissions.

⭐ **Hospital Variations:** Recovery ratings and average cost differ significantly across hospitals.

---

# 🖥️ **How to Open the Project**

1. Download the `.pbix` file
2. Open using **Power BI Desktop** (latest version recommended)
3. If prompted, refresh the dataset
4. Explore dashboards using slicers & filters

---

# 🤝 **Contributing**

Pull requests are welcome! For major changes:

* Fork the repo
* Create a feature branch
* Submit a PR describing improvements

---

# 📬 **Contact**

👤 **Umesh Teja Chowdary**
🔗 GitHub: [https://github.com/Umeshteja23](https://github.com/Umeshteja23)

---

# 🚀 **Next Steps**

* Add AI-powered forecasting using Power BI
* Implement a Python ETL pipeline for automation
* Deploy dashboard to Power BI Service
* Add row-level security (RLS) for hospital-level access control

---

<div align="center">

### 🌟 *Thank you for exploring this project!*

### If you want a **portfolio‑ready version** or **GitHub‑optimized layout**, just ask! 💬

</div>
