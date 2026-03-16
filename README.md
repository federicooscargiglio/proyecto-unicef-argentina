# Proyecto UNICEF Argentina — Bullying Escolar y Apuestas Online

> **English summary:** Data analysis and machine learning project on school bullying and online gambling among Argentine adolescents. Built with Python, pandas, scikit-learn and Looker Studio. Data sources: UNICEF Argentina, Ministry of Education, INDEC. Currently in progress — Week 2 of 8.

---

## ¿De qué trata este proyecto?

Este proyecto analiza dos problemáticas que afectan a los adolescentes argentinos: el **bullying escolar** y las **apuestas online**. A través de datos públicos de UNICEF Argentina, el Ministerio de Educación e INDEC, se construye un análisis completo que va desde la exploración de los datos hasta un modelo de Machine Learning para identificar perfiles de riesgo.

El objetivo final es presentar los hallazgos como propuesta de colaboración a **UNICEF Argentina**.

---

## Estado actual

| Semana | Fase | Estado |
|--------|------|--------|
| Semana 1 | Fundamentos y entorno | ✅ Completada |
| Semana 2 | Limpieza y auditoría de datos | 🔄 En progreso |
| Semana 3 | Análisis exploratorio I | ⏳ Pendiente |
| Semana 4 | Análisis exploratorio II | ⏳ Pendiente |
| Semana 5 | Feature Engineering | ⏳ Pendiente |
| Semana 6 | Machine Learning I | ⏳ Pendiente |
| Semana 7 | Machine Learning II | ⏳ Pendiente |
| Semana 8 | Dashboard y propuesta final | ⏳ Pendiente |

---

## Fuentes de datos

| Fuente | Descripción |
|--------|-------------|
| [UNICEF Argentina — Encuesta Rápida 2020–2024](https://www.unicef.org/argentina/informes) | Bullying, bienestar y conductas de riesgo en adolescentes |
| [Ministerio de Educación](https://www.argentina.gob.ar/educacion/planeamiento/siteal) | Matrícula, deserción y repitencia por provincia |
| [INDEC — EPH](https://www.indec.gob.ar) | Nivel socioeconómico y condiciones habitacionales |
| [SITAN UNICEF Argentina 2024](https://www.unicef.org/argentina/informes/sitan) | Situación de la infancia y adolescencia |
| [SENAF](https://www.argentina.gob.ar/senaf) | Protección de niñez y vulnerabilidad |

---

## Stack tecnológico

- **Lenguaje:** Python 3.11
- **Análisis de datos:** pandas, numpy
- **Visualización:** matplotlib, seaborn
- **Machine Learning:** scikit-learn
- **Dashboard:** Google Looker Studio
- **Entorno:** Jupyter Notebooks / VS Code

---

## Estructura del proyecto

```
PROYECTO UNICEF/
│
├── data/
│   ├── raw/          # Datos originales sin modificar
│   ├── clean/        # Datos procesados y limpios
│   └── ml/           # Datasets preparados para ML
│
├── notebooks/
│   ├── 00_test_entorno.ipynb
│   ├── 01_carga_datos.ipynb
│   └── 02_limpieza_datos.ipynb
│
├── outputs/          # Visualizaciones y resultados
├── docs/             # Documentación y contexto de sesión
└── README.md
```

---

## Autor

**Federico Oscar Giglio**
Diplomado en Ciencias de Datos — UTN
[LinkedIn](https://www.linkedin.com/in/federico-claudio-sait-oscar-giglio/) · [GitHub](https://github.com/federicooscargiglio)

---

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).