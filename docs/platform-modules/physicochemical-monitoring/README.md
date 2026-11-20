
# AQUABOT MAX ECOSYSTEM

## Physicochemical Monitoring | Monitoreo fisicoquímico

**Project | Proyecto:** AQUABOT MAX ECOSYSTEM  
**Organization | Organización:** ODEVE — Open Development Ecosystem  
**Platform | Plataforma:** https://monitoreo.trespalos.org  
**Module | Módulo:** Physicochemical Monitoring | Monitoreo fisicoquímico  
**Languages | Idiomas:** English and Spanish | Inglés y español

---

## 1. Overview | Descripción general

### English

The AQUABOT MAX ECOSYSTEM Physicochemical Monitoring module provides a detailed view of local water-quality information, including physicochemical indicators, variable-level interpretation, temporal behavior, descriptive statistics, and an operational data table.

The module supports the examination of available observations by monitoring station and selected period.

### Español

El módulo de Monitoreo fisicoquímico de AQUABOT MAX ECOSYSTEM presenta información detallada de la calidad del agua, incluyendo indicadores fisicoquímicos locales, interpretación por variable, comportamiento temporal, estadísticas descriptivas y una tabla operativa de datos.

El módulo permite examinar las observaciones disponibles por estación de monitoreo y periodo seleccionado.

---

## 2. Monitoring Summary | Resumen del monitoreo

The interface presents a summary of monitored variables and their classifications.

La interfaz presenta un resumen de las variables monitoreadas y sus clasificaciones.

| Indicator | English description | Descripción en español |
|---|---|---|
| Monitored variables | Number of local variables included in the monitoring classification. | Número de variables locales incluidas en la clasificación de monitoreo. |
| Stable variables | Variables classified as stable by the system backend. | Variables clasificadas como estables por el backend del sistema. |
| Variables under observation | Variables requiring additional monitoring attention. | Variables que requieren seguimiento adicional. |
| Priority attention | Variables classified as critical according to configured criteria. | Variables clasificadas como críticas conforme a los criterios configurados. |

### Reference example | Ejemplo de referencia

The November 19, 2026 screenshot displays:

La captura del 19 de noviembre de 2026 muestra:

| Indicator | Value | Valor |
|---|---:|---:|
| Monitored variables | 6 | 6 |
| Stable variables | 5 | 5 |
| Under observation | 1 | 1 |
| Priority attention | 0 | 0 |

These classifications correspond to the selected station and period. They do not represent a comprehensive ecological diagnosis of the lagoon.

Estas clasificaciones corresponden a la estación y el periodo seleccionados. No representan un diagnóstico ecológico integral de la laguna.

---

## 3. Physicochemical Variables | Variables fisicoquímicas

| Variable | English description | Descripción en español |
|---|---|---|
| pH | Indicator of water acidity or alkalinity. | Indicador de acidez o alcalinidad del agua. |
| Temperature | Water temperature expressed in degrees Celsius. | Temperatura del agua expresada en grados Celsius. |
| TDS | Total dissolved solids expressed in ppm. | Sólidos disueltos totales expresados en ppm. |
| Electrical conductivity | Electrical conductivity expressed in µS/cm. | Conductividad eléctrica expresada en µS/cm. |
| Salinity | Salt concentration estimate displayed in ppt. | Estimación de concentración de sales mostrada en ppt. |
| Millivolts (mV) | Electrical potential indicator when valid readings are available. | Indicador de potencial eléctrico cuando existen lecturas válidas. |
| Dissolved oxygen | Dissolved oxygen indicator displayed in mg/L. | Indicador de oxígeno disuelto mostrado en mg/L. |
| Carbon dioxide | Carbon dioxide indicator displayed when data are available. | Indicador de dióxido de carbono mostrado cuando existen datos disponibles. |

### Reference readings | Lecturas de referencia

The following values were displayed on November 19, 2026, at 18:00.

Los siguientes valores se mostraron el 19 de noviembre de 2026 a las 18:00.

| Variable | Displayed value | Unit |
|---|---:|---|
| pH | 7.94 | pH |
| Temperature / Temperatura | 30.6 | °C |
| TDS | 2001 | ppm |
| Electrical conductivity / Conductividad eléctrica | 3942.5 | µS/cm |
| Salinity / Salinidad | 2.00 | ppt |
| Millivolts / Milivoltios | No valid reading / Sin lectura válida | mV |
| Dissolved oxygen / Oxígeno disuelto | 3.383 | mg/L |
| Carbon dioxide / Dióxido de carbono | No valid reading / Sin lectura válida | mg/L |

These values document the information displayed by the platform at the time of the screenshot. Their measurement or estimation methods must be interpreted according to the system's technical documentation.

Estos valores documentan la información mostrada por la plataforma al momento de la captura. Sus métodos de medición o estimación deben interpretarse conforme a la documentación técnica del sistema.

---

## 4. Variable-Level Interpretation | Interpretación por variable

### English

Each physicochemical indicator includes an interpretation panel when the necessary information is available.

The interface may display:

- A description of whether a variable is within an expected range.
- A message indicating that additional monitoring is recommended.
- A notification when no specific interpretation is available.
- An indication when updated information is pending.

The interpretation must be considered together with the monitoring context and available measurements.

### Español

Cada indicador fisicoquímico incorpora un panel de interpretación cuando existe información suficiente.

La interfaz puede presentar:

- Una descripción sobre si la variable se encuentra dentro de un rango esperado.
- Un mensaje indicando que se recomienda seguimiento adicional.
- Una notificación cuando no existe una interpretación específica disponible.
- Una indicación cuando está pendiente la actualización de información.

