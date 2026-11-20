
# AQUABOT MAX ECOSYSTEM

## Satellite Environmental Monitoring | Monitoreo ambiental satelital

**Project | Proyecto:** AQUABOT MAX ECOSYSTEM  
**Organization | Organización:** ODEVE — Open Development Ecosystem  
**Platform | Plataforma:** https://monitoreo.trespalos.org  
**Module | Módulo:** Satellite Monitoring | Satélite  
**Languages | Idiomas:** English and Spanish | Inglés y español  
**Reference interface | Interfaz de referencia:** November 19, 2026 | 19 de noviembre de 2026

---

## 1. Overview | Descripción general

### English

The Satellite Monitoring module of AQUABOT MAX ECOSYSTEM provides an integrated interface for exploring environmental information derived from Earth observation technologies.

The interface combines satellite product selection, lagoon selection, geographic visualization, temporal observations, statistical summaries, and contextual interpretation of environmental indicators.

It is designed to complement local physicochemical water-quality monitoring with spatial and temporal information obtained from remote sensing.

The availability of observations depends on the selected lagoon, satellite product, period, and applicable quality criteria.

### Español

El módulo Satélite de AQUABOT MAX ECOSYSTEM proporciona una interfaz integrada para explorar información ambiental obtenida mediante tecnologías de observación de la Tierra.

La interfaz combina selección de productos satelitales, selección de lagunas, visualización geográfica, observaciones temporales, resúmenes estadísticos e interpretación contextual de indicadores ambientales.

Está diseñado para complementar el monitoreo fisicoquímico local de la calidad del agua con información espacial y temporal obtenida mediante percepción remota.

La disponibilidad de observaciones depende de la laguna, el producto satelital, el periodo seleccionado y los criterios de calidad aplicables.

---

## 2. Satellite Observation Products | Productos de observación satelital

The visible interface presents four satellite observation options.

La interfaz visible presenta cuatro opciones de observación satelital.

| Product | Description | Descripción |
|---|---|---|
| NDWI | Spectral index related to relative surface-water presence and moisture conditions. | Índice espectral relacionado con la presencia relativa de agua superficial y las condiciones de humedad. |
| Precipitation | Satellite-derived rainfall information for the lagoon environment. | Información de precipitación obtenida mediante satélites para el entorno lagunar. |
| Lagoon surface temperature | Satellite-derived surface temperature associated with water-classified areas in Landsat processing. | Temperatura superficial obtenida mediante satélites, asociada con áreas clasificadas como agua durante el procesamiento Landsat. |
| NISAR Radar | Radar backscatter information associated with L-band observations and HH polarization, as described by the interface. | Información de retrodispersión radar asociada con observaciones en banda L y polarización HH, conforme a la descripción de la interfaz. |

### English

The four product options are visible in the application.

However, the reference screenshot specifically documents NDWI observations. It does not independently verify successful map rendering or valid results for every other product.

### Español

Las cuatro opciones de productos aparecen en la aplicación.

Sin embargo, la captura de referencia documenta específicamente observaciones NDWI. No verifica de manera independiente la representación cartográfica correcta ni la existencia de resultados válidos para todos los demás productos.

---

## 3. Lagoon and Time Selection | Selección de laguna y periodo

| Component | Description | Descripción |
|---|---|---|
| Lagoon selector | Selection of an available lagoon for remote-sensing consultation. | Selección de una laguna disponible para consulta de percepción remota. |
| Time-range selector | Selection of the period used for satellite observations. | Selección del periodo utilizado para consultar observaciones satelitales. |
| Refresh control | Manual request to update the displayed information. | Control manual para solicitar la actualización de la información presentada. |
| Language selector | Interface available in English and Spanish. | Interfaz disponible en inglés y español. |

### Reference selection | Selección de referencia

**Lagoon | Laguna:** Tres Palos Lagoon | Laguna de Tres Palos  
**Selected product | Producto seleccionado:** NDWI  
**Period | Periodo:** Last 28 days | Últimos 28 días

---

## 4. Geographic Visualization | Visualización geográfica

### English

The module includes an interactive geographic map for displaying environmental satellite information associated with the selected lagoon.

The map provides spatial context through geographic reference information and the selected environmental layer.

Satellite-layer rendering may require loading and processing time.

In the reference screenshot, the map displays the message:

**"Loading satellite layer..."**

Therefore, the screenshot confirms the presence of the geographic interface but does not demonstrate that the selected satellite layer finished rendering at that moment.

### Español

El módulo incorpora un mapa geográfico interactivo para presentar información ambiental satelital asociada con la laguna seleccionada.

