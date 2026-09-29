<!-- ===================================================== -->
<!--  HEADER                                                -->
<!--  Replace every YOUR_USERNAME with your GitHub username -->
<!-- ===================================================== -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,55:1B2838,100:F2C811&height=220&section=header&text=Matheus%20Arag%C3%A3o%20Cavalcante&fontSize=42&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=Senior%20BI%20Developer%20%E2%80%A2%20Data%20Engineer&descSize=18&descAlignY=56" width="100%" alt="Header" />

<a href="https://github.com/DenverCoder1/readme-typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=F2C811&center=true&vCenter=true&width=720&lines=Senior+BI+Developer+%26+Data+Engineer;Fragmented+data+%E2%86%92+scalable+data+products;Microsoft+Fabric+%E2%80%A2+Power+BI+%E2%80%A2+PySpark+%E2%80%A2+SQL;Bronze+%E2%86%92+Silver+%E2%86%92+Gold+%E2%86%92+Business+Impact" alt="Typing SVG" />
</a>

<br/>

<a href="https://linkedin.com/in/matheus2002ac"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://portfolio-matheuss.netlify.app"><img src="https://img.shields.io/badge/Portfolio-F2C811?style=for-the-badge&logo=netlify&logoColor=black" alt="Portfolio"/></a>
<a href="mailto:matheus2002ac@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=F2C811&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

---

## ⚡ About Me

I build the bridge between **raw operational data** and **executive decisions**.

With **4+ years** of experience across the public sector, higher education, and legislative operations, I turn fragmented data, disconnected systems, and manual workflows into **scalable data products, analytical applications, and decision-support solutions**. I design lakehouse architectures, ETL/ELT pipelines, and semantic models, and when a dashboard isn't enough, I build **React / Next.js applications** that put insights directly into business users' hands.

```sql
-- whoami.sql  |  Microsoft Fabric Warehouse
SELECT
    'Matheus Aragão Cavalcante'                            AS name,
    'Senior BI Developer & Data Engineer'                  AS role,
    'Lakehouse · ETL/ELT · Semantic Models · BI Apps'      AS focus,
    'Postgraduate in Data Engineering & AI (Xperiun)'      AS currently_learning,
    'English (full professional) · Portuguese (native)'    AS languages,
    'Remote & international opportunities'                 AS open_to
FROM   career.gold_layer
WHERE  business_impact > 0
  AND  manual_work     = 0;
```

---

## 📊 Impact at a Glance

<div align="center">

| | | | |
|:---:|:---:|:---:|:---:|
| <img src="https://img.shields.io/badge/%E2%86%93%2080%25-Reporting%20Effort-F2C811?style=for-the-badge&labelColor=0D1117" /> | <img src="https://img.shields.io/badge/10%2B-Data%20Sources%20Unified-F2C811?style=for-the-badge&labelColor=0D1117" /> | <img src="https://img.shields.io/badge/14-Stakeholder%20Groups-F2C811?style=for-the-badge&labelColor=0D1117" /> | <img src="https://img.shields.io/badge/23-Initiatives%20Monitored-F2C811?style=for-the-badge&labelColor=0D1117" /> |
| <img src="https://img.shields.io/badge/%E2%86%93%2060%25-Manual%20Process%20Steps-3FB950?style=for-the-badge&labelColor=0D1117" /> | <img src="https://img.shields.io/badge/%E2%86%91%2090%25-Timekeeping%20Accuracy-3FB950?style=for-the-badge&labelColor=0D1117" /> | <img src="https://img.shields.io/badge/2h%20daily-Manual%20Work%20Eliminated-3FB950?style=for-the-badge&labelColor=0D1117" /> | <img src="https://img.shields.io/badge/%E2%86%93%2040%25-Info%20Bottlenecks-3FB950?style=for-the-badge&labelColor=0D1117" /> |

</div>

---

## 🔄 Pipeline Running in Production

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=1800&pause=600&color=3FB950&background=0D1117&multiline=true&repeat=true&width=760&height=230&lines=%24+python+run_pipeline.py+--layer+all;%5BEXTRACT%5D+10%2B+sources+%E2%80%94+APIs%2C+Apps+Script%2C+Azure%2C+Sheets+%E2%9C%93;%5BBRONZE%5D++raw+data+landed+in+Delta+tables+%E2%9C%93;%5BSILVER%5D++PySpark+cleansing+%26+conformance+%E2%9C%93;%5BGOLD%5D++++governed+semantic+models+published+%E2%9C%93;%5BSERVE%5D+++Power+BI+%2B+Next.js+apps+refreshed+%E2%9C%93;%3E%3E+Pipeline+succeeded+%7C+reporting+effort+-80%25" alt="Pipeline terminal animation" />

