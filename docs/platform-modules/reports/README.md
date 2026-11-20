
# AQUABOT MAX ECOSYSTEM

## Environmental Diagnostic Reports | Informes diagnósticos ambientales

**Project | Proyecto:** AQUABOT MAX ECOSYSTEM  
**Organization | Organización:** ODEVE — Open Development Ecosystem  
**Platform | Plataforma:** https://monitoreo.trespalos.org  
**Module | Módulo:** Reports | Reportes  
**Development status | Estado de desarrollo:** Operational report generation interface | Interfaz operativa de generación de informes  
**Languages | Idiomas:** English and Spanish | Inglés y español  
**Reference interface | Interfaz de referencia:** November 19, 2026 | 19 de noviembre de 2026

---

## 1. Overview | Descripción general

### English

The Reports module of AQUABOT MAX ECOSYSTEM provides an on-demand interface for generating environmental diagnostic summaries using available lagoon monitoring information.

The module combines results from the system's analytical services to present current environmental conditions, statistical consistency assessments, and spectral analysis of a selected principal variable when sufficient observations are available.

The interface supports two monitoring source categories:

- Local physicochemical sensors.
- Satellite environmental observations.

The reference screenshots demonstrate successful generation and display of reports for different local and satellite variables.

PDF and CSV export controls are available in the generated-report interface. The contents and successful downloading of these files require separate verification.

The current version does not maintain a permanent document history on the server.

### Español

El módulo Reportes de AQUABOT MAX ECOSYSTEM proporciona una interfaz para generar, bajo demanda, resúmenes diagnósticos ambientales utilizando información de monitoreo lagunar disponible.

El módulo combina resultados de los servicios analíticos del sistema para presentar condiciones ambientales actuales, evaluaciones de consistencia estadística y análisis espectral de una variable principal seleccionada cuando existen observaciones suficientes.

La interfaz admite dos categorías de fuentes de monitoreo:

- Sensores fisicoquímicos locales.
- Observaciones ambientales satelitales.

Las capturas de referencia demuestran la generación y visualización de informes para diferentes variables locales y satelitales.

Los controles de exportación PDF y CSV están disponibles en la interfaz del informe generado. El contenido de estos archivos y su descarga correcta requieren verificación independiente.

La versión actual no conserva un historial documental permanente en el servidor.

---

## 2. Current Functional Scope | Alcance funcional actual

### English

The reference interface demonstrates the following capabilities:

- Lagoon selection.
- Monitoring source selection.
- Station selection or consolidated station view.
- Time-range selection.
- Principal variable selection.
- On-demand report generation.
- Current environmental condition summaries.
- Consolidated monitoring variable tables.
- Statistical consistency results.
- Observation and atypical-value counts.
- Spectral analysis results when supported by available data.
- Explicit insufficient-data messages.
- PDF and CSV export controls.
- Scientific interpretation limitations.

The report generated during a session is displayed without relying on a permanent server-side report archive.

### Español

La interfaz de referencia demuestra las siguientes capacidades:

- Selección de laguna.
- Selección de fuente de monitoreo.
- Selección de estación o vista consolidada de estaciones.
- Selección del intervalo temporal.
- Selección de variable principal.
- Generación de informes bajo demanda.
- Resúmenes de condiciones ambientales actuales.
- Tablas consolidadas de variables de monitoreo.
- Resultados de consistencia estadística.
- Conteos de observaciones y valores atípicos.
- Resultados de análisis espectral cuando los datos lo permiten.
- Mensajes explícitos de datos insuficientes.
- Controles de exportación PDF y CSV.
- Limitaciones de interpretación científica.

El informe generado durante una sesión se presenta sin depender de un archivo documental permanente en el servidor.

---

## 3. Report Generation Workflow | Procedimiento de generación

