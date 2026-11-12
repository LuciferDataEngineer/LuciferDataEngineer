<h1 align="center">Hi, I'm LuciferDataEngineer 👋</h1>
<p align="center"><b>Data Engineer · Analytics Engineer</b> · Melbourne, Australia</p>
<p align="center">I build production-style data pipelines on open data: ingestion, lakehouse modelling, data quality and decision-focused dashboards.</p>

---

### 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)
![SQLMesh](https://img.shields.io/badge/SQLMesh-805AD5)
![MetricFlow](https://img.shields.io/badge/MetricFlow-7C3AED)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black)
![DuckDB VSS](https://img.shields.io/badge/DuckDB_VSS-FFF000?logo=duckdb&logoColor=black)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Dagster](https://img.shields.io/badge/Dagster-4F43DD?logo=dagster&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?logo=polars&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka%20%2F%20Redpanda-231F20?logo=apachekafka&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-2B6CB0?logo=apache&logoColor=white)
![Apache Polaris](https://img.shields.io/badge/Apache_Polaris-0E6EB8?logo=apache&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?logo=minio&logoColor=white)
![lakeFS](https://img.shields.io/badge/lakeFS-3C8C4E)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?logo=delta&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-91D443?logoColor=black)
![OpenLineage](https://img.shields.io/badge/OpenLineage-74A4BC?logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?logo=opentelemetry&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-60D0E4?logoColor=black)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Apache Flink](https://img.shields.io/badge/Apache_Flink-E6526F?logo=apacheflink&logoColor=white)
![Feast](https://img.shields.io/badge/Feast-FF6F00?logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![PyMC](https://img.shields.io/badge/PyMC-5B2C6F)
![LightGBM](https://img.shields.io/badge/LightGBM-1B9AD7?logoColor=white)
![Evidently](https://img.shields.io/badge/Evidently-ED0400?logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white)
![Argo](https://img.shields.io/badge/Argo_Workflows-EF7B4D?logo=argo&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?logo=opentofu&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?logo=postgresql&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face_(sentence--transformers)-FFD21E?logo=huggingface&logoColor=black)
![ECharts](https://img.shields.io/badge/Apache_ECharts-AA344D?logo=apacheecharts&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?logo=trino&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great_Expectations-FF6310?logoColor=white)
![Pandera](https://img.shields.io/badge/Pandera-82B428?logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

**Patterns I work with:** medallion and lakehouse architecture · incremental loads and high-watermarks · dimensional modelling · data contracts · dbt tests and data quality · orchestration · CI/CD for data · static dashboards on GitHub Pages

---

### 🚀 Featured projects

<!-- PROJECTS:START -->
| Project | What it answers | Stack | Live |
|---|---|---|---|
| [**living-cost-squeeze**](https://github.com/LuciferDataEngineer/living-cost-squeeze) | Who is losing Australia's cost-of-living race, living costs vs wages by household type, with a next-quarter forecast range | lakeFS on MinIO · SQLMesh + DuckDB · Argo Workflows on kind · OpenTelemetry + Jaeger · statsforecast · GitHub Pages | [Live dashboard](https://luciferdataengineer.github.io/living-cost-squeeze/) |
| [**road-toll-reversal**](https://github.com/LuciferDataEngineer/road-toll-reversal) | Where Australia's rising road toll is concentrated and where to focus summer enforcement | DuckDB · ODCS data contracts · Apache Polaris + Iceberg on MinIO · Airflow 3 · PyMC · ClickHouse · Helm/kind · GitHub Pages | [Live dashboard](https://luciferdataengineer.github.io/road-toll-reversal/) |
| [**home-battery-payback**](https://github.com/LuciferDataEngineer/home-battery-payback) | Where is Australia's home-battery rebate landing, and where does a battery pay back from real wholesale price swings? | PyFlink 2.1 SQL (event-time windows, watermarks) · Apache Iceberg (REST catalog + MinIO + Trino merge-on-read) · DuckDB marts · Dagster asset checks · OpenLineage · Pandera contracts · kind/Kubernetes Job · GitHub Pages | [Live dashboard](https://luciferdataengineer.github.io/home-battery-payback/) |
| [**aged-care-bed-block**](https://github.com/LuciferDataEngineer/aged-care-bed-block) | CDC lakehouse tracking Australia's residential aged care place shortfall (40,939 places short of a 78-per-1,000 benchmark; only 794 places added last year vs ~10,600 needed). | Postgres 16 · Debezium Server · Redpanda · PySpark Structured Streaming · Delta Lake MERGE + SCD2 · OpenLineage · data contracts · DuckDB · Terraform · GitHub Actions | [Live dashboard](https://luciferdataengineer.github.io/aged-care-bed-block/) |
| [**jobs-risk-radar**](https://github.com/LuciferDataEngineer/jobs-risk-radar) | Which Australian regions are seeing unemployment rise, and where should support be targeted? | Polars · dbt-duckdb · Dagster · Feast (DuckDB offline/SQLite online, point-in-time retrieval) · LightGBM with MLflow · Evidently · kind/Kubernetes · Terraform Docker provider | [Live dashboard](https://luciferdataengineer.github.io/jobs-risk-radar/) |
| [**elective-wait-metrics**](https://github.com/LuciferDataEngineer/elective-wait-metrics) | Where are elective surgery patients missing recommended waits across Australia? | AIHW snapshots · Polars · dbt-duckdb · MetricFlow semantic layer saved queries · Dagster · Great Expectations Data Docs · static five-tab dashboard | [Live dashboard](https://luciferdataengineer.github.io/elective-wait-metrics/) |
| [**grocery-shock-agent**](https://github.com/LuciferDataEngineer/grocery-shock-agent) | Which grocery lines are driving price pressure, and how could basket swaps change it? | Polars · dbt-duckdb · Dagster · Great Expectations · DuckDB VSS HNSW · 128-d feature hashing · deterministic ReAct tool-use agent · ECharts | [Live dashboard](https://luciferdataengineer.github.io/grocery-shock-agent/) |
| [**ai-grid-pressure**](https://github.com/LuciferDataEngineer/ai-grid-pressure) | Is the AI data-centre boom straining Australia's grid? Where NEM demand peaks, price spikes and household power bills are showing stress | Iceberg · Trino · OpenLineage/Marquez · Great Expectations · dbt-duckdb · Dagster | [Live dashboard](https://luciferdataengineer.github.io/ai-grid-pressure/) |
| [**housing-slump-radar**](https://github.com/LuciferDataEngineer/housing-slump-radar) | Australia's 2026 housing slump: where prices and approvals are softening, how repayments jumped after the cash rate hit 4.85%, and which Victorian suburbs fell hardest | ClickHouse · Redpanda · data contracts · dbt-duckdb · Dagster · ECharts · GitHub Pages | [Live dashboard](https://luciferdataengineer.github.io/housing-slump-radar/) |
| [**supply-chain-control-tower**](https://github.com/LuciferDataEngineer/supply-chain-control-tower) | Logistics control tower on 100k real e-commerce orders: on-time delivery, late lanes, freight burden, seller delays and review impact, with recommendations | DuckDB · dbt · Dagster · ECharts · GitHub Actions | [Live dashboard](https://luciferdataengineer.github.io/supply-chain-control-tower/) |
| [**rba-rate-shock-copilot**](https://github.com/LuciferDataEngineer/rba-rate-shock-copilot) | An AI copilot answering questions about the RBA's 2026 cash-rate rises and what they cost mortgage holders, with RAG over Reserve Bank statements | Postgres + pgvector · sentence-transformers embeddings · RAG · MetricFlow semantic layer · dbt-duckdb · Dagster · OpenTofu | [Live dashboard](https://luciferdataengineer.github.io/rba-rate-shock-copilot/) |
| [**vic-heat-health-sentinel**](https://github.com/LuciferDataEngineer/vic-heat-health-sentinel) | Which Victorian areas face dangerous heat in the next 16 days, who lives there, and where should councils prepare cooling centres and outreach? | Redpanda · PyFlink · Delta Lake · Feast · scikit-learn + MLflow · Evidently · dbt-duckdb · Dagster · OpenTofu · Kubernetes (kind) | [Live dashboard](https://luciferdataengineer.github.io/vic-heat-health-sentinel/) |
| [**fuel-shock-radar**](https://github.com/LuciferDataEngineer/fuel-shock-radar) | Australia's 2026 fuel price shock: which day is cheapest to fill up, are retail margins fair, and how much more do regional drivers pay? | Postgres · Debezium CDC · Redpanda · PySpark Structured Streaming · Delta Lake (MERGE/SCD2) · Airflow Datasets · OpenLineage/Marquez · Great Expectations · DuckDB | [Live dashboard](https://luciferdataengineer.github.io/fuel-shock-radar/) |
| [**aus-hazard-stream**](https://github.com/LuciferDataEngineer/aus-hazard-stream) | Is the 2026 Gippsland earthquake swarm unusual, and where do quakes and bushfire hotspots threaten people and infrastructure? (near real-time) | Redpanda/Kafka · JSON Schema registry · Apache Iceberg · H3 + DuckDB spatial · dbt-duckdb · Dagster · Soda · MapLibre | [Live map](https://luciferdataengineer.github.io/aus-hazard-stream/) |
| [**nem-grid-pulse**](https://github.com/LuciferDataEngineer/nem-grid-pulse) | Will Australia's AI data-centre boom strain the electricity grid? Prices, negative-price hours, renewables and load scenarios across the NEM | Python · dbt-duckdb · Dagster · data contracts · ECharts · GitHub Actions | [Dashboard](https://luciferdataengineer.github.io/nem-grid-pulse/) |
| [**nt-education-insights**](https://github.com/LuciferDataEngineer/nt-education-insights) | Why is Aboriginal school attendance in the NT falling, where is it worst, and what should policymakers act on? | Python · DuckDB · pandas · medallion pipeline · Plotly · Streamlit | [Dashboard](https://luciferdataengineer.github.io/nt-education-insights/) |
| [**victorian-home-data-platform**](https://github.com/LuciferDataEngineer/victorian-home-data-platform) | A free-first medallion platform for Victorian property market research | Python · medallion architecture | |
<!-- PROJECTS:END -->

All projects use **free, openly licensed public data** (AEMO, ACARA, ABS, NT Department of Education and others) and document their sources, cleaning, transformations and limitations in the README.

---

### 📊 GitHub stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=LuciferDataEngineer&show_icons=true&hide_border=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LuciferDataEngineer&layout=compact&hide_border=true" />
</p>

### 🤝 Let's connect

Open to data engineering and analytics engineering roles in Australia. Feel free to open an issue on any project or reach out.
