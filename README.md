## *⭐ Junwu0615-Analytics ⭐*
> _🧟‍♂️ Starting from July 6, 2026, this project will continuously record the entire project journey of Junwu0615._ 
<!-- update_time:start -->
>
> _Generated at [ UTC+0 ] :　2026-07-16T17:48:56_

<!-- update_time:end -->

<br>

### *📌　Implement*

<details>
<summary><b><i>　Tree </i></b></summary>
<ul>

```bash
tree -I 'venv|.git|__pycache__|docs|logs|assets|kafka_data|charts'

.
├── LICENSE
├── README.md
├── config
│   ├── analytics.yml
│   └── repositories.yml
├── data
│   ├── latest
│   └── summary.json
├── history
│   ├── 2026-07.csv
│   ├── ....
│   └── 20xx-xx.csv
├── reports
│   ├── dashboard.md
│   ├── growth.md
│   ├── summary.md
│   ├── traffic.md
│   └── update_time.md
├── requirements.txt
└── scripts
    ├── collect.py
    ├── export_history.py
    ├── generate_report.py
    ├── sync_readme.py
    └── utils.py

```

</ul>
</details>

<details>
<summary><b><i>　Workflow </i></b></summary>
<ul>

```bash
# STAGE. 1
 • collect.py
      ↓
 • data/latest/*.json
   ( 最新快照 )


# STAGE. 2
 • export_history.py
      ↓
 • history/YYYY-MM-history.csv
   ( 每日快照累積 / 按月分區 )


# STAGE. 3
 • generate_report.py
      ↓
 • data/summary.json
   ( 所有 Repo 最新統計總覽 )
      ↓
 • dashboard.md ( 目前快照 )
 • traffic.md   ( 近 14 天流量 )
 • growth.md    ( 本月累積成長 )
 • summary.md   ( 總覽報表 )

# STAGE. 4
 • sync_readme.py
      ↓
 • README.md
   ( 所有 Report 渲染至首頁 )
```

</ul>
</details>

<br>

### *📋　Repository Summary Report*

<!-- summary:start -->
> _Note :　Metrics are aggregated across all tracked repositories._

| *📐 Metric* | *🧮 Value* |
|:--|--:|
| *📁 Total Repositories* | *49* |
| *⭐ Total Stars* | *70* |
| *🍴 Total Forks* | *4* |
| *📦 Size (MB)* | *241.68* |
| *👀 Total Views* | *1417* |
| *👤 Total Unique Visitors* | *158* |
| *📥 Total Clones* | *3557* |
| *👤 Total Unique Cloners* | *1437* |
<!-- summary:end -->

<br>

### *📊　Repository Dashboard*

