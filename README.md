# 🏥 Hospital Resource Utilization Dashboard (Canada 2022–2023)

<p align="center">
  <img src="assets/preview.png" alt="Hospital Resource Utilization Dashboard" width="90%">
</p>


## 🎯 Project Overview
Analyze hospital bed utilization across Canadian provinces using **Excel** and **Tableau** to identify under- and over-utilized regions and compare teaching vs non-teaching hospitals.

---

## 🧩 Tools Used
- **Excel** – data cleaning and slicer-based dashboard  
- **Tableau** – interactive KPI visualizations  
- **CIHI (Canadian Institute for Health Information)** – official dataset source

---

## 📊 Key Performance Indicators (KPIs)

| Metric | Formula | Insight |
|---------|----------|----------|
| **Occupancy Rate** | Inpatient Days ÷ (Staffed Beds × Days) | Measures resource use |
| **Underutilized Hospitals** | Occupancy < 70 % | Possible excess capacity |
| **Overburdened Hospitals** | Occupancy > 90 % | Possible bed shortage |

---

## 💡 Insights Summary
- Teaching hospitals show **higher average occupancy** across provinces.  
- **3 provinces** fall below 70 % utilization → potential resource reallocation.  
- **Non-teaching** facilities show higher variance in utilization rates.

🔗 **Interactive Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/rachna.kandari/viz/HospitalResourceUtilization2022-23/Dashboard1)

---

## 🗂️ Project Structure

| Folder | Description |
|---------|-------------|
| `excel/` | Excel dashboard file |
| `tableau/` | Tableau packaged workbook (.twbx) |
| `docs/` | PDF summaries |
| `data/` | Sample or reference data |
| `assets/` | Images & screenshots |

---

## 📘 Data Source
- **Canadian Institute for Health Information (CIHI)**  
- Dataset : Hospital Resource Utilization FY 2022–2023  
- Used for educational and analytical purposes only.

---

## 🧠 Future Improvements
- Automate data updates with Tableau Prep  
- Integrate Python ETL pipeline  
- Add multi-year trend comparison

---

## 👩‍💻 Author
**Rachna Kandari**  
📧 kandari.rachna74@gmail.com | [LinkedIn Profile](https://www.linkedin.com/in/rachna-kandari/)  
📅 Updated October 2025  🪪 License MIT
