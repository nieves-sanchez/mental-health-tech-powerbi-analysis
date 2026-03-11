# Mental Health in Tech — Análisis del impacto de la salud mental en el entorno laboral
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) [Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

---

Proyecto académico desarrollado en el **Bootcamp de Data Analyst & IA de Adalab**.

Este proyecto analiza la relación entre la **salud mental y el entorno laboral en el sector tecnológico**, utilizando datos de la encuesta **OSMI Mental Health in Tech Survey**.  

El objetivo es explorar patrones, identificar factores que influyen en el bienestar de los empleados y visualizar los resultados mediante **dashboards interactivos en Power BI**.

---

## Autoras

**Nieves Sánchez**  

[![GitHub](https://img.shields.io/badge/GitHub-Perfil-black?logo=github&logoColor=white)](https://github.com/nieves-sanchez)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nieves-sanchez-data)

**Ana María Castro**  

[![GitHub](https://img.shields.io/badge/GitHub-Perfil-black?logo=github&logoColor=white)](https://github.com/Narciandi90)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ana-maria-castro-narciandi/)

---

## Objetivo del proyecto

El objetivo principal del proyecto es analizar cómo diferentes factores laborales influyen en la salud mental de los profesionales del sector tecnológico.

A través del análisis exploratorio de datos y la visualización interactiva se busca:

- Explorar la relación entre salud mental y entorno laboral
- Analizar el impacto del apoyo empresarial y los beneficios disponibles
- Identificar perfiles de empleados con mayor vulnerabilidad
- Facilitar la interpretación de los datos mediante dashboards interactivos

---

## Dataset

El dataset utilizado proviene de la encuesta **Mental Health in Tech Survey** realizada por **Open Sourcing Mental Illness (OSMI)**.

La encuesta recoge información sobre:

- situación laboral
- tamaño de la empresa
- beneficios de salud mental
- cultura organizacional
- actitudes hacia la salud mental en el trabajo
- experiencias personales relacionadas con la salud mental

Fuente de datos:

OSMI Mental Health in Tech Survey

---

## Tecnologías utilizadas

Este proyecto combina herramientas de análisis de datos y visualización:

- Python
- Pandas
- Jupyter Notebook
- Power BI
- Git
- GitHub

---

## Estructura del repositorio

```text
data
│
├── raw
│ └── survey.csv
│
└── processed
└── osmi_mental_health_clean.csv

notebooks
│
└── 01_eda_limpieza_osmi.ipynb

dashboards
│
└── osmi_mental_health_dashboard.pbix

README.md
```

Descripción de carpetas:

**data/raw**  
Contiene el dataset original sin modificar.

**data/processed**  
Incluye el dataset limpio y preparado para su uso en el dashboard.

**notebooks**  
Notebook con el análisis exploratorio de datos (EDA) y el proceso de limpieza.

**dashboards**  
Archivo de Power BI con las visualizaciones finales del proyecto.

---

## Análisis exploratorio de datos

En el notebook se realiza un proceso de **EDA (Exploratory Data Analysis)** para comprender la estructura del dataset y preparar los datos para la visualización.

Las principales etapas incluyen:

- revisión de estructura del dataset
- análisis de tipos de variables
- detección de valores nulos
- identificación de duplicados
- limpieza y transformación de variables
- generación de un dataset final limpio para Power BI

---

## Dashboards en Power BI

El proyecto se presenta mediante una serie de **dashboards interactivos desarrollados en Power BI**, diseñados para explorar la relación entre salud mental y entorno laboral en el sector tecnológico a partir de la encuesta **OSMI Mental Health in Tech Survey**.

Los dashboards permiten analizar el problema desde distintas perspectivas: características de la muestra, impacto laboral, políticas empresariales, estigma en el entorno de trabajo y perfiles de empleados según su nivel de impacto.

### Visión general de la muestra

Este dashboard ofrece una **visión global del dataset y del perfil general de los encuestados**.

Incluye indicadores clave como:

- número total de participantes en la encuesta
- edad media de los encuestados
- número de países representados
- número de variables analizadas

Además, incorpora un **mapa geográfico** que permite visualizar la distribución de la muestra por países, junto con filtros interactivos para explorar los datos según:

- género  
- región  
- modalidad de trabajo remoto  
- perfil de empleado  

Este dashboard sirve como **punto de partida para contextualizar el análisis**.

---

### Impacto de la salud mental en el trabajo

Este dashboard analiza cómo la salud mental **interfiere en el desempeño laboral y cómo se relaciona con la búsqueda de tratamiento**.

Entre los aspectos analizados destacan:

- relación entre interferencia en el trabajo y tratamiento recibido  
- impacto del historial familiar de problemas de salud mental  
- distribución del tratamiento según grupos de edad  

Los resultados muestran que la **interferencia de la salud mental en el trabajo está estrechamente relacionada con la probabilidad de recibir tratamiento**, y que el grupo de edad entre **30 y 39 años** presenta mayor proporción de personas en tratamiento.

---

### La empresa ante la salud mental

Este dashboard examina **el papel de las empresas tecnológicas en el apoyo a la salud mental de sus empleados**.

El análisis incluye:

- acceso a beneficios de salud mental en la empresa  
- diferencias según el tamaño de la organización  
- existencia de programas de bienestar específicos  
- facilidad percibida para solicitar una baja por salud mental  

Los datos revelan que, aunque muchas empresas ofrecen **beneficios relacionados con la salud mental**, la presencia de **programas preventivos estructurados sigue siendo limitada**.

---

### Estigma y comunicación en el entorno tecnológico

Este dashboard aborda uno de los aspectos más relevantes del estudio: **el estigma asociado a la salud mental en el entorno laboral**.

Se analizan variables como:

- consecuencias percibidas al hablar de salud mental en el trabajo  
- disposición a mencionar problemas de salud mental en entrevistas laborales  
- comparación entre percepciones sobre salud mental y salud física  

Los resultados sugieren que **existe un estigma significativo**, ya que una gran parte de los empleados percibe posibles consecuencias negativas al abordar estos temas en el ámbito profesional.

---

### Perfiles de empleados según impacto en la salud mental

En este dashboard se realiza una **segmentación de los encuestados en distintos perfiles de impacto**, basada en la interferencia de la salud mental en el trabajo y la búsqueda de tratamiento.

Se identifican cuatro perfiles principales:

- alto impacto  
- impacto moderado  
- bajo impacto  
- sin impacto aparente  

El análisis permite comprender **cómo se distribuye la muestra entre distintos niveles de impacto**, destacando que una proporción significativa de empleados reporta un impacto relevante de la salud mental en su vida laboral.

---

### Perfiles de impacto y confianza para hablar de salud mental

El último dashboard explora **cómo los diferentes perfiles de impacto se relacionan con la disposición a hablar sobre salud mental en el entorno laboral**.

Se analizan aspectos como:

- disposición a hablar con supervisores  
- disposición a hablar con compañeros  
- percepción de posibles consecuencias laborales  

Este análisis permite identificar patrones de comportamiento y **niveles de confianza dentro de las organizaciones**, mostrando que el impacto personal en la salud mental influye en la forma en que los empleados gestionan la comunicación sobre estos temas.

---

## Conclusiones

El análisis de la encuesta **OSMI Mental Health in Tech Survey** permite identificar varios hallazgos relevantes sobre la salud mental en el sector tecnológico.

### Estigma laboral

Los datos muestran que **el estigma en torno a la salud mental sigue presente en el entorno laboral**.  

Solo **41 de los 1.246 encuestados** indicarían abiertamente problemas de salud mental durante una entrevista de trabajo, lo que refleja un fuerte temor a posibles consecuencias profesionales.

---

### Beneficios frente a prevención

Aunque una parte significativa de las empresas ofrece **beneficios relacionados con la salud mental**, la implementación de **programas de bienestar activos y preventivos es considerablemente menor**.

Esto sugiere que muchas organizaciones abordan la salud mental de forma reactiva, pero todavía existe margen de mejora en estrategias preventivas.

---

### Doble estándar entre salud mental y salud física

Los resultados indican que **hablar de salud mental en el trabajo se percibe como más arriesgado profesionalmente que hablar de salud física**.

Este doble estándar contribuye a que muchos empleados **eviten comunicar sus dificultades**, lo que puede agravar los problemas y retrasar la búsqueda de apoyo.

---

### Impacto real en el desempeño laboral

Una parte importante de los encuestados afirma que su salud mental **interfiere ocasionalmente en su desempeño laboral**.

Este hallazgo evidencia que la salud mental **no es solo un tema personal**, sino también un factor relevante para el funcionamiento y la productividad dentro de las organizaciones.

---

### Reflexión final

En conjunto, los resultados muestran que **la salud mental es un desafío real dentro del sector tecnológico**.

Aunque existe una creciente conciencia sobre el problema, aún persiste una **brecha entre el reconocimiento de la importancia de la salud mental y la implementación de medidas efectivas para abordarla dentro de las empresas**.

---

## Contexto académico

Este proyecto forma parte del **Bootcamp de Data Analyst & IA de Adalab**, donde se aplican conocimientos de:

- análisis de datos
- limpieza y preparación de datasets
- visualización de información
- comunicación de insights mediante dashboards

El objetivo del proyecto es aplicar metodologías de análisis de datos en un caso práctico y desarrollar habilidades técnicas y analíticas propias del rol de **Data Analyst**.

---

## Licencia

Este proyecto se desarrolla con fines educativos como parte del bootcamp de Adalab.