El mapa proporciona contexto espacial mediante información de referencia geográfica y la capa ambiental seleccionada.

La representación de las capas satelitales puede requerir tiempo de carga y procesamiento.

En la captura de referencia, el mapa muestra el mensaje:

**«Cargando capa satelital...»**

Por lo tanto, la captura confirma la presencia de la interfaz geográfica, pero no demuestra que la capa satelital seleccionada haya terminado de representarse en ese momento.

---

## 5. Satellite Information Panel | Ficha satelital

| Component | Description | Descripción |
|---|---|---|
| Satellite product | Identification of the selected environmental indicator. | Identificación del indicador ambiental seleccionado. |
| Lagoon | Water body associated with the consultation. | Cuerpo de agua asociado con la consulta. |
| Latest observation | Most recent available satellite record. | Registro satelital disponible más reciente. |
| Coverage | Number of available observations and their temporal range. | Número de observaciones disponibles y su intervalo temporal. |
| General interpretation | Descriptive explanation of the selected indicator. | Explicación descriptiva del indicador seleccionado. |
| Technical reference | Context for interpreting the indicator. | Contexto técnico para interpretar el indicador. |
| Temporal behavior | Direction and reported change of the selected indicator. | Dirección y cambio reportado del indicador seleccionado. |

---

## 6. Reference NDWI Observations | Observaciones NDWI de referencia

### English

The screenshot documented on November 19, 2026, presents NDWI observations for Tres Palos Lagoon.

The interface reports five available observations for the selected period.

The latest available satellite record is dated November 10, 2026, at 18:00, according to the application display.

### Español

La captura documentada el 19 de noviembre de 2026 presenta observaciones NDWI de la laguna de Tres Palos.

La interfaz reporta cinco observaciones disponibles para el periodo seleccionado.

El registro satelital disponible más reciente corresponde al 10 de noviembre de 2026 a las 18:00, según la información mostrada por la aplicación.

| Indicator | Displayed value | Valor mostrado |
|---|---:|---:|
| Latest NDWI / NDWI reciente | 0.267 | 0.267 |
| Reported change / Cambio reportado | 0.048 | 0.048 |
| Minimum / Mínimo | 0.158 | 0.158 |
| Maximum / Máximo | 0.267 | 0.267 |
| Average / Promedio | 0.209 | 0.209 |
| Median / Mediana | 0.219 | 0.219 |
| Standard deviation / Desviación estándar | 0.038 | 0.038 |
| Observation count / Conteo | 5 | 5 |

**Displayed trend | Tendencia mostrada:** Ascending | Ascendente

**Observation range | Intervalo de observaciones:** October 26 – November 10, 2026 | 26 de octubre – 10 de noviembre de 2026

### English

These values are associated with the platform's selected NDWI observations and should not be interpreted as measurements of physicochemical water quality.

The reported trend describes the behavior of the selected satellite index, not a comprehensive assessment of lagoon health.

### Español

Estos valores corresponden a las observaciones NDWI seleccionadas en la plataforma y no deben interpretarse como mediciones fisicoquímicas de calidad del agua.

La tendencia reportada describe el comportamiento del índice satelital seleccionado, no una evaluación integral de la salud lagunar.

---

## 7. NDWI Interpretation | Interpretación del NDWI

### English

The interface describes NDWI as an indicator of surface-water presence and moisture.

Higher values may be associated with greater relative presence of surface water, while lower values may correspond to soil, vegetation, or lower moisture conditions.

The interpretation depends on the spectral bands, processing methodology, geographic context, and characteristics of the observed surface.

An increase in NDWI does not, by itself, establish improved ecological water quality, greater water depth, or increased water volume.

### Español

La interfaz describe el NDWI como un indicador de presencia de agua superficial y humedad.

Los valores más altos pueden asociarse con mayor presencia relativa de agua superficial, mientras que los valores bajos pueden corresponder a suelo, vegetación o condiciones de menor humedad.

La interpretación depende de las bandas espectrales, la metodología de procesamiento, el contexto geográfico y las características de la superficie observada.

Un incremento del NDWI no demuestra, por sí solo, una mejora de la calidad ecológica del agua, mayor profundidad o incremento del volumen de agua.

---

## 8. Precipitation Observations | Observaciones de precipitación

### English

The interface includes a precipitation observation option.

Satellite-derived precipitation products may provide environmental context for interpreting rainfall conditions affecting lagoon ecosystems.

Such products represent estimates based on satellite observations and processing methods.

The reference screenshot does not include numerical precipitation results or verification of a completed precipitation-layer rendering.

### Español

