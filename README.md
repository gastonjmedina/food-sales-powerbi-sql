# Proyecto de Análisis de Ventas | Power BI + SQL Server

Repositorio orientado al desarrollo de un dashboard interactivo en Power BI para el análisis de un conjunto de datos de ventas.

El proyecto incluye las etapas de limpieza, transformación, modelado y visualización de datos mediante Power Query y DAX, con el objetivo de responder a distintos requerimientos de negocio a través de indicadores clave (KPIs) y visualizaciones interactivas. Además, se desarrollaron consultas en SQL Server para validar los indicadores y resultados obtenidos en el dashboard.

---

## Objetivos del proyecto

- Analizar el desempeño de las ventas mediante indicadores clave (KPIs)
- Identificar tendencias y patrones de comportamiento
- Comparar el rendimiento de categorías y productos
- Obtener información útil para la toma de decisiones
- Desarrollar un dashboard interactivo para el análisis de datos comerciales

---

## Tecnologías utilizadas

- Power BI Desktop
- Power Query
- DAX
- SQL Server

---

## Proceso desarrollado

Durante el proyecto se realizaron las siguientes etapas:

- Limpieza y transformación de datos mediante Power Query
- Creación de columnas auxiliares para el análisis temporal
- Desarrollo de medidas DAX para el cálculo de KPIs
- Desarrollo de visualizaciones para el análisis de tendencias, categorías y productos
- Implementación de segmentadores, filtros y navegación entre páginas

---

## Validación mediante SQL

Como complemento al desarrollo del dashboard, se implementaron consultas en SQL Server para validar los principales indicadores y métricas del proyecto.

Cada consulta se encuentra documentada junto con su respectivo resultado, permitiendo verificar la consistencia entre los valores obtenidos mediante SQL y las medidas DAX utilizadas en Power BI.

### Vista previa

![Sales Queries 1](images/sales_queries(1).png)


---

## Requerimientos del proyecto


### KPIs requeridos

![KPIs Requirement](images/KPIs_requirement.png)

### Visualizaciones requeridas

![Charts Requirement](images/charts_requirement.png)

---

## Dashboard

### Vista general

![Dashboard Overview](images/dashboard_overview.png)

### Resumen del análisis

![Dashboard Summary](images/dashboard_summary.png)

### Interactividad

La información puede explorarse dinámicamente mediante segmentadores por categoría y rango de fechas, actualizando automáticamente todos los indicadores y visualizaciones.

![Interactive View](images/interactive_view.png)

### Tabla y Datos

![Table View](images/table_view.png)

---

## Archivos de proyecto

- `dashboard/Pizza_Sales_Dashboard.pbix` → Desarrollo completo del proyecto en Power BI.
- `data/pizza_sales.csv` → Conjunto de datos original.
- `pizza_sales_queries.rtf` → Archivo original con las consultas SQL y capturas de sus resultados.
- `images/` → Capturas del proyecto.
- `README.md` → Documentación del proyecto.
