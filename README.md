<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=900&duration=2400&color=5CD2FF&center=true&vCenter=true&width=620&height=70&lines=Hello+%F0%9F%91%8B;%E0%A4%A8%E0%A4%AE%E0%A4%B8%E0%A5%8D%E0%A4%A4%E0%A5%87;Hola;%E3%81%93%E3%82%93%E3%81%AB%E3%81%A1%E3%81%AF;%E4%BD%A0%E5%A5%BD;Bonjour;Detection+Engineer" alt="Hello in several languages, then: Detection Engineer" />

# Azhad Shahzad Shaik

**Detection Engineering · Applied ML · IEEE first-author**

M.S. Cyber Forensics. I work on intrusion detection, IoT security, and healthcare data pipelines, and I care about results that still hold up when you run them again.

[![GitHub Stats](https://github-readme-stats-sigma-five.vercel.app/api?username=s-shahzad&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)](https://github.com/s-shahzad)
[![GitHub Streak](https://streak-stats.demolab.com?user=s-shahzad&theme=github-dark-blue&hide_border=true)](https://github.com/s-shahzad)

</div>

---

## Research

**IEEE GCAIoT 2025 (first author).**
[Plugged-in and Protected: Leveraging Machine Learning to Secure IoT-Based EV Charging Stations from DoS Threats](https://doi.org/10.1109/GCAIoT68269.2025.11275540)
ML-based intrusion detection for IoT. Feature engineering, model selection, and evaluation on charging-station network traffic.

**JIST 2022 (co-author).**
[Remote monitoring system of heart conditions for elderly persons with ECG machine using IoT platform](https://jist.ir/en/Article/15692)
An IoT sensing and signal pipeline for continuous remote health screening.

---

## Universal NIDS

A multi-engine intrusion detection system. Suricata and Zeek telemetry feed a CatBoost classifier, with a signature / anomaly / ML fusion layer on top. I built it to be reproducible, since a lot of IDS papers aren't.

| Metric | Result |
|---|---|
| Flows analyzed | 87,432 |
| Runtime | 6 hr continuous soak |
| False positives | 0 |
| Validation replay (509 flows) | 10 alerts, 1.96% alert ratio, 100% reproducible |
| Detection engines | Signature, supervised ML, unsupervised ML, weighted fusion |
| Test coverage | 79% |

Detection content ships as Sigma rules, Splunk SPL, Suricata rules, and Zeek scripts, each mapped to the MITRE ATT&CK technique it catches.

Repo: [github.com/s-shahzad/Universal-NIDS](https://github.com/s-shahzad/Universal-NIDS)

---

## What I work on

- **Applied ML.** Feature pipelines, supervised and anomaly models, and evaluation that holds up under replay (scikit-learn, CatBoost, Pandas).
- **IoT and sensing.** Intrusion detection and health monitoring on real device telemetry.
- **Backend.** Python and FastAPI services with real auth, retries that aren't optimistic, and structured errors.
- **Healthcare data.** HL7 v2.5 to FHIR R4 pipelines on Azure, validated at every stage.

---

## Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=flat-square&logoColor=white)
![Zeek](https://img.shields.io/badge/Zeek-2980B9?style=flat-square&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma-4A90D9?style=flat-square&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Education & Certifications

- **M.S. Cyber/Computer Forensics**, Sacred Heart University
- **B.Tech, Electronics & Communication**, Koneru Lakshmaiah University
- CompTIA Security+ (SY0-701), Fortinet NSE 1 & 2

---

## Contact

Email: azhadshahzads@gmail.com
Portfolio: [azhadshahzadshaik.netlify.app](https://azhadshahzadshaik.netlify.app)
