# Análisis del Rendimiento Escolar en Chile (2002-2024) 🇨🇱📚

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-SQL%20Server-red.svg)](https://www.microsoft.com/en-us/sql-server/)
[![Status](https://img.shields.io/badge/Status-Project%20Portfolio-green.svg)]()

## 📌 Descripción del Proyecto
Este proyecto realiza un análisis del rendimiento académico en Chile utilizando microdatos del MINEDUC. Se coleccionaron los datos del MINEDUC de rendimiento academico entre el 2002 al 2024. [link](https://datosabiertos.mineduc.cl/resumen-de-rendimiento-por-unidad-educativa/). El objetivo es identificar cómo eventos históricos, tipos de establecimientos de estudio y cambios demográficos han afectado la educación en el país.

Este análisis es el resultado de un interés personal por entender el sistema educativo chileno a través de herramientas cuantitativas y técnicas de **Data Engineering (ETL)** y **Data Analysis**.

Para un detalle de los datos sugiero revisar el [documento oficial](./docs/ER_Resumen_rendimiento_UE.pdf).

---

## 🛠️ Herramientas Utilizadas
*   **Python**: ETL, limpieza y transformación de datos (Pandas, Numpy).
*   **SQL Server & SSMS**: Almacenamiento, modelado en estrella de base de datos y consultas complejas.
*   **Jupyter Notebooks**: Documentación del proceso exploratorio (EDA).
---

## 📂 Estructura del Proyecto
Organizado siguiendo las mejores prácticas de la industria:

```text
├── data/               # Datos del proyecto (raw/processed)
├── notebooks/          # Procesos de ETL y Exploración (EDA)
├── sql/                # Scripts de creación y consultas analíticas
├── docs/               # Documentación complementaria y reportes
├── .gitignore          # Archivos excluidos del control de versiones
├── requirements.txt    # Dependencias del proyecto
├── README.md           # Presentación principal
└── Resumen.md          # Detalles del proyecto
```

---

## 💡 Hallazgos Clave (Insights)

### 1. El Impacto de las Crisis y Fenómenos Naturales
*   **Terremoto de 2010**: Se observó una caída significativa en la aprobación (-1.72% en hombres, -1.37% en mujeres). El desastre natural eclipsó el impacto de la ley de procesos de admisión de 2009.
*   **Pandemia COVID-19 (2020-2021)**: Un aumento anómalo en la aprobación (+6.4%), posiblemente vinculado a la flexibilización de criterios y herramientas digitales (ChatGPT, IA), seguido de un "golpe de realidad" en 2022 con una caída del -4.5%.

### 2. Disparidad Regional
*   Las regiones alejadas de la capital presentan una mayor proporción de establecimientos rurales, lo que correlaciona con diferentes dinámicas de aprobación.

### 3. Educación Técnica-Profesional (T-P)
*   Se identificaron brechas marcadas de género en especialidades: las mujeres presentan menor aprobación en Industrial Adultos, mientras que los hombres enfrentan mayores desafíos en el área Agrícola.

---

## ⚙️ Cómo Ejecutar
1.  **Clonar el repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/proyecto-rendimiento-escolar.git
    ```
2.  **Instalar dependencias**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Procesar datos**:
    Ejecuta el notebook en `notebooks/ETL_Rendimiento_Escolar.ipynb` para procesar los archivos CSV.
4.  **Cargar Base de Datos**:
    Usa los scripts en `sql/` para crear la base de datos y tablas en tu instancia de SQL Server.

---

## 🚀 Próximos Pasos
*   [ ] Análisis profundo del impacto del SLEP en la educación pública.
*   [ ] Desarrollo de un Dashboard interactivo en Power BI/Tableau.
*   [ ] Modelos predictivos para identificar riesgo de deserción escolar.

---

**Contacto:**
Rodolfo Godoy arteaga – [LinkedIn](https://www.linkedin.com/in/rodolfo-godoy-arteaga-64396121b/)–[Correo](mailto:[EMAIL_ADDRESS])
