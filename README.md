# Daniel Torres · DannyTM12
**ML Engineer · NLP & Applied Cybersecurity · Aguascalientes, México**

Ingeniería en Computación Inteligente (UAA '26). Me especializo en sistemas de 
machine learning aplicados a ciberseguridad: detección de amenazas, 
explicabilidad de modelos y despliegue en producción. 
También docente de programación a nivel bachillerato.

---

## Stack

**ML & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-6C3483?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)

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

### [PhishGuard](https://github.com/DannyTM12/email-threat-classifier) — Sistema end-to-end de detección de phishing

Proyecto que nació como tesina de licenciatura y evolucionará hacia un sistema 
completo de detección de phishing con capa de producto: API de inferencia, 
extensión de navegador y dashboard de monitoreo.

**Núcleo ML (tesina)**
- **MetaSubModel:** Random Forest sobre 32 features de metadatos técnicos → ROC-AUC 0.9121
- **TextSubModel:** TF-IDF + Logistic Regression → ROC-AUC 0.9988
- **Fusión tardía con gating** (`θ_meta = 0.70`): evita inferencia NLP en casos de alta confianza
- **Explicabilidad:** SHAP TreeExplainer con 94% de coincidencia respecto a juicio experto
- **Dataset:** 164,563 registros de 7 fuentes públicas, deduplicados por MD5

**Capa de producto (en desarrollo)**
- **Extensión de navegador** (Chrome/Brave) — detección en tiempo real en Gmail y Outlook Web
- **Dashboard** — monitoreo de predicciones, visualización SHAP y feedback loop
- **Infraestructura:** FastAPI · Docker · GitHub Actions CI · Git LFS

---

## Otros proyectos

| Proyecto | Descripción | Stack |
|---|---|---|
| [moodle-cluster-rpi](https://github.com/DannyTM12/moodle-cluster-rpi) | Clúster de 5 nodos Raspberry Pi corriendo Moodle con NFS, MariaDB federada y balanceo Apache. 150 usuarios simultáneos, 30× menos consumo energético | Linux · MariaDB · Apache · NFS |
| [UAAWorks](https://github.com/DannyTM12/UAAWorks) | Portafolio universitario — IA, datos y algoritmos | Python · Jupyter · C++ |
| [mi-portafolio](https://github.com/DannyTM12/mi-portafolio) | Sitio web personal y portafolio | HTML · CSS · JavaScript |

---

## Actualmente
- Construyendo: extensión de navegador para PhishGuard (Chrome MV3 · Plasmo · TypeScript)
- Estudiando: SQL avanzado · Python para Data Science
- Próximo: **ISC2 Certified in Cybersecurity (CC)** — dic 2026

---

## Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-daniel-torres-macías-608b8b209)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carlosdtm8@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DannyTM12)
