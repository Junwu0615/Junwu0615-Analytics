## *⭐ Junwu0615-Analytics ⭐*
> _🧟‍♂️ Starting from July 23, 2026, this project will continuously record the entire project journey of Junwu0615._

<!-- update_time:start -->
>
> _Generated at [ UTC+0 ] :　2026-07-29T14:49:46_

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
| *⭐ Total Stars* | *73* |
| *🍴 Total Forks* | *5* |
| *📩 Total Commit* | *3954* |
| *📦 Size ( MB )* | *261.36* |
| *👀 Total Views* | *1764* |
| *👤 Total Unique Visitors* | *378* |
| *📥 Total Clones* | *2942* |
| *👤 Total Unique Cloners* | *1759* |
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
 | _**[Cloudflare-Dockeriz...](https://github.com/Junwu0615/Cloudflare-Dockerization)**_ | *1* | *0* | *2* | *0.19* | *2025-02-02* | *2025-02-01* |
 | _**[Crawler-Keywords-An...](https://github.com/Junwu0615/Crawler-Keywords-And-Use-LineBot)**_ | *1* | *0* | *10* | *1.04* | *2024-12-29* | *2023-12-19* |
 | _**[Database-Template](https://github.com/Junwu0615/Database-Template)**_ | *1* | *0* | *42* | *2.60* | *2025-09-26* | *2024-12-25* |
 | _**[Docker-Registry-Server](https://github.com/Junwu0615/Docker-Registry-Server)**_ | *1* | *0* | *6* | *0.05* | *2025-09-29* | *2025-09-29* |
 | _**[Downloads-YouTube-T...](https://github.com/Junwu0615/Downloads-YouTube-To-MP3-4)**_ | *3* | *0* | *10* | *0.35* | *2024-12-29* | *2024-01-02* |
 | _**[Forex-Get-Quotes](https://github.com/Junwu0615/Forex-Get-Quotes)**_ | *3* | *0* | *23* | *1.58* | *2025-09-26* | *2024-09-11* |
 | _**[github-readme-terminal](https://github.com/Junwu0615/github-readme-terminal)**_ | *1* | *0* | *85* | *0.23* | *2024-11-08* | *2025-02-16* |
 | _**[How-To-Use-Clone-Sh...](https://github.com/Junwu0615/How-To-Use-Clone-Shields)**_ | *2* | *0* | *8* | *0.51* | *2024-11-24* | *2023-12-28* |
 | _**[Junwu0615](https://github.com/Junwu0615/Junwu0615)**_ | *1* | *0* | *645* | *11.51* | *2026-07-29* | *2023-12-26* |
 | _**[Junwu0615-Analytics](https://github.com/Junwu0615/Junwu0615-Analytics)**_ | *1* | *0* | *49* | *0.48* | *2026-07-29* | *2026-07-06* |
 | _**[Junwu0615.github.io](https://github.com/Junwu0615/Junwu0615.github.io)**_ | *1* | *0* | *2* | *0.00* | *2024-01-28* | *2024-01-27* |
 | _**[Latency-Throughput-...](https://github.com/Junwu0615/Latency-Throughput-Simulation-Test)**_ | *1* | *0* | *46* | *6.04* | *2025-10-15* | *2025-10-02* |
 | _**[LCII-Rec-Model](https://github.com/Junwu0615/LCII-Rec-Model)**_ | *2* | *0* | *2* | *1.16* | *2024-12-29* | *2023-12-08* |
 | _**[LeetCode-Practice-R...](https://github.com/Junwu0615/LeetCode-Practice-Record)**_ | *1* | *0* | *60* | *0.05* | *2025-11-24* | *2025-02-02* |
 | _**[LeetCode-Record-Sha...](https://github.com/Junwu0615/LeetCode-Record-Sharing-Method)**_ | *1* | *0* | *6* | *95.90* | *2024-12-29* | *2024-01-26* |
 | _**[My-English-Learning...](https://github.com/Junwu0615/My-English-Learning-Journey)**_ | *1* | *0* | *23* | *0.04* | *2026-03-09* | *2026-03-04* |
 | _**[My-Win-Apps](https://github.com/Junwu0615/My-Win-Apps)**_ | *1* | *0* | *97* | *4.24* | *2026-07-18* | *2026-07-12* |
 | _**[NGROK-Dockerization](https://github.com/Junwu0615/NGROK-Dockerization)**_ | *1* | *0* | *2* | *0.12* | *2025-01-24* | *2025-01-24* |
 | _**[NVDA-Price-Stock-Pr...](https://github.com/Junwu0615/NVDA-Price-Stock-Prediction)**_ | *1* | *0* | *4* | *1.23* | *2024-12-29* | *2024-02-25* |
 | _**[One-Click-Database-...](https://github.com/Junwu0615/One-Click-Database-Deployment)**_ | *1* | *0* | *17* | *0.53* | *2025-09-26* | *2025-02-27* |
 | _**[Other](https://github.com/Junwu0615/Other)**_ | *1* | *0* | *26* | *0.46* | *2026-07-26* | *2023-12-08* |
 | _**[Parsing-Media-From-...](https://github.com/Junwu0615/Parsing-Media-From-JVID)**_ | *10* | *4* | *18* | *0.43* | *2026-07-26* | *2024-12-15* |
 | _**[Parsing-Media-From-...](https://github.com/Junwu0615/Parsing-Media-From-PornHub)**_ | *3* | *1* | *4* | *0.34* | *2024-12-29* | *2024-12-18* |
 | _**[PC-Activity-Tracker](https://github.com/Junwu0615/PC-Activity-Tracker)**_ | *1* | *0* | *1028* | *0.28* | *2026-07-29* | *2025-11-16* |
 | _**[PC-Bot-With-GenAI](https://github.com/Junwu0615/PC-Bot-With-GenAI)**_ | *4* | *0* | *28* | *7.30* | *2026-04-14* | *2025-01-07* |
 | _**[PG-Airflow-DAGs](https://github.com/Junwu0615/PG-Airflow-DAGs)**_ | *1* | *0* | *28* | *0.06* | *2026-07-23* | *2026-05-08* |
 | _**[PG-Analytics](https://github.com/Junwu0615/PG-Analytics)**_ | *1* | *0* | *200* | *0.33* | *2026-07-29* | *2026-07-03* |
 | _**[PG-APP-Core](https://github.com/Junwu0615/PG-APP-Core)**_ | *1* | *0* | *63* | *0.12* | *2026-07-23* | *2026-05-08* |
 | _**[PG-Core](https://github.com/Junwu0615/PG-Core)**_ | *1* | *0* | *54* | *9.08* | *2026-07-23* | *2026-07-03* |
 | _**[PG-Cortex](https://github.com/Junwu0615/PG-Cortex)**_ | *1* | *0* | *6* | *0.01* | *2026-07-23* | *2026-07-03* |
 | _**[PG-Edge-Container](https://github.com/Junwu0615/PG-Edge-Container)**_ | *1* | *0* | *25* | *0.04* | *2026-07-23* | *2026-05-08* |
 | _**[PG-Infrastructure](https://github.com/Junwu0615/PG-Infrastructure)**_ | *1* | *0* | *363* | *4.98* | *2026-07-23* | *2026-05-08* |
 | _**[PG-Sentinel](https://github.com/Junwu0615/PG-Sentinel)**_ | *1* | *0* | *3* | *0.00* | *2026-07-23* | *2026-07-03* |
 | _**[PG-Shared-Lib](https://github.com/Junwu0615/PG-Shared-Lib)**_ | *1* | *0* | *21* | *0.05* | *2026-07-23* | *2026-05-08* |
 | _**[PG-Synapse](https://github.com/Junwu0615/PG-Synapse)**_ | *1* | *0* | *4* | *0.01* | *2026-07-23* | *2026-07-03* |
 | _**[Platform-Genesis](https://github.com/Junwu0615/Platform-Genesis)**_ | *3* | *0* | *608* | *57.94* | *2026-07-28* | *2026-03-20* |
 | _**[RAG-With-LangChain-...](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)**_ | *1* | *0* | *5* | *0.18* | *2025-10-15* | *2025-02-27* |
 | _**[RESTful-API-FastAPI](https://github.com/Junwu0615/RESTful-API-FastAPI)**_ | *1* | *0* | *2* | *0.68* | *2025-02-20* | *2025-02-02* |
 | _**[ROI-Tool](https://github.com/Junwu0615/ROI-Tool)**_ | *1* | *0* | *16* | *13.68* | *2024-12-29* | *2022-05-21* |
 | _**[The-First-PHP-Login...](https://github.com/Junwu0615/The-First-PHP-Login-System)**_ | *2* | *0* | *9* | *0.74* | *2024-11-24* | *2024-01-04* |
 | _**[Using-Streamlit-Cre...](https://github.com/Junwu0615/Using-Streamlit-Create-Dashboard)**_ | *1* | *0* | *53* | *17.28* | *2025-10-30* | *2025-01-04* |
 | _**[Web-Crawler-Downloa...](https://github.com/Junwu0615/Web-Crawler-Download-Img)**_ | *1* | *0* | *12* | *6.49* | *2024-12-29* | *2023-12-08* |
 | _**[Web-Crawler-FamilyM...](https://github.com/Junwu0615/Web-Crawler-FamilyMart-Shop)**_ | *1* | *0* | *3* | *1.46* | *2025-01-03* | *2025-01-01* |
 | _**[Web-Crawler-News](https://github.com/Junwu0615/Web-Crawler-News)**_ | *1* | *0* | *11* | *0.11* | *2024-12-29* | *2023-12-10* |
<!-- dashboard:end -->

<br>

### *🔍　Traffic Analytics*

<!-- traffic:start -->
> _Traffic in the past **14 Days**_

| *📁 Repository* | *👀 Views* | *👤 Views Unique* | *📥 Clones* | *👤 Clones Unique* |
|:--|--:|--:|--:|--:|
| _**[Activity-Tracker](https://github.com/Junwu0615/Activity-Tracker)**_ | *0* | *0* | *4* | *4* |
| _**[Airflow-E2E-DevEnv](https://github.com/Junwu0615/Airflow-E2E-DevEnv)**_ | *3* | *1* | *6* | *6* |
| _**[Airflow-Template](https://github.com/Junwu0615/Airflow-Template)**_ | *0* | *0* | *4* | *4* |
| _**[Ansible-Deploy-To-Edge](https://github.com/Junwu0615/Ansible-Deploy-To-Edge)**_ | *0* | *0* | *5* | *5* |
| _**[CAED](https://github.com/Junwu0615/CAED)**_ | *0* | *0* | *3* | *3* |
| _**[Cloudflare-Dockeriz...](https://github.com/Junwu0615/Cloudflare-Dockerization)**_ | *0* | *0* | *3* | *3* |
| _**[Crawler-Keywords-An...](https://github.com/Junwu0615/Crawler-Keywords-And-Use-LineBot)**_ | *0* | *0* | *6* | *6* |
| _**[Database-Template](https://github.com/Junwu0615/Database-Template)**_ | *2* | *1* | *6* | *6* |
| _**[Docker-Registry-Server](https://github.com/Junwu0615/Docker-Registry-Server)**_ | *1* | *1* | *3* | *3* |
| _**[Downloads-YouTube-T...](https://github.com/Junwu0615/Downloads-YouTube-To-MP3-4)**_ | *8* | *8* | *7* | *7* |
| _**[Forex-Get-Quotes](https://github.com/Junwu0615/Forex-Get-Quotes)**_ | *0* | *0* | *6* | *6* |
| _**[github-readme-terminal](https://github.com/Junwu0615/github-readme-terminal)**_ | *1* | *1* | *3* | *3* |
| _**[How-To-Use-Clone-Sh...](https://github.com/Junwu0615/How-To-Use-Clone-Shields)**_ | *41* | *1* | *6* | *6* |
| _**[Junwu0615](https://github.com/Junwu0615/Junwu0615)**_ | *44* | *3* | *321* | *128* |
| _**[Junwu0615-Analytics](https://github.com/Junwu0615/Junwu0615-Analytics)**_ | *42* | *2* | *131* | *66* |
| _**[Junwu0615.github.io](https://github.com/Junwu0615/Junwu0615.github.io)**_ | *1* | *1* | *4* | *4* |
| _**[Latency-Throughput-...](https://github.com/Junwu0615/Latency-Throughput-Simulation-Test)**_ | *1* | *1* | *5* | *5* |
| _**[LCII-Rec-Model](https://github.com/Junwu0615/LCII-Rec-Model)**_ | *0* | *0* | *43* | *6* |
| _**[LeetCode-Practice-R...](https://github.com/Junwu0615/LeetCode-Practice-Record)**_ | *0* | *0* | *3* | *3* |
| _**[LeetCode-Record-Sha...](https://github.com/Junwu0615/LeetCode-Record-Sharing-Method)**_ | *0* | *0* | *7* | *7* |
| _**[My-English-Learning...](https://github.com/Junwu0615/My-English-Learning-Journey)**_ | *0* | *0* | *4* | *4* |
| _**[My-Win-Apps](https://github.com/Junwu0615/My-Win-Apps)**_ | *273* | *12* | *119* | *69* |
| _**[NGROK-Dockerization](https://github.com/Junwu0615/NGROK-Dockerization)**_ | *0* | *0* | *4* | *4* |
| _**[NVDA-Price-Stock-Pr...](https://github.com/Junwu0615/NVDA-Price-Stock-Prediction)**_ | *5* | *5* | *4* | *4* |
| _**[One-Click-Database-...](https://github.com/Junwu0615/One-Click-Database-Deployment)**_ | *1* | *1* | *7* | *6* |
| _**[Other](https://github.com/Junwu0615/Other)**_ | *32* | *2* | *19* | *18* |
| _**[Parsing-Media-From-...](https://github.com/Junwu0615/Parsing-Media-From-JVID)**_ | *314* | *82* | *60* | *31* |
| _**[Parsing-Media-From-...](https://github.com/Junwu0615/Parsing-Media-From-PornHub)**_ | *3* | *3* | *3* | *3* |
| _**[PC-Activity-Tracker](https://github.com/Junwu0615/PC-Activity-Tracker)**_ | *16* | *1* | *360* | *145* |
| _**[PC-Bot-With-GenAI](https://github.com/Junwu0615/PC-Bot-With-GenAI)**_ | *3* | *2* | *5* | *5* |
| _**[PG-Airflow-DAGs](https://github.com/Junwu0615/PG-Airflow-DAGs)**_ | *30* | *1* | *26* | *19* |
| _**[PG-Analytics](https://github.com/Junwu0615/PG-Analytics)**_ | *104* | *4* | *246* | *114* |
| _**[PG-APP-Core](https://github.com/Junwu0615/PG-APP-Core)**_ | *17* | *2* | *36* | *24* |
| _**[PG-Core](https://github.com/Junwu0615/PG-Core)**_ | *121* | *6* | *91* | *50* |
| _**[PG-Cortex](https://github.com/Junwu0615/PG-Cortex)**_ | *5* | *2* | *18* | *15* |
| _**[PG-Edge-Container](https://github.com/Junwu0615/PG-Edge-Container)**_ | *14* | *1* | *17* | *15* |
| _**[PG-Infrastructure](https://github.com/Junwu0615/PG-Infrastructure)**_ | *33* | *3* | *55* | *41* |
| _**[PG-Sentinel](https://github.com/Junwu0615/PG-Sentinel)**_ | *5* | *2* | *12* | *12* |
| _**[PG-Shared-Lib](https://github.com/Junwu0615/PG-Shared-Lib)**_ | *15* | *1* | *21* | *16* |
| _**[PG-Synapse](https://github.com/Junwu0615/PG-Synapse)**_ | *6* | *3* | *13* | *13* |
| _**[Platform-Genesis](https://github.com/Junwu0615/Platform-Genesis)**_ | *248* | *10* | *270* | *137* |
| _**[RAG-With-LangChain-...](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)**_ | *3* | *1* | *4* | *4* |
| _**[RESTful-API-FastAPI](https://github.com/Junwu0615/RESTful-API-FastAPI)**_ | *1* | *1* | *3* | *3* |
| _**[ROI-Tool](https://github.com/Junwu0615/ROI-Tool)**_ | *1* | *1* | *3* | *3* |
| _**[The-First-PHP-Login...](https://github.com/Junwu0615/The-First-PHP-Login-System)**_ | *0* | *0* | *3* | *3* |
| _**[Using-Streamlit-Cre...](https://github.com/Junwu0615/Using-Streamlit-Create-Dashboard)**_ | *3* | *1* | *3* | *3* |
| _**[Web-Crawler-Downloa...](https://github.com/Junwu0615/Web-Crawler-Download-Img)**_ | *0* | *0* | *5* | *5* |
| _**[Web-Crawler-FamilyM...](https://github.com/Junwu0615/Web-Crawler-FamilyMart-Shop)**_ | *0* | *0* | *4* | *4* |
| _**[Web-Crawler-News](https://github.com/Junwu0615/Web-Crawler-News)**_ | *0* | *0* | *4* | *4* |
- ### *Summary*
  - *👀 Views :　1397*
  - *👤 Unique Visitors :　167*
  - *📥 Clones :　1995*
  - *👤 Unique Cloners :　1055*
<!-- traffic:end -->

<br>

### *📈　Monthly Growth Analytics*

<!-- growth:start -->
> _Statistical Scope : **2026-07**_

| *📁 Repository* | *⭐ Stars ↕* | *🍴 Forks ↕* | *💡 Open Issues ↕* | *👀 Views ↕* | *📥 Clones ↕* |
|:--|--:|--:|--:|--:|--:|
| _**[Activity-Tracker](https://github.com/Junwu0615/Activity-Tracker)**_ | *+0* | *+0* | *+0* | *0* | *4* | 
| _**[Airflow-E2E-DevEnv](https://github.com/Junwu0615/Airflow-E2E-DevEnv)**_ | *+0* | *+0* | *+0* | *4* | *6* | 
| _**[Airflow-Template](https://github.com/Junwu0615/Airflow-Template)**_ | *+0* | *+0* | *+0* | *0* | *4* | 
| _**[Ansible-Deploy-To-Edge](https://github.com/Junwu0615/Ansible-Deploy-To-Edge)**_ | *+0* | *+0* | *+0* | *0* | *5* | 
| _**[CAED](https://github.com/Junwu0615/CAED)**_ | *+0* | *+0* | *+0* | *0* | *3* | 
| _**[Cloudflare-Dockeriz...](https://github.com/Junwu0615/Cloudflare-Dockerization)**_ | *+0* | *+0* | *+0* | *0* | *3* | 
| _**[Crawler-Keywords-An...](https://github.com/Junwu0615/Crawler-Keywords-And-Use-LineBot)**_ | *+0* | *+0* | *+0* | *0* | *6* | 
| _**[Database-Template](https://github.com/Junwu0615/Database-Template)**_ | *+0* | *+0* | *+0* | *2* | *6* | 
| _**[Docker-Registry-Server](https://github.com/Junwu0615/Docker-Registry-Server)**_ | *+0* | *+0* | *+0* | *2* | *3* | 
| _**[Downloads-YouTube-T...](https://github.com/Junwu0615/Downloads-YouTube-To-MP3-4)**_ | *+0* | *+0* | *+0* | *15* | *7* | 
| _**[Forex-Get-Quotes](https://github.com/Junwu0615/Forex-Get-Quotes)**_ | *+0* | *+0* | *+0* | *0* | *6* | 
| _**[github-readme-terminal](https://github.com/Junwu0615/github-readme-terminal)**_ | *+0* | *+0* | *+0* | *1* | *3* | 
| _**[How-To-Use-Clone-Sh...](https://github.com/Junwu0615/How-To-Use-Clone-Shields)**_ | *+0* | *+0* | *+0* | *41* | *6* | 
| _**[Junwu0615](https://github.com/Junwu0615/Junwu0615)**_ | *+0* | *+0* | *+0* | *53* | *471* | 
| _**[Junwu0615-Analytics](https://github.com/Junwu0615/Junwu0615-Analytics)**_ | *+0* | *+0* | *+0* | *61* | *181* | 
| _**[Junwu0615.github.io](https://github.com/Junwu0615/Junwu0615.github.io)**_ | *+0* | *+0* | *+0* | *1* | *4* | 
| _**[Latency-Throughput-...](https://github.com/Junwu0615/Latency-Throughput-Simulation-Test)**_ | *+0* | *+0* | *+0* | *1* | *5* | 
| _**[LCII-Rec-Model](https://github.com/Junwu0615/LCII-Rec-Model)**_ | *+0* | *+0* | *+0* | *0* | *45* | 
| _**[LeetCode-Practice-R...](https://github.com/Junwu0615/LeetCode-Practice-Record)**_ | *+0* | *+0* | *+0* | *0* | *3* | 
| _**[LeetCode-Record-Sha...](https://github.com/Junwu0615/LeetCode-Record-Sharing-Method)**_ | *+0* | *+0* | *+0* | *1* | *7* | 
| _**[My-English-Learning...](https://github.com/Junwu0615/My-English-Learning-Journey)**_ | *+0* | *+0* | *+0* | *0* | *5* | 
| _**[My-Win-Apps](https://github.com/Junwu0615/My-Win-Apps)**_ | *+0* | *+0* | *+0* | *433* | *451* | 
| _**[NGROK-Dockerization](https://github.com/Junwu0615/NGROK-Dockerization)**_ | *+0* | *+0* | *+0* | *0* | *4* | 
| _**[NVDA-Price-Stock-Pr...](https://github.com/Junwu0615/NVDA-Price-Stock-Prediction)**_ | *+0* | *+0* | *+0* | *5* | *4* | 
| _**[One-Click-Database-...](https://github.com/Junwu0615/One-Click-Database-Deployment)**_ | *+0* | *+0* | *+0* | *1* | *7* | 
| _**[Other](https://github.com/Junwu0615/Other)**_ | *+0* | *+0* | *+0* | *32* | *19* | 
| _**[Parsing-Media-From-...](https://github.com/Junwu0615/Parsing-Media-From-JVID)**_ | *+2* | *+1* | *-1* | *389* | *64* | 
| _**[Parsing-Media-From-...](https://github.com/Junwu0615/Parsing-Media-From-PornHub)**_ | *+0* | *+0* | *+0* | *3* | *3* | 
| _**[PC-Activity-Tracker](https://github.com/Junwu0615/PC-Activity-Tracker)**_ | *+0* | *+0* | *+0* | *16* | *517* | 
| _**[PC-Bot-With-GenAI](https://github.com/Junwu0615/PC-Bot-With-GenAI)**_ | *+0* | *+0* | *+0* | *7* | *5* | 
| _**[PG-Airflow-DAGs](https://github.com/Junwu0615/PG-Airflow-DAGs)**_ | *+0* | *+0* | *+0* | *33* | *29* | 
| _**[PG-Analytics](https://github.com/Junwu0615/PG-Analytics)**_ | *+0* | *+0* | *+0* | *107* | *278* | 
| _**[PG-APP-Core](https://github.com/Junwu0615/PG-APP-Core)**_ | *+0* | *+0* | *+0* | *25* | *81* | 
| _**[PG-Core](https://github.com/Junwu0615/PG-Core)**_ | *+0* | *+0* | *+0* | *135* | *121* | 
| _**[PG-Cortex](https://github.com/Junwu0615/PG-Cortex)**_ | *+0* | *+0* | *+0* | *7* | *24* | 
| _**[PG-Edge-Container](https://github.com/Junwu0615/PG-Edge-Container)**_ | *+0* | *+0* | *+0* | *16* | *22* | 
| _**[PG-Infrastructure](https://github.com/Junwu0615/PG-Infrastructure)**_ | *+0* | *+0* | *+0* | *40* | *103* | 
| _**[PG-Sentinel](https://github.com/Junwu0615/PG-Sentinel)**_ | *+0* | *+0* | *+0* | *7* | *18* | 
| _**[PG-Shared-Lib](https://github.com/Junwu0615/PG-Shared-Lib)**_ | *+0* | *+0* | *+0* | *18* | *23* | 
| _**[PG-Synapse](https://github.com/Junwu0615/PG-Synapse)**_ | *+0* | *+0* | *+0* | *9* | *18* | 
| _**[Platform-Genesis](https://github.com/Junwu0615/Platform-Genesis)**_ | *+0* | *+0* | *+0* | *288* | *338* | 
| _**[RAG-With-LangChain-...](https://github.com/Junwu0615/RAG-With-LangChain-And-FAISS)**_ | *+0* | *+0* | *+0* | *3* | *4* | 
| _**[RESTful-API-FastAPI](https://github.com/Junwu0615/RESTful-API-FastAPI)**_ | *+0* | *+0* | *+0* | *1* | *3* | 
| _**[ROI-Tool](https://github.com/Junwu0615/ROI-Tool)**_ | *+0* | *+0* | *+0* | *1* | *3* | 
| _**[The-First-PHP-Login...](https://github.com/Junwu0615/The-First-PHP-Login-System)**_ | *+0* | *+0* | *+0* | *0* | *3* | 
| _**[Using-Streamlit-Cre...](https://github.com/Junwu0615/Using-Streamlit-Create-Dashboard)**_ | *+0* | *+0* | *+0* | *5* | *4* | 
| _**[Web-Crawler-Downloa...](https://github.com/Junwu0615/Web-Crawler-Download-Img)**_ | *+0* | *+0* | *+0* | *1* | *5* | 
| _**[Web-Crawler-FamilyM...](https://github.com/Junwu0615/Web-Crawler-FamilyMart-Shop)**_ | *+0* | *+0* | *+0* | *0* | *4* | 
| _**[Web-Crawler-News](https://github.com/Junwu0615/Web-Crawler-News)**_ | *+0* | *+0* | *+0* | *0* | *4* | 
<!-- growth:end -->


<br><br><br>