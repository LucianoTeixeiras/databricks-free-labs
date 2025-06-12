# 🧠 databricks-free-labs

![Databricks](https://img.shields.io/badge/Platform-Databricks-red)
![License](https://img.shields.io/github/license/seuusuario/databricks-free-labs)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

Repositório dedicado a **estudos práticos, experimentos e protótipos** utilizando a plataforma gratuita da [Databricks Free](https://databricks.com/try-databricks).  
Ideal para quem deseja aprender Databricks mesmo sem acesso a um ambiente corporativo.

---

## 🚀 Objetivos

- Aprender a usar o **Databricks Free** com recursos reais de engenharia e ciência de dados
- Explorar funcionalidades como:
  - 🔸 Notebooks com PySpark
  - 🔸 Delta Lake
  - 🔸 Unity Catalog (metadados)
  - 🔸 Databricks SQL
  - 🔸 Streamlit Apps nativos
  - 🔸 MLflow e AutoML
- Criar uma base de conhecimento para projetos futuros em ambientes corporativos

---

## 🧱 Estrutura do Repositório

```bash
databricks-free-labs/
├── notebooks/                 # Notebooks para ingestão, transformação e análise
│   ├── bronze_ingestao.ipynb
│   ├── silver_transformacoes.ipynb
│   └── gold_kpis.ipynb
├── apps/                     # Apps interativos criados com Streamlit no Databricks
│   └── streamlit_kpi_dashboard/
│       └── app.py
├── datasets/                 # Arquivos CSV ou Parquet de exemplo
│   └── exemplo.csv
├── .databricks/              # Arquivos auxiliares para versionamento no workspace
│   └── workspace.json
└── README.md                 # Este arquivo
