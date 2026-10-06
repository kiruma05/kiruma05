<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Frank Joseph Kiruma, Data Engineer: streaming and CDC pipelines, AML transaction monitoring, data warehousing and BI" src="assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/frank-kiruma-45293b26a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:frankkiruma05@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Databricks%20Certified-Data%20Engineer%20Associate-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks Certified"/>
</p>

I build the data platforms that banks and financial institutions run on: real-time transaction streams,
anti-money-laundering (AML) monitoring, data warehouses and BI. My focus is pipelines that are reliable,
auditable and secure enough for regulated financial data.

---

## What I work on

**Streaming & CDC.** Change-data-capture from core banking systems with Debezium and Kafka, processed in Flink and Spark.

**AML transaction monitoring.** Behavioural features computed in Spark that feed rules and anomaly-detection models, with alerts flowing into case management.

**Data warehousing & BI.** Warehouse modelling on Apache Doris and departmental reporting in Apache Superset for a commercial bank.

**Data security & governance.** Encryption, role-based access with Apache Ranger and Keycloak, and database activity monitoring with IBM Guardium.

---

## Core stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark"/>
  <img src="https://img.shields.io/badge/Apache%20Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white" alt="Apache Flink"/>
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka"/>
  <img src="https://img.shields.io/badge/Debezium-91D443?style=flat-square" alt="Debezium"/>
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Apache Airflow"/>
  <img src="https://img.shields.io/badge/Apache%20Doris-45B4E8?style=flat-square&logo=apache&logoColor=white" alt="Apache Doris"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle"/>
  <img src="https://img.shields.io/badge/Apache%20Superset-20A6C9?style=flat-square&logo=apachesuperset&logoColor=white" alt="Apache Superset"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
</p>

<sub>Also: Dagster, dbt, Iceberg, Trino, NiFi, Redis, FastAPI, Spring Boot, React, Apache Ranger, Keycloak, Power BI.</sub>

---

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**mobile-money-fraud-pipeline**](https://github.com/kiruma05/mobile-money-fraud-pipeline) | Chunked ETL that loads 6.3M mobile money transactions (PaySim) into PostgreSQL in about 2 minutes, plus a ledger-reconciliation fraud rule that catches 99.3% of fraudulent transfers, served through an importable Superset dashboard and a short technical report. | Python · pandas · PostgreSQL · Apache Superset · Docker |
| [**credit-score-ML**](https://github.com/kiruma05/credit-score-ML) | End-to-end credit scoring and fraud detection: Airflow DAGs for training and scheduled retraining, MLflow model registry, and a FastAPI scoring service that returns SHAP explanations. Containerised, with a Jenkins pipeline and Trivy/OPA image security checks. | Airflow · Spark · MLflow · FastAPI · PostgreSQL · Docker |
| [**fleet-model**](https://github.com/kiruma05/fleet-model) | Proof of concept for fleet telematics: a scheduled collector ingests vehicle telemetry, scores driver safety, detects speeding and harsh-driving violations, and flags likely maintenance needs. | Python · XGBoost · scikit-learn · FastAPI · APScheduler |
| [**griggsML**](https://github.com/kiruma05/griggsML) | Voice-to-SQL agent: speech is transcribed with a fine-tuned Whisper model, and a local LLM (Llama via Ollama) turns the question into SQL against a business database. | Whisper · Ollama · Python · Docker |
| [**animal-notification-system**](https://github.com/kiruma05/animal-notification-system) | Livestock tracking and alerting system built for a ranching company in Dodoma. | Spring Boot · PostgreSQL · JavaScript |

---

## Experience

- **Data Engineer**, software company serving East African financial institutions: AML monitoring, CDC pipelines, data warehouse and BI for a commercial bank.
- **NARCO (National Ranching Company):** backend services and data ingestion for livestock tracking and notifications.
- **FADEMO:** internal financial management system and APIs (Laravel).

## Certifications & education

- Databricks Certified Data Engineer Associate
- IBM Watson (data) · IBM Guardium (data security)
- BSc Software Engineering, University of Dodoma (UDOM)

---

<p align="center">Open to conversations about data engineering, streaming and financial-crime analytics: <a href="mailto:frankkiruma05@gmail.com">frankkiruma05@gmail.com</a></p>
