# AQUABOT MAX ECOSYSTEM
## Technology Stack, Geospatial Platforms and Scientific Data Sources
## Tecnologías, plataformas geoespaciales y fuentes de datos científicos

**Project / Proyecto:** AQUABOT MAX ECOSYSTEM  
**Documentation version / Versión:** 1.0  
**Updated / Actualización:** November 20, 2026 / 20 de noviembre de 2026  
**Status / Estado:** Technical documentation / Documentación técnica

---

## 1. Overview | Descripción general

### English

AQUABOT MAX ECOSYSTEM is a technological ecosystem for monitoring the physicochemical characteristics of water bodies and providing environmental information to support socio-environmental decision-making.

The ecosystem combines in situ monitoring stations, electronic sensors, IoT communications, databases, interactive visualization, satellite observations, and historical environmental analysis.

Its development has involved multiple technologies, data providers, scientific products, and open-source components. This document identifies their roles and distinguishes direct measurements, remotely sensed observations, geospatial processing tools, and software infrastructure.

Listing a technology or scientific data source does not imply a formal partnership with its developer or provider.

### Español

AQUABOT MAX ECOSYSTEM es un ecosistema tecnológico para el monitoreo de las características fisicoquímicas de cuerpos de agua y la generación de información ambiental que apoye la toma de decisiones socioambientales.

El ecosistema integra estaciones de monitoreo in situ, sensores electrónicos, comunicaciones IoT, bases de datos, visualización interactiva, observaciones satelitales y análisis ambiental histórico.

Durante su desarrollo se han utilizado diversas tecnologías, proveedores de datos, productos científicos y componentes de software libre. Este documento identifica sus funciones y diferencia las mediciones directas, las observaciones remotas, las herramientas de procesamiento geoespacial y la infraestructura informática.

La inclusión de una tecnología o fuente de datos no implica una colaboración institucional formal con su desarrollador o proveedor.

---

## 2. Geospatial Processing Platforms | Plataformas de procesamiento geoespacial

### 2.1 Google Earth Engine

**Provider / Proveedor:** Google

**Official documentation:** https://developers.google.com/earth-engine/

#### English

Google Earth Engine provides cloud-based tools for processing and analyzing geospatial datasets and satellite imagery.

In the AQUABOT development workflow, Earth Engine has been considered and used as a geospatial processing environment for working with environmental observations, historical datasets, and areas of interest associated with monitored water bodies.

Relevant activities include:

- Selection of geographical areas of interest.
- Consultation of satellite imagery collections.
- Calculation and analysis of spectral indices.
- Temporal aggregation of environmental observations.
- Preparation of results for subsequent visualization and interpretation.

The use of Google Earth Engine does not mean that every environmental product displayed in AQUABOT is processed directly by Earth Engine. Individual processing pipelines must be identified according to their actual implementation.

#### Español

Google Earth Engine proporciona herramientas de procesamiento y análisis geoespacial en la nube para trabajar con imágenes satelitales y conjuntos de datos ambientales.

Durante el desarrollo de AQUABOT se ha utilizado como entorno de trabajo geoespacial para consultar y procesar observaciones ambientales, series históricas y áreas de interés asociadas con los cuerpos de agua monitoreados.

Entre las actividades relevantes se encuentran:

- Selección de áreas geográficas de interés.
- Consulta de colecciones de imágenes satelitales.
- Cálculo y análisis de índices espectrales.
- Agregación temporal de observaciones ambientales.
- Preparación de resultados para su visualización e interpretación.

El uso de Google Earth Engine no significa que todos los productos mostrados por AQUABOT sean procesados directamente mediante esta plataforma. Cada flujo de procesamiento deberá identificarse conforme a su implementación real.

### 2.2 NASA Earthdata and Alaska Satellite Facility

**Providers / Proveedores:** NASA and ASF DAAC

**References:**
- https://www.earthdata.nasa.gov/
- https://search.earthdata.nasa.gov/
- https://asf.alaska.edu/

#### English

NASA Earthdata provides discovery and access mechanisms for Earth observation datasets.

AQUABOT's satellite research and data acquisition activities include the consultation of NASA-related environmental products and the exploration of radar observations available through the Alaska Satellite Facility.

In particular, NISAR-related activities include searching and reviewing available radar products for selected monitoring areas.

Access to a satellite dataset must be distinguished from its operational integration into the public monitoring platform.

#### Español

NASA Earthdata proporciona mecanismos para descubrir y acceder a conjuntos de datos de observación de la Tierra.

