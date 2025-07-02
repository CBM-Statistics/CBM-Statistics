# 🏛️ Central Bank of Malta – Statistics Department

Welcome to the official GitHub Organization of the **Statistics Department** at the **Central Bank of Malta (CBM)**.  
This GitHub space is designed to host projects, tools, and documentation supporting the collection, transformation, analysis, and dissemination of statistical data.

---

## 🧭 Organizational Overview

The Statistics Department plays a central role in:

- Managing **data collection and processing** from domestic and external sources
- Ensuring compliance with **ECB**, **IMF**, and **Eurostat** reporting standards
- Automating **data pipelines** and reducing manual interventions
- Supporting internal and external stakeholders with **reliable statistics**

---

## 🔗 Key Teams Involved

### 🔹 Business Architecture & Application Development (BAA)
- Designs internal tools, scripts, and applications
- Develops and maintains **ETL pipelines**, Python utilities, and SQL procedures
- Integrates systems and supports automation initiatives

### 🔹 External Statistics Team
- Produces key international datasets: **BoP**, **IIP**, **International Reserves**
- Validates and reconciles external sector data
- Manages outbound data flows to ECB/IMF

### 🔹 Internal Statistics Teams
- Handles survey workflows (e.g., banking, finance, insurance)
- Maintains business registers and static tables
- Works closely with data providers and internal units

---

## ⚙️ ETL Framework & Automation Setup

The department uses a modular **ETL (Extract, Transform, Load)** framework to automate the statistical data pipeline. The framework is built using:

- **Python**: Core scripting language for automation, transformation, and validation
- **Oracle SQL**: Used for querying, transforming, and storing structured data
- **Cron/Scheduled Tasks**: For executing recurring ETL jobs (e.g., monthly surveys)
- **Version Control (GitHub)**: All scripts and logic are maintained in repositories with branch tracking and audit trails
- **Data Warehouse (BDA/Infostat)**: Main source and destination for transformed datasets

### ETL Stages:

| Stage       | Description |
|-------------|-------------|
| **Extract** | Pull data from BDA/Infostat, Excel/CSV uploads, or survey systems |
| **Transform** | Apply business rules, filter criteria, mappings, and harmonization |
| **Load**     | Push data into output schemas or generate validated output files |

Workflows are designed to be:
- Modular and reusable
- Transparent (code tracked via Git)
- Auditable (logs and change tracking)
- Documented (via `README.md` and `docs/` folders in each repo)

---

## 📁 Repository Structure

| Repository                | Description                                             |
|---------------------------|---------------------------------------------------------|
| `data-catalogue`          | Metadata management, data inventory, ownership mapping |
| `survey-automation`       | Python + SQL scripts to automate survey-based data flows |
| `external-statistics-tools` | Scripts for international reporting, BoP/IIP modules |
| `bba-apps`                | Internal tool development and ETL integration scripts |
| `shared-utils`            | Common Python functions, DB connectors, logging modules |

---

## ✅ Best Practices

- Use **feature branches** with descriptive names
- Open **pull requests** for all changes
- Add a `README.md` to every repository
- Use **GitHub Projects** or **Issues** for coordination
- Maintain access control via GitHub Teams

---

## 👥 Contact Points

| Team | Contact |
|------|---------|
| BAA Team | baa@centralbankmalta.org |
| External Statistics | external.stats@centralbankmalta.org |
| Department Head | statistics@centralbankmalta.org |

---

© 2025 Central Bank of Malta – Statistics Department  
This repository is for **internal use only** unless otherwise authorized.
