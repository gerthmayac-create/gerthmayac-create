<h1 align="center">Gerthmay Clair</h1>
<p align="center"><b>Data Engineer · Panamá</b><br>Convierto procesos manuales y macros de Excel en pipelines y herramientas que corren solas, se auditan y no dependen de nadie.</p>

<p align="center">
  <a href="https://gerthmayac-create.github.io"><img src="https://img.shields.io/badge/Portafolio-ver_casos-0f1b2d?style=for-the-badge&labelColor=f2a541"></a>
  <a href="https://www.linkedin.com/in/gerthmay-ashtbell-clair-m-b7086929a"><img src="https://img.shields.io/badge/LinkedIn-conectemos-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

<p align="center"><b>Español</b> · <a href="#english">English</a></p>

---

### Qué hago

Trabajo en ingeniería de datos en banca: llevo datos desde Excel, CSV, PDF escaneados y sistemas internos hasta un data lake en **Impala/HDFS**, con contratos de datos, validaciones y trazabilidad, y construyo las herramientas de escritorio que usan los equipos de operaciones cada día.

Antes pasé cerca de cinco años en **RRHH, compensación y nómina**. Vengo de **Psicología**: antes de mover un dato pregunto quién lo va a usar y para qué.

### En números

- **+100 000 líneas de Python** en herramientas y pipelines en producción
- **~130 archivos de pruebas** (pytest, pytest-qt) y CI con GitHub Actions
- **29 repositorios**: pipelines, ETL, automatización, apps de escritorio y BI

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Impala/HDFS](https://img.shields.io/badge/Impala%20%2F%20HDFS-66CCFF?logo=apachehadoop&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?logo=apache&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?logo=polars&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?logo=qt&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract%20OCR-5A5A5A)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![SAP](https://img.shields.io/badge/SAP%20HCM%20%2F%20MM-0FAAFF?logo=sap&logoColor=white)

### Casos destacados

> El código de estos proyectos es privado por confidencialidad. Aquí está qué resuelven y cómo están hechos; los detalles, en el [portafolio](https://gerthmayac-create.github.io).

| Proyecto | Qué resuelve | Cómo |
|---|---|---|
| **Unificación de histórico 2015–2019** | Cinco años de transacciones en CSV y Excel con formatos distintos, que al unirse daban números incorrectos | Contrato único de 64 columnas, lectura en streaming, manifiesto por archivo con md5, Parquet → Impala, pruebas de integración |
| **Ingesta de Excel al data lake** | Reportes que llegaban en Excel y se procesaban a mano | Carga particionada por fecha, columnas nuevas sin romper la tabla, inserción todo-o-nada, sin duplicados, programada |
| **ETL de casos del CRM** | Casos, interacciones, órdenes y visitas dispersos | ETL modular: lectura, limpieza, enriquecimiento y carga por proceso |
| **Notificaciones automáticas a clientes** | Avisos que se armaban y enviaban a mano | Consulta a Impala tres veces al día, reglas en YAML, evidencia de cada envío, bloqueo de envíos fuera de producción, 50+ archivos de pruebas |
| **Gestión multiusuario sin servidor** | Un Excel trimestral compartido por todo un equipo | App PyQt6 + SQLite que sincroniza por carpeta compartida, bandeja priorizada por persona, aprobaciones, auditoría y dashboard |
| **OCR para documentos escaneados** | Renombrar y clasificar cientos de PDF a mano | Visor + OCR (Tesseract), lectura de casillas marcadas, revisión en tabla y deshacer con historial |
| **Correos masivos por flujo** | Respuestas masivas con plantillas elegidas a mano | Plantilla automática según departamento y flujo, configuración en JSON, trazabilidad completa |

### Proyecto público

**[Análisis del mercado laboral en Panamá](https://github.com/gerthmayac-create/analisis-mercado-laboral-panama)**: brecha salarial por sexo, informalidad y participación laboral con datos oficiales (Python, pandas, Matplotlib).

---

<p align="center"><sub>Psicólogo de formación · Data Engineer por elección · Abierto a roles de Data Engineering y Analytics Engineering</sub></p>

---

<a id="english"></a>

<h2 align="center">English</h2>
<p align="center"><b>Data Engineer · Panama</b><br>I turn manual processes and Excel macros into pipelines and tools that run on their own, can be audited, and don't depend on anyone.</p>

<p align="center">
  <a href="https://gerthmayac-create.github.io/?lang=en"><img src="https://img.shields.io/badge/Portfolio-see_case_studies-0f1b2d?style=for-the-badge&labelColor=f2a541"></a>
  <a href="https://www.linkedin.com/in/gerthmay-ashtbell-clair-m-b7086929a"><img src="https://img.shields.io/badge/LinkedIn-let's_connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

### What I do

I work in data engineering in banking: I take data from Excel, CSV, scanned PDFs and internal systems into a data lake on **Impala/HDFS**, with data contracts, validations and traceability, and I build the desktop tools that operations teams use every day.

Before that I spent close to five years in **HR, compensation and payroll**. I'm a **psychologist** by training: before I move any data, I ask who will use it and what for.

### By the numbers

- **100,000+ lines of Python** in tools and pipelines in production
- **~130 test files** (pytest, pytest-qt) and CI with GitHub Actions
- **29 repositories**: pipelines, ETL, automation, desktop apps and BI

The stack is the same one listed above.

### Highlighted cases

> The code of these projects is private for confidentiality. Here is what they solve and how they are built; the details are in the [portfolio](https://gerthmayac-create.github.io/?lang=en).

| Project | What it solves | How |
|---|---|---|
| **2015–2019 history unification** | Five years of transactions in CSV and Excel with different formats, which gave wrong numbers when joined | Single 64-column contract, streaming reads, per-file md5 manifest, Parquet → Impala, integration tests |
| **Excel ingestion into the data lake** | Reports that arrived in Excel and were processed by hand | Date-partitioned load, new columns without breaking the table, all-or-nothing insert, no duplicates, scheduled |
| **CRM case ETL** | Cases, interactions, orders and visits scattered across the CRM | Modular ETL: read, clean, enrich and load per process |
| **Automatic customer notifications** | Notices that were put together and sent by hand | Impala query three times a day, rules in YAML, evidence of every send, sending blocked outside production, 50+ test files |
| **Serverless multi-user management** | A quarterly Excel file shared by a whole team | PyQt6 + SQLite app that syncs through a shared folder, per-person prioritized inbox, approvals, audit trail and dashboard |
| **OCR for scanned documents** | Renaming and classifying hundreds of PDFs by hand | Viewer + OCR (Tesseract), checkbox reading, table review and undo with history |
| **Bulk email by workflow** | Bulk replies with templates picked by hand | Automatic template by department and workflow, JSON configuration, full traceability |

### Public project

**[Panama labor market analysis](https://github.com/gerthmayac-create/analisis-mercado-laboral-panama)**: gender pay gap, informality and labor participation with official data (Python, pandas, Matplotlib).

---

<p align="center"><sub>Psychologist by training · Data Engineer by choice · Open to Data Engineering and Analytics Engineering roles</sub></p>