Las actividades de investigación y adquisición de información satelital de AQUABOT incluyen la consulta de productos ambientales relacionados con NASA y la exploración de observaciones radar disponibles mediante Alaska Satellite Facility.

En particular, las actividades relacionadas con NISAR comprenden la búsqueda y revisión de productos radar disponibles para áreas seleccionadas de monitoreo.

El acceso a un conjunto de datos satelitales debe distinguirse de su integración operativa en la plataforma pública de monitoreo.

---

## 3. Satellite Missions and Sensors | Misiones y sensores satelitales

| Mission or source | Main technology | Relevance to AQUABOT |
|---|---|---|
| Landsat 5, 7, 8 and 9 | Multispectral and thermal observations | Historical surface conditions and temperature-related products |
| Sentinel-2 | Multispectral optical imagery | Water-related spectral indices and environmental context |
| Sentinel-3 OLCI | Ocean and Land Colour Instrument | Aquatic optical observations and selected derived products |
| MODIS | Moderate-resolution optical observations | Historical optical products, including KD490 |
| GPM | Satellite precipitation observations | Recent precipitation products such as IMERG |
| NISAR | Synthetic aperture radar | Radar-based environmental research and exploratory analysis |
| NOAA OISST | Blended sea surface temperature dataset | Regional marine temperature context |
| CHIRPS | Satellite-informed precipitation dataset | Historical precipitation analysis |

### Español

| Misión o fuente | Tecnología principal | Aplicación en AQUABOT |
|---|---|---|
| Landsat 5, 7, 8 y 9 | Observaciones multiespectrales y térmicas | Condiciones históricas de superficie y productos relacionados con temperatura |
| Sentinel-2 | Imágenes ópticas multiespectrales | Índices espectrales relacionados con agua y contexto ambiental |
| Sentinel-3 OLCI | Instrumento óptico de color del océano y superficie terrestre | Observaciones ópticas acuáticas y productos derivados seleccionados |
| MODIS | Observaciones ópticas de resolución moderada | Productos ópticos históricos, incluido KD490 |
| GPM | Observaciones satelitales de precipitación | Productos recientes de precipitación, como IMERG |
| NISAR | Radar de apertura sintética | Investigación ambiental y análisis exploratorio radar |
| NOAA OISST | Conjunto integrado de temperatura superficial marina | Contexto térmico marino regional |
| CHIRPS | Conjunto de precipitación apoyado en observaciones satelitales | Análisis histórico de precipitación |

**Technical clarification / Aclaración técnica:** CHIRPS and OISST are datasets, not individual satellites. NISAR and Landsat are missions; OLCI and MODIS are instruments. Their roles should not be confused.

---

## 4. Environmental Data Products | Productos ambientales

### 4.1 NDWI — Normalized Difference Water Index

**English:** NDWI is used to analyze spectral conditions associated with surface water presence and related land-water characteristics. Its interpretation depends on the specific formula, sensor, processing method, and study context.

**Español:** El NDWI se utiliza para analizar condiciones espectrales asociadas con la presencia de agua superficial y características relacionadas con la interacción entre agua y superficie terrestre. Su interpretación depende de la fórmula específica, el sensor, el procesamiento y el contexto de estudio.

### 4.2 LST — Land Surface Temperature

**English:** Landsat-derived surface temperature products provide thermal information about observed surfaces. Water-focused summaries require appropriate masks, spatial coverage assessment, and quality checks. LST must not automatically be interpreted as a direct in situ water temperature measurement.

**Español:** Los productos de temperatura superficial derivados de Landsat proporcionan información térmica sobre las superficies observadas. Los resúmenes aplicados al agua requieren máscaras adecuadas, evaluación de cobertura espacial y controles de calidad. La LST no debe interpretarse automáticamente como temperatura del agua medida directamente in situ.

### 4.3 Precipitation — CHIRPS and GPM IMERG

**English:** Historical and recent precipitation products support the environmental interpretation of hydrological conditions around monitored water bodies. Different products have distinct temporal resolutions, spatial resolutions, and uncertainty characteristics.

**Español:** Los productos históricos y recientes de precipitación ayudan a interpretar las condiciones hidrológicas del entorno de los cuerpos de agua monitoreados. Cada producto tiene resoluciones espaciales y temporales, así como características de incertidumbre, diferentes.

### 4.4 OISST — Sea Surface Temperature

**English:** NOAA OISST provides regional marine temperature context. It is not a direct measurement of lagoon water temperature.

