# Minor Irrigation & Groundwater Analysis - Uttar Pradesh 📊💧

[![Deploy Showcase to GitHub Pages](https://github.com/Singhkunall/Minor-Irrigation-Analysis-PowerBI/actions/workflows/deploy.yml/badge.svg)](https://github.com/Singhkunall/Minor-Irrigation-Analysis-PowerBI/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live_Web_Showcase-GitHub_Pages-6366f1?style=flat&logo=github)](https://singhkunall.github.io/Minor-Irrigation-Analysis-PowerBI/)
[![Power BI](https://img.shields.io/badge/Power_BI-Desktop_%26_Service-f2c811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Dataset](https://img.shields.io/badge/Dataset-106%2C402_Villages-059669?style=flat&logo=sqlite)](UPVillageSchedule.csv)

An end-to-end data analytics and business intelligence project built using **Microsoft Power BI** and web analytics technologies. This project analyzes village-level minor irrigation infrastructure, crop season dependencies (Kharif, Rabi, Perennial), land utilization, and pre/post-monsoon groundwater fluctuations across **106,402 villages** and **75 districts** in Uttar Pradesh.

🚀 **Live Web Showcase & Interactive Viewer:**  
👉 **[https://singhkunall.github.io/Minor-Irrigation-Analysis-PowerBI/](https://singhkunall.github.io/Minor-Irrigation-Analysis-PowerBI/)**

---

## 📌 Executive Summary

Irrigation availability and groundwater sustainability are vital for agricultural productivity in Uttar Pradesh. This project transforms raw survey data into actionable visual intelligence for policymakers and regional water resource managers.

### Key Metrics At A Glance:
- 🗺️ **Total Geographical Area:** `23.60 Million Hectares`
- 🌾 **Total Cultivable Area:** `17.87 Million Hectares` (75.7% of total area)
- 💧 **Total Gross Irrigated Area:** `19.10 Million Hectares`
- 🌧️ **Seasonal Breakdown:** Rabi (`7.96M ha` / 41.7%), Kharif (`7.33M ha` / 38.4%), Perennial (`1.87M ha` / 9.8%)
- 📉 **Groundwater Recharging:** Pre-monsoon avg depth `9.00m` → Post-monsoon avg depth `8.88m`
- 👥 **Water User Associations (WUA):** `14,058 Villages` equipped with active WUAs

---

## 🌟 Web Showcase Features (`index.html`)

1. **Embedded Live Power BI Viewer:** Seamless container to stream your `powerBIFinalProject.pbix` directly from `app.powerbi.com` with full-screen support.
2. **Interactive Chart.js Web Analytics:** Real-time dynamic visual breakdown of top districts, crop seasons, water table shifts, and WUA governance.
3. **Project Documentation Viewer:** In-app tabbed accordion reading experience for the project report (`FinalPowerBIreport.pdf` & `.doc`).
4. **Asset Download Center:** One-click downloads for `.pbix`, `.csv`, `.pdf`, and `.doc` files.

---

## 🛠️ How to Connect Live Power BI to GitHub Pages

To view your live interactive Power BI report on the deployed website:

1. Open `powerBIFinalProject.pbix` in **Power BI Desktop**.
2. Click **Publish** (Home ribbon) and log into your **Power BI Service** account (`app.powerbi.com`).
3. Select your workspace and publish the report.
4. In Power BI Service, open the report and go to:
   `File` ➔ `Embed Report` ➔ `Publish to Web (Public)`.
5. Copy the generated `iframe` source link (starts with `https://app.powerbi.com/view?r=...`).
6. Open your live website at [https://singhkunall.github.io/Minor-Irrigation-Analysis-PowerBI/](https://singhkunall.github.io/Minor-Irrigation-Analysis-PowerBI/), click **"Update Embed Link"**, and paste your link!

---

## 📁 Repository Directory Structure

```micro
Minor-Irrigation-Analysis-PowerBI/
├── index.html                   # Responsive GitHub Pages web showcase & interactive viewer
├── powerBIFinalProject.pbix     # Microsoft Power BI desktop report source file
├── UPVillageSchedule.csv        # Primary dataset (106,402 village schedule records)
├── FinalPowerBIreport.pdf       # Compiled final project report (PDF format)
├── FinalPowerBIreport.doc       # Project documentation (Word format)
├── README.md                    # Project overview & deployment guide
└── .github/
    └── workflows/
        └── deploy.yml           # GitHub Actions automated deployment workflow
```

---

## 💡 Key Findings & Strategic Insights

- **High Rabi Season Reliance:** Rabi season requires intensive irrigation (41.7%), driven predominantly by private and deep tube-well extraction.
- **Top Irrigated Districts:** *Kheri* (684,101 ha), *Aligarh* (515,247 ha), *Bareilly* (504,062 ha), and *Shahjahanpur* (492,608 ha) exhibit the highest total irrigated acreage.
- **Water Table Shifts:** Districts like *Prayagraj* (pre 20.2m / post 17.7m) and *Firozabad* (pre 17.2m / post 16.2m) show significant monsoon recovery, yet remain at deep water table thresholds requiring conservation schemes.
- **WUA Expansion Need:** Only 13.2% of villages have established Water User Associations, highlighting a major opportunity for community-based water management policies.

---

## 🧑‍💻 Author

**Kunal Singh**  
GitHub: [@Singhkunall](https://github.com/Singhkunall)