| Step | Description | Descripción |
|---|---|---|
| 1 | Select the lagoon. | Seleccionar la laguna. |
| 2 | Select the monitoring source. | Seleccionar la fuente de monitoreo. |
| 3 | Select the station or all available stations. | Seleccionar una estación o todas las disponibles. |
| 4 | Define the analysis period. | Definir el periodo de análisis. |
| 5 | Select the principal environmental variable. | Seleccionar la variable ambiental principal. |
| 6 | Activate the Generate Report control. | Activar el control Generar informe. |
| 7 | Review the generated diagnostic information. | Revisar la información diagnóstica generada. |
| 8 | Use the available PDF or CSV export controls if required. | Utilizar los controles disponibles de exportación PDF o CSV cuando corresponda. |

### English

The reference screenshots show the transition from a pending report state to a generated report state.

The displayed information changes according to the selected monitoring source, principal variable, and available observations.

### Español

Las capturas de referencia muestran la transición del estado de informe pendiente al estado de informe generado.

La información presentada cambia conforme a la fuente de monitoreo, variable principal y observaciones disponibles seleccionadas.

---

## 4. Reference Monitoring Configuration | Configuración de monitoreo de referencia

| Parameter | Local monitoring | Satellite monitoring |
|---|---|---|
| Lagoon / Laguna | Tres Palos Lagoon | Tres Palos Lagoon |
| Source / Fuente | Local sensors | Satellite observation |
| Station filter / Estaciones | All | All |
| Reference period / Periodo | Last 7 days | Last 60 days |
| Report generation / Generación | Completed in interface | Completed in interface |

### English

The screenshots cover multiple selected variables within these monitoring configurations.

The displayed information represents the results returned for these consultations, not permanent baseline values for the lagoon.

### Español

Las capturas comprenden distintas variables seleccionadas dentro de estas configuraciones de monitoreo.

La información mostrada representa los resultados entregados para estas consultas y no valores permanentes de referencia de la laguna.

---

## 5. Report Information Architecture | Estructura informativa del reporte

### English

The generated report interface contains several information sections.

**General summary**

- Monitoring source.
- Current environmental condition.
- Number of evaluable variables.
- Principal selected variable.

**Current conditions**

- Environmental interpretation returned by the analytical service.
- Most recent observation timestamp.

**Included variables**

- Variable identifier.
- Current displayed value.
- Monitoring classification.
- Statistical consistency result.
- Number of observations.
- Number of atypical observations.

**Spectral analysis**

- Principal variable.
- Analytical method.
- Number of usable observations.
- Dominant period when available.
- Sampling classification.
- Insufficient-data status where applicable.

**Scientific scope**

- Measurement validation limitations.
- Interpretation requirements for remote sensing.
- Limitations concerning periodicity and environmental causality.

### Español

La interfaz del informe generado contiene distintas secciones informativas.

**Resumen general**

- Fuente de monitoreo.
- Condición ambiental actual.
- Número de variables evaluables.
- Variable principal seleccionada.

**Condiciones actuales**

- Interpretación ambiental entregada por el servicio analítico.
- Fecha y hora de la observación más reciente.

**Variables incluidas**

- Identificador de variable.
- Valor actual mostrado.
- Clasificación de monitoreo.
- Resultado de consistencia estadística.
- Número de observaciones.
- Número de observaciones atípicas.

**Análisis espectral**

- Variable principal.
- Método analítico.
- Número de observaciones utilizables.
- Periodo dominante cuando está disponible.
- Clasificación del muestreo.
- Estado de datos insuficientes cuando corresponde.

**Alcance científico**

- Limitaciones de validación de las mediciones.
- Requisitos de interpretación de percepción remota.
- Limitaciones relacionadas con periodicidad y causalidad ambiental.

---

## 6. Local Physicochemical Monitoring | Monitoreo fisicoquímico local

### English

The local-sensor report includes a consolidated table of available physicochemical measurements.

In the reference screenshots, six variables are reported as evaluable with sufficient observations for consistency scoring.

Two additional listed variables do not have usable measurements in the corresponding consultation.

### Español

El informe de sensores locales incorpora una tabla consolidada de mediciones fisicoquímicas disponibles.

