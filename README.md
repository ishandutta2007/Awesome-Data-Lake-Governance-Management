# Awesome-Data-Lake-Governance-Management

# Awesome-Data-Lake-Governance-Management

# Awesome-Data-Lake-Governance-Management 🏞️ 🛡️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Data Lake Governance Management Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Data-Lake-Governance-Management"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Data-Lake-Governance-Management?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Data-Lake-Governance-Management/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Data-Lake-Governance-Management?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Data-Lake-Governance-Management/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Data-Lake-Governance-Management?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Data Lake Governance & Management Ecosystem

**Curated List of Commercial Data Governance Platforms & Open-Source Data Catalog Tools**  
*Focused on Data Catalogs, Access Control, Column-Level Security, Data Lineage, Metadata Management & Self-Hosted Governance Engines*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **data lake governance platforms**, **open-source data catalog tools**, and **metadata management frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *AWS Lake Formation*, *Databricks Unity Catalog*, and *Collibra*), or self-hostable open-source alternatives (like *Apache Atlas*, *DataHub*, and *OpenMetadata*), this list covers category leaders, column-level security, and privacy-respecting data governance.

**Key Market Context:**
- **DataHub (LinkedIn)** is the **most comprehensive open-source data catalog**, with **10K+ GitHub stars**, **50+ metadata ingestion sources**, and **real-time lineage**.
- **Apache Atlas** is the **most widely deployed open-source governance platform** in Hadoop ecosystems, with **native Ranger integration for fine-grained access control**.
- **OpenMetadata** provides a **unified metadata platform** with **100+ connectors**, **data lineage, quality, and governance** in one place.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The data lake governance market spans **hyperscaler-native governance services** (AWS Lake Formation, Microsoft Purview) that provide **deep cloud integration with fine-grained access control**, **data platform governance layers** (Databricks Unity Catalog, Snowflake Horizon) that embed **governance directly into the data platform**, and **standalone data catalog platforms** (Collibra, Alation, Atlan) that offer **enterprise-wide metadata management and business glossaries**. **AWS Lake Formation** charges **per data processed and catalog requests** . **Databricks Unity Catalog** is **included with Databricks workspace subscriptions** . **Collibra** uses **custom enterprise pricing** starting at **$100K+/year**. **Atlan** starts at **$350/month** for small teams.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AWS Lake Formation](https://aws.amazon.com/lake-formation/)** ☁️ | Amazon | ~$2.0 Trillion | **Pay-per-use** for data processed and catalog requests | **Free tier: 1M catalog requests/month for 12 months**  | **AWS-native data lake governance** — **Fine-grained access control** at table, column, and row level . **Centralized permissions management** across S3, Glue, Athena, and Redshift . **Tag-based access control (LF-TBAC)** for scalable governance . **Cross-account data sharing** with governed tables . |
| **[Databricks Unity Catalog](https://www.databricks.com/product/unity-catalog)** 🧱 | Databricks | ~$43 Billion | **Included with Databricks workspace subscriptions**  | **Free tier: 14-day trial**  | **Unified governance for data and AI** — **Fine-grained access control** for tables, views, volumes, and models . **Automated data lineage** across notebooks, jobs, and dashboards . **Attribute-based access control (ABAC)** with Unity Catalog . **Cross-workspace and cross-cloud governance** . |
| **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)** 🔷 | Microsoft | ~$3.90 Trillion | **$5/user/month** (Information Protection) + **$0.50/catalog hour**  | **Free tier: limited**  | **Microsoft-native data governance** — **Data catalog, lineage, and classification** . **Integrates with Azure, Microsoft 365, and Dynamics 365** . **Data Loss Prevention (DLP)** and **Insider Risk Management** . |
| **[Collibra](https://www.collibra.com/)** 🏢 | Collibra | ~$2.6 Billion | **Custom enterprise pricing** (from $100K+/year)  | **No free tier**; demo available | **Enterprise data intelligence platform** — **Data catalog, governance, and lineage** . **Business glossary and data stewardship** . **The most comprehensive enterprise data governance platform** . |
| **[Alation](https://www.alation.com/)** 🔵 | Alation | ~$1.7 Billion | **Custom enterprise pricing**  | **Demo available** | **Data intelligence platform** — **Data catalog with behavioral analysis** . **Collaborative data curation and governance** . **The most user-friendly enterprise data catalog** . |
| **[Immuta](https://www.immuta.com/)** 🛡️ | Immuta | Private | **Custom enterprise pricing**  | **Demo available** | **Data security platform** — **Dynamic data access control** and **policy enforcement** . **Attribute-based access control (ABAC)** . **Sensitive data discovery and masking** . |
| **[Privacera](https://privacera.com/)** 🔒 | Privacera | Private | **Custom enterprise pricing**  | **Demo available** | **Data security and governance platform** — **Unified access control across multi-cloud** . **Built on Apache Ranger** . **Data discovery, classification, and masking** . |
| **[Okera](https://www.okera.com/)** 🎯 | Okera (Databricks) | Private | **Acquired by Databricks**  | **Service discontinued**  | **Data access platform (acquired)** — **Acquired by Databricks** in 2023. **Technology integrated into Unity Catalog** . |
| **[Atlan](https://atlan.com/)** 🟣 | Atlan | Private | **$350/month** (starting)  | **Free trial available**  | **Modern data catalog** — **Data discovery, lineage, and governance** . **Collaborative workspace for data teams** . **The most modern data catalog platform** . |
| **[Alation](https://www.alation.com/)** 🔵 | Alation | ~$1.7 Billion | **Custom enterprise pricing**  | **Demo available** | **Data intelligence platform** — **Data catalog with behavioral analysis** . **Collaborative data curation** . **The most user-friendly enterprise data catalog** . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[DataHub (LinkedIn)](https://github.com/datahub-project/datahub)** [![Stars](https://img.shields.io/github/stars/datahub-project/datahub?style=social&color=white)](https://github.com/datahub-project/datahub/stargazers)  
  **Open-source metadata platform for data discovery**, Apache-2.0 licensed. **10K+ GitHub stars** — **the most comprehensive open-source data catalog** . **Metadata ingestion from 50+ sources** — Snowflake, BigQuery, PostgreSQL, Kafka, dbt, Looker, and more . **Data lineage, governance, and discovery** . **Real-time metadata streaming** with Kafka . **The enterprise-grade open-source data marketplace foundation** . 🏢

- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** [![Stars](https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white)](https://github.com/open-metadata/OpenMetadata/stargazers)  
  **Unified metadata platform for data discovery and governance**, Apache-2.0 licensed. **5K+ GitHub stars** — **100+ connectors** for databases, dashboards, pipelines, and messaging . **Data lineage, quality, and governance** in one platform . **Column-level lineage** and **data profiling** . **The most modern open-source data catalog** . 📋

- **[Apache Atlas](https://github.com/apache/atlas)** [![Stars](https://img.shields.io/github/stars/apache/atlas?style=social&color=white)](https://github.com/apache/atlas/stargazers)  
  **Metadata and governance framework for Hadoop**, Apache-2.0 licensed. **5K+ GitHub stars** — **the most widely deployed open-source governance platform** in Hadoop ecosystems . **Native Apache Ranger integration** for **fine-grained access control** . **Data classification, lineage, and search** . **The foundation for enterprise Hadoop governance** . 🏛️

- **[Apache Ranger](https://github.com/apache/ranger)** [![Stars](https://img.shields.io/github/stars/apache/ranger?style=social&color=white)](https://github.com/apache/ranger/stargazers)  
  **Centralized security framework for Hadoop**, Apache-2.0 licensed. **3K+ GitHub stars** — **the most widely deployed open-source data access control platform** . **Fine-grained authorization** for HDFS, Hive, HBase, Kafka, and more . **Centralized policy management** with **audit logging** . **The standard for Hadoop security governance** . 🛡️

- **[Amundsen (Lyft)](https://github.com/amundsen-io/amundsen)** [![Stars](https://img.shields.io/github/stars/amundsen-io/amundsen?style=social&color=white)](https://github.com/amundsen-io/amundsen/stargazers)  
  **Data discovery and metadata engine**, Apache-2.0 licensed. **4K+ GitHub stars** — **data catalog with search and lineage** . **Neo4j graph for relationship mapping** . **Used by Lyft, ING, and other enterprises** . **The most widely adopted open-source data catalog** . 🔍

- **[Marquez (WeWork)](https://github.com/MarquezProject/marquez)** [![Stars](https://img.shields.io/github/stars/MarquezProject/marquez?style=social&color=white)](https://github.com/MarquezProject/marquez/stargazers)  
  **Open-source metadata service for data lineage**, Apache-2.0 licensed. **2K+ GitHub stars** — **collects, aggregates, and visualizes data lineage** . **OpenLineage standard** for interoperability . **The standard for open-source data lineage** . 🔗

- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)** [![Stars](https://img.shields.io/github/stars/OpenLineage/OpenLineage?style=social&color=white)](https://github.com/OpenLineage/OpenLineage/stargazers)  
  **Data lineage collection framework**, Apache-2.0 licensed. **2K+ GitHub stars** — **vendor-neutral lineage metadata** for Spark, Airflow, dbt, and more . **The missing observability layer** for data pipelines . **The emerging standard for data lineage** . 📊

- **[DataHub (Acryl)](https://github.com/acryldata/datahub)** [![Stars](https://img.shields.io/github/stars/acryldata/datahub?style=social&color=white)](https://github.com/acryldata/datahub/stargazers)  
  **Cloud-native metadata platform**, Apache-2.0 licensed. **Managed DataHub Cloud** from Acryl Data . **Enterprise-grade metadata management** with **SLA and support** . **The commercial distribution of LinkedIn DataHub** . ☁️

- **[Magda](https://github.com/magda-io/magda)** [![Stars](https://img.shields.io/github/stars/magda-io/magda?style=social&color=white)](https://github.com/magda-io/magda/stargazers)  
  **Open-source data catalog for government and enterprise**, Apache-2.0 licensed. **Data discovery and access** for public sector . **Federated data catalog** across agencies . **The leading open-source government data marketplace** . 🏛️

- **[CKAN](https://github.com/ckan/ckan)** [![Stars](https://img.shields.io/github/stars/ckan/ckan?style=social&color=white)](https://github.com/ckan/ckan/stargazers)  
  **Open-source data portal platform**, AGPL-3.0 licensed. **The most widely adopted open data portal** — powers **data.gov, data.gov.uk, and hundreds of government portals** . **Dataset publishing, search, and APIs** . **The standard for open data marketplaces** . 🌍

- **[Atlas (Kylo)](https://github.com/Teradata/kylo)** [![Stars](https://img.shields.io/github/stars/Teradata/kylo?style=social&color=white)](https://github.com/Teradata/kylo/stargazers)  
  **Enterprise data lake management**, Apache-2.0 licensed. **Data ingestion, preparation, and governance** . **Built on Apache Spark and NiFi** . **The most complete open-source data lake management platform** . 🎯

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new data lake governance platforms or open-source data catalog software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Data-Lake-Governance-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Data-Lake-Governance-Management&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this data lake governance repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow data engineers, governance teams, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **AWS Lake Formation and Databricks Unity Catalog provide fine-grained access control** at table, column, and row level . **Apache Ranger is the standard for Hadoop security governance** with **native Atlas integration** .
- **DataHub and OpenMetadata are the leading open-source data catalogs** — **DataHub has 10K+ GitHub stars and 50+ ingestion sources** . **OpenMetadata provides 100+ connectors** and **unified metadata management** .
- **Open-source governance tools are not turnkey** — they require **deployment, metadata ingestion configuration, and ongoing maintenance** . **Apache Atlas requires HBase and Solr** . **DataHub requires Kafka, Elasticsearch, and MySQL/PostgreSQL** . **Always validate access controls and lineage accuracy with a proof-of-concept** before production deployment . 🏞️

---

<p align="center">
  <b>Made with ❤️ for data engineers, governance teams, and open-source data catalog advocates.</b>
</p>