**Español:** NOAA OISST proporciona contexto térmico marino regional. No constituye una medición directa de la temperatura del agua de la laguna.

### 4.5 NDVI — Normalized Difference Vegetation Index

**English:** NDVI contributes information about vegetation conditions within the environmental context of monitored areas.

**Español:** El NDVI aporta información sobre las condiciones de la vegetación dentro del contexto ambiental de las áreas monitoreadas.

### 4.6 CHL_A — Chlorophyll-a

**English:** Satellite-derived chlorophyll-a products can provide optical information relevant to aquatic environmental research. Their interpretation in coastal lagoons requires caution because suspended sediments, shallow water, and other optical conditions may affect retrieval accuracy.

**Español:** Los productos satelitales derivados de clorofila-a pueden aportar información óptica relevante para la investigación ambiental acuática. Su interpretación en lagunas costeras requiere precaución debido a sedimentos suspendidos, poca profundidad y otras condiciones ópticas que pueden afectar la precisión de las estimaciones.

### 4.7 KD490 — Diffuse Attenuation Coefficient

**English:** KD490 is an optical product related to light attenuation in water. Its use in complex coastal waters requires appropriate scientific validation.

**Español:** KD490 es un producto óptico relacionado con la atenuación de la luz en el agua. Su utilización en aguas costeras complejas requiere validación científica apropiada.

### 4.8 NISAR Radar Observations

**English:** NISAR radar products provide an additional observation modality that may help investigate environmental surface characteristics. Radar measurements are not direct readings of pH, dissolved oxygen, salinity, or other physicochemical water-quality parameters.

**Español:** Los productos radar de NISAR proporcionan una modalidad adicional de observación que puede contribuir al estudio de características ambientales de superficie. Las mediciones radar no equivalen a lecturas directas de pH, oxígeno disuelto, salinidad u otros parámetros fisicoquímicos del agua.

---

## 5. Mapping and Visualization | Cartografía y visualización

### 5.1 OpenStreetMap

**Website:** https://www.openstreetmap.org/

**English:** OpenStreetMap provides community-maintained geographic data used as a cartographic reference for the visualization of monitoring areas and environmental observations.

**Español:** OpenStreetMap proporciona información geográfica mantenida por una comunidad de colaboradores, utilizada como referencia cartográfica para visualizar áreas de monitoreo y observaciones ambientales.

**Attribution / Atribución:** © OpenStreetMap contributors — https://www.openstreetmap.org/copyright

### 5.2 Leaflet and React-Leaflet

**References:**
- https://leafletjs.com/
- https://react-leaflet.js.org/

**English:** Leaflet and React-Leaflet support interactive map presentation, including environmental layers, geographical interfaces, and the visualization of spatially referenced monitoring information.

**Español:** Leaflet y React-Leaflet permiten presentar mapas interactivos, incluyendo capas ambientales, interfaces geográficas y la visualización de información de monitoreo con referencia espacial.

### 5.3 Recharts

**Reference:** https://recharts.org/

**English:** Recharts supports the graphical presentation of environmental measurements, trends, and historical time series within the web platform.

**Español:** Recharts permite representar gráficamente mediciones ambientales, tendencias y series temporales históricas dentro de la plataforma web.

---

## 6. IoT Hardware and Communications | Hardware y comunicaciones IoT

### 6.1 ESP32 Microcontrollers

**English:** ESP32-based devices form part of AQUABOT's electronic monitoring architecture, enabling sensor acquisition, local processing, and network communications.

**Español:** Los dispositivos basados en ESP32 forman parte de la arquitectura electrónica de monitoreo de AQUABOT y permiten adquirir datos de sensores, realizar procesamiento local y establecer comunicaciones de red.

### 6.2 Physicochemical Sensors

**English:** The monitoring architecture includes sensors and calculations associated with parameters such as temperature, pH, total dissolved solids (TDS), electrical conductivity (EC), oxidation-reduction potential (ORP), salinity, dissolved oxygen (DO), and carbon dioxide (CO₂).

The measurement status, calibration, and whether a value is directly measured or estimated must be documented for each parameter.

**Español:** La arquitectura de monitoreo incluye sensores y cálculos relacionados con parámetros como temperatura, pH, sólidos disueltos totales (TDS), conductividad eléctrica (EC), potencial de oxidación-reducción (ORP), salinidad, oxígeno disuelto (OD) y dióxido de carbono (CO₂).

