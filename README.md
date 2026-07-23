## *⭐ Junwu0615-Analytics ⭐*
> _🧟‍♂️ Starting from July 23, 2026, this project will continuously record the entire project journey of Junwu0615._

<!-- update_time:start -->
>
> _Generated at [ UTC+0 ] :　2026-07-23T16:58:56_

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
| *⭐ Total Stars* | *71* |
| *🍴 Total Forks* | *4* |
| *📩 Total Commit* | *3858* |
| *📦 Size (MB)* | *254.02* |
| *👀 Total Views* | *1000* |
| *👤 Total Unique Visitors* | *151* |
| *📥 Total Clones* | *2102* |
| *👤 Total Unique Cloners* | *973* |
<!-- summary:end -->

<br>

### *📊　Repository Dashboard*

<!-- dashboard:start -->

 | *📁 Repository* | *⭐ Stars* | *🍴 Forks* | *📩 Commit* | *📦 Size<br>( MB )* | *📝 Updated* | *📅 Created* |
 |:--|--:|--:|--:|--:|--:|--:|
 | _**[Activity-Tracker](https://github.com/Junwu0615/Activity-Tracker)**_ | *2* | *0* | *42* | *0.01* | *2025-11-16* | *2025-11-10* |
 | _**[Airflow-E2E-DevEnv](https://github.com/Junwu0615/Airflow-E2E-DevEnv)**_ | *1* | *0* | *56* | *7.38* | *2026-03-25* | *2025-10-26* |
 | _**[Airflow-Template](https://github.com/Junwu0615/Airflow-Template)**_ | *1* | *0* | *13* | *0.54* | *2025-09-25* | *2025-01-17* |
 | _**[Ansible-Deploy-To-Edge](https://github.com/Junwu0615/Ansible-Deploy-To-Edge)**_ | *1* | *0* | *22* | *0.52* | *2025-09-29* | *2025-09-29* |
 | _**[CAED](https://github.com/Junwu0615/CAED)**_ | *1* | *0* | *92* | *3.01* | *2025-02-16* | *2025-01-13* |
 | _**[Cloudflare-Dockerization](https://github.com/Junwu0615/Cloudflare-Dockerization)**_ | *1* | *0* | *2* | *0.19* | *2025-02-02* | *2025-02-01* |
 | _**[Crawler-Keywords-And-Use-LineBot](https://github.com/Junwu0615/Crawler-Keywords-And-Use-LineBot)**_ | *1* | *0* | *10* | *1.04* | *2024-12-29* | *2023-12-19* |
 | _**[Database-Template](https://github.com/Junwu0615/Database-Template)**_ | *1* | *0* | *42* | *2.60* | *2025-09-26* | *2024-12-25* |
 | _**[Docker-Registry-Server](https://github.com/Junwu0615/Docker-Registry-Server)**_ | *1* | *0* | *6* | *0.05* | *2025-09-29* | *2025-09-29* |
 | _**[Downloads-YouTube-To-MP3-4](https://github.com/Junwu0615/Downloads-YouTube-To-MP3-4)**_ | *3* | *0* | *10* | *0.35* | *2024-12-29* | *2024-01-02* |
 | _**[Forex-Get-Quotes](https://github.com/Junwu0615/Forex-Get-Quotes)**_ | *3* | *0* | *23* | *1.58* | *2025-09-26* | *2024-09-11* |
 | _**[github-readme-terminal](https://github.com/Junwu0615/github-readme-terminal)**_ | *1* | *0* | *85* | *0.23* | *2024-11-08* | *2025-02-16* |
 | _**[How-To-Use-Clone-Shields](https://github.com/Junwu0615/How-To-Use-Clone-Shields)**_ | *2* | *0* | *8* | *0.51* | *2024-11-24* | *2023-12-28* |
 | _**[Junwu0615](https://github.com/Junwu0615/Junwu0615)**_ | *1* | *0* | *638* | *9.42* | *2026-07-23* | *2023-12-26* |
 | _**[Junwu0615-Analytics](https://github.com/Junwu0615/Junwu0615-Analytics)**_ | *1* | *0* | *32* | *0.30* | *2026-07-23* | *2026-07-06* |
 | _**[Junwu0615.github.io](https://github.com/Junwu0615/Junwu0615.github.io)**_ | *1* | *0* | *2* | *0.00* | *2024-01-28* | *2024-01-27* |
 | _**[Latency-Throughput-Simulation-Test](https://github.com/Junwu0615/Latency-Throughput-Simulation-Test)**_ | *1* | *0* | *46* | *6.04* | *2025-10-15* | *2025-10-02* |
 | _**[LCII-Rec-Model](https://github.com/Junwu0615/LCII-Rec-Model)**_ | *2* | *0* | *2* | *1.16* | *2024-12-29* | *2023-12-08* |
 | _**[LeetCode-Practice-Record](https://github.com/Junwu0615/LeetCode-Practice-Record)**_ | *1* | *0* | *60* | *0.05* | *2025-11-24* | *2025-02-02* |
 | _**[LeetCode-Record-Sharing-Method](https://github.com/Junwu0615/LeetCode-Record-Sharing-Method)**_ | *1* | *0* | *6* | *95.90* | *2024-12-29* | *2024-01-26* |
 | _**[My-English-Learning-Journey](https://github.com/Junwu0615/My-English-Learning-Journey)**_ | *1* | *0* | *23* | *0.04* | *2026-03-09* | *2026-03-04* |
 | _**[My-Win-Apps](https://github.com/Junwu0615/My-Win-Apps)**_ | *1* | *0* | *97* | *4.24* | *2026-07-18* | *2026-07-12* |
 | _**[NGROK-Dockerization](https://github.com/Junwu0615/NGROK-Dockerization)**_ | *1* | *0* | *2* | *0.12* | *2025-01-24* | *2025-01-24* |
 | _**[NVDA-Price-Stock-Prediction](https://github.com/Junwu0615/NVDA-Price-Stock-Prediction)**_ | *1* | *0* | *4* | *1.23* | *2024-12-29* | *2024-02-25* |
 | _**[One-Click-Database-Deployment](https://github.com/Junwu0615/One-Click-Database-Deployment)**_ | *1* | *0* | *17* | *0.53* | *2025-09-26* | *2025-02-27* |
 | _**[Other](https://github.com/Junwu0615/Other)**_ | *1* | *0* | *24* | *0.47* | *2026-07-20* | *2023-12-08* |
 | _**[Parsing-Media-From-JVID](https://github.com/Junwu0615/Parsing-Media-From-JVID)**_ | *8* | *3* | *9* | *0.42* | *2025-11-14* | *2024-12-15* |
 | _**[Parsing-Media-From-PornHub](https://github.com/Junwu0615/Parsing-Media-From-PornHub)**_ | *3* | *1* | *4* | *0.34* | *2024-12-29* | *2024-12-18* |
 | _**[PC-Activity-Tracker](https://github.com/Junwu0615/PC-Activity-Tracker)**_ | *1* | *0* | *1006* | *0.28* | *2026-07-23* | *2025-11-16* |
 | _**[PC-Bot-With-GenAI](https://github.com/Junwu0615/PC-Bot-With-GenAI)**_ | *4* | *0* | *28* | *7.30* | *2026-04-14* | *2025-01-07* |
 | _**[PG-Airflow-DAGs](https://github.com/Junwu0615/PG-Airflow-DAGs)**_ | *1* | *0* | *27* | *0.06* | *2026-06-22* | *2026-05-08* |
 | _**[PG-Analytics](https://github.com/Junwu0615/PG-Analytics)**_ | *1* | *0* | *180* | *0.25* | *2026-07-23* | *2026-07-03* |
 | _**[PG-APP-Core](https://github.com/Junwu0615/PG-APP-Core)**_ | *1* | *0* | *62* | *0.12* | *2026-07-22* | *2026-05-08* |
 | _**[PG-Core](https://github.com/Junwu0615/PG-Core)**_ | *1* | *0* | *52* | *6.60* | *2026-07-23* | *2026-07-03* |
 | _**[PG-Cortex](https://github.com/Junwu0615/PG-Cortex)**_ | *1* | *0* | *4* | *0.01* | *2026-07-05* | *2026-07-03* |
 | _**[PG-Edge-Container](https://github.com/Junwu0615/PG-Edge-Container)**_ | *1* | *0* | *24* | *0.03* | *2026-07-21* | *2026-05-08* |
 | _**[PG-Infrastructure](https://github.com/Junwu0615/PG-Infrastructure)**_ | *1* | *0* | *361* | *4.97* | *2026-07-22* | *2026-05-08* |
 | _**[PG-Sentinel](https://github.com/Junwu0615/PG-Sentinel)**_ | *1* | *0* | *2* | *0.00* | *2026-07-05* | *2026-07-03* |
 | _**[PG-Shared-Lib](https://github.com/Junwu0615/PG-Shared-Lib)**_ | *1* | *0* | *20* | *0.05* | *2026-07-21* | *2026-05-08* |
 | _**[PG-Synapse](https://github.com/Junwu0615/PG-Synapse)**_ | *1* | *0* | *2* | *0.00* | *2026-07-05* | *2026-07-03* |
 | _**[Platform-Genesis](https://github.com/Junwu0615/Platform-Genesis)**_ | *3* | *0* | *602* | *55.46* | *2026-07-23* | *2026-03-20* |
 | _**[RAG-With-LangChain-And-FAISS](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)**_ | *1* | *0* | *5* | *0.18* | *2025-10-15* | *2025-02-27* |
 | _**[RESTful-API-FastAPI](https://github.com/Junwu0615/RESTful-API-FastAPI)**_ | *1* | *0* | *2* | *0.68* | *2025-02-20* | *2025-02-02* |
 | _**[ROI-Tool](https://github.com/Junwu0615/ROI-Tool)**_ | *1* | *0* | *16* | *13.68* | *2024-12-29* | *2022-05-21* |
 | _**[The-First-PHP-Login-System](https://github.com/Junwu0615/The-First-PHP-Login-System)**_ | *2* | *0* | *9* | *0.74* | *2024-11-24* | *2024-01-04* |
 | _**[Using-Streamlit-Create-Dashboard](https://github.com/Junwu0615/Using-Streamlit-Create-Dashboard)**_ | *1* | *0* | *53* | *17.28* | *2025-10-30* | *2025-01-04* |
 | _**[Web-Crawler-Download-Img](https://github.com/Junwu0615/Web-Crawler-Download-Img)**_ | *1* | *0* | *12* | *6.49* | *2024-12-29* | *2023-12-08* |
 | _**[Web-Crawler-FamilyMart-Shop](https://github.com/Junwu0615/Web-Crawler-FamilyMart-Shop)**_ | *1* | *0* | *3* | *1.46* | *2025-01-03* | *2025-01-01* |
 | _**[Web-Crawler-News](https://github.com/Junwu0615/Web-Crawler-News)**_ | *1* | *0* | *11* | *0.11* | *2024-12-29* | *2023-12-10* |
<!-- dashboard:end -->

<br>

### *🔍　Traffic Analytics*

<!-- traffic:start -->
> _Traffic in the past **14 Days**_

| *📁 Repository* | *👀 Views* | *👤 Views Unique* | *📥 Clones* | *👤 Clones Unique* |
|:--|--:|--:|--:|--:|
| _**[Activity-Tracker](https://github.com/Junwu0615/Activity-Tracker)**_ | *0* | *0* | *2* | *2* |
| _**[Airflow-E2E-DevEnv](https://github.com/Junwu0615/Airflow-E2E-DevEnv)**_ | *1* | *1* | *4* | *4* |
| _**[Airflow-Template](https://github.com/Junwu0615/Airflow-Template)**_ | *0* | *0* | *3* | *3* |
| _**[Ansible-Deploy-To-Edge](https://github.com/Junwu0615/Ansible-Deploy-To-Edge)**_ | *0* | *0* | *4* | *4* |
| _**[CAED](https://github.com/Junwu0615/CAED)**_ | *0* | *0* | *1* | *1* |
| _**[Cloudflare-Dockerization](https://github.com/Junwu0615/Cloudflare-Dockerization)**_ | *0* | *0* | *3* | *3* |
| _**[Crawler-Keywords-And-Use-LineBot](https://github.com/Junwu0615/Crawler-Keywords-And-Use-LineBot)**_ | *0* | *0* | *4* | *4* |
| _**[Database-Template](https://github.com/Junwu0615/Database-Template)**_ | *2* | *1* | *4* | *4* |
| _**[Docker-Registry-Server](https://github.com/Junwu0615/Docker-Registry-Server)**_ | *2* | *2* | *2* | *2* |
| _**[Downloads-YouTube-To-MP3-4](https://github.com/Junwu0615/Downloads-YouTube-To-MP3-4)**_ | *10* | *10* | *3* | *3* |
| _**[Forex-Get-Quotes](https://github.com/Junwu0615/Forex-Get-Quotes)**_ | *0* | *0* | *2* | *2* |
| _**[github-readme-terminal](https://github.com/Junwu0615/github-readme-terminal)**_ | *1* | *1* | *3* | *3* |
| _**[How-To-Use-Clone-Shields](https://github.com/Junwu0615/How-To-Use-Clone-Shields)**_ | *0* | *0* | *4* | *4* |
| _**[Junwu0615](https://github.com/Junwu0615/Junwu0615)**_ | *41* | *2* | *353* | *135* |
| _**[Junwu0615-Analytics](https://github.com/Junwu0615/Junwu0615-Analytics)**_ | *35* | *3* | *98* | *53* |
| _**[Junwu0615.github.io](https://github.com/Junwu0615/Junwu0615.github.io)**_ | *1* | *1* | *2* | *2* |
| _**[Latency-Throughput-Simulation-Test](https://github.com/Junwu0615/Latency-Throughput-Simulation-Test)**_ | *1* | *1* | *2* | *2* |
| _**[LCII-Rec-Model](https://github.com/Junwu0615/LCII-Rec-Model)**_ | *0* | *0* | *42* | *4* |
| _**[LeetCode-Practice-Record](https://github.com/Junwu0615/LeetCode-Practice-Record)**_ | *0* | *0* | *2* | *2* |
| _**[LeetCode-Record-Sharing-Method](https://github.com/Junwu0615/LeetCode-Record-Sharing-Method)**_ | *1* | *1* | *5* | *5* |
| _**[My-English-Learning-Journey](https://github.com/Junwu0615/My-English-Learning-Journey)**_ | *0* | *0* | *3* | *3* |
| _**[My-Win-Apps](https://github.com/Junwu0615/My-Win-Apps)**_ | *412* | *9* | *450* | *196* |
| _**[NGROK-Dockerization](https://github.com/Junwu0615/NGROK-Dockerization)**_ | *0* | *0* | *2* | *2* |
| _**[NVDA-Price-Stock-Prediction](https://github.com/Junwu0615/NVDA-Price-Stock-Prediction)**_ | *2* | *2* | *3* | *3* |
| _**[One-Click-Database-Deployment](https://github.com/Junwu0615/One-Click-Database-Deployment)**_ | *1* | *1* | *4* | *4* |
| _**[Other](https://github.com/Junwu0615/Other)**_ | *12* | *2* | *10* | *10* |
| _**[Parsing-Media-From-JVID](https://github.com/Junwu0615/Parsing-Media-From-JVID)**_ | *161* | *78* | *15* | *14* |
| _**[Parsing-Media-From-PornHub](https://github.com/Junwu0615/Parsing-Media-From-PornHub)**_ | *2* | *2* | *2* | *2* |
| _**[PC-Activity-Tracker](https://github.com/Junwu0615/PC-Activity-Tracker)**_ | *16* | *1* | *383* | *144* |
| _**[PC-Bot-With-GenAI](https://github.com/Junwu0615/PC-Bot-With-GenAI)**_ | *6* | *2* | *2* | *2* |
| _**[PG-Airflow-DAGs](https://github.com/Junwu0615/PG-Airflow-DAGs)**_ | *4* | *2* | *6* | *5* |
| _**[PG-Analytics](https://github.com/Junwu0615/PG-Analytics)**_ | *8* | *2* | *87* | *46* |
| _**[PG-APP-Core](https://github.com/Junwu0615/PG-APP-Core)**_ | *10* | *2* | *74* | *44* |
| _**[PG-Core](https://github.com/Junwu0615/PG-Core)**_ | *46* | *4* | *94* | *45* |
| _**[PG-Cortex](https://github.com/Junwu0615/PG-Cortex)**_ | *3* | *1* | *11* | *9* |
| _**[PG-Edge-Container](https://github.com/Junwu0615/PG-Edge-Container)**_ | *3* | *1* | *13* | *8* |
| _**[PG-Infrastructure](https://github.com/Junwu0615/PG-Infrastructure)**_ | *29* | *3* | *86* | *39* |
| _**[PG-Sentinel](https://github.com/Junwu0615/PG-Sentinel)**_ | *3* | *1* | *10* | *9* |
| _**[PG-Shared-Lib](https://github.com/Junwu0615/PG-Shared-Lib)**_ | *5* | *2* | *15* | *9* |
| _**[PG-Synapse](https://github.com/Junwu0615/PG-Synapse)**_ | *4* | *2* | *10* | *9* |
| _**[Platform-Genesis](https://github.com/Junwu0615/Platform-Genesis)**_ | *171* | *7* | *256* | *105* |
| _**[RAG-With-LangChain-And-FAISS](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)**_ | *0* | *0* | *3* | *3* |
| _**[RESTful-API-FastAPI](https://github.com/Junwu0615/RESTful-API-FastAPI)**_ | *1* | *1* | *3* | *3* |
| _**[ROI-Tool](https://github.com/Junwu0615/ROI-Tool)**_ | *0* | *0* | *3* | *3* |
| _**[The-First-PHP-Login-System](https://github.com/Junwu0615/The-First-PHP-Login-System)**_ | *0* | *0* | *2* | *2* |
| _**[Using-Streamlit-Create-Dashboard](https://github.com/Junwu0615/Using-Streamlit-Create-Dashboard)**_ | *5* | *2* | *3* | *3* |
| _**[Web-Crawler-Download-Img](https://github.com/Junwu0615/Web-Crawler-Download-Img)**_ | *1* | *1* | *3* | *3* |
| _**[Web-Crawler-FamilyMart-Shop](https://github.com/Junwu0615/Web-Crawler-FamilyMart-Shop)**_ | *0* | *0* | *3* | *3* |
| _**[Web-Crawler-News](https://github.com/Junwu0615/Web-Crawler-News)**_ | *0* | *0* | *3* | *3* |
- ### *Summary*
  - *👀 Views :　1000*
  - *👤 Unique Visitors :　151*
  - *📥 Clones :　2102*
  - *👤 Unique Cloners :　973*
<!-- traffic:end -->

<br>

### *📈　Monthly Growth Analytics*

<!-- growth:start -->
> _Statistical Scope : **2026-07**_

| *📁 Repository* | *⭐ Stars ↕* | *🍴 Forks ↕* | *💡 Open Issues ↕* | *👀 Views ↕* | *📥 Clones ↕* |
|:--|--:|--:|--:|--:|--:|
| _**[Activity-Tracker](https://github.com/Junwu0615/Activity-Tracker)**_ | *+0* | *+0* | *+0* | *0* | *8* | 
| _**[Airflow-E2E-DevEnv](https://github.com/Junwu0615/Airflow-E2E-DevEnv)**_ | *+0* | *+0* | *+0* | *31* | *32* | 
| _**[Airflow-Template](https://github.com/Junwu0615/Airflow-Template)**_ | *+0* | *+0* | *+0* | *0* | *6* | 
| _**[Ansible-Deploy-To-Edge](https://github.com/Junwu0615/Ansible-Deploy-To-Edge)**_ | *+0* | *+0* | *+0* | *3* | *7* | 
| _**[CAED](https://github.com/Junwu0615/CAED)**_ | *+0* | *+0* | *+0* | *0* | *13* | 
| _**[Cloudflare-Dockerization](https://github.com/Junwu0615/Cloudflare-Dockerization)**_ | *+0* | *+0* | *+0* | *0* | *12* | 
| _**[Crawler-Keywords-And-Use-LineBot](https://github.com/Junwu0615/Crawler-Keywords-And-Use-LineBot)**_ | *+0* | *+0* | *+0* | *3* | *11* | 
| _**[Database-Template](https://github.com/Junwu0615/Database-Template)**_ | *+0* | *+0* | *+0* | *4* | *5* | 
| _**[Docker-Registry-Server](https://github.com/Junwu0615/Docker-Registry-Server)**_ | *+0* | *+0* | *+0* | *2* | *5* | 
| _**[Downloads-YouTube-To-MP3-4](https://github.com/Junwu0615/Downloads-YouTube-To-MP3-4)**_ | *+0* | *+0* | *+0* | *72* | *6* | 
| _**[Forex-Get-Quotes](https://github.com/Junwu0615/Forex-Get-Quotes)**_ | *+0* | *+0* | *+0* | *5* | *5* | 
| _**[github-readme-terminal](https://github.com/Junwu0615/github-readme-terminal)**_ | *+0* | *+0* | *+0* | *1* | *9* | 
| _**[How-To-Use-Clone-Shields](https://github.com/Junwu0615/How-To-Use-Clone-Shields)**_ | *+0* | *+0* | *+0* | *66* | *11* | 
| _**[Junwu0615](https://github.com/Junwu0615/Junwu0615)**_ | *+0* | *+0* | *+0* | *86* | *1800* | 
| _**[Junwu0615-Analytics](https://github.com/Junwu0615/Junwu0615-Analytics)**_ | *+0* | *+0* | *+0* | *66* | *208* | 
| _**[Junwu0615.github.io](https://github.com/Junwu0615/Junwu0615.github.io)**_ | *+0* | *+0* | *+0* | *1* | *5* | 
| _**[Latency-Throughput-Simulation-Test](https://github.com/Junwu0615/Latency-Throughput-Simulation-Test)**_ | *+0* | *+0* | *+0* | *1* | *9* | 
| _**[LCII-Rec-Model](https://github.com/Junwu0615/LCII-Rec-Model)**_ | *+0* | *+0* | *+0* | *0* | *45* | 
| _**[LeetCode-Practice-Record](https://github.com/Junwu0615/LeetCode-Practice-Record)**_ | *+0* | *+0* | *+0* | *0* | *5* | 
| _**[LeetCode-Record-Sharing-Method](https://github.com/Junwu0615/LeetCode-Record-Sharing-Method)**_ | *+0* | *+0* | *+0* | *1* | *11* | 
| _**[My-English-Learning-Journey](https://github.com/Junwu0615/My-English-Learning-Journey)**_ | *+0* | *+0* | *+0* | *0* | *15* | 
| _**[My-Win-Apps](https://github.com/Junwu0615/My-Win-Apps)**_ | *+0* | *+0* | *+0* | *412* | *450* | 
| _**[NGROK-Dockerization](https://github.com/Junwu0615/NGROK-Dockerization)**_ | *+0* | *+0* | *+0* | *3* | *19* | 
| _**[NVDA-Price-Stock-Prediction](https://github.com/Junwu0615/NVDA-Price-Stock-Prediction)**_ | *+0* | *+0* | *+0* | *5* | *4* | 
| _**[One-Click-Database-Deployment](https://github.com/Junwu0615/One-Click-Database-Deployment)**_ | *+0* | *+0* | *+0* | *7* | *13* | 
| _**[Other](https://github.com/Junwu0615/Other)**_ | *+0* | *+0* | *+0* | *15* | *17* | 
| _**[Parsing-Media-From-JVID](https://github.com/Junwu0615/Parsing-Media-From-JVID)**_ | *+0* | *+0* | *+0* | *903* | *35* | 
| _**[Parsing-Media-From-PornHub](https://github.com/Junwu0615/Parsing-Media-From-PornHub)**_ | *+0* | *+0* | *+0* | *5* | *8* | 
| _**[PC-Activity-Tracker](https://github.com/Junwu0615/PC-Activity-Tracker)**_ | *+0* | *+0* | *+0* | *25* | *1969* | 
| _**[PC-Bot-With-GenAI](https://github.com/Junwu0615/PC-Bot-With-GenAI)**_ | *+0* | *+0* | *+0* | *18* | *32* | 
| _**[PG-Airflow-DAGs](https://github.com/Junwu0615/PG-Airflow-DAGs)**_ | *+0* | *+0* | *+0* | *44* | *24* | 
| _**[PG-Analytics](https://github.com/Junwu0615/PG-Analytics)**_ | *+0* | *+0* | *+0* | *1026* | *2905* | 
| _**[PG-APP-Core](https://github.com/Junwu0615/PG-APP-Core)**_ | *+0* | *+0* | *+0* | *77* | *226* | 
| _**[PG-Core](https://github.com/Junwu0615/PG-Core)**_ | *+0* | *+0* | *+0* | *263* | *951* | 
| _**[PG-Cortex](https://github.com/Junwu0615/PG-Cortex)**_ | *+0* | *+0* | *+0* | *93* | *132* | 
| _**[PG-Edge-Container](https://github.com/Junwu0615/PG-Edge-Container)**_ | *+0* | *+0* | *+0* | *34* | *42* | 
| _**[PG-Infrastructure](https://github.com/Junwu0615/PG-Infrastructure)**_ | *+0* | *+0* | *+0* | *224* | *569* | 
| _**[PG-Sentinel](https://github.com/Junwu0615/PG-Sentinel)**_ | *+0* | *+0* | *+0* | *75* | *104* | 
| _**[PG-Shared-Lib](https://github.com/Junwu0615/PG-Shared-Lib)**_ | *+0* | *+0* | *+0* | *53* | *61* | 
| _**[PG-Synapse](https://github.com/Junwu0615/PG-Synapse)**_ | *+0* | *+0* | *+0* | *80* | *152* | 
| _**[Platform-Genesis](https://github.com/Junwu0615/Platform-Genesis)**_ | *+1* | *+0* | *+0* | *1148* | *2074* | 
| _**[RAG-With-LangChain-And-FAISS](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)**_ | *+0* | *+0* | *+0* | *24* | *15* | 
| _**[RESTful-API-FastAPI](https://github.com/Junwu0615/RESTful-API-FastAPI)**_ | *+0* | *+0* | *+0* | *1* | *12* | 
| _**[ROI-Tool](https://github.com/Junwu0615/ROI-Tool)**_ | *+0* | *+0* | *+0* | *0* | *7* | 
| _**[The-First-PHP-Login-System](https://github.com/Junwu0615/The-First-PHP-Login-System)**_ | *+0* | *+0* | *+0* | *6* | *5* | 
| _**[Using-Streamlit-Create-Dashboard](https://github.com/Junwu0615/Using-Streamlit-Create-Dashboard)**_ | *+0* | *+0* | *+0* | *5* | *9* | 
| _**[Web-Crawler-Download-Img](https://github.com/Junwu0615/Web-Crawler-Download-Img)**_ | *+0* | *+0* | *+0* | *1* | *7* | 
| _**[Web-Crawler-FamilyMart-Shop](https://github.com/Junwu0615/Web-Crawler-FamilyMart-Shop)**_ | *+0* | *+0* | *+0* | *0* | *14* | 
| _**[Web-Crawler-News](https://github.com/Junwu0615/Web-Crawler-News)**_ | *+0* | *+0* | *+0* | *3* | *7* | 
<!-- growth:end -->


<br><br><br>