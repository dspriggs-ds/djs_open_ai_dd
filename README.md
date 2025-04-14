### 📘 `OpenAI Data Lake Inventory` – Azure Databricks Notebook

Welcome to the **OpenAI Data Lake Inventory** notebook repository. This notebook is designed to explore, audit, and generate metadata inventory for datasets stored in an Azure-based data lake using Databricks.

---

## 🚀 Overview

This notebook provides:

- A comprehensive scan of directories and files within an Azure Data Lake Storage (ADLS) Gen2 container.
- Metadata extraction such as:
  - File sizes
  - File types
  - Directory structure
  - Timestamps
- Optional generation of summary reports or tables for auditing purposes.

---

## 🧰 Technologies Used

- **Azure Databricks** (Notebook-based execution)
- **PySpark** and **Databricks Utilities (dbutils)**
- **Delta Lake** (optional)
- **Azure Data Lake Storage Gen2**

---

## 📂 Typical Use Cases

- Data lake inventory and audit
- Metadata catalog generation
- Compliance checks
- Pipeline validation (checking if expected files are present)

---

## 🛠️ Getting Started

1. Open the notebook in your Databricks workspace.
2. Attach to a cluster with access to your ADLS Gen2 storage.
3. Set the required configurations, such as the storage account path and credentials.
4. Run each cell to explore and inventory your data lake contents.

---

## ⚠️ Prerequisites

- A configured **Databricks workspace**
- Access to **Azure Data Lake Storage (Gen2)**
- Properly scoped **service principal or credential passthrough** for secure access

---

## 📊 Output

Depending on customization, the notebook may produce:

- A DataFrame listing file metadata
- Summary statistics on storage usage
- Optional exports to Delta tables or CSV

---