En las capturas de referencia, seis variables aparecen como evaluables con observaciones suficientes para obtener puntuaciones de consistencia.

Otras dos variables incluidas no tienen mediciones utilizables en la consulta correspondiente.

### Reference values | Valores de referencia

| Variable | Displayed value | Monitoring status | Estado |
|---|---|---|---|
| pH | 7.94 | No rule activated | Sin regla activada |
| Temperature / Temperatura | 30.02 °C | No rule activated | Sin regla activada |
| Total dissolved solids / Sólidos disueltos totales | 1997 ppm | No rule activated | Sin regla activada |
| Electrical conductivity / Conductividad eléctrica | 3933 µS/cm | No rule activated | Sin regla activada |
| Salinity / Salinidad | 2 ppt | No rule activated | Sin regla activada |
| Dissolved oxygen / Oxígeno disuelto | 2.96 mg/L | Under monitoring | Seguimiento |
| Millivolts / Milivoltios | No available measurement | No data | Sin datos |
| Carbon dioxide / Dióxido de carbono | No available measurement | No data | Sin datos |

### English

The reference screenshots show 334 or 336 observations for measured local variables, depending on the particular report consultation.

The exact observation count should be recorded together with the corresponding report configuration rather than treated as a fixed value.

Missing values are not equivalent to zero measurements.

### Español

Las capturas de referencia muestran 334 o 336 observaciones para las variables locales medidas, dependiendo de la consulta particular del informe.

El número exacto de observaciones debe registrarse junto con la configuración correspondiente del reporte y no considerarse un valor fijo.

La ausencia de valores no equivale a mediciones iguales a cero.

---

## 7. Current Environmental Condition | Condición ambiental actual

### English

The local-sensor reports identify oxygenation as the principal current monitoring concern.

The generated interpretation indicates that dissolved oxygen requires additional examination because it may affect ecological stability.

The reference screenshots identify the most recent observation as November 19, 2026, at 23:00 in the displayed interface.

This interpretation is produced using the available monitoring information and backend classification rules.

It does not independently establish the cause of an environmental condition or provide a comprehensive ecological diagnosis.

### Español

Los informes de sensores locales identifican la oxigenación como la principal condición actual de atención.

La interpretación generada indica que el oxígeno disuelto requiere revisión adicional porque puede afectar la estabilidad ecológica.

Las capturas de referencia identifican como observación más reciente el 19 de noviembre de 2026, a las 23:00, según la interfaz mostrada.

Esta interpretación se produce utilizando la información de monitoreo disponible y las reglas de clasificación del backend.

No establece de manera independiente la causa de una condición ambiental ni proporciona un diagnóstico ecológico integral.

---

## 8. Statistical Consistency Assessment | Evaluación de consistencia estadística

### English

The generated reports incorporate results from the statistical consistency service.

The interface provides:

- Consistency classifications.
- Numerical consistency scores.
- Observation counts.
- Atypical observation counts.

In the local monitoring screenshots, several variables receive high consistency classifications.

For pH, temperature, total dissolved solids, electrical conductivity, and dissolved oxygen, the displayed consistency score is 100.00.

Salinity is also classified as having high consistency, with a score of approximately 98.9 and 12 atypical observations in the reference consultations.

The reported score can change with the selected consultation and available observations.

### Español

Los informes generados incorporan resultados del servicio de consistencia estadística.

La interfaz proporciona:

- Clasificaciones de consistencia.
- Puntuaciones numéricas de consistencia.
- Conteos de observaciones.
- Conteos de observaciones atípicas.

En las capturas de monitoreo local, varias variables reciben clasificaciones de consistencia alta.

Para pH, temperatura, sólidos disueltos totales, conductividad eléctrica y oxígeno disuelto, la puntuación de consistencia mostrada es 100.00.

La salinidad también aparece clasificada con consistencia alta, con una puntuación aproximada de 98.9 y 12 observaciones atípicas en las consultas de referencia.

