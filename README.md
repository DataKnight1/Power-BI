# 📊 Power BI Portfolio

Welcome to my Power BI portfolio repository! This is a curated collection of interactive dashboards and analytical reports showcasing data modeling, DAX calculations, and business intelligence solutions across various domains.

---

## 🎯 About This Repository

This repository serves as a comprehensive showcase of my Power BI development skills, featuring:

- **Advanced Data Modeling** - Star schema implementations, relationship management, and optimized data structures
- **DAX Mastery** - Complex calculations, time intelligence, and custom measures
- **Interactive Visualizations** - Dynamic dashboards with bookmarks, drill-through, and custom visuals
- **Real-World Applications** - Projects addressing actual business scenarios and analytical challenges

---

## 📁 Projects

### 1️⃣ [FC Porto - Club Management Dashboard](./Twelve%20Power%20BI%20360/)

> **Power BI 360 Course - Final Project** | *Twelve powered by Objetivo Analista*

A comprehensive football club management system integrating financial, sporting, and medical data for FC Porto's Youth and Senior teams.

<div align="center">
  <img src="./Twelve Power BI 360/assets/First_Cover.jpg" alt="FC Porto Dashboard Cover" width="700"/>
</div>

#### 📋 Project Overview

- **Domain**: Sports Analytics & Club Management
- **Teams Tracked**: Youth Team (U-18) & Senior Team
- **Total Players**: 47 players across both squads
- **Data Sources**: 5 CSV files + 1 Excel workbook
- **Report Pages**: 3 interactive dashboards + navigation & context pages

#### 🌐 Live Demo

<div align="center">