Para cada parámetro debe documentarse su condición de medición, calibración y si el valor se mide directamente o se obtiene mediante estimación.

### 6.3 MQTT and TLS

**English:** MQTT supports communication between monitoring devices and server-side services. TLS is used to protect communications in the documented deployment architecture.

**Español:** MQTT permite la comunicación entre los dispositivos de monitoreo y los servicios del servidor. TLS se utiliza para proteger las comunicaciones dentro de la arquitectura de despliegue documentada.

---

## 7. Software Architecture and Infrastructure | Arquitectura informática e infraestructura

| Component | Role / Función |
|---|---|
| Next.js and React | Web application interface / Interfaz de la aplicación web |
| Tailwind CSS | User interface styling / Estilos de la interfaz |
| Recharts | Time-series and graphical visualization / Gráficas y series temporales |
| Leaflet / React-Leaflet | Interactive cartography / Cartografía interactiva |
| Python and Flask | Environmental analysis services and API endpoints / Servicios de análisis ambiental y API |
| MySQL | Storage of monitoring records / Almacenamiento de registros de monitoreo |
| MQTT over TLS | Secure IoT data transport / Transporte protegido de datos IoT |
| ESP32 | Embedded sensor acquisition / Adquisición electrónica de sensores |
| Docker | Containerized service deployment where applicable / Despliegue de servicios en contenedores cuando corresponda |
| Linux / VPS infrastructure | Server-side operation and service hosting / Operación y alojamiento de servicios |

**English:** The presence of a component in this inventory does not guarantee that all project services currently run on the same server or use the same deployment architecture.

**Español:** La presencia de un componente en este inventario no significa que todos los servicios del proyecto se ejecuten actualmente en el mismo servidor o utilicen idéntica arquitectura de despliegue.

---

## 8. Data Integration Workflow | Flujo de integración de datos

### English

AQUABOT's environmental information workflow can be represented as a combination of two complementary branches:

**In situ monitoring:**

Sensors → ESP32 devices → MQTT communications → Backend services → Database → Web dashboard.

**Satellite and environmental observations:**

Scientific data providers → Data discovery and acquisition → Geospatial or numerical processing → Quality assessment → Environmental data services → Interactive maps and historical analysis.

These branches provide different kinds of evidence. Their results may be interpreted together, but they must not be treated as interchangeable measurements.

### Español

El flujo de información ambiental de AQUABOT puede representarse mediante dos ramas complementarias:

**Monitoreo in situ:**

Sensores → Dispositivos ESP32 → Comunicaciones MQTT → Servicios backend → Base de datos → Panel web.

**Observaciones satelitales y ambientales:**

Proveedores científicos → Búsqueda y adquisición de datos → Procesamiento geoespacial o numérico → Evaluación de calidad → Servicios de información ambiental → Mapas interactivos y análisis histórico.

Estas ramas proporcionan tipos diferentes de evidencia. Sus resultados pueden interpretarse conjuntamente, pero no deben considerarse mediciones equivalentes.

---

## 9. Data Provenance and Scientific Traceability | Procedencia de datos y trazabilidad científica

### English

Whenever possible, every environmental observation or derived result should preserve:

1. Source organization and dataset name.
2. Satellite mission, sensor, or measuring instrument.
3. Product identifier and processing level.
4. Acquisition date and time, with time zone.
5. Geographical coverage and spatial resolution.
6. Processing method, formula, and relevant parameters.
7. Quality indicators, coverage, and known limitations.
8. Data retrieval or processing date.
9. Dataset version and reference documentation.
10. Attribution and applicable usage terms.

Satellite observations, field readings, estimated variables, and conceptual representations must be clearly differentiated.

### Español

Siempre que sea posible, cada observación ambiental o resultado derivado deberá conservar:

1. Organización de origen y nombre del conjunto de datos.
2. Misión satelital, sensor o instrumento de medición.
3. Identificador del producto y nivel de procesamiento.
4. Fecha y hora de adquisición, incluyendo zona horaria.
5. Cobertura geográfica y resolución espacial.
6. Método de procesamiento, fórmula y parámetros relevantes.
7. Indicadores de calidad, cobertura y limitaciones conocidas.
8. Fecha de consulta o procesamiento.
9. Versión del conjunto de datos y documentación de referencia.
10. Atribución y condiciones de uso aplicables.

Las observaciones satelitales, lecturas de campo, variables estimadas y representaciones conceptuales deben diferenciarse claramente.

---