La puntuación reportada puede cambiar según la consulta seleccionada y las observaciones disponibles.

### Scientific limitation | Limitación científica

**English:** Statistical consistency does not establish measurement accuracy, precision, sensor calibration, metrological traceability, or laboratory agreement.

**Español:** La consistencia estadística no establece exactitud, precisión, calibración de sensores, trazabilidad metrológica ni concordancia con laboratorio.

---

## 9. Spectral Analysis | Análisis espectral

### English

The Reports module includes a spectral-analysis section for the selected principal variable.

Depending on the sampling pattern and availability of observations, the interface reports an applicable analytical method and an estimated dominant period.

The reference screenshots demonstrate the following methods:

- Fast Fourier Transform (FFT).
- Lomb–Scargle periodogram.

The availability of a dominant period depends on the information returned by the analytical service.

Not every selected variable produces a valid dominant periodicity.

### Español

El módulo Reportes incorpora una sección de análisis espectral para la variable principal seleccionada.

Dependiendo del patrón de muestreo y la disponibilidad de observaciones, la interfaz reporta un método analítico aplicable y un periodo dominante estimado.

Las capturas de referencia demuestran los siguientes métodos:

- Transformada rápida de Fourier (FFT).
- Periodograma de Lomb–Scargle.

La disponibilidad de un periodo dominante depende de la información entregada por el servicio analítico.

No todas las variables seleccionadas producen una periodicidad dominante válida.

---

## 10. Fast Fourier Transform | Transformada rápida de Fourier

### English

The Fast Fourier Transform is a computational method used to examine frequency components in a sampled time series.

The reference reports display FFT results for multiple local variables and for regional sea surface temperature.

The interface identifies the sampling type as regular in the corresponding reports.

The following results are documented from the screenshots.

### Español

La transformada rápida de Fourier es un método computacional utilizado para examinar componentes de frecuencia en una serie temporal muestreada.

Los informes de referencia muestran resultados FFT para varias variables locales y para temperatura superficial marina regional.

La interfaz identifica el tipo de muestreo como regular en los reportes correspondientes.

Los siguientes resultados están documentados a partir de las capturas.

| Principal variable / Variable principal | Method / Método | Observations / Observaciones | Dominant period / Periodo dominante |
|---|---|---:|---|
| pH | FFT | 168 | 24.00 hours / horas |
| Temperature / Temperatura | FFT | 168 | 24.00 hours / horas |
| Total dissolved solids / Sólidos disueltos totales | FFT | 168 | 24.00 hours / horas |
| Electrical conductivity / Conductividad eléctrica | FFT | 168 | 24.00 hours / horas |
| Salinity / Salinidad | FFT | 168 | 7.00 days / días |
| Dissolved oxygen / Oxígeno disuelto | FFT | 167 | 23.86 hours / horas |
| Regional sea surface temperature / Temperatura superficial marina regional | FFT | 56 | 56.00 days / días |

### English

These results describe dominant periods returned by the service for the reference consultations.

They do not independently prove that the observed periodicities are caused by specific environmental mechanisms.

A reported period comparable to the total observation-window length, such as 56 days from a 56-day window, requires particular caution because of limited evidence for repeated cycles.

### Español

Estos resultados describen los periodos dominantes entregados por el servicio para las consultas de referencia.

No demuestran de manera independiente que las periodicidades observadas sean causadas por mecanismos ambientales específicos.

Un periodo reportado comparable con la duración total de la ventana de observación, como 56 días obtenidos en una ventana de 56 días, requiere especial precaución debido a la evidencia limitada de ciclos repetidos.

---

## 11. Lomb–Scargle Periodogram | Periodograma de Lomb–Scargle

### English

The reference satellite report for precipitation identifies Lomb–Scargle as the applied spectral-analysis method.

The interface reports irregular sampling for this consultation.

The displayed results are:

- Principal variable: Precipitation.
- Monitoring source: Satellite observation.
- Reference period: Last 60 days.
- Spectral method: Lomb–Scargle periodogram.
- Observations: 56.
- Reported dominant period: 29.88 days.
- Sampling classification: Irregular.