<!-- dashboard:start -->

 | *📁 Repository* | *⭐ Stars* | *🍴 Forks* | *📦 Size (MB)* | *📝 Last Updated* | *📅 Creation Date* |
 |:--|--:|--:|--:|--:|--:|
 | *Activity-Tracker* | *2* | *0* | *0.01* | *2025-11-16* | *2025-11-10* |
 | *Airflow-E2E-DevEnv* | *1* | *0* | *7.38* | *2026-03-25* | *2025-10-26* |
 | *Airflow-Template* | *1* | *0* | *0.54* | *2025-09-25* | *2025-01-17* |
 | *Ansible-Deploy-To-Edge* | *1* | *0* | *0.52* | *2025-09-29* | *2025-09-29* |
 | *CAED* | *1* | *0* | *3.01* | *2025-02-16* | *2025-01-13* |
 | *Cloudflare-Dockerization* | *1* | *0* | *0.19* | *2025-02-02* | *2025-02-01* |
 | *Crawler-Keywords-And-Use-LineBot* | *1* | *0* | *1.04* | *2024-12-29* | *2023-12-19* |
 | *Database-Template* | *1* | *0* | *2.60* | *2025-09-26* | *2024-12-25* |
 | *Docker-Registry-Server* | *1* | *0* | *0.05* | *2025-09-29* | *2025-09-29* |
 | *Downloads-YouTube-To-MP3-4* | *3* | *0* | *0.35* | *2024-12-29* | *2024-01-02* |
 | *Forex-Get-Quotes* | *3* | *0* | *1.58* | *2025-09-26* | *2024-09-11* |
 | *github-readme-terminal* | *1* | *0* | *0.23* | *2024-11-08* | *2025-02-16* |
 | *How-To-Use-Clone-Shields* | *2* | *0* | *0.51* | *2024-11-24* | *2023-12-28* |
 | *Junwu0615* | *1* | *0* | *7.53* | *2026-07-16* | *2023-12-26* |
 | *Junwu0615-Analytics* | *1* | *0* | *0.19* | *2026-07-15* | *2026-07-06* |
 | *Junwu0615.github.io* | *1* | *0* | *0.00* | *2024-01-28* | *2024-01-27* |
 | *Latency-Throughput-Simulation-Test* | *1* | *0* | *6.04* | *2025-10-15* | *2025-10-02* |
 | *LCII-Rec-Model* | *2* | *0* | *1.16* | *2024-12-29* | *2023-12-08* |
 | *LeetCode-Practice-Record* | *1* | *0* | *0.05* | *2025-11-24* | *2025-02-02* |
 | *LeetCode-Record-Sharing-Method* | *1* | *0* | *95.90* | *2024-12-29* | *2024-01-26* |
 | *My-English-Learning-Journey* | *1* | *0* | *0.04* | *2026-03-09* | *2026-03-04* |
 | *My-Win-Apps* | *1* | *0* | *4.20* | *2026-07-16* | *2026-07-12* |
 | *NGROK-Dockerization* | *1* | *0* | *0.12* | *2025-01-24* | *2025-01-24* |
 | *NVDA-Price-Stock-Prediction* | *1* | *0* | *1.23* | *2024-12-29* | *2024-02-25* |
 | *One-Click-Database-Deployment* | *1* | *0* | *0.53* | *2025-09-26* | *2025-02-27* |
 | *Other* | *1* | *0* | *0.45* | *2025-02-12* | *2023-12-08* |
 | *Parsing-Media-From-JVID* | *8* | *3* | *0.42* | *2025-11-14* | *2024-12-15* |
 | *Parsing-Media-From-PornHub* | *3* | *1* | *0.34* | *2024-12-29* | *2024-12-18* |
 | *PC-Activity-Tracker* | *1* | *0* | *0.27* | *2026-07-16* | *2025-11-16* |
 | *PC-Bot-With-GenAI* | *4* | *0* | *7.30* | *2026-04-14* | *2025-01-07* |
 | *PG-Airflow-DAGs* | *1* | *0* | *0.06* | *2026-06-22* | *2026-05-08* |
 | *PG-Analytics* | *1* | *0* | *0.22* | *2026-07-16* | *2026-07-03* |
 | *PG-APP-Core* | *1* | *0* | *0.10* | *2026-07-12* | *2026-05-08* |
 | *PG-Core* | *1* | *0* | *2.82* | *2026-07-12* | *2026-07-03* |
 | *PG-Cortex* | *1* | *0* | *0.01* | *2026-07-05* | *2026-07-03* |
 | *PG-Edge-Container* | *1* | *0* | *0.03* | *2026-06-22* | *2026-05-08* |
 | *PG-Infrastructure* | *1* | *0* | *5.11* | *2026-07-10* | *2026-05-08* |
 | *PG-Sentinel* | *1* | *0* | *0.00* | *2026-07-05* | *2026-07-03* |
 | *PG-Shared-Lib* | *1* | *0* | *0.05* | *2026-06-22* | *2026-05-08* |
 | *PG-Synapse* | *1* | *0* | *0.00* | *2026-07-05* | *2026-07-03* |
 | *Platform-Genesis* | *2* | *0* | *48.88* | *2026-07-12* | *2026-03-20* |
 | *RAG-With-LangChain-And-FAISS* | *1* | *0* | *0.18* | *2025-10-15* | *2025-02-27* |
 | *RESTful-API-FastAPI* | *1* | *0* | *0.68* | *2025-02-20* | *2025-02-02* |
 | *ROI-Tool* | *1* | *0* | *13.68* | *2024-12-29* | *2022-05-21* |
 | *The-First-PHP-Login-System* | *2* | *0* | *0.74* | *2024-11-24* | *2024-01-04* |
 | *Using-Streamlit-Create-Dashboard* | *1* | *0* | *17.28* | *2025-10-30* | *2025-01-04* |
 | *Web-Crawler-Download-Img* | *1* | *0* | *6.49* | *2024-12-29* | *2023-12-08* |
 | *Web-Crawler-FamilyMart-Shop* | *1* | *0* | *1.46* | *2025-01-03* | *2025-01-01* |
 | *Web-Crawler-News* | *1* | *0* | *0.11* | *2024-12-29* | *2023-12-10* |
<!-- dashboard:end -->

<br>

### *🔍　Traffic Analytics*

<!-- traffic:start -->
> _Traffic in the past **14 Days**_

