## *⭐ Junwu0615-Analytics ⭐*
> _🧟‍♂️ Starting from July 6, 2026, this project will continuously record the entire project journey of Junwu0615._ 
<!-- update_time:start -->
>
> _Generated at [ UTC+0 ] :　2026-07-06T14:12:04_

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
| *📁 Total Repositories* | *48* |
| *⭐ Total Stars* | *69* |
| *🍴 Total Forks* | *4* |
| *📦 Size (MB)* | *235.02* |
| *👀 Total Views* | *1347* |
| *👤 Total Unique Visitors* | *201* |
| *📥 Total Clones* | *3399* |
| *👤 Total Unique Cloners* | *1331* |
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
 | *Junwu0615* | *1* | *0* | *7.35* | *2026-07-06* | *2023-12-26* |
 | *Junwu0615-Analytics* | *1* | *0* | *0.00* | *2026-07-06* | *2026-07-06* |
 | *Junwu0615.github.io* | *1* | *0* | *0.00* | *2024-01-28* | *2024-01-27* |
 | *Latency-Throughput-Simulation-Test* | *1* | *0* | *6.04* | *2025-10-15* | *2025-10-02* |
 | *LCII-Rec-Model* | *2* | *0* | *1.16* | *2024-12-29* | *2023-12-08* |
 | *LeetCode-Practice-Record* | *1* | *0* | *0.05* | *2025-11-24* | *2025-02-02* |
 | *LeetCode-Record-Sharing-Method* | *1* | *0* | *95.90* | *2024-12-29* | *2024-01-26* |
 | *My-English-Learning-Journey* | *1* | *0* | *0.04* | *2026-03-09* | *2026-03-04* |
 | *NGROK-Dockerization* | *1* | *0* | *0.12* | *2025-01-24* | *2025-01-24* |
 | *NVDA-Price-Stock-Prediction* | *1* | *0* | *1.23* | *2024-12-29* | *2024-02-25* |
 | *One-Click-Database-Deployment* | *1* | *0* | *0.53* | *2025-09-26* | *2025-02-27* |
 | *Other* | *1* | *0* | *0.45* | *2025-02-12* | *2023-12-08* |
 | *Parsing-Media-From-JVID* | *8* | *3* | *0.42* | *2025-11-14* | *2024-12-15* |
 | *Parsing-Media-From-PornHub* | *3* | *1* | *0.34* | *2024-12-29* | *2024-12-18* |
 | *PC-Activity-Tracker* | *1* | *0* | *0.26* | *2026-07-06* | *2025-11-16* |
 | *PC-Bot-With-GenAI* | *4* | *0* | *7.30* | *2026-04-14* | *2025-01-07* |
 | *PG-Airflow-DAGs* | *1* | *0* | *0.06* | *2026-06-22* | *2026-05-08* |
 | *PG-Analytics* | *1* | *0* | *0.17* | *2026-07-06* | *2026-07-03* |
 | *PG-APP-Core* | *1* | *0* | *0.14* | *2026-07-05* | *2026-05-08* |
 | *PG-Core* | *1* | *0* | *2.05* | *2026-07-06* | *2026-07-03* |
 | *PG-Cortex* | *1* | *0* | *0.01* | *2026-07-05* | *2026-07-03* |
 | *PG-Edge-Container* | *1* | *0* | *0.03* | *2026-06-22* | *2026-05-08* |
 | *PG-Infrastructure* | *1* | *0* | *5.06* | *2026-07-05* | *2026-05-08* |
 | *PG-Sentinel* | *1* | *0* | *0.00* | *2026-07-05* | *2026-07-03* |
 | *PG-Shared-Lib* | *1* | *0* | *0.05* | *2026-06-22* | *2026-05-08* |
 | *PG-Synapse* | *1* | *0* | *0.00* | *2026-07-05* | *2026-07-03* |
 | *Platform-Genesis* | *2* | *0* | *47.63* | *2026-07-06* | *2026-03-20* |
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
| *Activity-Tracker* | *0* | *0* | *2* | *2* |
| *Airflow-E2E-DevEnv* | *9* | *3* | *9* | *7* |
| *Airflow-Template* | *0* | *0* | *1* | *1* |
| *Ansible-Deploy-To-Edge* | *1* | *1* | *1* | *1* |
| *CAED* | *0* | *0* | *4* | *3* |
| *Cloudflare-Dockerization* | *0* | *0* | *3* | *2* |
| *Crawler-Keywords-And-Use-LineBot* | *1* | *1* | *3* | *3* |
| *Database-Template* | *0* | *0* | *1* | *1* |
| *Docker-Registry-Server* | *0* | *0* | *1* | *1* |
| *Downloads-YouTube-To-MP3-4* | *21* | *14* | *1* | *1* |
| *Forex-Get-Quotes* | *1* | *1* | *1* | *1* |
| *github-readme-terminal* | *0* | *0* | *2* | *2* |
| *How-To-Use-Clone-Shields* | *22* | *1* | *3* | *3* |
| *Junwu0615* | *11* | *2* | *510* | *176* |
| *Junwu0615-Analytics* | *0* | *0* | *0* | *0* |
| *Junwu0615.github.io* | *0* | *0* | *1* | *1* |
| *Latency-Throughput-Simulation-Test* | *0* | *0* | *3* | *3* |
| *LCII-Rec-Model* | *0* | *0* | *1* | *1* |
| *LeetCode-Practice-Record* | *0* | *0* | *1* | *1* |
| *LeetCode-Record-Sharing-Method* | *0* | *0* | *2* | *2* |
| *My-English-Learning-Journey* | *0* | *0* | *4* | *4* |
| *NGROK-Dockerization* | *1* | *1* | *5* | *4* |
| *NVDA-Price-Stock-Prediction* | *1* | *1* | *1* | *1* |
| *One-Click-Database-Deployment* | *2* | *1* | *3* | *3* |
| *Other* | *1* | *1* | *3* | *2* |
| *Parsing-Media-From-JVID* | *290* | *119* | *7* | *7* |
| *Parsing-Media-From-PornHub* | *1* | *1* | *2* | *2* |
| *PC-Activity-Tracker* | *3* | *1* | *573* | *200* |
| *PC-Bot-With-GenAI* | *4* | *2* | *12* | *6* |
| *PG-Airflow-DAGs* | *16* | *3* | *8* | *8* |
| *PG-Analytics* | *333* | *2* | *886* | *288* |
| *PG-APP-Core* | *26* | *3* | *53* | *30* |
| *PG-Core* | *62* | *1* | *268* | *110* |
| *PG-Cortex* | *30* | *2* | *40* | *25* |
| *PG-Edge-Container* | *13* | *1* | *18* | *14* |
| *PG-Infrastructure* | *67* | *4* | *172* | *72* |
| *PG-Sentinel* | *24* | *2* | *31* | *24* |
| *PG-Shared-Lib* | *19* | *3* | *24* | *15* |
| *PG-Synapse* | *25* | *3* | *47* | *30* |
| *Platform-Genesis* | *352* | *21* | *672* | *257* |
| *RAG-With-LangChain-And-FAISS* | *8* | *3* | *4* | *3* |
| *RESTful-API-FastAPI* | *0* | *0* | *3* | *2* |
| *ROI-Tool* | *0* | *0* | *2* | *2* |
| *The-First-PHP-Login-System* | *2* | *2* | *1* | *1* |
| *Using-Streamlit-Create-Dashboard* | *0* | *0* | *2* | *2* |
| *Web-Crawler-Download-Img* | *0* | *0* | *2* | *2* |
| *Web-Crawler-FamilyMart-Shop* | *0* | *0* | *4* | *3* |
| *Web-Crawler-News* | *1* | *1* | *2* | *2* |
- ### *Summary*
  - *👀 Views :　1347*
  - *👤 Unique Visitors :　201*
  - *📥 Clones :　3399*
  - *👤 Unique Cloners :　1331*
