# Chien-Hsiang Yeh

Canberra, Australia | [linkedin.com/in/chienhsiang-yeh](https://linkedin.com/in/chienhsiang-yeh) | [github.com/chypwc](https://github.com/chypwc)

## Summary

- Data analyst with an Economics PhD background, combining statistics, econometrics, causal reasoning, forecasting, and quantitative modelling with practical analytics delivery.
- Focused on public-sector reporting and decision-support analytics, demonstrated through portfolio projects in education, public health surveillance, workers compensation, and patient-level costing.
- Skilled in turning raw operational data into validated reporting datasets, SQL checks, Power BI dashboards, written briefs, and stakeholder-ready insights with clear assumptions and caveats.
- Experienced with Azure and AWS ETL pipelines for data ingestion, transformation, validation, and reporting-ready analytics.

## Skills

- **Data & Analytics:** SQL, Python, pandas, NumPy, Excel, Stata, R, MATLAB, statistical modelling, econometrics, time-series forecasting
- **Databases & SQL Platforms:** SQL Server, SSMS, PostgreSQL, MySQL, Azure SQL Database, Snowflake, AWS Redshift, DynamoDB
- **Azure Stack:** Azure Data Factory, Azure Databricks, Azure Data Lake Storage Gen2, Synapse Analytics, Azure SQL Database, serverless SQL, Power BI semantic models
- **Power BI & Reporting:** Power BI, DAX, Power Query, star-schema modelling, reusable metrics, Excel Power Pivot, Tableau, stakeholder reporting
- **AWS Stack:** Glue, Athena, EMR, Lambda, Step Functions, S3, DynamoDB, SageMaker, MWAA, DMS, API Gateway
- **ETL, APIs & Automation:** PySpark, dbt, Airflow, Kafka, FastAPI, Streamlit, Docker, Terraform, GitHub Actions, CloudFormation
- **AI & ML:** scikit-learn, LangChain, Retrieval-Augmented Generation (RAG), prompt engineering, OpenAI Responses API

## Experience

**Data Engineer Intern** — JobpinAI (Aug 2025 – Sep 2025)
- Redesigned a two-step PDF extraction pipeline into a single AI-driven workflow using the OpenAI Responses API, cutting processing costs by 40% and improving parse accuracy on unstructured resume documents.
- Refined prompt strategies for ATS keyword extraction, raising parsing reliability across diverse document formats.

**Data Engineer** — InsightFlow (June 2025 – Aug 2025)  
[github.com/InsightFlow8/insightflow](https://github.com/InsightFlow8/insightflow)
- Analysed large-scale customer transaction data with 3M+ records to identify purchasing patterns and support business decision-making and reporting.
- Developed SQL/AWS data pipelines and analytical datasets to support repeatable reporting on customer behaviour and product-level purchasing trends.
- Delivered Streamlit/FastAPI analytics tools that enabled non-technical users to explore purchasing patterns without ad-hoc data requests.
- Automated data processing workflows, reducing manual reporting effort and improving timeliness of analysis.

**Research Assistant (Data Analyst)** — ANU RSE (Oct 2024 – May 2025)
- Prepared and transformed raw household survey datasets into structured, analysis-ready panel data using Python and Stata, improving data consistency, reproducibility, and usability for education and labour outcome research.
- Delivered statistical summaries, tables, and written briefs to support evidence-based research in labour and education policy.
- Developed OCR-based data extraction pipelines to digitise historical government records, enabling analysis of previously inaccessible data on China's agricultural reform.

**Teaching Assistant** — ANU RSE (Feb 2019 – Nov 2024)
- Taught econometrics, causal inference, dynamic programming, and macroeconomics to 500+ students across 20+ tutorial groups, adapting explanations to diverse technical backgrounds.
- Coordinated marking standardisation across tutorial groups, reducing assessment inconsistency and freeing academic staff time for research.

## Projects

### Public Sector Reporting and Decision-Support Portfolio

**Education Azure Lakehouse Analytics and Monthly Reporting Portfolio**  
[github.com/chypwc/education_data_lakehouse](https://github.com/chypwc/education_data_lakehouse)
- Built an Azure analytics and reporting portfolio using synthetic school, student, attendance, assessment, and event data to demonstrate end-to-end ingestion, validation, reporting layers, Power BI dashboards, and written insights.
- Implemented three Azure reporting patterns: an ADF/Synapse baseline pipeline, a Databricks Bronze/Silver/QA/Gold lakehouse, and an Azure SQL monthly insights pipeline with audit, quality, and reporting layers.
- Developed SQL validation checks, reconciliation outputs, reporting views, Power BI dashboard pages, and stakeholder-facing briefs to support reliable decision-making and clear communication of trends, caveats, and data quality issues.

**Patient-Level Costing and ABF Decision Support Portfolio**  
[github.com/chypwc/patient-costing-abf](https://github.com/chypwc/patient-costing-abf)
- Built a SQL Server and Excel patient-level costing workflow connecting clinical activity, resource-use, and general-ledger data to produce validated reporting outputs for service-line costing, budget review, and resource-planning decisions.
- Designed controlled costing, validation, and reconciliation logic covering direct assignment, indirect allocation, overhead allocation, and unallocated exceptions, preserving traceability from source data to reporting outputs.
- Developed an Excel decision-support workbook using Power Query, Power Pivot, slicers, PivotTables, and charts to communicate service-line cost, cost drivers, high-cost encounters, ABF-style comparison, and data-quality insights.

**Public Sector Workers Compensation Reporting Portfolio**  
[github.com/chypwc/workers-comp-reporting](https://github.com/chypwc/workers-comp-reporting)
- Built an end-to-end workers compensation reporting portfolio using synthetic claims, return-to-work, financial, governance, and reporting extracts to support claims operations, financial reporting, governance review, and reporting obligations.
- Designed SQL Server data layers from raw ingestion to curated reporting views, with controlled mappings, data quality checks, load audit controls, reconciliation outputs, and privacy-aware reporting rules.
- Delivered decision-support outputs including Power BI dashboards, an annual-report-style Excel pack, FOI-style de-identified extract, executive briefing, and statistical/ML high-cost claim review appendix.

**Public Health Surveillance Lakehouse**  
[github.com/chypwc/health-surveillance-lakehouse](https://github.com/chypwc/health-surveillance-lakehouse)
- Built an Azure-based public health surveillance workflow simulating REDCap-style case intake and lab test exports to support case reporting, testing outcomes, facility monitoring, workflow review, and data quality triage.
- Designed staging, curated, quality, and reporting layers with SQL views, Parquet outputs, row-count reconciliation, and Power BI-facing Synapse reporting views.
- Implemented SQL validation checks and documentation for missing identifiers, duplicate cases, invalid statuses, future dates, lab result issues, ICU admission logic, facility gaps, issue triage, and repeatable operational reporting.

**ACT Employment Analysis**  
[github.com/chypwc/act_employment](https://github.com/chypwc/act_employment)
- Built a SQL Server star schema and Power BI dashboard using 500,000+ ABS Labour Force records to turn ACT employment data into decision-support outputs for workforce planning, gender equity monitoring, and economic resilience analysis.
- Developed DAX measures and interactive Power BI views for employment growth, full-time/part-time composition, gender ratios, industry concentration, and workforce volatility to support repeatable labour market reporting.
- Produced a policy-oriented analytical report translating trend, concentration, and volatility findings into practical considerations for workforce diversification, employment stability monitoring, and ACT public-sector planning.

**Community Battery Network Optimisation**  
[github.com/chypwc/battery-network-dp](https://github.com/chypwc/battery-network-dp)
- Built a community battery decision-support framework using dynamic programming, Q-learning, stochastic DP, AEMO price data, and OpenDSS network simulation to evaluate dispatch revenue, voltage safety, tariff design, and investment viability.
- Modelled battery dispatch under wholesale spot and retail time-of-use business models, quantifying revenue, price volatility, network-safety trade-offs, and long-term NPV outcomes.
- Analysed price uncertainty and the value of perfect price information using stochastic DP with Bayesian belief updating, supporting energy-market decision-making under uncertain market conditions.

### AWS Data Engineering Portfolio

**AWS Spark and SQL Lakehouse Data Pipeline**  
[github.com/chypwc/aws-dms-emr-terraform](https://github.com/chypwc/aws-dms-emr-terraform)
- Built an AWS lakehouse workflow using AWS DMS, EMR Spark, S3, Glue Catalog, SQL, Airflow/MWAA, Terraform, and GitHub Actions to automate ingestion and transformation from PostgreSQL into reporting-ready analytical datasets.
- Designed scalable Spark and SQL transformation workflows to improve data quality, repeatability, and availability for downstream analytics and business performance reporting.
- Implemented infrastructure-as-code and orchestration patterns to support reliable, maintainable, and automated cloud data processing.

**Real-Time Inference**  
[github.com/chypwc/kinesis-webui](https://github.com/chypwc/kinesis-webui)
- Engineered a serverless real-time recommendation system using Lambda, API Gateway, Kinesis, and DynamoDB for low-latency XGBoost predictions via RESTful APIs.
- Preprocessed data with Glue Spark and automated ML training and deployment on SageMaker, all orchestrated through Step Functions.
- Enabled global delivery with CloudFront and automated provisioning with Terraform and GitHub Actions.

**dbt-Glue ETL**  
[github.com/chypwc/aws-resources-exercises](https://github.com/chypwc/aws-resources-exercises)
- Implemented a scalable ETL pipeline by integrating Glue Jobs, Crawlers, and dbt-glue for SQL-based transformations; ingested Snowflake data into S3 in Parquet format, cataloged it with Glue, and transformed it into features.
- Automated infrastructure and deployments using CloudFormation and GitHub Actions CI/CD, orchestrating ingestion, catalog updates, and dbt transformation runs end-to-end.

---

## Education

**Australian National University, Ph.D. in Economics** (July 2019 – July 2024)

**Australian National University, Master of Economics** (Feb 2017 – Dec 2018)

**National Tsing Hua University, B.S. in Physics; B.A. in Economics** (Sep 2008 – June 2012)

---

## Research Experience

**[Dynamic Programming with State-Action-Dependent Discounting](papers/paper_dpsadd_v2.pdf)**
- Extended discrete-time dynamic programming to allow state-action-dependent discounting.
- Established "eventual discounting" as a sufficient condition for standard optimality results.
- Showed the condition becomes necessary for policy value existence under compact state spaces and concave functions.
- Covered bounded and unbounded reward settings and extended the framework to risk-sensitive preferences.

**[Temporal-Difference Learning with State-Action-Dependent Discounting](papers/paper_Qsadd_v2.pdf)**
- Extended model-free learning algorithms, including Q-learning, SARSA, and Double Q-learning, to state-action-dependent discount factors.
- Allowed discount factors greater than one with positive probability under an eventual discounting condition.
- Replaced the standard beta < 1 discounting restriction with a spectral-radius condition, rho(L) < 1.
- Framed convergence around expected discounted future values dominated by the appropriate linear operator.

**[Uniqueness of Equilibria in Interactive Networks](papers/paper_unique_network_v2.pdf)**
- Studied a unified network framework for equilibrium existence and uniqueness.
- Proved equilibrium existence and almost-sure uniqueness under eventual contraction or non-expansive assumptions.
- Analysed computation methods and the role of boundedness conditions for non-expansive interaction functions.
- Applied the framework to systemic risk by measuring which network participant has the largest impact when removed.

**[Explaining Systematic Departures from Gibrat's Law](papers/paper_Depature_Gibrat_v2.pdf)**
- Investigated why empirical firm dynamics often depart from Gibrat's Law of proportionate growth.
- Modelled a hierarchical production network in which smaller upstream firms exhibit greater volatility than larger downstream firms.
- Linked firm position in the production network to systematic size-volatility patterns.
- Showed how the model can also explain power-law patterns in the firm size distribution.

---

## Certificates & Compliance

- Microsoft Certified: Power BI Data Analyst Associate
- AWS Certified Data Engineer – Associate
- CPA Skills Assessment (Accountant – General)
- Working with Vulnerable People (WWVP)

## Conferences

**NCI Open Hackathon** — Canberra 2023  
*Presented:* Improving Economic Dynamic Programming Using Parallel Computation with GPU

**The Australasian Leadership Computing Symposium (ALCS)** — Canberra 2023  
*Presented:* Harold Zurcher as a Q-learner

**36th PhD Conference in Economics and Business** — Perth 2021  
*Presented:* Uniqueness of Equilibria in Interactive Network

**Society for the Advancement of Economic Theory (SAET)** — Canberra 2022  
*Presented:* Uniqueness of Equilibria in Interactive Network

## Referees

Available upon request.
