<p align="center">
  <img src="FOTO%20PERFIL.png" alt="Amílcar Carrillo" width="160" style="border-radius: 50%;" />
</p>

# 🚀 Amílcar Carrillo | Data Engineer & Analytics Specialist

Bienvenido a mi repositorio central. Aquí encontrarás arquitecturas y soluciones de extremo a extremo en **Data Engineering**, **Generative AI Data Pipelines (RAG)** y **Business Intelligence**.

[![Portfolio Web](https://img.shields.io/badge/Website-amilcar--carrillo.github.io-007ACC?style=flat&logo=google-chrome&logoColor=white)](https://amilcar-carrillo.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amílcar_Carrillo-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amilcar-carrillo/)
[![GitHub](https://img.shields.io/badge/GitHub-Amilcar--Carrillo-181717?style=flat&logo=github&logoColor=white)](https://github.com/Amilcar-Carrillo)
[![Email](https://img.shields.io/badge/Email-amilcp%40outlook.com-D83B01?style=flat&logo=microsoft-outlook&logoColor=white)](mailto:amilcp@outlook.com)

---

### 👨‍💻 Perfil Profesional
**Licenciado en Ciencia de Datos para Negocios** enfocado en el diseño, automatización y despliegue de soluciones analíticas escalables y rentables (FinOps). Experiencia en todo el ciclo de vida del dato: desde la ingesta cruda en arquitecturas Cloud y transformaciones distribuidas (ETL/ELT), hasta orquestación serverless, bases de datos vectoriales para GenAI, modelado dimensional e interfaces analíticas y tableros ejecutivos para la toma de decisiones.

---

### 🛠️ Stack Tecnológico

| Área | Tecnologías y Herramientas |
| :--- | :--- |
| **Cloud & Data Lakes** | Google Cloud Platform (GCP), Amazon Web Services (AWS), Azure |
| **Generative AI & Vector DB** | Retrieval-Augmented Generation (RAG), BigQuery Vector Search (`ML.DISTANCE`), Vertex AI (`text-embedding-004`, `gemini`), LangChain |
| **Ingeniería de Datos & ETL/ELT** | Python (Pandas, PySpark, Boto3, Requests), Cloud Run Functions, Cloud Scheduler, dbt, Apache Airflow, Docker, Pentaho PDI |
| **Bases de Datos & Data Warehouses** | Google BigQuery (Dimensional Modeling, MERGE, SQL Aggregations), AWS Athena, PostgreSQL, MySQL, SQL Server, MongoDB |
| **Business Intelligence & Web Apps** | Streamlit, Looker Studio, Power BI (DAX, Power Query, Data Gateways), Tableau (Desktop, Public) |

---

## 📂 Proyectos Destacados

### 1. 🏛️️ [Congreso CDMX: Serverless Data Pipeline, Hybrid RAG & Legislative Analytics](https://github.com/Amilcar-Carrillo/congreso-cdmx-analytics)
* **Enfoque:** Plataforma integral de inteligencia legislativa para el análisis cuantitativo y consulta semántica de la actividad parlamentaria del Congreso de la Ciudad de México (I, II y III Legislaturas).
* **Tech Stack:** `GCP (Cloud Run Functions, Cloud Scheduler, BigQuery)` | `Vertex AI (Gemini 2.5 Flash, text-embedding-004)` | `Python` | `Streamlit` | `Looker Studio`
* **Logro Clave:** Arquitectura serverless desatendida con escala a cero ($0 en reposo FinOps); modelado dimensional (`dim_diputados`, `fact_asistencias`, `fact_iniciativas_vectors`) con inserciones idempotentes (`MERGE`); motor RAG Híbrido que cruza agregaciones analíticas SQL (`COUNTIF` por 4 estatus de trámite) con búsqueda semántica vectorial por similitud coseno (`ML.DISTANCE`) sobre vectores de 768 dimensiones.
* **Accesos Rápidos:** 
  [![Probar Asistente en Vivo](https://img.shields.io/badge/%F0%9F%9A%80_Probar_Asistente_en_Vivo-Streamlit_App-10b981?style=for-the-badge)](https://congreso-cdmx-analytics.streamlit.app/)
  [![Ver Tablero Looker](https://img.shields.io/badge/%F0%9F%93%8A_Ver_Tablero_Looker_Studio-Dashboard_P%C3%BAblico-38bdf8?style=for-the-badge&logo=googlecloud&logoColor=white)](https://datastudio.google.com/reporting/6d4edf9f-de42-4600-b6ce-a27a21b2ab05)
  [![Ver Repositorio](https://img.shields.io/badge/Ver_Repositorio_y_Arquitectura_%E2%86%92-GitHub-1e293b?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Amilcar-Carrillo/congreso-cdmx-analytics)

---

### 2. 🧠 [Enterprise RAG Data Pipeline on Google Cloud Platform](https://github.com/Amilcar-Carrillo/gcp-rag-data-pipeline)
* **Enfoque:** Arquitectura de datos para Inteligencia Artificial Generativa (RAG) sobre gobernanza de políticas corporativas.
* **Tech Stack:** `GCP (Cloud Storage, BigQuery Vector Search)` | `Vertex AI (Gemini, text-embedding-004)` | `Python` | `LangChain` | `Streamlit`
* **Logro Clave:** Diseño de pipeline de datos no estructurados con *Recursive Chunking* y metadatos de auditoría; generación e indexación de vectores (768 dims) con búsqueda por similitud coseno en BigQuery (`ML.DISTANCE`) y control de alucinaciones con Guardrails estrictos.
* **Accesos Rápidos:** 
  [![Probar Asistente Web](https://img.shields.io/badge/%F0%9F%9A%80_Probar_Asistente_en_Vivo-Streamlit_App-10b981?style=for-the-badge)](https://gcp-rag-asistente.streamlit.app/)
  [![Ver Repositorio](https://img.shields.io/badge/Ver_Repositorio_y_Arquitectura_%E2%86%92-GitHub-1e293b?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Amilcar-Carrillo/gcp-rag-data-pipeline)

---

### 3. ✈️ [Data Lakehouse: Monitor de Tráfico Aéreo en Tiempo Real](https://github.com/Amilcar-Carrillo/Data-Lakehouse-AWS-PowerBI-Vuelos)
* **Enfoque:** Arquitectura híbrida serverless de telemetría geoespacial en vivo para sedes mundialistas 2026.
* **Tech Stack:** `Python (Boto3)` | `AWS S3` | `AWS Glue (PySpark)` | `Amazon Athena (SQL)` | `Power BI`
* **Logro Clave:** Implementación de particionado cronológico, optimización de almacenamiento JSON a Parquet en Capa Silver, tratamiento de excepciones de cobertura ADS-B (*Data Quality*) y actualización automatizada en Power BI Service vía Gateway.
* **Código:** [Ver Repositorio](https://github.com/Amilcar-Carrillo/Data-Lakehouse-AWS-PowerBI-Vuelos)

---

### 4. 📊 [Customer Churn & Revenue Attrition Analysis](https://github.com/Amilcar-Carrillo/customer-churn-revenue-analysis)
* **Enfoque:** Analítica financiera de retención y mitigación de fuga de capital en clientes recurrentes.
* **Tech Stack:** `Python (Pandas, NumPy)` | `SQL Relacional` | `Business Analytics & FinOps`
* **Logro Clave:** Identificación de una concentración del 75% del churn en contratos mensuales y cuantificación de **$139K USD en riesgo (MRR)**, planteando estrategias de migración contractual y detección temprana.
* **Código:** [Ver Repositorio](https://github.com/Amilcar-Carrillo/customer-churn-revenue-analysis)

---

### 5. 🚕 [Análisis Geoespacial y Pruebas Estadísticas - Zuber](https://github.com/Amilcar-Carrillo/Zuber-Data-Engineering-Analysis)
* **Enfoque:** Optimización logística de movilidad y evaluación del impacto meteorológico en viajes urbanos.
* **Tech Stack:** `Python (Pandas, Scipy)` | `SQL` | `Pruebas de Hipótesis (T-test)`
* **Logro Clave:** Integración de bases meteorológicas y registros de viajes con SQL; formulación y validación de hipótesis estadísticas para soporte en toma de decisiones de tarifas dinámicas.
* **Código:** [Ver Repositorio](https://github.com/Amilcar-Carrillo/Zuber-Data-Engineering-Analysis)

---

### 6. 📈 [Market Trends & Content Performance Analytics](https://github.com/Amilcar-Carrillo/Analisis_Ventas_Tableau)
* **Enfoque:** BI de autoservicio para evaluación de consumo de medios en 5 mercados internacionales.
* **Tech Stack:** `Tableau Desktop` | `Tableau Public` | `Data Storytelling`
* **Logro Clave:** Detección de patrones de alto rendimiento en categorías dominantes (Entertainment y Music), reduciendo la dependencia de reportes estáticos operativos.
* **Código:** [Ver Repositorio](https://github.com/Amilcar-Carrillo/Analisis_Ventas_Tableau)

---

## 📬 Contacto
* **Ubicación:** Ciudad de México
* **Email:** [amilcp@outlook.com](mailto:amilcp@outlook.com)
* **LinkedIn:** [linkedin.com/in/amilcar-carrillo](https://www.linkedin.com/in/amilcar-carrillo/)
* **Portafolio Web:** [amilcar-carrillo.github.io](https://amilcar-carrillo.github.io/)
