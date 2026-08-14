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
<br/>
<a href="https://www.credly.com/users/kalla-goutham"><img src="https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly"/></a>
<a href="https://devpost.com/kallagoutham"><img src="https://img.shields.io/badge/Devpost-003E54?style=for-the-badge&logo=devpost&logoColor=white" alt="Devpost"/></a>
<a href="https://hub.docker.com/u/kallagoutham"><img src="https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Hub"/></a>
<a href="mailto:kallagoutham33@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br/>

<img src="https://komarev.com/ghpvc/?username=kallagoutham&style=flat-square&color=2C9EF0&label=Profile+Views" alt="Profile views"/>
<a href="https://github.com/kallagoutham?tab=repositories"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fkallagoutham&query=%24.public_repos&label=Public%20Repos&style=flat-square&logo=github&color=181717" alt="Public repos"/></a>
<a href="https://github.com/kallagoutham?tab=followers"><img src="https://img.shields.io/github/followers/kallagoutham?style=flat-square&color=181717&logo=github&label=Followers" alt="Followers"/></a>

</div>

---

## 👨‍💻 About

**M.S. Computer Science @ Stony Brook University** (2024–2026) · **Software Engineer @ Allocore** (STG Capital Group)
Previously **AT&T** — Senior Associate Application Developer · **Ennea Solutions** — SDE

I build systems where **correctness under failure** matters more than the happy path — consensus protocols, replicated state machines and high-throughput transactional storage — and apply the same rigor to **LLM-powered tooling**.