La interfaz incorpora una opción de observación de precipitación.

Los productos de precipitación derivados de satélites pueden proporcionar contexto ambiental para interpretar las condiciones de lluvia que afectan a los ecosistemas lagunares.

Estos productos representan estimaciones basadas en observaciones satelitales y métodos de procesamiento.

La captura de referencia no contiene resultados numéricos de precipitación ni verifica que la capa correspondiente haya terminado de representarse.

---

## 9. Lagoon Surface Temperature | Temperatura superficial lagunar

### English

The module includes a lagoon surface-temperature option described as satellite-derived surface temperature over areas classified as water during Landsat processing.

Surface temperature obtained through remote sensing differs from direct in-water temperature measurements at specific depths.

Its interpretation requires consideration of observation time, cloud conditions, water classification, spatial resolution, and product quality.

The screenshot does not independently demonstrate valid temperature observations for the selected period.

### Español

El módulo incorpora una opción de temperatura superficial lagunar descrita como temperatura obtenida mediante satélites sobre áreas clasificadas como agua durante el procesamiento Landsat.

La temperatura superficial obtenida mediante percepción remota es diferente de las mediciones directas de temperatura dentro del agua a profundidades específicas.

Su interpretación requiere considerar la hora de observación, nubosidad, clasificación de agua, resolución espacial y calidad del producto.

La captura no demuestra de manera independiente observaciones válidas de temperatura para el periodo seleccionado.

---

## 10. NISAR Radar Observations | Observaciones radar NISAR

### English

The interface includes an option labeled NISAR Radar, described as L-band radar backscatter with HH polarization.

Radar backscatter is an electromagnetic measurement influenced by observation geometry and the physical characteristics of the target surface.

Its interpretation over aquatic environments requires attention to acquisition conditions, polarization, processing level, and the influence of surface roughness.

The presence of the NISAR option does not, by itself, verify the availability or successful rendering of a radar scene for the selected consultation.

### Español

La interfaz incorpora una opción denominada Radar NISAR, descrita como retrodispersión radar en banda L con polarización HH.

La retrodispersión radar es una medición electromagnética influida por la geometría de observación y las características físicas de la superficie analizada.

Su interpretación sobre ambientes acuáticos requiere considerar las condiciones de adquisición, polarización, nivel de procesamiento y la influencia de la rugosidad superficial.

La presencia de la opción NISAR no verifica, por sí sola, la disponibilidad o visualización correcta de una escena radar para la consulta seleccionada.

---

## 11. Temporal Satellite Series | Serie temporal satelital

### English

The module includes a temporal chart showing the evolution of the selected satellite indicator over the available observation dates.

The chart allows users to examine variations within the selected period.

The availability and spacing of observations depend on the product, satellite acquisition schedule, processing workflow, and data-quality requirements.

### Español

El módulo incorpora una gráfica temporal que muestra la evolución del indicador satelital seleccionado entre las fechas de observación disponibles.

La gráfica permite examinar las variaciones dentro del periodo seleccionado.

La disponibilidad y separación temporal de las observaciones dependen del producto, calendario de adquisición satelital, procesamiento y requisitos de calidad de los datos.

---

## 12. Descriptive Statistics | Estadísticas descriptivas

| Statistic | Description | Descripción |
|---|---|---|
| Minimum | Lowest available value in the selected series. | Valor mínimo disponible en la serie seleccionada. |
| Maximum | Highest available value in the selected series. | Valor máximo disponible en la serie seleccionada. |
| Average | Arithmetic mean of available observations. | Media aritmética de las observaciones disponibles. |
| Median | Central value of the ordered observations. | Valor central de las observaciones ordenadas. |
| Standard deviation | Dispersion of values around their average. | Dispersión de los valores respecto de su promedio. |
| Count | Number of observations in the selected dataset. | Número de observaciones del conjunto de datos seleccionado. |

### English

The statistics describe the selected satellite dataset and must be interpreted according to the physical meaning and units of each product.

### Español

Las estadísticas describen el conjunto de datos satelitales seleccionado y deben interpretarse conforme al significado físico y las unidades de cada producto.

---

## 13. Integration with Local Water-Quality Monitoring | Integración con el monitoreo local de calidad del agua

### English

Satellite observations provide spatial and temporal environmental context that can complement local physicochemical monitoring.

Combined interpretation requires care because satellite products and local sensors observe different physical properties, spatial scales, and sampling periods.

Comparisons must account for observation dates, measurement methods, coverage, and quality criteria.

Satellite observations should not be presented as direct replacements for in situ physicochemical measurements.

### Español

