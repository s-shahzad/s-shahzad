<!-- GENERATED:header START -->
<div align="center">

# Azhad Shahzad Shaik

**Post-Quantum Migration Security · ML-Based Detection · IEEE first-author**

[Portfolio](https://azhadshahzadshaik.netlify.app) ·
[ORCID](https://orcid.org/0009-0009-6450-5837) ·
[Google Scholar](https://scholar.google.com/citations?user=l2McKRYAAAAJ) ·
[LinkedIn](https://www.linkedin.com/in/azhad-shahzad-shaik/)

</div>
<!-- GENERATED:header END -->

M.S. in Cybersecurity. I work on the security of the post-quantum migration in real infrastructure: measuring whether systems actually move to PQC or only look like they have. It grows out of my intrusion-detection and IoT-protocol work, and I care about results that still hold up when you run them again.

---

## What I work on

- **Post-quantum migration security.** Measuring and detecting incomplete, downgraded, or misconfigured PQC rollouts across TLS and OT/IoT fleets. Crypto-agility and cryptographic supply-chain assurance, not scheme design.
- **ML for intrusion and anomaly detection.** Feature pipelines, supervised and anomaly models, and evaluation that holds up under replay (scikit-learn, CatBoost, Pandas).
- **Critical-infrastructure and IoT protocols.** Attack-surface modeling (OCPP, MQTT, CAN), intrusion detection, and sensing on real device telemetry.
- **Backend.** Python and FastAPI services with real auth, retries that aren't optimistic, and structured errors.

---

## PQC-readiness scanner

A small tool that checks whether TLS endpoints have actually moved to post-quantum key exchange, or only look like they have. It flags hosts that negotiate classical-only key exchange, that can be downgraded, or whose migration is incomplete across a fleet. The start of a measurement-first take on the PQC transition.

*Repository is private pending publication of the associated papers.*

---

## Research

**IEEE GCAIoT 2025 (first author).**
[Plugged-in and Protected: Leveraging Machine Learning to Secure IoT-Based Electric Vehicle Charging Stations from Denial-of-Service Threats](https://doi.org/10.1109/GCAIoT68269.2025.11275540)
ML-based intrusion detection for IoT. Feature engineering, model selection, and evaluation on charging-station network traffic.

**JIST 2022 (co-author).**
[Remote monitoring system of heart conditions for elderly persons with ECG machine using IoT platform](https://doi.org/10.52547/jist.15692.10.37.11)
An IoT sensing and signal pipeline for continuous remote health screening.

---

## Fusion NIDS

A multi-engine intrusion detection system. Suricata and Zeek telemetry feed a CatBoost classifier, with a signature / anomaly / ML fusion layer on top. I built it to be reproducible, since a lot of IDS papers aren't.

| Metric | Result |
|---|---|
| Per-packet records | 87,533 |
| Soak duration | 21,600 s configured; 3 h 19 m of flow records |
| Emitted alerts | 0 |
| Peak capture-side packet loss | 30.9% |
| Peak memory | 409 MB |
| Restart recovery | 13.3 s |
| Detection engines | Signature, supervised ML, unsupervised ML, weighted fusion |
| Test coverage | 79% |

**What this does and does not show.** The corpus contained no attack-labelled traffic, so zero emitted alerts demonstrates **pipeline stability under sustained load — not detection quality, and not a false-positive rate.** I audited my own headline number and published the qualification rather than letting it stand unqualified.

Detection content ships as Sigma rules, Splunk SPL, Suricata rules, and Zeek scripts, each mapped to the MITRE ATT&CK® technique it catches.

Repo: [github.com/s-shahzad/fusion-nids](https://github.com/s-shahzad/fusion-nids)

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

<!-- GENERATED:credentials START -->
- **<!--f:education.ms.degree-->Master of Science, Cybersecurity<!--/f-->** — Jack Welch College of Business & Technology, <!--f:education.ms.school-->Sacred Heart University<!--/f-->
- **Bachelor of Technology, Electronics and Communication Engineering** — Koneru Lakshmaiah Education Foundation (KL University) — specialization in Embedded Controllers, IoTs & Power Electronics, First Class with Distinction
- **CompTIA Security+ ce (SY0-701)** — CompTIA, valid through October 2028
- **NSA CAE Designated Institution Certificate in Cyber Defense** — Sacred Heart University
<!-- GENERATED:credentials END -->

---

## Contact

<!-- GENERATED:contact START -->
Email: shaikazhadshahzad@gmail.com
ORCID: [<!--f:identity.orcid-->0009-0009-6450-5837<!--/f-->](https://orcid.org/0009-0009-6450-5837)
Portfolio: [azhadshahzadshaik.netlify.app](https://azhadshahzadshaik.netlify.app)
<!-- GENERATED:contact END -->
