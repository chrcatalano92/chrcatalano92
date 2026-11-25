# Christian Catalano — Software Engineer

**B.Sc. in Computer Science @ University of Naples Federico II (DIETI)**  
Focused on **Distributed Systems, Database Internals, Scalable Backend Architecture, Cloud Native (AWS) & AI Engineering**.

[![LinkedIn](https://shields.io)](https://linkedin.com)
[![LeetCode](https://shields.io)](https://leetcode.com)
[![HackerRank](https://shields.io)](https://hackerrank.com)
[![Docker](https://shields.io)](https://docker.com)
[![UNINA DIETI](https://shields.io)](https://unina.it)
[![Location](https://shields.io)]()
[![Status](https://shields.io)]()

---

### Architectural Philosophy & Engineering Focus

I design and build resilient, maintainable, and data-intensive software systems grounded in rigorous computer science fundamentals (CLRS asymptotic complexity, formal algorithm analysis, and data structure trade-offs):

* **Backend & Distributed Systems:** Designing modular, fault-tolerant RESTful services and concurrent applications adhering to **SOLID principles**, **GoF Design Patterns**, and structured architectural modeling (**UML / C4 Model**).
* **Database Internals & Storage Engines:** Investigating physical data layouts, query execution plans, and indexing trade-offs across relational, NoSQL, and AI vector engines (**B+ Tree, GiST, SP-GiST, Radix Tree, LSM-Tree, HNSW & ScaNN**), focusing on asymptotic bounds, tail latency (p95/p99), and memory footprint.
* **Cloud Native & AWS Infrastructure:** Deploying containerized multi-service architectures with **Docker**, **Docker Compose**, and **Amazon Web Services (AWS)**, enforcing deterministic environments and performance telemetry.
* **Applied AI & High-Dimensional Retrieval:** Engineering approximate nearest neighbor (ANN) pipelines and computer vision workflows overcoming the curse of dimensionality on 768D–3072D embeddings.

---

### Core Technical Stack

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | `Java` · `C` · `C++` · `Python` · `SQL` · `JavaScript / TypeScript` |
| **Databases & Big Data** | `PostgreSQL` · `PostGIS` · `pgvector` · `RocksDB (LSM-Tree)` · `MySQL` · `Redis` |
| **AI & Vector Indexing** | `HNSW` · `ScaNN` · `NumPy` · `PyTorch` · `OpenCV` |
| **Cloud & DevOps** | `AWS (EC2, RDS, S3)` · `Docker` · `Docker Compose` · `Git / GitHub Actions` · `Linux` |
| **Software Engineering** | `Algorithms & Data Structures (CLRS)` · `SOLID` · `Design Patterns` · `UML` · `JUnit` |

---

### Featured Engineering Projects

#### 1. [db-indexing-internals-benchmark](https://github.com) — Storage & AI Vector Engine Lab
* **Objective:** Reproducible Dockerized benchmark evaluating asymptotic scaling, tail latency (p50, p95, p99), write throughput, and memory footprint across **1M+ relational/LSM records** and **high-dimensional AI embeddings (768D–3072D)**.
* **Highlights:** Demonstrated **527k ops/s** write throughput and **0.01 ms** p50 lookup on **RocksDB (LSM-Tree)** vs. **PostgreSQL 17 (B+ Tree, GiST, SP-GiST)**, and up to **92x speedup** using **ScaNN / HNSW** over **Ball Tree** on 3072D embeddings.

#### 2. [DietiEstates25](https://github.com) — Enterprise Real Estate Platform
* **Role & Scope:** End-to-end Software Engineering project developed at [UNINA DIETI](https://unina.it) following formal requirements specification, architectural design, AWS cloud deployment, and automated verification.
* **Technical Highlights:** Layered backend architecture, spatial and multi-criteria property search, role-based access control (RBAC), clean separation of concerns, and relational persistence.

---

### Contact & Collaboration

* **Email:** `christian.catalano92@gmail.com`
* **Profiles:** [LinkedIn](https://linkedin.com) · [LeetCode](https://leetcode.com) · [HackerRank](https://hackerrank.com) · [Docker Hub](https://docker.com) · [UNINA DIETI](https://unina.it)
* **Availability:** Open to Software Engineering, Backend, Cloud, and Data/AI Engineering opportunities (Campania / Remote).