| *📁 Repository* | *👀 Views* | *👤 Views Unique* | *📥 Clones* | *👤 Clones Unique* |
|:--|--:|--:|--:|--:|
| *Activity-Tracker* | *0* | *0* | *1* | *1* |
| *Airflow-E2E-DevEnv* | *10* | *3* | *4* | *4* |
| *Airflow-Template* | *0* | *0* | *1* | *1* |
| *Ansible-Deploy-To-Edge* | *0* | *0* | *1* | *1* |
| *CAED* | *0* | *0* | *1* | *1* |
| *Cloudflare-Dockerization* | *0* | *0* | *2* | *1* |
| *Crawler-Keywords-And-Use-LineBot* | *0* | *0* | *1* | *1* |
| *Database-Template* | *1* | *1* | *0* | *0* |
| *Docker-Registry-Server* | *1* | *1* | *0* | *0* |
| *Downloads-YouTube-To-MP3-4* | *20* | *14* | *1* | *1* |
| *Forex-Get-Quotes* | *2* | *1* | *0* | *0* |
| *github-readme-terminal* | *0* | *0* | *1* | *1* |
| *How-To-Use-Clone-Shields* | *22* | *1* | *1* | *1* |
| *Junwu0615* | *25* | *3* | *401* | *143* |
| *Junwu0615-Analytics* | *39* | *4* | *121* | *70* |
| *Junwu0615.github.io* | *0* | *0* | *1* | *1* |
| *Latency-Throughput-Simulation-Test* | *0* | *0* | *1* | *1* |
| *LCII-Rec-Model* | *0* | *0* | *2* | *1* |
| *LeetCode-Practice-Record* | *0* | *0* | *1* | *1* |
| *LeetCode-Record-Sharing-Method* | *1* | *1* | *0* | *0* |
| *My-English-Learning-Journey* | *0* | *0* | *3* | *3* |
| *My-Win-Apps* | *208* | *6* | *380* | *163* |
| *NGROK-Dockerization* | *0* | *0* | *1* | *1* |
| *NVDA-Price-Stock-Prediction* | *1* | *1* | *0* | *0* |
| *One-Click-Database-Deployment* | *0* | *0* | *1* | *1* |
| *Other* | *0* | *0* | *2* | *1* |
| *Parsing-Media-From-JVID* | *162* | *82* | *6* | *6* |
| *Parsing-Media-From-PornHub* | *1* | *1* | *1* | *1* |
| *PC-Activity-Tracker* | *0* | *0* | *405* | *148* |
| *PC-Bot-With-GenAI* | *8* | *3* | *2* | *2* |
| *PG-Airflow-DAGs* | *11* | *2* | *5* | *5* |
| *PG-Analytics* | *346* | *3* | *1007* | *330* |
| *PG-APP-Core* | *28* | *2* | *98* | *53* |
| *PG-Core* | *94* | *3* | *328* | *137* |
| *PG-Cortex* | *32* | *2* | *50* | *33* |
| *PG-Edge-Container* | *10* | *1* | *6* | *4* |
| *PG-Infrastructure* | *75* | *3* | *209* | *78* |
| *PG-Sentinel* | *26* | *2* | *40* | *32* |
| *PG-Shared-Lib* | *16* | *3* | *8* | *4* |
| *PG-Synapse* | *29* | *3* | *55* | *37* |
| *Platform-Genesis* | *243* | *9* | *401* | *161* |
| *RAG-With-LangChain-And-FAISS* | *0* | *0* | *1* | *1* |
| *RESTful-API-FastAPI* | *0* | *0* | *2* | *1* |
| *ROI-Tool* | *0* | *0* | *1* | *1* |
| *The-First-PHP-Login-System* | *0* | *0* | *1* | *1* |
| *Using-Streamlit-Create-Dashboard* | *5* | *2* | *1* | *1* |
| *Web-Crawler-Download-Img* | *1* | *1* | *0* | *0* |
| *Web-Crawler-FamilyMart-Shop* | *0* | *0* | *1* | *1* |
| *Web-Crawler-News* | *0* | *0* | *1* | *1* |
- ### *Summary*
  - *👀 Views :　1417*
  - *👤 Unique Visitors :　158*
  - *📥 Clones :　3557*
  - *👤 Unique Cloners :　1437*
<!-- traffic:end -->

<br>

### *📈　Monthly Growth Analytics*

<!-- growth:start -->
> _Statistical Scope :　**2026-07**_

