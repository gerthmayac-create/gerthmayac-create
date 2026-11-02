<h1 align="center">Gerthmay Clair</h1>
<p align="center"><b>Data Engineer · Panamá</b><br>Convierto procesos manuales y macros de Excel en pipelines y herramientas que corren solas, se auditan y no dependen de nadie.</p>

<p align="center">
  <a href="https://gerthmayac-create.github.io"><img src="https://img.shields.io/badge/Portafolio-ver_casos-0f1b2d?style=for-the-badge&labelColor=f2a541"></a>
  <a href="https://www.linkedin.com/in/gerthmay-ashtbell-clair-m-b7086929a"><img src="https://img.shields.io/badge/LinkedIn-conectemos-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

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
