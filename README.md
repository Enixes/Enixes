<div align="center">

# Asu Singh

### Senior Software Engineer · Distributed Systems · Performance Engineering

I build **high-throughput, failure-tolerant production systems** for workloads where latency, scale and reliability matter.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/asusingh)
[![Portfolio](https://img.shields.io/badge/Portfolio-Source-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Enixes/portfolio-next)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:itsasusingh@gmail.com)

</div>

---

## ⚡ Engineering impact

<div align="center">

![20x](https://img.shields.io/badge/TRADE_THROUGHPUT-20×-00A86B?style=for-the-badge)
![50x](https://img.shields.io/badge/CACHE_ACCELERATION-UP_TO_50×-7C3AED?style=for-the-badge)
![90pct](https://img.shields.io/badge/DOWNTIME_REDUCTION-90%25-2563EB?style=for-the-badge)
![100gb](https://img.shields.io/badge/PRODUCTION_LOGS_ANALYSED-100_GB%2B-F59E0B?style=for-the-badge)

</div>

- Led a Java multithreading refactor that improved end-of-day trade processing by **20×**.
- Built an off-heap persistent cache that accelerated supported workflows by **up to 50×**.
- Automated recovery for halted processing, reducing operational downtime by **90%**.
- Built tooling for **100 GB+ production logs**, reducing incident-triage time by **30%**.
- Improved CI build time by **40%** while reducing AWS cost by **35%**.

Most of this work sits inside a production trading platform, so the interesting problems are usually around **concurrency, failure recovery, data volume, latency and operational correctness**.

---

## 🔭 What I’m working on now

### [TailCache](https://github.com/Enixes/TailCache) — Tail-Latency Trade-offs in Java Caching

![Java 21](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JMH](https://img.shields.io/badge/JMH-Benchmarking-4B5563?style=flat-square)
![Caffeine](https://img.shields.io/badge/Caffeine-On--Heap-22C55E?style=flat-square)
![Chronicle Map](https://img.shields.io/badge/Chronicle_Map-Off--Heap-8B5CF6?style=flat-square)
![Status](https://img.shields.io/badge/Status-Research_in_Progress-2563EB?style=flat-square)

A reproducible empirical systems project studying **Caffeine vs Chronicle Map** under identical deterministic workloads.

The questions I care about are not just “which is faster?” but:

- When does off-heap memory improve **p99 / p99.9 latency stability**?
- How much of that benefit is explained by **GC pressure**?
- What memory and serialization costs does off-heap access introduce?
- How sensitive is Chronicle Map to sizing assumptions?
- Do the expected advantages survive controlled, repeatable experiments?

> **Research rule:** a negative result is still a useful result if the experiment is sound.

---

## 🧩 Selected work

| Project / system | What was interesting about it |
|---|---|
| **[TailCache](https://github.com/Enixes/TailCache)** | Tail latency, JVM memory behaviour, off-heap vs on-heap caching, reproducible benchmarking |
| **XTP trading platform · ION** | High-throughput EOD processing, multithreading, event-driven workflows, failure recovery, production reliability |
| **Off-heap persistent caching · ION** | Removing inter-process calls and improving supported workflows by up to **50×** |
| **Production log analysis tooling** | Parsing **100 GB+** of logs and shortening incident diagnosis by **30%** |
| **[Hybrid Social Group Optimization](https://github.com/Enixes/Hybrid-Social-Group-Optimization-algorithm)** | Meta-heuristic optimization applied to medical-image classification; peer-reviewed research |
| **[portfolio-next](https://github.com/Enixes/portfolio-next)** | Experimental personal portfolio built with modern Next.js / React tooling |

---

## 📚 Research

### COVID-19 Infection Detection from Chest X-Ray Images Using Hybrid Social Group Optimization and Support Vector Classifier

**Cognitive Computation · Springer**

My earlier research work applied a hybrid meta-heuristic optimization technique to medical-image classification. It gave me an early taste for a style of engineering I still prefer today: **define a measurable hypothesis, build the system, instrument it, and let the results decide**.

→ [Research implementation](https://github.com/Enixes/Hybrid-Social-Group-Optimization-algorithm)

---

## 🛠️ Stack

### Systems & backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![C Sharp](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

### Data, infrastructure & observability

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 🧠 Problems I like working on

`Distributed systems` · `Concurrency` · `Tail latency` · `Caching` · `JVM/runtime behaviour` · `Performance engineering` · `Failure recovery` · `Production observability` · `Applied ML`

I’m especially interested in systems questions where **average-case performance hides the real operational story**.

---

<div align="center">

**6+ years building production software · Senior SDE @ ION Trading · India**

</div>