| *📁<br>Repository* | *⭐<br>Stars ↕* | *🍴<br>Forks ↕* | *💡<br>Open Issues ↕* | *👀<br>Views ↕<br>( 14 Days )* | *📥<br>Clones ↕<br>( 14 Days )* |
|:--|:--:|:--:|:--:|:--:|:--:|
| *Activity-Tracker* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *Airflow-E2E-DevEnv* | *+0* | *+0* | *+0* |*+1* | *-8* | 
| *Airflow-Template* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Ansible-Deploy-To-Edge* | *+0* | *+0* | *+0* |*-2* | *+0* | 
| *CAED* | *+0* | *+0* | *+0* |*+0* | *-5* | 
| *Cloudflare-Dockerization* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *Crawler-Keywords-And-Use-LineBot* | *+0* | *+0* | *+0* |*-2* | *-4* | 
| *Database-Template* | *+0* | *+0* | *+0* |*+2* | *-2* | 
| *Docker-Registry-Server* | *+0* | *+0* | *+0* |*+2* | *-2* | 
| *Downloads-YouTube-To-MP3-4* | *+0* | *+0* | *+0* |*-1* | *+0* | 
| *Forex-Get-Quotes* | *+0* | *+0* | *+0* |*+1* | *-2* | 
| *github-readme-terminal* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *How-To-Use-Clone-Shields* | *+0* | *+0* | *+0* |*+0* | *-4* | 
| *Junwu0615* | *+0* | *+0* | *+0* |*+15* | *-142* | 
| *Junwu0615-Analytics* | *+0* | *+0* | *+0* |*+43* | *+191* | 
| *Junwu0615.github.io* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Latency-Throughput-Simulation-Test* | *+0* | *+0* | *+0* |*+0* | *-4* | 
| *LCII-Rec-Model* | *+0* | *+0* | *+0* |*+0* | *+1* | 
| *LeetCode-Practice-Record* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *LeetCode-Record-Sharing-Method* | *+0* | *+0* | *+0* |*+2* | *-4* | 
| *My-English-Learning-Journey* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *My-Win-Apps* | *+0* | *+0* | *+0* |*+117* | *+218* | 
| *NGROK-Dockerization* | *+0* | *+0* | *+0* |*-2* | *-7* | 
| *NVDA-Price-Stock-Prediction* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *One-Click-Database-Deployment* | *+0* | *+0* | *+0* |*-3* | *-4* | 
| *Other* | *+0* | *+0* | *+0* |*-2* | *-2* | 
| *Parsing-Media-From-JVID* | *+0* | *+0* | *+0* |*-165* | *-2* | 
| *Parsing-Media-From-PornHub* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *PC-Activity-Tracker* | *+0* | *+0* | *+0* |*-4* | *-220* | 
| *PC-Bot-With-GenAI* | *+0* | *+0* | *+0* |*+5* | *-14* | 
| *PG-Airflow-DAGs* | *+0* | *+0* | *+0* |*-6* | *-6* | 
| *PG-Analytics* | *+0* | *+0* | *+0* |*+14* | *+163* | 
| *PG-APP-Core* | *+0* | *+0* | *+0* |*+1* | *+68* | 
| *PG-Core* | *+0* | *+0* | *+0* |*+34* | *+87* | 
| *PG-Cortex* | *+0* | *+0* | *+0* |*+2* | *+18* | 
| *PG-Edge-Container* | *+0* | *+0* | *+0* |*-3* | *-22* | 
| *PG-Infrastructure* | *+0* | *+0* | *+0* |*+7* | *+43* | 
| *PG-Sentinel* | *+0* | *+0* | *+0* |*+2* | *+17* | 
| *PG-Shared-Lib* | *+0* | *+0* | *+0* |*-3* | *-27* | 
| *PG-Synapse* | *+0* | *+0* | *+0* |*+4* | *+15* | 
| *Platform-Genesis* | *+0* | *+0* | *+0* |*-121* | *-367* | 
| *RAG-With-LangChain-And-FAISS* | *+0* | *+0* | *+0* |*-11* | *-5* | 
| *RESTful-API-FastAPI* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *ROI-Tool* | *+0* | *+0* | *+0* |*+0* | *-2* | 
| *The-First-PHP-Login-System* | *+0* | *+0* | *+0* |*-4* | *+0* | 
| *Using-Streamlit-Create-Dashboard* | *+0* | *+0* | *+0* |*+7* | *-2* | 
| *Web-Crawler-Download-Img* | *+0* | *+0* | *+0* |*+2* | *-4* | 
| *Web-Crawler-FamilyMart-Shop* | *+0* | *+0* | *+0* |*+0* | *-5* | 
| *Web-Crawler-News* | *+0* | *+0* | *+0* |*-2* | *-2* | 
<!-- growth:end -->


<br><br><br>