[![View Live Dashboard](https://img.shields.io/badge/🔴_LIVE-View_Interactive_Dashboard-0078D4?style=for-the-badge&logo=powerbi&logoColor=white)](https://app.powerbi.com/view?r=eyJrIjoiZjUzYjA1ZmMtYTkyYi00OTlkLTlmZDQtNTk2OTA2MDIwZGVmIiwidCI6ImQzYTc2ODZiLTBkNWItNGM3My1iZWY3LTQ3MTljNWU1M2IzOSIsImMiOjh9&embedImagePlaceholder=true&pageName=9f05f58d8886a63875bd)

**🎮 Try it yourself!** Click above to explore the interactive dashboard with full filtering and drill-through capabilities.

</div>

#### 🎨 Dashboards

<table>
<tr>
<td width="33%" align="center">
<b>💰 Financial Dashboard</b><br/>
<img src="./Twelve Power BI 360/assets/Page 3.png" width="100%"/><br/>
<em>Revenue tracking, payment compliance, and financial KPIs</em>
</td>
<td width="33%" align="center">
<b>⚽ Sporting Dashboard</b><br/>
<img src="./Twelve Power BI 360/assets/Page 4.png" width="100%"/><br/>
<em>Performance metrics, pitch analysis, and player statistics</em>
</td>
<td width="33%" align="center">
<b>🏥 Injury Dashboard</b><br/>
<img src="./Twelve Power BI 360/assets/Page 5.png" width="100%"/><br/>
<em>Injury tracking, body area analysis, and recovery metrics</em>
</td>
</tr>
</table>

#### 🔑 Key Features

- **Star Schema Data Model** with Player_ID and Team_ID relationships
- **Centralized Measures Table** containing 20+ DAX calculations
- **Interactive Navigation** with bookmarks and page transitions
- **Dynamic Filtering** across teams, players, and time periods
- **Synoptic Panel Integration** for visual injury mapping

#### 📊 Key Metrics & Insights

**Financial Performance:**
- 💶 **€15M** Total Revenue Collected
- 📈 Payment breakdown across 4 methods (MBWay, Cash, Debit Card, Bank Transfer)
- 📉 Outstanding payments tracking by player and team
- 🎯 Age-based fee analysis (Under 18 to 31-35 age bands)

**Sporting Analytics:**
- ⚽ **543** Total Matches Played
- ⏱️ **28K** Total Minutes Played
- 🎯 **118** Total Goals Scored
- 📊 Advanced metrics: Goals/90min, Assists/90min, Cards/90min
- 🏆 Minutes-weighted match ratings

**Medical Intelligence:**
- 🏥 **13** Total Injuries Recorded
- ⏳ **62.46 days** Average Recovery Time
- 🎯 Injury severity classification (1-3 scale)
- 📍 Body area distribution (Brain, Knee, Leg Upper, Thigh, etc.)

#### 🛠️ Technical Implementation

**Data Architecture:**
```
📂 Data Sources
├── Personal_Information.csv    → Player profiles (47 records)
├── Financial_Information.csv   → Payment transactions
├── Sporting_Information.csv    → Performance statistics
├── Injuries_Record.csv         → Medical records (13 injuries)
└── Teams.csv                   → Team reference (2 teams)
```

**DAX Measures Categories:**
- 💰 Financial: Total Revenue, Outstanding Payments, Payment Compliance Rate
- ⚽ Sporting: Goals/Assists/Cards per Match, per 90 Minutes, Minutes-Weighted Ratings
- 🏥 Injury: Total Injuries, Average Recovery Time, Most Common Injury Type

**Visualization Techniques:**
- Custom pitch visualization for tactical analysis
- Synoptic Panel for anatomical injury mapping
- Conditional formatting for performance indicators
- Data bars and heatmaps for comparative analysis

#### 📚 Skills Demonstrated

- ✅ Complex data modeling with multiple fact and dimension tables
- ✅ Advanced DAX including time intelligence and statistical measures
- ✅ Custom visual integration and configuration
- ✅ UX/UI design with consistent branding and navigation
- ✅ Business storytelling through data visualization

#### 📄 Documentation

Full project documentation available in [`Final_Project.pdf`](./Twelve%20Power%20BI%20360/Final_Project.pdf)

---

## 🚀 Coming Soon

More exciting Power BI projects will be added to this portfolio soon! Stay tuned for:

- 📈 Sales & Marketing Analytics
- 🏭 Supply Chain & Operations Dashboards
- 💼 HR & Workforce Analytics
- 🌐 Web Analytics & Digital Marketing
- 💹 Financial Reporting & KPI Tracking

---

## 🛠️ Technologies & Tools

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-FF6600?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-3D9970?style=for-the-badge&logo=microsoftpowerautomate&logoColor=white)

</div>

**Core Competencies:**
- Data Modeling (Star Schema, Snowflake Schema)
- DAX (Data Analysis Expressions)
- Power Query / M Language
- ETL/ELT Processes
- Data Visualization Best Practices
- Interactive Report Design

---

## 📂 Repository Structure

```
Power-BI/
├── Twelve Power BI 360/          # FC Porto Club Management Dashboard
│   ├── Final_Project.pbix        # Power BI Report File
│   ├── Final_Project.pdf         # Project Documentation
│   ├── Dataset_Excel.xlsx        # Excel Data Source
│   ├── data/                     # CSV Data Files
│   │   ├── Personal_Information.csv
│   │   ├── Financial_Information.csv
│   │   ├── Sporting_Information.csv
│   │   ├── Injuries_Record.csv
│   │   └── Teams.csv
│   └── assets/                   # Images & Screenshots
│       ├── Logo.png
│       ├── First_Cover.jpg
│       └── Page [1-6].png
│
├── [Future Project 1]/
├── [Future Project 2]/
└── README.md                     # This file
```

---

## 📬 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://your-portfolio.com)

</div>

---

## 🙏 Acknowledgments

### Power BI 360 Course
Special thanks to **Luis Mosquera Toscano** and **Twelve powered by Objetivo Analista** for their exceptional instruction and methodology. The analytical approaches, DAX logic structures, and visualization techniques learned throughout the course were fundamental to achieving professional results.

### Data Sources
- Player names extracted from **Transfermarkt**
- Synthetic data generated using **Claude AI**
- Logo and branding: **FC Porto** official assets

---

## 📝 License

This repository is for **portfolio and educational purposes**.

- **Code & Techniques**: MIT License - Feel free to learn from and adapt the approaches used
- **Data**: Synthetic data (except player names from Transfermarkt)
- **Logos & Branding**: All rights reserved to their respective owners (FC Porto, Twelve)

---

## 📊 Repository Stats

![Last Updated](https://img.shields.io/badge/Last%20Updated-January%202025-blue?style=flat-square)
![Projects](https://img.shields.io/badge/Projects-1-green?style=flat-square)
![Language](https://img.shields.io/badge/Primary%20Language-DAX-orange?style=flat-square)

---

<div align="center">

### ⭐ If you find these projects useful, please consider giving this repository a star!

**Made with 📊 and Power BI**

</div>