</div>

<!-- ============ DASHBOARD SHOWCASE (optional) ============
     Record a short GIF of one of your own dashboards (anonymized),
     save it as assets/dashboard-demo.gif in this repo and uncomment:

<div align="center">
  <img src="./assets/dashboard-demo.gif" width="85%" alt="Power BI dashboard demo" />
  <br/><sub>Power BI executive dashboard — sample data</sub>
</div>
========================================================= -->

---

## 🚀 Featured Projects

### 🏗️ Enterprise Lakehouse Analytics Platform

End-to-end **Microsoft Fabric** cloud data platform that integrates **10+ heterogeneous sources** through REST APIs, Apps Script endpoints, Azure APIs, and spreadsheets, processing data with **PySpark** and **SQL** across a **Medallion Architecture** to deliver governed, analysis-ready datasets.

- 📉 **80% reduction** in recurring reporting time
- 🧱 Bronze → Silver → Gold layers with standardized ingestion and modeling
- 🗺️ Serves Power BI semantic models, APIs, and GeoJSON-based geospatial apps

```mermaid
flowchart LR
    subgraph SRC["📥 Sources"]
        A1["REST APIs"]
        A2["Apps Script Endpoints"]
        A3["Azure APIs"]
        A4["Spreadsheets"]
    end

    subgraph LH["🏗️ Microsoft Fabric Lakehouse"]
        B[("🥉 Bronze<br/>Raw ingestion")]
        S[("🥈 Silver<br/>Cleansed & conformed")]
        G[("🥇 Gold<br/>Business-ready models")]
    end

    subgraph SERVE["📊 Serving Layer"]
        P["Power BI<br/>Semantic Models"]
        W["React / Next.js<br/>Apps & APIs"]
        GEO["GeoJSON<br/>Geospatial Apps"]
    end

    SRC -->|"Pipelines · Notebooks"| B
    B -->|"PySpark"| S
    S -->|"SQL · Modeling"| G
    G --> P
    G --> W
    G --> GEO

    classDef bronze fill:#CD7F32,stroke:#8B5A2B,color:#ffffff
    classDef silver fill:#C0C0C0,stroke:#808080,color:#000000
    classDef gold fill:#F2C811,stroke:#B8960C,color:#000000
    classDef serve fill:#0D1117,stroke:#F2C811,color:#ffffff
    class B bronze
    class S silver
    class G gold
    class P,W,GEO serve
```

<img src="https://img.shields.io/badge/Microsoft%20Fabric-117865?style=flat-square" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-336791?style=flat-square" /> <img src="https://img.shields.io/badge/REST%20APIs-0D1117?style=flat-square" /> <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square" />

<!-- Add the repository link here when public -->

---

### 🤖 BI Reporting Automation — n8n, APIs & Power BI

Automated BI workflow connecting **APIs, webhooks, spreadsheets, notification channels, and Power BI datasets**, integrated with **GitLab CI/CD** build pipelines, turning a manual refresh-validate-communicate cycle into a hands-off process.

- ⚙️ **60% fewer** refresh, validation, and communication steps
- 🔔 Stakeholders notified automatically when data is ready
- 🧪 Validation gates before every dataset refresh

```mermaid
flowchart LR
    T["⏱️ Schedule / Webhook"] --> N{{"⚙️ n8n Workflow"}}
    A["🌐 REST APIs"] --> N
    X["📄 Spreadsheets"] --> N
    N --> V["✅ Data Validation"]
    V --> R["📊 Power BI Dataset Refresh"]
    R --> M["🔔 Stakeholder Notifications"]
    CI["🦊 GitLab CI/CD"] -.-> N
```

<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/Webhooks-0D1117?style=flat-square" /> <img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />

---

### 🖥️ Analytical Platform with Data Pipeline