The result represents a periodicity estimated by the analytical service and does not establish the physical cause of precipitation variability.

### Español

El reporte satelital de referencia para precipitación identifica Lomb–Scargle como el método de análisis espectral aplicado.

La interfaz reporta muestreo irregular para esta consulta.

Los resultados mostrados son:

- Variable principal: Precipitación.
- Fuente de monitoreo: Observación satelital.
- Periodo de referencia: Últimos 60 días.
- Método espectral: Periodograma de Lomb–Scargle.
- Observaciones: 56.
- Periodo dominante reportado: 29.88 días.
- Clasificación del muestreo: Irregular.

El resultado representa una periodicidad estimada por el servicio analítico y no establece la causa física de la variabilidad de precipitación.

---

## 12. Insufficient Spectral Data | Datos insuficientes para análisis espectral

### English

The interface explicitly reports when no valid dominant periodicity is available.

In the reference screenshots, this situation is shown for selections including:

- Oxidation-reduction potential.
- Carbon dioxide.
- Normalized Difference Water Index.
- Landsat-derived surface temperature selection.
- NISAR radar backscatter.

The reported analytical service status is:

`insufficient_data`

This behavior is important because it distinguishes unavailable analytical results from valid estimated periodicities.

### Español

La interfaz informa expresamente cuando no existe una periodicidad dominante válida.

En las capturas de referencia, esta situación se presenta para selecciones que incluyen:

- Potencial de oxidación-reducción.
- Dióxido de carbono.
- Índice normalizado de diferencia de agua.
- Selección de temperatura superficial derivada de Landsat.
- Retrodispersión radar NISAR.

El estado reportado por el servicio analítico es:

`insufficient_data`

Este comportamiento es importante porque distingue los resultados analíticos no disponibles de las periodicidades estimadas válidas.

---

## 13. Satellite Environmental Reports | Informes ambientales satelitales

### English

The reference screenshots demonstrate report generation using the Satellite Observation monitoring source.

The generated reports include selected satellite-derived environmental variables, current displayed values, statistical consistency information, and spectral-analysis results where available.

The displayed satellite variables include:

- Normalized Difference Water Index (NDWI).
- Landsat-classified water surface temperature.
- Precipitation.
- Regional sea surface temperature from OISST.
- NISAR radar backscatter HHHH.

These products represent remote-sensing observations and contextual environmental information.

They should not automatically be interpreted as direct in situ physicochemical measurements.

### Español

Las capturas de referencia demuestran la generación de informes utilizando la fuente Observación satelital.

Los informes generados incluyen variables ambientales seleccionadas derivadas de satélites, valores actuales mostrados, información de consistencia estadística y resultados de análisis espectral cuando están disponibles.

Las variables satelitales mostradas incluyen:

- Índice normalizado de diferencia de agua (NDWI).
- Temperatura de superficie del agua clasificada mediante Landsat.
- Precipitación.
- Temperatura superficial marina regional de OISST.
- Retrodispersión radar NISAR HHHH.

Estos productos representan observaciones de percepción remota e información ambiental contextual.

No deben interpretarse automáticamente como mediciones fisicoquímicas directas in situ.

---

## 14. Satellite Reference Results | Resultados satelitales de referencia

### English

The reference report for satellite observations presents the following values.

### Español

El informe de referencia de observaciones satelitales presenta los siguientes valores.

| Variable | Displayed value | Observations | Consistency |
|---|---|---:|---|
| NDWI | 0.267 index | 7 | Insufficient sample / Muestra insuficiente |
| Landsat water surface temperature / Temperatura superficial del agua Landsat | 32.5 °C | 1 | Insufficient sample / Muestra insuficiente |
| Precipitation / Precipitación | 0 mm/day | 56 | High consistency / Consistencia alta |
| Regional OISST sea surface temperature / Temperatura superficial marina OISST | 30 °C | 56 | High consistency / Consistencia alta |
| NISAR HHHH radar backscatter / Retrodispersión radar NISAR HHHH | -19.15 dB | 0 | No data for consistency assessment / Sin datos para evaluación de consistencia |

