# Airflow DAG Example

This repository contains a simple Apache Airflow DAG that demonstrates a basic ETL workflow using Python operators.

## 🚀 DAG Overview

The workflow includes three tasks:
1. **Extract** — Simulates reading raw data  
2. **Transform** — Simulates data cleaning/transformation  
3. **Load** — Simulates loading processed data  

```txt
extract → transform → load
