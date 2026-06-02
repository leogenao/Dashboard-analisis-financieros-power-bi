# Dashboard-analisis-financieros-power-bi

# 📊 Dashboard de Análisis Financiero | Power BI

![Preview del Dashboard](images/preview.png)

## 🔗 Dashboard Interactivo

**Power BI Service:**
https://app.powerbi.com/groups/me/reports/440bf669-5b07-4746-9d67-9a0677db6bcd/24113e6cc83b6d0220e9?redirectedFromSignup=1&experience=power-bi

---

## 📌 Descripción del Proyecto

Este proyecto presenta un **Dashboard de Análisis Financiero** desarrollado en **Power BI** para una empresa del sector **Consumer Tech**, con dos líneas de negocio:

* 💻 **Dispositivos (Hardware)**
* ☁️ **Digital (Software y Servicios)**

El modelo analiza información financiera del período **2025–2027** con presencia comercial en **cinco continentes**, permitiendo evaluar rentabilidad, crecimiento y desempeño geográfico mediante visualizaciones ejecutivas orientadas a la toma de decisiones.

---

## 🎯 Objetivos del Análisis

* Analizar la evolución de ingresos, gastos y utilidad entre 2025 y 2027.
* Comparar la rentabilidad entre las categorías Dispositivos y Digital.
* Evaluar el desempeño financiero por continente y país.
* Identificar tendencias trimestrales de ingresos y márgenes.
* Apoyar decisiones estratégicas de asignación de recursos.

---

## 📊 KPIs Principales

| Indicador            |          Valor |
| -------------------- | -------------: |
| Ingresos Totales     | $3.363.434.207 |
| Gastos Totales       | $2.692.324.708 |
| Utilidad Total       |   $671.109.499 |
| Margen Neto Promedio |         19,95% |

---

## 📈 Visualizaciones Incluidas

### KPIs Ejecutivos

* Ingresos Totales
* Gastos Totales
* Utilidad Total
* Margen Neto

### Análisis Temporal

* Evolución anual de resultados financieros (2025–2027)
* Evolución trimestral de ingresos y utilidad

### Análisis por Producto

* Comparación de rentabilidad por categoría
* Participación de ingresos por línea de negocio

### Análisis Geográfico

* Distribución de ingresos por continente
* Margen por región
* Ranking de países por ingresos

### Interactividad

* Filtros por:

  * Año
  * Trimestre
  * Categoría
  * Región

---

## 🔎 Principales Hallazgos

### 💰 Digital lidera en rentabilidad

La categoría **Digital** alcanza un margen de **38,8%**, casi tres veces superior al margen de **Dispositivos (13,9%)**, convirtiéndose en el segmento más rentable.

### 🌍 América y Europa destacan en eficiencia

Presentan márgenes de **22,5%** y **22,0%** respectivamente, superando el promedio global.

### 🌏 Asia genera el mayor volumen

Con ingresos superiores a **$1.380M**, Asia es el principal mercado en ventas, aunque su margen (**17,1%**) se encuentra por debajo del promedio consolidado.

### ⚠️ Oportunidad en Hardware

La diferencia de aproximadamente **25 puntos porcentuales** entre ambas categorías sugiere revisar costos y eficiencia operativa del segmento Dispositivos.

### 📅 Estabilidad financiera

El margen neto se mantiene cercano al **20%** durante los 12 trimestres analizados, mostrando consistencia operativa.

---

## 🧮 Medidas DAX Utilizadas

```DAX
Total Ingresos =
SUM(Datos[Ingresos])

Total de Gastos =
SUM(Datos[Gastos])

Utilidad =
[Total Ingresos] - [Total de Gastos]

Margen =
DIVIDE([Utilidad], [Total Ingresos], 0)
```

---

## 🗂 Modelo de Datos

### Tabla de Hechos

**Datos**

* Ingresos
* Gastos
* Año
* Trimestre
* Continente
* País

### Tabla Dimensión

**Productos**

* Tipo Producto
* Categoría Producto

### Tabla de Medidas

**Medidas**

* Medidas DAX centralizadas

### Relación

```text
Datos[Tipo Producto]
        │
        ▼
Productos[Tipo Producto]
(Muchos a Uno)
```

---

## 🛠 Herramientas Utilizadas

* Power BI Desktop
* Power BI Service
* DAX
* Modelado de Datos

---

## 🧩 Habilidades Aplicadas

* DAX
* Modelado relacional
* Storytelling con datos
* Diseño de dashboards ejecutivos
* Business Intelligence
* Análisis financiero
* Visualización de datos

---

## 🧠 Enfoque Analítico

El dashboard fue diseñado bajo principios de:

* Jerarquía visual clara
* Diseño corporativo moderno
* KPIs orientados al negocio
* Storytelling visual
* Segmentación geográfica y por producto
* Toma de decisiones basada en datos

---

## 📂 Estructura del Proyecto

```text
proyecto-datdata/
│
├── data/
│   └── dataset.csv
│
├── dashboard/
│   └── proyecto_datdata.pbix
│
├── images/
│   └── preview.png
│
└── README.md
```

---

## 📌 Aplicabilidad Empresarial

Este análisis puede ser utilizado por:

* Dirección Financiera
* Gerencia General
* Equipos de Estrategia
* Analistas BI
* Product Managers
* Equipos Comerciales Internacionales

---

## 👤 Autor

**Leo Genao**

Proyecto desarrollado como parte de mi portafolio profesional de **Data Analytics y Business Intelligence**.

**Fuente de datos:** Academia Datdata

### Conecta conmigo

LinkedIn: https://www.linkedin.com/in/leo-genao/

---

⭐ Si te gustó este proyecto, considera darle una estrella al repositorio.

#PowerBI #DataAnalytics #BusinessIntelligence #FinancialAnalysis #DAX #DataPortfolio #ConsumerTech #Datdata