### English

The precipitation consistency score is displayed as 98.93, with two atypical observations.

The regional sea surface temperature consistency score is displayed as 99.46, with one atypical observation.

A variable may have a displayed current value while still having insufficient historical observations for statistical evaluation.

The radar backscatter example illustrates this distinction: a value is displayed, but the report provides no usable observations for the statistical consistency assessment.

### Español

La puntuación de consistencia de precipitación aparece como 98.93, con dos observaciones atípicas.

La puntuación de consistencia de temperatura superficial marina regional aparece como 99.46, con una observación atípica.

Una variable puede tener un valor actual mostrado y, aun así, contar con observaciones históricas insuficientes para una evaluación estadística.

El ejemplo de retrodispersión radar ilustra esta diferencia: aparece un valor, pero el informe no proporciona observaciones utilizables para evaluar su consistencia estadística.

---

## 15. Satellite Environmental Status | Estado ambiental satelital

### English

The satellite reports display the current condition:

**No satellite monitoring rules activated.**

The explanatory text states that the latest available observations did not activate the explicit satellite monitoring rules currently implemented.

The interface also clarifies that this result does not mean the ecosystem is free from risk.

The reference screenshots identify the latest satellite observation as November 16, 2026, at 18:00.

### Español

Los informes satelitales presentan la condición actual:

**Sin reglas satelitales de seguimiento activadas.**

El texto explicativo señala que las últimas observaciones disponibles no activaron las reglas satelitales explícitas implementadas actualmente.

La interfaz también aclara que este resultado no significa que el ecosistema esté libre de riesgos.

Las capturas de referencia identifican la observación satelital más reciente como el 16 de noviembre de 2026, a las 18:00.

---

## 16. Principal Variable Selection | Selección de variable principal

### English

The selected principal variable determines which environmental series is submitted for the spectral-analysis section.

The consolidated report can still include other monitoring variables.

The reference screenshots demonstrate this behavior across multiple local and satellite selections.

Changing the principal variable may alter:

- The analytical method.
- The usable observation count.
- The reported dominant period.
- The sampling classification.
- The insufficient-data result.

### Español

La variable principal seleccionada determina cuál serie ambiental se utiliza en la sección de análisis espectral.

El informe consolidado puede seguir incluyendo otras variables de monitoreo.

Las capturas de referencia demuestran este comportamiento en distintas selecciones locales y satelitales.

Cambiar la variable principal puede modificar:

- El método analítico.
- El número de observaciones utilizables.
- El periodo dominante reportado.
- La clasificación del muestreo.
- El resultado de datos insuficientes.

---

## 17. PDF and CSV Export | Exportación PDF y CSV

### English

After a report is generated, the interface presents two export controls:

- Download PDF.
- Download CSV.

These controls indicate that the report is intended to be exportable in document and tabular formats.

The reference screenshots confirm that both controls are displayed.

However, the successful generation, file structure, contents, and integrity of the exported files have not yet been independently verified in this documentation.

### Español

Después de generar un informe, la interfaz presenta dos controles de exportación:

- Descargar PDF.
- Descargar CSV.

Estos controles indican que el reporte está diseñado para exportarse en formatos documental y tabular.

Las capturas de referencia confirman que ambos controles aparecen en pantalla.

Sin embargo, la generación correcta, estructura, contenido e integridad de los archivos exportados todavía no se han verificado de manera independiente en esta documentación.

---

## 18. Report Storage and History | Almacenamiento e historial de informes

### English

The interface explicitly states that the current implementation does not maintain a server-side document history.

The download is associated with the report generated during the current session.

This means that permanent archival, report version tracking, and historical document retrieval are not demonstrated as current capabilities.

Future implementation of a persistent archive would require suitable storage, identification, access control, and traceability mechanisms.