La interpretación debe considerarse junto con el contexto de monitoreo y las mediciones disponibles.

---

## 5. Temporal Behavior | Comportamiento temporal

### English

The module includes an interactive temporal chart for examining the evolution of physicochemical variables.

Users can select the variable of interest and review the observations associated with the selected station and reporting period.

The visualization supports comparisons of temporal variations and helps identify changes that may require further analysis.

### Español

El módulo incorpora una gráfica temporal interactiva para examinar la evolución de las variables fisicoquímicas.

El usuario puede seleccionar la variable de interés y consultar las observaciones correspondientes a la estación y al periodo seleccionados.

La visualización facilita la comparación de variaciones temporales y ayuda a identificar cambios que pueden requerir análisis adicional.

---

## 6. Variable Information Panel | Ficha de la variable

| Component | English description | Descripción en español |
|---|---|---|
| Current value | Latest displayed value of the selected variable. | Último valor mostrado de la variable seleccionada. |
| Status | Information about the availability or update status of the variable. | Información sobre la disponibilidad o actualización de la variable. |
| Purpose | Explanation of the environmental relevance of the variable. | Explicación de la relevancia ambiental de la variable. |
| Average | Mean value of available observations. | Valor promedio de las observaciones disponibles. |
| Minimum | Lowest value in the analyzed period. | Valor mínimo del periodo analizado. |
| Maximum | Highest value in the analyzed period. | Valor máximo del periodo analizado. |
| Standard deviation | Statistical dispersion of the available values. | Dispersión estadística de los valores disponibles. |
| Trend | General behavior of the variable over time. | Comportamiento general de la variable a lo largo del tiempo. |
| Reading count | Number of observations used in the displayed statistics. | Número de observaciones utilizadas en las estadísticas mostradas. |

---

## 7. Operational Data Table | Tabla operativa de datos

### English

The operational table organizes the monitored variables and provides an overview of their displayed values, availability status, last valid observation, and descriptive statistics.

It supports the review of individual indicators within the selected monitoring context.

### Español

La tabla operativa organiza las variables monitoreadas y presenta sus valores, estado de disponibilidad, última observación válida y estadísticas descriptivas.

Facilita la revisión individual de los indicadores dentro del contexto de monitoreo seleccionado.

---

## 8. Data Availability | Disponibilidad de datos

### English

The platform distinguishes between valid monitoring information and variables with incomplete or unavailable data.

Possible interface messages include:

- **Update pending:** New information has not yet been reflected in the displayed update status.
- **No status available:** A valid operational status is not available.
- **No valid reading:** The variable does not have a valid observation.
- **No diagnosis available:** The system does not provide a specific interpretation for the variable.

Missing information must not be interpreted as a measured value of zero.

### Español

La plataforma distingue entre información válida de monitoreo y variables con datos incompletos o no disponibles.

Entre los mensajes de la interfaz se encuentran:

- **Actualización pendiente:** La información nueva todavía no se refleja en el estado de actualización mostrado.
- **Sin estado disponible:** No se dispone de un estado operativo válido.
- **Sin lectura válida:** La variable no cuenta con una observación válida.
- **Sin diagnóstico disponible:** El sistema no proporciona una interpretación específica de la variable.

La ausencia de información no debe interpretarse como un valor medido igual a cero.

---

## 9. User Interface | Interfaz de usuario

| Feature | English description | Descripción en español |
|---|---|---|
| Station filter | Selection of the monitoring station or available view. | Selección de estación de monitoreo o vista disponible. |
| Time-range filter | Selection of the period for temporal analysis. | Selección del periodo para el análisis temporal. |
| Variable selector | Interactive selection of physicochemical variables. | Selección interactiva de variables fisicoquímicas. |
| Language selector | Interface available in English and Spanish. | Interfaz disponible en inglés y español. |
| Diagnostic cards | Presentation of available interpretations by variable. | Presentación de las interpretaciones disponibles por variable. |
| Operational table | Structured consultation of monitoring records and statistics. | Consulta estructurada de registros y estadísticas de monitoreo. |

---

## 10. Scientific Relevance | Relevancia científica

### English

The Physicochemical Monitoring module supports the interpretation of local aquatic conditions by combining recent indicators, temporal information, variable-level explanations, and descriptive statistics.

Its information may be compared with historical monitoring data and complementary satellite-derived environmental observations, taking into account the methods and limitations of each data source.

### Español

El módulo de Monitoreo fisicoquímico contribuye a interpretar las condiciones acuáticas locales mediante la integración de indicadores recientes, información temporal, explicaciones por variable y estadísticas descriptivas.

Su información puede compararse con registros históricos y observaciones ambientales satelitales complementarias, considerando los métodos y limitaciones de cada fuente de datos.

---

## 11. Functional Development | Desarrollo funcional

### English

The Physicochemical Monitoring module is available in the AQUABOT MAX ECOSYSTEM web application.

It presents monitored variables, classifications, diagnostic messages, temporal visualization, statistical information, and an operational data table.

The availability of individual measurements and interpretations depends on valid data and the functionality implemented for each indicator.

### Español

El módulo de Monitoreo fisicoquímico está disponible en la aplicación web AQUABOT MAX ECOSYSTEM.

Presenta variables monitoreadas, clasificaciones, mensajes de diagnóstico, visualización temporal, información estadística y una tabla operativa de datos.

La disponibilidad de mediciones e interpretaciones individuales depende de la existencia de datos válidos y de la funcionalidad implementada para cada indicador.

---

**AQUABOT MAX ECOSYSTEM**  
**ODEVE — Open Development Ecosystem**
