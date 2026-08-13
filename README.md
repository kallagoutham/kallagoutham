<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=190&section=header&text=Goutham%20Kalla&fontSize=52&fontColor=ffffff&fontAlignY=34&desc=Software%20Engineer%20%7C%20Distributed%20Systems%20%7C%20AI%2FML%20%7C%20Cloud&descAlignY=54&descSize=17&animation=fadeIn" width="100%" alt="Goutham Kalla banner"/>

<a href="https://gouthamkalla.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=2C9EF0&center=true&vCenter=true&width=680&lines=MS+Computer+Science+%40+Stony+Brook+University;Software+Engineer+%40+Allocore+(STG+Capital+Group);Consensus%2C+Replication+%26+Fault-Tolerant+Systems;Paxos+%E2%80%A2+RAFT+%E2%80%A2+PBFT+%E2%80%A2+RDMA+%E2%80%A2+Kafka+%E2%80%A2+Kubernetes;Building+at+the+intersection+of+Systems+and+AI" alt="Typing SVG"/>
</a>

<br/>

<!-- ─────────────── PROFILES ─────────────── -->
<a href="https://www.linkedin.com/in/goutham-kalla-3b6133112/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://gouthamkalla.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://medium.com/@kallagoutham33"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="https://leetcode.com/u/goutham_kalla/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
<a href="https://hub.docker.com/u/kallagoutham"><img src="https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Hub"/></a>
<a href="mailto:kallagoutham33@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br/>

<img src="https://komarev.com/ghpvc/?username=kallagoutham&style=flat-square&color=2C9EF0&label=Profile+Views" alt="Profile views"/>
<a href="https://github.com/kallagoutham?tab=repositories"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fkallagoutham&query=%24.public_repos&label=Public%20Repos&style=flat-square&logo=github&color=181717" alt="Public repos"/></a>
<a href="https://github.com/kallagoutham?tab=followers"><img src="https://img.shields.io/github/followers/kallagoutham?style=flat-square&color=181717&logo=github&label=Followers" alt="Followers"/></a>

</div>

---

## 👨‍💻 About Me

```yaml
name:      Goutham Kalla
role:      Software Engineer @ Allocore (STG Capital Group)
education: M.S. Computer Science — Stony Brook University (2024 – 2026)
location:  New York, USA
previously:
  - Senior Associate Application Developer @ AT&T
  - Software Development Engineer @ Ennea Solutions
focus:
  - Distributed consensus & replicated state machines (Paxos, RAFT, PBFT)
  - High-throughput transactional storage (RDMA, sharding, 2PC, WAL)
  - Applied AI/ML & LLM-powered developer tooling
  - Cloud-native platforms (Kubernetes, Docker, Azure, AWS)
learning:  Quantum Computing · Large-Scale ML Systems
solved:    690+ DSA solutions committed across LeetCode, GFG, InterviewBit
```