### Español

La interfaz establece expresamente que la implementación actual no mantiene un historial documental en el servidor.

La descarga corresponde al informe generado durante la sesión actual.

Esto significa que el archivo permanente, el seguimiento de versiones de informes y la recuperación de documentos históricos no se demuestran como capacidades actuales.

Una futura implementación de un archivo persistente requerirá mecanismos adecuados de almacenamiento, identificación, control de acceso y trazabilidad.

---

## 19. Statistical and Spectral Interpretation | Interpretación estadística y espectral

### English

Statistical and spectral summaries can help characterize monitoring data, but their interpretation requires attention to several factors:

1. Observation availability.
2. Sampling frequency.
3. Sampling regularity.
4. Time-window duration.
5. Missing measurements.
6. Atypical observations.
7. Measurement uncertainty.
8. Instrumental quality assurance.
9. Characteristics of the observed environmental process.
10. Independent evaluation of potential environmental mechanisms.

A periodicity detected in a selected series does not independently establish an environmental causal mechanism.

A high statistical consistency score is not proof of metrological accuracy.

### Español

Los resúmenes estadísticos y espectrales pueden ayudar a caracterizar los datos de monitoreo, pero su interpretación requiere considerar diversos factores:

1. Disponibilidad de observaciones.
2. Frecuencia de muestreo.
3. Regularidad del muestreo.
4. Duración de la ventana temporal.
5. Mediciones faltantes.
6. Observaciones atípicas.
7. Incertidumbre de medición.
8. Aseguramiento de calidad instrumental.
9. Características del proceso ambiental observado.
10. Evaluación independiente de posibles mecanismos ambientales.

Una periodicidad detectada en una serie seleccionada no establece de manera independiente un mecanismo causal ambiental.

Una puntuación alta de consistencia estadística no demuestra exactitud metrológica.

---

## 20. Scientific and Environmental Limitations | Limitaciones científicas y ambientales

### English

The current report interface presents the following scientific considerations:

- Statistical consistency is not equivalent to metrological validation.
- Consistency scores do not certify precision or accuracy.
- Sensor calibration is not established by the report.
- Laboratory agreement is not demonstrated.
- Satellite products must be interpreted as remote-sensing observations rather than direct physicochemical measurements.
- Spectral periodicities require comparison with additional data and plausible environmental mechanisms.
- Reported periodicities do not independently establish causality.
- An insufficient-data result must not be replaced with an assumed periodicity.
- A missing satellite monitoring alert does not prove the absence of ecological risk.
- The current report interface does not demonstrate permanent document storage.

### Español

La interfaz actual de informes presenta las siguientes consideraciones científicas:

- La consistencia estadística no equivale a validación metrológica.
- Las puntuaciones de consistencia no certifican precisión ni exactitud.
- La calibración de sensores no queda establecida por el informe.
- No se demuestra concordancia con laboratorio.
- Los productos satelitales deben interpretarse como observaciones de percepción remota y no como mediciones fisicoquímicas directas.
- Las periodicidades espectrales requieren comparación con datos adicionales y mecanismos ambientales plausibles.
- Las periodicidades reportadas no establecen de manera independiente causalidad.
- Un resultado de datos insuficientes no debe sustituirse por una periodicidad supuesta.
- La ausencia de alertas satelitales no demuestra ausencia de riesgo ecológico.
- La interfaz actual no demuestra almacenamiento documental permanente.

---

## 21. Scientific and Environmental Relevance | Relevancia científica y ambiental

### English

The Reports module represents an important analytical integration capability within AQUABOT MAX ECOSYSTEM.

It consolidates available local and satellite observations into structured diagnostic summaries.

The combination of current environmental interpretations, statistical consistency information, and spectral processing can support the examination of environmental variability.

The module also provides transparent insufficient-data messages and explicit scientific interpretation limitations.

These capabilities can support environmental monitoring and informed decision-making when results are interpreted according to their data quality, methodological scope, and evidentiary limitations.

### Español

