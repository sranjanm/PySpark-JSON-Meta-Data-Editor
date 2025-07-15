Assisted JSON Schema Editor for PySpark Pipelines

This project introduces a configurable and auditable **JSON Schema Editing Framework** to manage and transform structured data pipelines in PySpark. It supports human-in-the-loop schema customization, field-level enforcement, and change logging for enterprise-scale use cases.

---

## 🚀 Overview

Traditional data ingestion pipelines often lack dynamic schema enforcement and auditable control over transformations. This system allows users to:

- Extract schema from raw datasets
- Define transformation and validation rules via editable JSON
- Apply schema-driven transformations using PySpark
- Log all schema changes for transparency and compliance

---

## 🗂️ Data Source

The dataset is loaded directly from **Azure Data Lake** using a service principal and OAuth authentication. You can use any Dataset for running this module.
