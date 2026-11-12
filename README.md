# Hi, I'm Nghiep Ha Van 👋

**Student at UIT (University of Information Technology, VNU-HCM) · aspiring Data Engineer**

I build data pipelines and the applications that produce the data: from a transactional database to a star-schema warehouse and the analytics on top of it.

🇻🇳 *Xin chào! Mình là Hà Văn Nghiệp, sinh viên UIT, đang theo định hướng Data Engineering.*

## 🔭 Featured project

### [Chợ Trời UIT](https://github.com/Nghiepcoder17v/cho-troi-uit)
A peer-to-peer marketplace for UIT students, paired with an end-to-end data pipeline for transaction analytics.

- **OLTP app:** React + TypeScript frontend, FastAPI backend, SQL Server, JWT auth, a two-sided purchase flow (request → seller approval → both parties confirm) and two-way reviews.
- **ETL → Data Warehouse:** incremental extract with watermark and overlap window, idempotent upsert load, Star Schema, SCD Type 2 for `dim_product`, rejected-row quarantine, reconciliation, and a scheduler with retry and run locking.
- **Analytics:** SQL with CTEs and window functions (top majors buying IT gear, seasonal peaks for textbooks, days-to-sell by category, seller Pareto).
- **Engineering practice:** pytest suites for backend and pipeline, GitHub Actions CI (tests, Ruff, frontend build), Docker Compose, migrations, API contract and ERD/DWH docs.

## 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

**Focus areas:** data modeling · ETL/ELT · SQL analytics · data quality · backend APIs

## 🎯 Currently

- Polishing and documenting Chợ Trời UIT
- Looking for a **Data Engineering internship / fresher position**

## 📫 Contact

- Email: `Havannghiep7798@gmail.com`
- LinkedIn: `Nghiep Ha Van`
- Location: Ho Chi Minh City, Vietnam