El módulo Reportes representa una capacidad importante de integración analítica dentro de AQUABOT MAX ECOSYSTEM.

Consolida observaciones locales y satelitales disponibles en resúmenes diagnósticos estructurados.

La combinación de interpretaciones ambientales actuales, información de consistencia estadística y procesamiento espectral puede apoyar el estudio de la variabilidad ambiental.

El módulo también proporciona mensajes transparentes de datos insuficientes y limitaciones explícitas de interpretación científica.

Estas capacidades pueden apoyar el monitoreo ambiental y la toma informada de decisiones cuando los resultados se interpretan conforme a su calidad de datos, alcance metodológico y limitaciones probatorias.

---

## 22. User Interface | Interfaz de usuario

| Feature | Description | Descripción |
|---|---|---|
| Lagoon selector | Selects the lagoon for the report. | Selecciona la laguna del informe. |
| Source selector | Selects local sensors or satellite observations. | Selecciona sensores locales u observaciones satelitales. |
| Station filter | Selects the available monitoring station scope. | Selecciona el alcance de las estaciones disponibles. |
| Time-range selector | Defines the report consultation period. | Define el periodo de consulta del informe. |
| Principal variable selector | Selects the variable used for spectral analysis. | Selecciona la variable utilizada para el análisis espectral. |
| Generate Report | Requests report generation. | Solicita la generación del informe. |
| Report status | Displays pending or generated status. | Muestra estado pendiente o generado. |
| Report summary | Presents source, current condition, evaluable variables, and principal variable. | Presenta fuente, condición actual, variables evaluables y variable principal. |
| Current conditions | Displays the current environmental interpretation. | Muestra la interpretación ambiental actual. |
| Included variables | Displays available variables, values, classifications, consistency, and counts. | Presenta variables, valores, clasificaciones, consistencia y conteos. |
| Spectral analysis | Displays the analytical method and available periodicity results. | Presenta el método analítico y los resultados de periodicidad disponibles. |
| PDF export control | Presents the option to download a PDF. | Presenta la opción de descargar un PDF. |
| CSV export control | Presents the option to download a CSV. | Presenta la opción de descargar un CSV. |
| Scientific scope | Displays methodological and scientific limitations. | Presenta las limitaciones metodológicas y científicas. |
| Language selector | Supports English and Spanish. | Admite inglés y español. |

---

## 23. Functional Development | Desarrollo funcional

### English

The Reports module is available in the AQUABOT MAX ECOSYSTEM web application.

The reference screenshots demonstrate successful on-demand generation of diagnostic reports for multiple physicochemical and satellite environmental variables.

The reports consolidate current conditions, available observations, statistical consistency classifications, observation counts, atypical-value counts, and spectral-analysis results.

The reference interfaces show both Fast Fourier Transform and Lomb–Scargle periodogram methods, as well as explicit insufficient-data messages when no valid dominant periodicity is available.

PDF and CSV export controls are present, but exported file contents have not yet been verified in this documentation.

The current version does not maintain a permanent report-document history on the server.

### Español

El módulo Reportes está disponible en la aplicación web AQUABOT MAX ECOSYSTEM.

Las capturas de referencia demuestran la generación bajo demanda de informes diagnósticos para múltiples variables fisicoquímicas y ambientales satelitales.

Los informes consolidan condiciones actuales, observaciones disponibles, clasificaciones de consistencia estadística, conteos de observaciones, conteos de valores atípicos y resultados de análisis espectral.

Las interfaces de referencia muestran los métodos de transformada rápida de Fourier y periodograma de Lomb–Scargle, además de mensajes explícitos de datos insuficientes cuando no existe una periodicidad dominante válida.

Los controles de exportación PDF y CSV están presentes, pero el contenido de los archivos exportados todavía no se ha verificado en esta documentación.

La versión actual no mantiene un historial documental permanente de informes en el servidor.

---

**AQUABOT MAX ECOSYSTEM**  
**ODEVE — Open Development Ecosystem**