<!-- traffic:end -->

<br>

### *📈　Monthly Growth Analytics*

<!-- growth:start -->
> _Statistical Scope :　**2026-07**_

| *📁<br>Repository* | *⭐<br>Stars ↕* | *🍴<br>Forks ↕* | *💡<br>Open Issues ↕* | *👀<br>Views ↕<br>( 14 Days )* | *📥<br>Clones ↕<br>( 14 Days )* |
|:--|--:|--:|--:|--:|--:|
| *Activity-Tracker* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Airflow-E2E-DevEnv* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Airflow-Template* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Ansible-Deploy-To-Edge* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *CAED* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Cloudflare-Dockerization* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Crawler-Keywords-And-Use-LineBot* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Database-Template* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Docker-Registry-Server* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Downloads-YouTube-To-MP3-4* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Forex-Get-Quotes* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *github-readme-terminal* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *How-To-Use-Clone-Shields* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Junwu0615* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Junwu0615-Analytics* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Junwu0615.github.io* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Latency-Throughput-Simulation-Test* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *LCII-Rec-Model* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *LeetCode-Practice-Record* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *LeetCode-Record-Sharing-Method* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *My-English-Learning-Journey* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *NGROK-Dockerization* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *NVDA-Price-Stock-Prediction* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *One-Click-Database-Deployment* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Other* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Parsing-Media-From-JVID* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Parsing-Media-From-PornHub* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PC-Activity-Tracker* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PC-Bot-With-GenAI* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Airflow-DAGs* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Analytics* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-APP-Core* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Core* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Cortex* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Edge-Container* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Infrastructure* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Sentinel* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Shared-Lib* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *PG-Synapse* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Platform-Genesis* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *RAG-With-LangChain-And-FAISS* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *RESTful-API-FastAPI* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *ROI-Tool* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *The-First-PHP-Login-System* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Using-Streamlit-Create-Dashboard* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Web-Crawler-Download-Img* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Web-Crawler-FamilyMart-Shop* | *+0* | *+0* | *+0* |*+0* | *+0* | 
| *Web-Crawler-News* | *+0* | *+0* | *+0* |*+0* | *+0* | 
<!-- growth:end -->


<br><br><br>