- 🔭 Currently building **fault-tolerant transaction engines** and **LLM-driven data tooling**.
- ⚡ Contributed **RDMA transport support** to [Mako](https://www.usenix.org/conference/osdi25/presentation/shen-weihai) — an **OSDI '25** geo-replicated transactional KV store benchmarked at **3.66M TPC-C txns/sec**.
- 🧠 I like problems where **correctness under failure** matters more than the happy path.
- 💬 Ask me about **consensus protocols, Spring Boot at scale, Kafka pipelines, or system design**.

---

## 🏗️ Featured Work

### ⚙️ Distributed Systems, Consensus & Storage

| Project | What it does | Stack |
|---|---|---|
| **[mako-rdma](https://github.com/kallagoutham/mako-rdma)** | Added **RDMA transport** to Mako (OSDI '25), a geo-replicated transactional KV store using speculative 2PC to decouple execution from replication. Masstree in-memory index, RocksDB persistence, DPDK kernel bypass. | `C++` `RDMA` `DPDK` `RocksDB` |
| **[ShardedBFT](https://github.com/kallagoutham/shardedBFT)** | Byzantine fault-tolerant **sharded ledger**: Linear PBFT for intra-shard consensus + **2PC** for atomic cross-shard transfers. 3 shards × 4 replicas, tolerates *f = 1* Byzantine node per cluster, view change, threshold signatures. | `Java` `Spring Boot` `H2` `RSA` |
| **[Helix](https://github.com/kallagoutham/Helix-Paxos-Powered-Distributed-Transaction-Engine)** | Paxos-powered **distributed transaction engine** for multi-datacenter banking. Multi-Paxos intra-shard, 2PC cross-shard, full ACID with lock-based isolation and **WAL durability**; survives *N−1* fail-stop failures. | `Java` `Multi-Paxos` `2PC` `WAL` |
| **[SyncVault](https://github.com/kallagoutham/SyncVault)** | **Linear PBFT** replicated banking ledger — reduces classic PBFT's quadratic messaging, with view change, SHA-256 + RSA message integrity, checkpointing and live throughput/latency telemetry. | `Java` `Spring Boot` `H2` |
| **[PaxLedger](https://github.com/kallagoutham/PaxLegder)** | **Modified Paxos** protocol over a 5-node replicated banking cluster: leader election, log catch-up for recovering replicas, block-linked datastore, throughput/latency benchmarking. | `Java` `Paxos` |
| **[RSM — RAFT](https://github.com/kallagoutham/Replicated-State-Machine-RAFT-Consensus-Algorithm)** | **MIT 6.824-style** labs rebuilt in C++ — building toward a transactional, sharded, fault-tolerant key/value store à la Spanner. | `C++` `RAFT` |
| **[RAFT-Distributed-KV-Store](https://github.com/kallagoutham/RAFT-Distributed-KV-Store)** | Replicated key/value store driven by the RAFT consensus algorithm. | `RAFT` `KV Store` |

### 🤖 AI/ML, Data Engineering & Visualization

| Project | What it does | Stack |
|---|---|---|
| **[VizQuery-Agent](https://github.com/kallagoutham/vizquery)** | **LLM agent that turns natural language into charts.** Uploads CSV → generates + executes analysis code inside an **E2B sandbox** → renders line/bar/scatter/pie/bubble plots. Model switching across Llama 3.3 70B, DeepSeek V3, Qwen 2.5. | `Python` `Streamlit` `Together AI` `E2B` |
| **[MarketPulse](https://github.com/kallagoutham/marketpulse)** | Real-time **stock market streaming pipeline**: simulated market events → **Kafka** on EC2 → **S3** raw zone → **Glue Crawler/Catalog** → **Athena** SQL analytics, wrapped in a secured Django control plane. | `Python` `Kafka` `AWS` `Django` |
| **[TrafficLens](https://github.com/kallagoutham/Traffic-Lens)** | Multi-view **traffic accident analytics platform** — Flask + pandas API with cached aggregations, React frontend with coordinated maps, time series, sunburst, parallel-coordinates and radial views under shared multi-dimensional filters. | `Flask` `React` `D3` `pandas` |
| **[Fake Currency Detection](https://github.com/kallagoutham/FakeCurrencyDetectionSystem)** | **CNN-based counterfeit note classifier** with desktop and Flutter mobile front-ends for on-device verification. | `TensorFlow` `OpenCV` `Flutter` |
| **[PointCloudVisualisation](https://github.com/kallagoutham/PointCloudVisualisation)** | Interactive 3D point-cloud rendering and exploration in the browser. | `HTML` `WebGL` |

### 🚀 Platform, Backend & Full-Stack

| Project | What it does | Stack |
|---|---|---|
| **[Confirmly](https://github.com/kallagoutham/Confirmly)** | **Multi-tenant appointment platform** that cuts no-shows: signed expiring one-click confirm/cancel links, explainable 0–100 risk scoring, immutable audit event timeline, revenue-at-risk dashboards, Celery-scheduled reminders. | `Django` `DRF` `PostgreSQL` `Celery` `Redis` |
| **[Compiler-API](https://github.com/kallagoutham/Compiler-API)** | **Sandboxed remote code execution service** for C/C++/Java/Python with batch test-case runs — horizontally scalable to *N* containers behind an **nginx load balancer**. | `Python` `Docker` `nginx` |
| **[Healthcare Device Monitoring](https://github.com/kallagoutham/healthcare-device-monitoring)** | **Real-time medical telemetry dashboard** — Spring Boot broadcasts device readings over **STOMP/WebSocket** every 2s with threshold-based alerting; Angular 17 live dashboard; Actuator health/metrics. | `Java 17` `Spring Boot` `Angular` |
| **[Product Inventory API](https://github.com/kallagoutham/product-inventory-django)** | **JWT-secured inventory service** with claim-based permissions, soft + hard delete semantics and full CRUD test coverage. | `Django REST` `JWT` |
| **[ERP](https://github.com/kallagoutham/ERP)** · **[CRM Application](https://github.com/kallagoutham/CRM-Application)** · **[CRM Frontend](https://github.com/kallagoutham/CRM-Application-FE)** | Enterprise resource planning and a full-stack CRM (Spring Boot API + React client, deployed on Vercel). | `Java` `React` `MongoDB` |
| **[MediStock-Analyzer](https://github.com/kallagoutham/MediStock-Analyzer)** · **[SplitWise](https://github.com/kallagoutham/split-wise)** · **[Bujji](https://github.com/kallagoutham/Bujji)** | Batch-wise pharmacy inventory analytics from CSV, an expense-splitting app, and a chat API service. | `JavaScript` `Python` |

### 🧮 Algorithms & Practice

| Repo | Contents |
|---|---|
| **[My_Solutions](https://github.com/kallagoutham/My_Solutions)** | **690+ solutions** — LeetCode (incl. contests, SQL, Shell, JS), GeeksforGeeks, InterviewBit SQL, organised by topic: Graphs, Trees, Backtracking, DP and more. |
| **[CPPprograms](https://github.com/kallagoutham/CPPprograms)** · **[Geeks-for-Geeks](https://github.com/kallagoutham/Geeks-for-Geeks)** | A complete C++ guide for beginners and topic-wise GFG solutions. |
| **[Git-Notes](https://github.com/kallagoutham/Git-Notes)** · **[gitflow-branching-lab](https://github.com/kallagoutham/gitflow-branching-lab)** | Git internals notes and a hands-on GitFlow branching lab. |
| **[RubiksCubeLogic](https://github.com/kallagoutham/RubiksCubeLogic)** | Step-by-step algorithms for solving the Rubik's cube. |

---

## 🛠️ Tech Stack

<details open>
<summary><b>Languages</b></summary>
<br/>

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

</details>

<details open>
<summary><b>Backend & Frameworks</b></summary>
<br/>

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Camunda](https://img.shields.io/badge/Camunda-FC5D0D?style=for-the-badge&logo=camunda&logoColor=white)
![MuleSoft](https://img.shields.io/badge/MuleSoft-00A0DF?style=for-the-badge&logo=mulesoft&logoColor=white)

</details>

<details open>
<summary><b>Frontend</b></summary>
<br/>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-0F0F11?style=for-the-badge&logo=angular&logoColor=E23237)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3dotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

</details>

<details open>
<summary><b>Data, Streaming & AI/ML</b></summary>
<br/>

![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![RocksDB](https://img.shields.io/badge/RocksDB-2C3E50?style=for-the-badge&logo=databricks&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</details>

<details open>
<summary><b>Cloud, DevOps & Tooling</b></summary>
<br/>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</details>

---

## 📊 GitHub Analytics

<div align="center">

<!-- All cards render in both light and dark GitHub themes -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kallagoutham&theme=github_dark"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kallagoutham&theme=default" width="100%" alt="Profile summary"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kallagoutham&theme=github_dark"/>
  <img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kallagoutham&theme=default" alt="Repos per language"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kallagoutham&theme=github_dark"/>
  <img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kallagoutham&theme=default" alt="Most committed language"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=kallagoutham&theme=github_dark"/>
  <img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=kallagoutham&theme=default" alt="Contribution stats"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=kallagoutham&theme=github_dark&utcOffset=-5"/>
  <img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=kallagoutham&theme=default&utcOffset=-5" alt="Productive time"/>
</picture>

<br/>

<img src="https://streak-stats.demolab.com?user=kallagoutham&hide_border=true&border_radius=12&background=0d1117&stroke=21262d&ring=2C9EF0&fire=FF6B35&currStreakLabel=2C9EF0&sideNums=c9d1d9&currStreakNum=ffffff&dates=8b949e&sideLabels=c9d1d9" alt="GitHub Streak"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=kallagoutham&bg_color=0d1117&color=2C9EF0&line=2C9EF0&point=ffffff&area=true&area_color=2C9EF0&hide_border=true&custom_title=Contribution%20Activity%20%E2%80%94%20Last%2031%20Days"/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kallagoutham&bg_color=ffffff&color=0F2027&line=2C9EF0&point=0F2027&area=true&area_color=2C9EF0&hide_border=true&custom_title=Contribution%20Activity%20%E2%80%94%20Last%2031%20Days" width="100%" alt="Activity Graph"/>
</picture>

</div>

### 🔐 Full Contribution Profile *(public + private)*

<div align="center">

<!-- Generated nightly by .github/workflows/metrics.yml — includes private repository activity -->
<img src="./github-metrics.svg" alt="GitHub metrics including private contributions" width="100%"/>

</div>

---

## ⚡ Competitive Programming

<div align="center">

<a href="https://leetcode.com/u/goutham_kalla/">
  <img src="https://leetcard.jacoblin.cool/goutham_kalla?theme=dark&font=JetBrains%20Mono&ext=heatmap&border=0&radius=12" alt="LeetCode Stats"/>
</a>

</div>

<div align="center">

| Platform | Profile |
|---|---|
| 🟠 **LeetCode** | [`goutham_kalla`](https://leetcode.com/u/goutham_kalla/) |
| 🔴 **Codeforces** | [`goutham_kalla`](https://codeforces.com/profile/goutham_kalla) |
| 🔵 **SPOJ** | [`goutham_kalla`](https://www.spoj.com/users/goutham_kalla/) |
| 🟢 **HackerRank** | [`kallagoutham33`](https://www.hackerrank.com/profile/kallagoutham33) |
| 🟣 **InterviewBit** | [`kallagoutham33`](https://www.interviewbit.com/profile/kallagoutham33/) |
| 🐳 **Docker Hub** | [`kallagoutham`](https://hub.docker.com/u/kallagoutham) |

</div>

---

## ✍️ Latest Writing

> Auto-synced from [medium.com/@kallagoutham33](https://medium.com/@kallagoutham33)

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

<div align="center">
  <a href="https://medium.com/@kallagoutham33"><img src="https://img.shields.io/badge/Read_more_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
</div>

---

## 🎓 Certifications & Learning

<a href="https://github.com/kallagoutham/AZ-900-MicroSoft_Azure_Fundamentals"><img src="https://img.shields.io/badge/Microsoft_Azure_Fundamentals-AZ--900-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="AZ-900"/></a>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kallagoutham/kallagoutham/snake-output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kallagoutham/kallagoutham/snake-output/snake.svg"/>
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/kallagoutham/kallagoutham/snake-output/snake.svg" width="100%"/>
</picture>

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm always open to talking about **distributed systems**, **applied AI**, **system design**, or **new opportunities**.

<a href="mailto:kallagoutham33@gmail.com"><img src="https://img.shields.io/badge/kallagoutham33@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Personal Email"/></a>
<a href="mailto:goutham.kalla@stonybrook.edu"><img src="https://img.shields.io/badge/goutham.kalla@stonybrook.edu-990000?style=for-the-badge&logo=maildotru&logoColor=white" alt="University Email"/></a>
<br/>
<a href="https://www.linkedin.com/in/goutham-kalla-3b6133112/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://gouthamkalla.netlify.app/"><img src="https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>

<br/><br/>

<i>"Correctness under failure beats speed on the happy path."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=110&section=footer" width="100%" alt="footer"/>

</div>