> ⚡ Contributed **RDMA transport support** to [**Mako**](https://www.usenix.org/conference/osdi25/presentation/shen-weihai) — an **OSDI '25** geo-replicated transactional KV store benchmarked at **3.66M TPC-C transactions/sec**.

`Paxos` · `RAFT` · `PBFT` · `2PC` · `RDMA` · `Sharding` · `WAL` · `Kafka` · `Kubernetes` · `LLM Agents`

---

## 🏗️ Selected Work

### ⚙️ Distributed Systems & Consensus

| Project | Summary | Stack |
|---|---|---|
| **[mako-rdma](https://github.com/kallagoutham/mako-rdma)** | RDMA transport for a geo-replicated KV store using speculative 2PC to decouple execution from replication. | `C++` `RDMA` `DPDK` |
| **[ShardedBFT](https://github.com/kallagoutham/shardedBFT)** | Byzantine-tolerant sharded ledger — Linear PBFT intra-shard, 2PC cross-shard, tolerates *f = 1* per cluster. | `Java` `PBFT` `2PC` |
| **[Helix](https://github.com/kallagoutham/Helix-Paxos-Powered-Distributed-Transaction-Engine)** | Multi-datacenter transaction engine: Multi-Paxos + 2PC, full ACID, survives *N−1* fail-stop failures. | `Java` `Paxos` `WAL` |
| **[SyncVault](https://github.com/kallagoutham/SyncVault)** | Linear PBFT banking ledger — sub-quadratic messaging, view change, SHA-256 + RSA integrity. | `Java` `Spring Boot` |
| **[PaxLedger](https://github.com/kallagoutham/PaxLegder)** | Modified Paxos across 5 replicas: leader election, log catch-up, block-linked datastore. | `Java` `Paxos` |
| **[RSM-RAFT](https://github.com/kallagoutham/Replicated-State-Machine-RAFT-Consensus-Algorithm)** · **[RAFT-KV](https://github.com/kallagoutham/RAFT-Distributed-KV-Store)** | MIT 6.824-style labs in C++ toward a sharded, fault-tolerant Spanner-like store. | `C++` `RAFT` |

### 🤖 AI/ML & Data Engineering

| Project | Summary | Stack |
|---|---|---|
| **[VizQuery-Agent](https://github.com/kallagoutham/vizquery)** | LLM agent turning natural language into charts — generates and executes analysis code in an E2B sandbox. | `Together AI` `E2B` |
| **[MarketPulse](https://github.com/kallagoutham/marketpulse)** | Market-data streaming pipeline: Kafka → S3 → Glue Catalog → Athena, behind a Django control plane. | `Kafka` `AWS` `Django` |
| **[TrafficLens](https://github.com/kallagoutham/Traffic-Lens)** | Accident analytics with coordinated map, sunburst and parallel-coordinate views under shared filters. | `Flask` `React` `D3` |
| **[Fake Currency Detection](https://github.com/kallagoutham/FakeCurrencyDetectionSystem)** · **[PointCloud](https://github.com/kallagoutham/PointCloudVisualisation)** | CNN counterfeit-note classifier with Flutter client; browser-based 3D point-cloud rendering. | `TensorFlow` `OpenCV` |

### 🚀 Platform & Backend

| Project | Summary | Stack |
|---|---|---|
| **[Confirmly](https://github.com/kallagoutham/Confirmly)** | Multi-tenant appointment platform — signed expiring action links, explainable risk scoring, audit timeline. | `Django` `Celery` `Postgres` |
| **[Compiler-API](https://github.com/kallagoutham/Compiler-API)** | Sandboxed multi-language code execution, scaling to *N* containers behind nginx. | `Docker` `nginx` |
| **[Healthcare Monitoring](https://github.com/kallagoutham/healthcare-device-monitoring)** | Live device telemetry over STOMP/WebSocket with threshold alerting and an Angular dashboard. | `Spring Boot` `Angular` |
| **[Inventory API](https://github.com/kallagoutham/product-inventory-django)** · **[ERP](https://github.com/kallagoutham/ERP)** · **[CRM](https://github.com/kallagoutham/CRM-Application)** | JWT claim-based permissions with soft delete; enterprise ERP and full-stack CRM. | `DRF` `Java` `React` |
| **[MediStock](https://github.com/kallagoutham/MediStock-Analyzer)** · **[SplitWise](https://github.com/kallagoutham/split-wise)** · **[Bujji](https://github.com/kallagoutham/Bujji)** | Pharmacy batch analytics, expense splitting, and a chat API service. | `JavaScript` `Python` |

### 🧮 Algorithms

**[My_Solutions](https://github.com/kallagoutham/My_Solutions)** — 690+ solutions across LeetCode (contests, SQL, Shell, JS), GFG and InterviewBit, organised by topic · **[CPPprograms](https://github.com/kallagoutham/CPPprograms)** · **[Geeks-for-Geeks](https://github.com/kallagoutham/Geeks-for-Geeks)** · **[Git-Notes](https://github.com/kallagoutham/Git-Notes)** · **[RubiksCubeLogic](https://github.com/kallagoutham/RubiksCubeLogic)**

---

## 🛠️ Tech Stack

<details>
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

<details>
<summary><b>Backend & Frontend</b></summary>
<br/>

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Camunda](https://img.shields.io/badge/Camunda-FC5D0D?style=for-the-badge&logo=camunda&logoColor=white)
![MuleSoft](https://img.shields.io/badge/MuleSoft-00A0DF?style=for-the-badge&logo=mulesoft&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-0F0F11?style=for-the-badge&logo=angular&logoColor=E23237)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3dotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

</details>

<details>
<summary><b>Data, Streaming & AI/ML</b></summary>
<br/>

![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</details>

<details>
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

<!-- Renders in both light and dark GitHub themes -->
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

<details>
<summary><b>🔐 Full contribution profile — public + private</b></summary>
<br/>
<div align="center">

<!-- Regenerated nightly by .github/workflows/metrics.yml -->
<img src="./github-metrics.svg" alt="GitHub metrics including private contributions" width="100%"/>

</div>
</details>

---

## ⚡ Competitive Programming

<div align="center">

<a href="https://leetcode.com/u/goutham_kalla/">
  <img src="https://leetcard.jacoblin.cool/goutham_kalla?theme=dark&font=JetBrains%20Mono&ext=heatmap&border=0&radius=12" alt="LeetCode Stats"/>
</a>

<br/>

[![LeetCode](https://img.shields.io/badge/LeetCode-goutham__kalla-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/goutham_kalla/)
[![Codeforces](https://img.shields.io/badge/Codeforces-goutham__kalla-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/goutham_kalla)
[![SPOJ](https://img.shields.io/badge/SPOJ-goutham__kalla-337AB7?style=flat-square)](https://www.spoj.com/users/goutham_kalla/)
[![HackerRank](https://img.shields.io/badge/HackerRank-kallagoutham33-00EA64?style=flat-square&logo=hackerrank&logoColor=black)](https://www.hackerrank.com/profile/kallagoutham33)
[![InterviewBit](https://img.shields.io/badge/InterviewBit-kallagoutham33-6C3FBF?style=flat-square)](https://www.interviewbit.com/profile/kallagoutham33/)

</div>

---

## ✍️ Latest Writing

<!-- BLOG-POST-LIST:START -->
- [Your Transaction Is Waiting on the Speed of Light](https://medium.com/@kallagoutham33/your-transaction-is-waiting-on-the-speed-of-light-5af90a912cad?source=rss-3d72e13fefb5------2) &nbsp;·&nbsp; <sub>Aug 14, 2026</sub>
- [Why Doesn’t macOS Finder Have a “New File” Option? Here’s How I Fixed It For Myself.](https://medium.com/@kallagoutham33/why-doesnt-macos-finder-have-a-new-file-option-here-s-how-i-fixed-it-for-myself-6b979fff54ab?source=rss-3d72e13fefb5------2) &nbsp;·&nbsp; <sub>Jul 28, 2026</sub>
- [Behind zone1, zone2, and zone5: How Enterprise SaaS Tenants Work](https://medium.com/@kallagoutham33/behind-zone1-zone2-and-zone5-how-enterprise-saas-tenants-work-d690c59bb5bf?source=rss-3d72e13fefb5------2) &nbsp;·&nbsp; <sub>Jul 1, 2026</sub>
- [One App, Many Customers: The Multi-Tenancy Model](https://medium.com/@kallagoutham33/one-app-many-customers-the-multi-tenancy-model-be76aa965afc?source=rss-3d72e13fefb5------2) &nbsp;·&nbsp; <sub>Jun 23, 2026</sub>
- [What Happens After an Event Occurs?](https://medium.com/@kallagoutham33/what-happens-after-an-event-occurs-10faea21966f?source=rss-3d72e13fefb5------2) &nbsp;·&nbsp; <sub>Jun 22, 2026</sub><!-- BLOG-POST-LIST:END -->

<sub>Auto-synced daily from <a href="https://medium.com/@kallagoutham33">medium.com/@kallagoutham33</a></sub>

---

## 🎓 Credentials & Hackathons

<a href="https://www.credly.com/users/kalla-goutham"><img src="https://img.shields.io/badge/Verified_Badges-Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly"/></a>
<a href="https://devpost.com/kallagoutham"><img src="https://img.shields.io/badge/Hackathon_Projects-Devpost-003E54?style=for-the-badge&logo=devpost&logoColor=white" alt="Devpost"/></a>
<a href="https://github.com/kallagoutham/AZ-900-MicroSoft_Azure_Fundamentals"><img src="https://img.shields.io/badge/AZ--900-Azure_Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="AZ-900"/></a>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kallagoutham/kallagoutham/snake-output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kallagoutham/kallagoutham/snake-output/snake.svg"/>
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/kallagoutham/kallagoutham/snake-output/snake.svg" width="100%"/>
</picture>

<br/>

### 🤝 Let's Connect

Open to conversations on **distributed systems**, **applied AI**, and **system design**.

<a href="mailto:kallagoutham33@gmail.com"><img src="https://img.shields.io/badge/kallagoutham33@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="mailto:goutham.kalla@stonybrook.edu"><img src="https://img.shields.io/badge/goutham.kalla@stonybrook.edu-990000?style=for-the-badge&logo=maildotru&logoColor=white" alt="University Email"/></a>
<br/>
<a href="https://www.linkedin.com/in/goutham-kalla-3b6133112/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://gouthamkalla.netlify.app/"><img src="https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>

<br/><br/>

<i>"Correctness under failure beats speed on the happy path."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=110&section=footer" width="100%" alt="footer"/>

</div>
