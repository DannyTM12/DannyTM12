# Daniel Torres · DannyTM12
**ML Engineer · NLP & Applied Cybersecurity · Aguascalientes, México**

Ingeniero en Computación Inteligente egresado de la UAA (2026). Me especializo en 
sistemas de machine learning aplicados a ciberseguridad: detección de amenazas, 
explicabilidad de modelos y despliegue en producción. Actualmente en internship 
remoto de Machine Learning en FlyRank.

---

## Stack

**ML & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-6C3483?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)

**Deployment & Dev**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Bases de datos & BI**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## Proyecto principal

### [PhishGuard](https://github.com/DannyTM12/phishguard) — Sistema de detección de phishing (tesina)

Proyecto de tesina de licenciatura: sistema de detección de phishing con fusión 
tardía de modelos. Este repo queda congelado como entregable académico — todo 
el desarrollo posterior (mejoras de modelo y capa de producto) vive en 
[email-threat-classifier](https://github.com/DannyTM12/email-threat-classifier).

**Núcleo ML (tesina)**
- **MetaSubModel:** Random Forest sobre 32 features de metadatos técnicos → ROC-AUC 0.9121
- **TextSubModel:** TF-IDF + Logistic Regression → ROC-AUC 0.9988
- **Fusión tardía con gating** (`θ_meta = 0.70`): evita inferencia NLP en casos de alta confianza
- **Explicabilidad:** SHAP TreeExplainer con 94% de coincidencia respecto a juicio experto
- **Dataset:** 164,563 registros de 7 fuentes públicas, deduplicados por MD5

---

## Email Threat Classifier

### [email-threat-classifier](https://github.com/DannyTM12/email-threat-classifier) — Evolución de PhishGuard hacia producto

Iteración activa de PhishGuard: mejoras de modelo (XGBoost, DistilBERT, calibración 
de probabilidad) y capa de producto completa.

- **Extensión de navegador** (Chrome/Brave) — detección en tiempo real en Gmail y Outlook Web
- **Dashboard** — monitoreo de predicciones, visualización SHAP y feedback loop
- **Infraestructura:** FastAPI · Docker · GitHub Actions CI · Git LFS

---

## FlyRank ML Internship

### [flyrank-capstone](https://github.com/DannyTM12/flyrank-capstone) — Search Intelligence Capstone

Proyecto de investigación aplicada sobre datos reales de búsqueda del dataset de FlyRank: 
modelado predictivo, validación con splits time-aware, controles de fuga de datos, y 
publicación como research paper reproducible.

**Stack:** Python · DuckDB · scikit-learn · Hugging Face · GitHub Pages

---

## Otros proyectos

| Proyecto | Descripción | Stack |
|---|---|---|
| [leetcode-python-exercise](https://github.com/DannyTM12/leetcode-python-exercise) | Práctica continua de algoritmos, estructuras de datos y SQL | Python · SQL |
| [moodle-cluster-rpi](https://github.com/DannyTM12/moodle-cluster-rpi) | Clúster de 5 nodos Raspberry Pi corriendo Moodle con NFS, MariaDB federada y balanceo Apache. 150 usuarios simultáneos, 30× menos consumo energético | Linux · MariaDB · Apache · NFS |
| [UAAWorks](https://github.com/DannyTM12/UAAWorks) | Portafolio universitario — IA, datos y algoritmos | Python · Jupyter · C++ |
| [mi-portafolio](https://github.com/DannyTM12/mi-portafolio) | Sitio web personal y portafolio | HTML · CSS · JavaScript |

---

## Actualmente
- Cursando: internship remoto de Machine Learning en FlyRank — capstone de Search Intelligence
- Construyendo: extensión de navegador para email-threat-classifier (Chrome MV3 · Plasmo · TypeScript)
- Estudiando: SQL avanzado · Python para Data Science · Docker
- Próximo: **EPAM DevOps Fundamentals** (sep 2026) · **ISC2 Certified in Cybersecurity (CC)** (dic 2026)

---

## Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-daniel-torres-macías-608b8b209)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carlosdtm8@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DannyTM12)