## 10. Technology Integration Status | Estado de integración tecnológica

### English

The technologies listed in this document have different roles and levels of integration within the AQUABOT ecosystem.

- **Implemented platform components:** technologies documented as part of deployed applications, monitoring devices, databases, and visualization services.
- **Integrated environmental products:** datasets and indicators included in existing environmental analysis workflows.
- **Research and exploratory tools:** resources used for dataset discovery, scientific evaluation, testing, or prototype development.
- **Pending verification:** tools or dependencies whose exact version, service location, or present operational use requires repository or deployment inspection.

A technology must not be classified as operational solely because it appears in an experimental script, screenshot, proposal, or design document.

### Español

Las tecnologías incluidas en este documento tienen diferentes funciones y niveles de integración dentro del ecosistema AQUABOT.

- **Componentes implementados:** tecnologías documentadas como parte de aplicaciones desplegadas, dispositivos de monitoreo, bases de datos y servicios de visualización.
- **Productos ambientales integrados:** conjuntos de datos e indicadores incorporados en los flujos existentes de análisis ambiental.
- **Herramientas de investigación y exploración:** recursos utilizados para descubrir conjuntos de datos, realizar evaluaciones científicas, pruebas o desarrollo de prototipos.
- **Verificación pendiente:** herramientas o dependencias cuya versión exacta, ubicación del servicio o uso operativo actual requiere inspeccionar el repositorio o despliegue.

Una tecnología no deberá clasificarse como operativa únicamente por aparecer en un script experimental, captura de pantalla, propuesta o documento de diseño.

---

## 11. Technology Providers and Attribution | Proveedores tecnológicos y atribuciones

The project acknowledges the scientific data infrastructures, open-source communities, and technology providers whose resources support its development.

El proyecto reconoce las infraestructuras de datos científicos, comunidades de software libre y proveedores tecnológicos cuyos recursos contribuyen a su desarrollo.

| Provider / Proveedor | Official reference / Referencia oficial |
|---|---|
| Google Earth Engine | https://developers.google.com/earth-engine/ |
| NASA Earthdata | https://www.earthdata.nasa.gov/ |
| NASA / USGS Landsat | https://landsat.gsfc.nasa.gov/ |
| Alaska Satellite Facility | https://asf.alaska.edu/ |
| Copernicus Data Space | https://dataspace.copernicus.eu/ |
| ESA | https://www.esa.int/ |
| NOAA | https://www.noaa.gov/ |
| CHIRPS / Climate Hazards Center | https://www.chc.ucsb.edu/data/chirps |
| OpenStreetMap | https://www.openstreetmap.org/copyright |
| Leaflet | https://leafletjs.com/ |
| React-Leaflet | https://react-leaflet.js.org/ |
| Recharts | https://recharts.org/ |
| Espressif Systems | https://www.espressif.com/ |

### Institutional clarification | Aclaración institucional

**English:** The use of data, tools, and publicly available services from these organizations does not imply endorsement, sponsorship, certification, or a formal institutional partnership with AQUABOT MAX ECOSYSTEM.

**Español:** El uso de datos, herramientas y servicios públicos de estas organizaciones no implica respaldo, patrocinio, certificación ni colaboración institucional formal con AQUABOT MAX ECOSYSTEM.

---

## 12. Security and Responsible Documentation | Seguridad y documentación responsable

### English

Public repositories must not contain credentials, API keys, access tokens, database passwords, private certificates, or other sensitive operational information.

Technical documentation should describe the architecture without exposing confidential configuration.

### Español

Los repositorios públicos no deben contener credenciales, claves de API, tokens de acceso, contraseñas de bases de datos, certificados privados ni otros datos operativos sensibles.

La documentación técnica debe describir la arquitectura sin divulgar configuraciones confidenciales.

---

## 13. Related Documentation | Documentación relacionada

- [Main Project README](../README.md)
- [System Architecture](../SYSTEM_ARCHITECTURE.md)
- [Technology Evolution 2025–2026](../TECHNOLOGY_EVOLUTION_2025-2026.md)
- [Platform Modules](platform-modules/README.md)
- [Satellite Monitoring Module](platform-modules/satellite-monitoring/README.md)
- [Satellite Observation Evidence](../evidence/satellite-observations/README.md)

---

**AQUABOT MAX ECOSYSTEM**

*Environmental monitoring through technology, scientific observation, and responsible data integration.*

*Monitoreo ambiental mediante tecnología, observación científica e integración responsable de datos.*
