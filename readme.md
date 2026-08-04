# Gideao Amaral
### Senior OT & Industrial Cloud Data Specialist

**End-to-End Industrial Data Lineage | Sensors & IIoT Telemetry to Multi-Cloud Platforms (AWS • Azure • OCI)**

---

I am a **Senior OT & Industrial Data Specialist** operating at the intersection of Operational Technology (OT), Field Instrumentation, Cyber-Physical Security, and Enterprise Cloud Data Infrastructure. Backed by **19 years of global hands-on experience across Singapore, China, Malaysia, and Brazil**, I specialize in architecting, securing, and managing the complete **Sensor-to-Cloud data lineage** in heavy industrial sectors including **Oil & Gas, Thermoelectric Power Generation, and Steel & Metallurgy**.

My core domain spans physical field instrumentation (4-20mA/HART, RTDs, field transmitters), machinery automation, operational time-series databases (**AVEVA PI System**), **Industrial DMZ design (Purdue Level 3.5)**, cybersecurity boundary controls (**ISA-95, IEC 62443**), and modern Multi-Cloud Data Platforms (**AWS, Azure, OCI**).

---

## 🌍 Global Footprint & Core Specializations

* **International Industry Experience:** Project execution, commissioning, and OT/IT integration across **Singapore, China, Malaysia, and Brazil**, serving critical offshore and onshore operations in Oil & Gas (FPSO/Topside), Thermoelectric Power Generation, and Steelmaking plants.
* **Industrial IoT & Cyber-Physical Security:** End-to-end data tracing from physical field sensors to supervisory systems (SCADA/DCS) and **Industrial DMZs**. OPC UA namespace design, AVEVA PI System deployment (PIBufss, OPCInt), network micro-segmentation, and store-and-forward link resilience.
* **Cloud Data Platforms & Lakehouses:** Near real-time IIoT streaming ingestion, Medallion Lakehouse Architecture (Bronze/Silver/Gold), distributed processing (PySpark/Databricks), Delta Lake, and dbt analytics engineering.
* **Enterprise Database Administration (HA/DR):** Mission-critical database management, multi-cloud zero-downtime migrations, cross-cloud connectivity, and analytical data warehousing (AWS Redshift, Azure SQL, OCI Autonomous DB, Snowflake).

---

## 🎓 Education

* **B.Sc. in Electrical Engineering**
* **Bachelor in Science and Technology**
* **Database Engineering** | *In Progress (Expected 2027)*

---

## 🚀 Featured Industrial & Cloud Projects

### 1. IIoT Data Pipeline & Industrial Reference Architecture (OT / Field Ingestion)
**Key Terms:** Sensors, IIoT, Industrial DMZ, OPC UA, AVEVA PI System, IEC 62443, Purdue Model, Time-Series Data.
* **The Challenge:** Safely extracting high-frequency IIoT telemetry from critical rotating assets (Baker Hughes gas turbines and compressors) while ensuring cyber-physical isolation between the factory floor (OT Level 2/3) and corporate network (IT Level 4).
* **The Architecture:** Designed an end-to-end OT reference architecture based on the Purdue Model and **Industrial DMZ (Level 3.5)**. Built an asynchronous Python simulator generating realistic physical sensor workloads via structured OPC UA nodes, strict firewall conduit rule mapping (IEC 62443), and active Store-and-Forward buffering for satellite link resilience.
* **Technical Value:** Demonstrates deep domain over OT topologies, network boundary controls, DMZ proxies, and industrial time-series data resilience.
* 🔗 [Access Repository](./industrial-iiot-pipeline-fpso)

### 2. Thermoelectric DB Migration to Multi-Cloud (Azure/OCI) | HA & Migration
**Key Terms:** Industrial DB, High Availability (HA/DR), Thermoelectric Energy, Oracle, SQL Server, OCI, Azure.
* **The Challenge:** Executing a zero-downtime lift-and-shift migration of legacy industrial operational databases from a thermoelectric power generation plant into managed multi-cloud environments.
* **The Architecture:** Blueprint for migrating historical relational schemas into managed cloud engines (OCI Autonomous Database & Azure SQL Database). Designed secure ETL/ELT pipelines via Azure Data Factory and SSIS, enforcing cross-cloud high-availability and query performance tuning.
* **Technical Value:** Proven experience in mission-critical database administration, multi-cloud interconnectivity, and zero-data-loss migration strategies.
* 🔗 [Access Repository](./oracle-sqlserver-integration-thermoelectric)

### 3. Industrial IoT Streaming & Medallion Lakehouse on AWS
**Key Terms:** IIoT Streaming, AWS Kinesis, Databricks, PySpark, Delta Lake, dbt, Redshift, Medallion Architecture.
* **The Challenge:** Ingesting, cleansing, and transforming continuous, high-frequency industrial sensor telemetry in near real-time for executive analytics and predictive maintenance models.
* **The Architecture:** Modern streaming Lakehouse architecture built on AWS and Databricks. Features a Python producer simulating OPC UA payloads into AWS Kinesis, Serverless Lambda ingestion into S3 Bronze, PySpark cleansing and deduplication into Delta Lake Silver, and dbt dimensional modeling (Star Schema) into AWS Redshift Gold layer.
* **Technical Value:** Hands-on mastery of modern Cloud Data Engineering, streaming micro-batches, automated data quality assertion tests, and analytical serving layers.
* 🔗 [Access Repository](./industrial-streaming-lakehouse-aws)

---

## ⚡ Technical Stack Overview

* **OT & Industrial Security:** Field Sensors (HART/RTD/4-20mA), OPC UA, AVEVA PI System (PI Data Archive, AF, Vision, Buffer), Purdue Model (Levels 0-4), Industrial DMZ (Level 3.5), ISA-95, IEC 62443.
* **Cloud & Data Engineering:** Databricks, PySpark, Delta Lake, AWS Kinesis Data Streams, AWS Lambda, S3, dbt Core, Azure Data Factory.
* **Databases & Data Warehouses:** AWS Redshift, OCI Autonomous Database, Oracle DB, Microsoft SQL Server, Azure SQL, Snowflake.