Las observaciones satelitales proporcionan contexto ambiental espacial y temporal que puede complementar el monitoreo fisicoquímico local.

Su interpretación conjunta requiere cuidado porque los productos satelitales y los sensores locales observan propiedades físicas, escalas espaciales y periodos de muestreo diferentes.

Las comparaciones deben considerar las fechas de observación, métodos de medición, cobertura y criterios de calidad.

Las observaciones satelitales no deben presentarse como sustitutos directos de las mediciones fisicoquímicas in situ.

---

## 14. Data Availability and Quality | Disponibilidad y calidad de los datos

### English

The module distinguishes satellite product options from the environmental observations actually available for a selected query.

Data availability may be affected by:

- Observation dates and satellite acquisition schedules.
- Geographic coverage.
- Cloud contamination and other quality limitations.
- Processing and classification criteria.
- Product-specific data availability.
- Satellite-layer loading or rendering status.

An empty or loading map must not be treated as a completed satellite observation.

Missing data must not be interpreted as a measured value of zero.

### Español

El módulo distingue las opciones de productos satelitales de las observaciones ambientales realmente disponibles para una consulta determinada.

La disponibilidad de datos puede verse afectada por:

- Fechas de observación y calendarios de adquisición satelital.
- Cobertura geográfica.
- Contaminación por nubes y otras limitaciones de calidad.
- Criterios de procesamiento y clasificación.
- Disponibilidad específica de cada producto.
- Estado de carga o representación de las capas satelitales.

Un mapa vacío o en proceso de carga no debe interpretarse como una observación satelital completada.

Los datos faltantes no deben interpretarse como valores medidos iguales a cero.

---

## 15. User Interface | Interfaz de usuario

| Feature | Description | Descripción |
|---|---|---|
| Satellite product cards | Selection of environmental observation products. | Selección de productos de observación ambiental. |
| Lagoon selector | Selection of the lagoon being monitored. | Selección de la laguna consultada. |
| Time-range selector | Definition of the observation period. | Definición del periodo de observación. |
| Geographic map | Spatial visualization of satellite-derived environmental information. | Visualización espacial de información ambiental obtenida mediante satélites. |
| Satellite information panel | Technical and contextual information about the selected indicator. | Información técnica y contextual del indicador seleccionado. |
| Temporal chart | Visualization of satellite observations over time. | Visualización temporal de observaciones satelitales. |
| Statistical indicators | Numerical summaries of available observations. | Resúmenes numéricos de las observaciones disponibles. |
| Refresh control | Manual request to update displayed information. | Control manual para solicitar la actualización de la información mostrada. |
| Language selector | Interface available in English and Spanish. | Interfaz disponible en inglés y español. |

---

## 16. Scientific and Environmental Relevance | Relevancia científica y ambiental

### English

The Satellite Monitoring module supports environmental observation by integrating multiple remote-sensing product options, geographic visualization, temporal information, and statistical interpretation.

These capabilities can contribute to the contextual analysis of lagoon conditions and help prioritize further field observations.

Scientific interpretation must consider each satellite product's physical meaning, observation geometry, temporal coverage, processing method, and uncertainty.

### Español

El módulo Satélite apoya la observación ambiental mediante la integración de distintas opciones de productos de percepción remota, visualización geográfica, información temporal e interpretación estadística.

Estas capacidades pueden contribuir al análisis contextual de las condiciones lagunares y ayudar a priorizar observaciones adicionales en campo.

La interpretación científica debe considerar el significado físico, geometría de observación, cobertura temporal, método de procesamiento e incertidumbre de cada producto satelital.

---

## 17. Functional Development | Desarrollo funcional

### English

The Satellite Monitoring module is available in the AQUABOT MAX ECOSYSTEM web application.

Its visible functions include four satellite product options, lagoon and period selection, an interactive geographic map, satellite information panels, temporal visualization, and descriptive statistics.

The reference screenshot confirms NDWI numerical and temporal information.

The successful rendering and availability of individual map layers and other satellite products require separate verification.

### Español

El módulo Satélite está disponible en la aplicación web AQUABOT MAX ECOSYSTEM.

Sus funciones visibles incluyen cuatro opciones de productos satelitales, selección de laguna y periodo, mapa geográfico interactivo, fichas satelitales, visualización temporal y estadísticas descriptivas.

La captura de referencia confirma información numérica y temporal de NDWI.

La representación correcta y disponibilidad de las capas cartográficas individuales y de los demás productos satelitales requieren verificación independiente.

---

**AQUABOT MAX ECOSYSTEM**  
**ODEVE — Open Development Ecosystem**