**TypeScript** analytical web platform that integrates REST API data, embedded dashboards, KPI cards, and interactive analytical pages, taking insights **beyond traditional dashboard delivery** and into purpose-built tools for business users.

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/REST%20APIs-0D1117?style=flat-square" />

<p align="left">
  <a href="https://portfolio-matheuss.netlify.app"><img src="https://img.shields.io/badge/See%20all%20case%20studies-%E2%86%92%20Portfolio-F2C811?style=for-the-badge&labelColor=0D1117" /></a>
</p>

---

## 🛠️ Tech Stack

**📊 BI & Analytics**

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&labelColor=0D1117" /> <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge" /> <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" /> <img src="https://img.shields.io/badge/Data%20Modeling-0D1117?style=for-the-badge" />

**⚙️ Data Engineering & Cloud**

<img src="https://img.shields.io/badge/Microsoft%20Fabric-117865?style=for-the-badge" /> <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge" /> <img src="https://img.shields.io/badge/ETL%20%2F%20ELT-0D1117?style=for-the-badge" /> <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />

**🗄️ Languages & Databases**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />

**🤖 Automation & Integration**

<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" /> <img src="https://img.shields.io/badge/REST%20APIs-0D1117?style=for-the-badge" /> <img src="https://img.shields.io/badge/Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white" /> <img src="https://img.shields.io/badge/Webhooks-0D1117?style=for-the-badge" />

**💻 Analytical Apps & DevOps**

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/GeoJSON-0D1117?style=for-the-badge" /> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />

---

## 💼 Experience

| Role | Organization | Period | Focus |
|:---|:---|:---:|:---|
| **Senior Data Analyst** | City Hall of Fortaleza | 08/2025 – Present | End-to-end data & geospatial analytics ecosystem · Microsoft Fabric · 10+ sources · React / Next.js BI apps |
| **Administrative Process Analyst — BI & Analytics** | Unichristus | 12/2024 – 08/2025 | BI for Finance, HR & Sales · Python / Apps Script automation · TOTVS integrations |
| **Data Analyst** | ALECE — Ceará Legislative Assembly | 04/2024 – 11/2024 | Operational dashboards · Power BI · KPI reporting workflows |

---

## 🎓 Education & Certifications

- 🎓 **Postgraduate Program in Data Engineering and AI** — Xperiun *(2026 – Present)*
- 🎓 **Technologist Degree in Systems Analysis and Development** — Descomplica *(2024 – 2026)*
- 🎓 **Residency Program in Full Stack Development** — State University of Ceará *(2024 – 2025)*
- 🎓 **Bachelor's Degree in Business Administration** — Federal University of Ceará *(2021 – 2025)*

**Certifications:** Lakehouse with Microsoft Fabric (Microsoft) · Databricks with Spark (Xperiun) · Cloud Data Engineering (Xperiun) · Data Engineering on Google Cloud Platform (Coursera) · Google Data Analytics Specialization (Google)

---

## 📈 GitHub Analytics Dashboard

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=F2C811&icon_color=F2C811&text_color=C9D1D9&rank_icon=github" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=F2C811&text_color=C9D1D9" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&hide_border=true&background=0D1117&ring=F2C811&fire=F2C811&currStreakLabel=F2C811&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E&stroke=30363D" alt="GitHub streak" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=0D1117&color=C9D1D9&line=F2C811&point=FFFFFF&area=true&area_color=F2C811&hide_border=true&custom_title=Contribution%20Trend%20%28Last%2031%20Days%29" alt="Contribution activity graph" />

<!-- Requires the snake GitHub Action (see setup instructions) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake-dark.svg" />
</picture>

</div>

---

## 🤝 Let's Connect

I'm open to **remote and international opportunities** in BI Development, Analytics Engineering, and Data Engineering. If your team needs someone who can own the full path, **from raw source to business decision**, let's talk.

<div align="center">

<a href="https://linkedin.com/in/matheus2002ac"><img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://portfolio-matheuss.netlify.app"><img src="https://img.shields.io/badge/Explore%20my-Portfolio-F2C811?style=for-the-badge&logo=netlify&logoColor=black&labelColor=0D1117" alt="Portfolio"/></a>
<a href="mailto:matheus2002ac@gmail.com"><img src="https://img.shields.io/badge/Send%20an-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F2C811,45:1B2838,100:0D1117&height=120&section=footer" width="100%" alt="Footer" />

</div>
