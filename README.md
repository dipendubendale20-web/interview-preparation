# Backend Interview Preparation (Java 8 + Python)

Study notes for **senior backend engineer interviews**. There is one detailed guide per technology, and each has 100+ questions ordered from basic to scenario-based. Every question comes with follow-up cross-questions, working Java 8 or Python examples, Mermaid diagrams, production scenarios, and a one-page cheat sheet. The examples draw on real-world backend work: high-volume event ingestion (Kafka, IBM MQ, GCP Pub/Sub), 200K+ record batch pipelines, Redis caching, Spring Security, and a FastAPI reporting platform.

## How to use these notes

1. **Read** a section end to end. Start with the mental model, then the Q&A.
2. **Hide the answers.** Go back to the questions and answer them out loud, as you would in an interview.
3. **Self-test** with the collapsible *Cross-questions*. These are the follow-ups interviewers actually ask.
4. **Solve the puzzles.** Try each "🎯 Predict the output" puzzle before you reveal the answer.
5. **The night before**, review only the **cheat sheet** and tick off the **revision checklist**.

Difficulty legend: 🟢 Basic · 🟡 Intermediate · 🔴 Advanced · ⚡ Scenario

## Progress

| # | Topic | Notes | Questions | Status |
|---|-------|-------|-----------|--------|
| 01 | Core Java | [01_Core_Java.md](01_Core_Java.md) | 134 | ✅ |
| 02 | Multithreading & Concurrency | [02_Multithreading_Concurrency.md](02_Multithreading_Concurrency.md) | 116 | ✅ |
| 03 | Spring Boot | [03_Spring_Boot.md](03_Spring_Boot.md) | 114 | ✅ |
| 04 | Spring Security | [04_Spring_Security.md](04_Spring_Security.md) | 120 | ✅ |
| 05 | Spring Data JPA & Hibernate | [05_Spring_Data_JPA_Hibernate.md](05_Spring_Data_JPA_Hibernate.md) | – | ⏳ |
| 06 | Microservices & Spring Cloud | [06_Microservices_Spring_Cloud.md](06_Microservices_Spring_Cloud.md) | – | ⏳ |
| 07 | Apache Kafka | [07_Apache_Kafka.md](07_Apache_Kafka.md) | – | ⏳ |
| 08 | IBM MQ & GCP Pub/Sub | [08_IBM_MQ_GCP_PubSub.md](08_IBM_MQ_GCP_PubSub.md) | – | ⏳ |
| 09 | SQL (PostgreSQL / MySQL) | [09_SQL_PostgreSQL_MySQL.md](09_SQL_PostgreSQL_MySQL.md) | – | ⏳ |
| 10 | MongoDB | [10_MongoDB.md](10_MongoDB.md) | – | ⏳ |
| 11 | Redis | [11_Redis.md](11_Redis.md) | – | ⏳ |
| 12 | Python & FastAPI | [12_Python_FastAPI.md](12_Python_FastAPI.md) | – | ⏳ |
| 13 | Docker & CI/CD | [13_Docker_CICD.md](13_Docker_CICD.md) | – | ⏳ |
| 14 | System Design | [14_System_Design.md](14_System_Design.md) | – | ⏳ |
| 15 | Design Patterns | [15_Design_Patterns.md](15_Design_Patterns.md) | – | ⏳ |

## Suggested 4-week study plan

| Week | Focus | Files | Daily routine |
|------|-------|-------|---------------|
| 1 | Java foundations | 01, 02, 15 | 25 Q&A, then self-test on yesterday's cross-questions |
| 2 | Spring ecosystem | 03, 04, 05, 06 | One section a day, then build one hands-on example |
| 3 | Data & messaging | 07, 08, 09, 10, 11 | Q&A plus one production scenario explained out loud |
| 4 | Python, delivery & design | 12, 13, 14 | Two mock system-design rounds, then all cheat sheets |

On the last two days, go through only the cheat sheets and revision checklists, plus the questions you marked as weak.
