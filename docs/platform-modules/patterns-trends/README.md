
# AQUABOT MAX ECOSYSTEM

## Environmental Patterns and Trends | Patrones y tendencias ambientales

**Project | Proyecto:** AQUABOT MAX ECOSYSTEM  
**Organization | Organización:** ODEVE — Open Development Ecosystem  
**Platform | Plataforma:** https://monitoreo.trespalos.org  
**Module | Módulo:** Patterns and Trends | Patrones y tendencias  
**Languages | Idiomas:** English and Spanish | Inglés y español  
**Reference interface | Interfaz de referencia:** November 19, 2026 | 19 de noviembre de 2026

---

## 1. Overview | Descripción general

### English

The Patterns and Trends module of AQUABOT MAX ECOSYSTEM provides statistical and temporal analysis of available environmental monitoring observations.

The interface combines variable selection, monitoring filters, descriptive statistics, temporal changes, time-series visualization, and Pearson correlation analysis.

Its purpose is to support the examination of environmental variability in lagoon ecosystems through available observational data.

The module distinguishes its currently implemented analytical functions from advanced methods that remain pending backend development.

### Español

El módulo Patrones y tendencias de AQUABOT MAX ECOSYSTEM proporciona análisis estadístico y temporal de las observaciones ambientales disponibles.

La interfaz integra selección de variables, filtros de monitoreo, estadísticas descriptivas, cambios temporales, visualización de series y análisis de correlación de Pearson.

Su propósito es apoyar el estudio de la variabilidad ambiental de los ecosistemas lagunares mediante datos observacionales disponibles.

El módulo diferencia sus funciones analíticas actualmente implementadas de los métodos avanzados que continúan pendientes de desarrollo en el backend.

---

## 2. Current Analytical Scope | Alcance analítico actual

### English

According to the application interface, the currently available analytical scope includes:

- Temporal change between the first and last readings of the selected period.
- Direction of the observed change.
- Absolute and percentage change.
- Descriptive statistics of available observations.
- Temporal visualization of the selected variable.
- Pearson linear correlation using observations aligned by day.

The interface also identifies advanced methods that remain pending implementation.

### Español

De acuerdo con la interfaz de la aplicación, el alcance analítico disponible actualmente incluye:

- Cambio temporal entre la primera y la última lectura del periodo seleccionado.
- Dirección del cambio observado.
- Cambio absoluto y porcentual.
- Estadísticas descriptivas de las observaciones disponibles.
- Visualización temporal de la variable seleccionada.
- Correlación lineal de Pearson mediante observaciones alineadas por día.

La interfaz también identifica métodos avanzados que todavía están pendientes de implementación.

---

## 3. Monitoring Selection | Selección del monitoreo

| Component | Description | Descripción |
|---|---|---|
| Station selector | Selection of a monitoring station or consolidated station view. | Selección de una estación de monitoreo o una vista consolidada. |
| Lagoon selector | Selection of the lagoon being examined. | Selección de la laguna que se desea examinar. |
| Time-range selector | Selection of the analysis period. | Selección del periodo de análisis. |
| Data source selector | Selection of the environmental observation source. | Selección de la fuente de observación ambiental. |
| Main variable selector | Selection of the variable used for temporal analysis. | Selección de la variable utilizada para el análisis temporal. |
| Second variable selector | Selection of a second variable for correlation analysis. | Selección de una segunda variable para el análisis de correlación. |
| Refresh control | Manual request to update the displayed information. | Control manual para solicitar la actualización de la información. |
| Language selector | Interface available in English and Spanish. | Interfaz disponible en inglés y español. |

### Reference selection | Selección de referencia

**Lagoon | Laguna:** Tres Palos Lagoon | Laguna de Tres Palos  
**Period | Periodo:** Last 28 days | Últimos 28 días  
**Main source | Fuente principal:** Local sensors | Sensores locales  
**Main variable | Variable principal:** Temperature | Temperatura  
**Correlation variable | Variable de correlación:** Dissolved oxygen (DO) | Oxígeno disuelto (OD)

---

## 4. Temporal Change Analysis | Análisis del cambio temporal

### English

The current interface describes the temporal trend as the change between the first and last readings of the selected period.

For a variable with initial observation x1 and final observation xn, the absolute change can be expressed as:

Delta x = xn - x1

When the initial value is different from zero, the percentage change can be expressed as:

Percentage change = (Delta x / x1) × 100

These expressions describe the general calculation presented by the interface. They do not establish the complete backend implementation or its handling of every edge case.

### Español

La interfaz actual describe la tendencia temporal como el cambio entre la primera y la última lectura del periodo seleccionado.

Para una variable con observación inicial x1 y observación final xn, el cambio absoluto puede expresarse como:

Delta x = xn - x1

Cuando el valor inicial es diferente de cero, el cambio porcentual puede expresarse como:

Cambio porcentual = (Delta x / x1) × 100

Estas expresiones describen el cálculo general presentado por la interfaz. No establecen la implementación completa del backend ni su tratamiento de todos los casos particulares.

---

## 5. Reference Temporal Results | Resultados temporales de referencia

### English

The screenshot documented on November 19, 2026, presents temperature observations for Tres Palos Lagoon over the selected 28-day period.

The application reports an ascending temporal change.

### Español

La captura documentada el 19 de noviembre de 2026 presenta observaciones de temperatura de la laguna de Tres Palos durante el periodo seleccionado de 28 días.

La aplicación reporta un cambio temporal ascendente.

| Indicator | Displayed value | Valor mostrado |
|---|---|---|
| Direction / Dirección | Ascending | Ascendente |
| Absolute change / Cambio absoluto | +0.2 °C | +0.2 °C |
| Percentage change / Cambio porcentual | +0.77% | +0.77% |
| Latest reading / Lectura actual | 30.3 °C | 30.3 °C |
| First observation / Primera observación | October 22, 2026, 22:00 | 22 de octubre de 2026, 22:00 |
| Last observation / Última observación | November 19, 2026, 21:00 | 19 de noviembre de 2026, 21:00 |

### English

The ascending classification describes the difference between the beginning and end of the selected interval.

It does not imply that temperature increased continuously throughout the entire period.

### Español

La clasificación ascendente describe la diferencia entre el inicio y el final del intervalo seleccionado.

No significa que la temperatura haya aumentado continuamente durante todo el periodo.

---

## 6. Descriptive Statistics | Estadísticas descriptivas

The reference screenshot presents the following temperature statistics.

La captura de referencia presenta las siguientes estadísticas de temperatura.

| Statistic | Displayed value | Valor mostrado |
|---|---:|---:|
| Latest reading / Lectura actual | 30.3 °C | 30.3 °C |
| Average / Promedio | 30.0 °C | 30.0 °C |
| Minimum / Mínimo | 28.6 °C | 28.6 °C |
| Maximum / Máximo | 32.2 °C | 32.2 °C |
| Median / Mediana | 30.0 °C | 30.0 °C |
| Standard deviation / Desviación estándar | 0.5 °C | 0.5 °C |
| Observed range / Amplitud observada | 3.6 °C | 3.6 °C |
| Measurements / Lecturas | 1,344 | 1,344 |
| Representative chart points / Puntos representativos en la gráfica | 913 | 913 |

### English

The statistics summarize the temperature observations available for the selected consultation.

The displayed number of representative chart points differs from the total number of readings.

The chart therefore must not be interpreted as a one-to-one display of every original measurement.

### Español

Las estadísticas resumen las observaciones de temperatura disponibles para la consulta seleccionada.

La cantidad de puntos representativos mostrados en la gráfica es diferente del número total de lecturas.

Por lo tanto, la gráfica no debe interpretarse como una representación individual de cada medición original.

---

## 7. Temperature Time Series | Serie temporal de temperatura

### English

The module presents an interactive temporal chart showing the evolution of the selected variable.

The interface describes the chart as a processed time series provided by the backend, with a representation of up to 960 points that preserves extreme observations.

The reference screenshot displays 1,344 received temperature readings and 913 representative chart points.

The visualization supports the examination of temporal variability, recurring changes visible in the series, and individual variations within the observation period.

However, visual repetition in a time series does not independently establish a statistically validated cycle or periodic process.

### Español

El módulo presenta una gráfica temporal interactiva que muestra la evolución de la variable seleccionada.

La interfaz describe la gráfica como una serie temporal procesada por el backend, con una representación de hasta 960 puntos que conserva observaciones extremas.

La captura de referencia muestra 1,344 lecturas de temperatura recibidas y 913 puntos representativos en la gráfica.

La visualización permite examinar la variabilidad temporal, cambios recurrentes visibles y variaciones individuales dentro del periodo de observación.

Sin embargo, la repetición visual en una serie temporal no establece de manera independiente un ciclo o proceso periódico validado estadísticamente.

---

## 8. Pearson Correlation Analysis | Análisis de correlación de Pearson

### English

The module includes a Pearson correlation analysis between the main variable and a second selected variable.

The interface states that the calculation uses observations aligned by day.

The Pearson coefficient describes linear association between paired numerical observations.

Its mathematical expression is:

r = sum[(xi - x_mean)(yi - y_mean)] /
    sqrt(sum[(xi - x_mean)^2] × sum[(yi - y_mean)^2])

Where:

- r is the Pearson correlation coefficient.
- xi and yi are paired observations.
- x_mean and y_mean represent their respective sample means.

The coefficient ranges from -1 to +1 when defined.

A positive coefficient indicates positive linear association, while a negative coefficient indicates negative linear association.

A coefficient near zero indicates weak linear association, but does not exclude nonlinear relationships.

### Español

El módulo incorpora un análisis de correlación de Pearson entre la variable principal y una segunda variable seleccionada.

La interfaz señala que el cálculo utiliza observaciones alineadas por día.

El coeficiente de Pearson describe la asociación lineal entre observaciones numéricas emparejadas.

Su expresión matemática es:

r = sum[(xi - x_media)(yi - y_media)] /
    sqrt(sum[(xi - x_media)^2] × sum[(yi - y_media)^2])

Donde:

- r es el coeficiente de correlación de Pearson.
- xi y yi son observaciones emparejadas.
- x_media y y_media representan sus respectivas medias muestrales.

El coeficiente varía entre -1 y +1 cuando está definido.

Un coeficiente positivo indica asociación lineal positiva, mientras que uno negativo indica asociación lineal negativa.

Un coeficiente cercano a cero indica asociación lineal débil, pero no descarta relaciones no lineales.

---

## 9. Reference Correlation Results | Resultados de correlación de referencia

### English

The reference screenshot presents a correlation between temperature and dissolved oxygen (DO).

The application reports the following result.

### Español

La captura de referencia presenta una correlación entre temperatura y oxígeno disuelto (OD).

La aplicación reporta el siguiente resultado.

| Indicator | Displayed result | Resultado mostrado |
|---|---|---|
| Main variable / Variable principal | Temperature | Temperatura |
| Second variable / Segunda variable | Dissolved oxygen (DO) | Oxígeno disuelto (OD) |
| Pearson coefficient / Coeficiente de Pearson | 0.213 | 0.213 |
| Aligned days / Días alineados | 29 | 29 |
| Classification / Clasificación | Very weak positive | Muy débil positiva |

### English

The result indicates a very weak positive linear association in the daily aligned dataset used by the application.

It does not establish that changes in water temperature cause changes in dissolved oxygen.

The reported coefficient is a descriptive statistical result for the selected dataset and analysis period.

### Español

El resultado indica una asociación lineal positiva muy débil en el conjunto de datos diarios alineados utilizado por la aplicación.

No establece que los cambios de temperatura del agua causen cambios en el oxígeno disuelto.

El coeficiente reportado es un resultado estadístico descriptivo del conjunto de datos y periodo de análisis seleccionados.

---

## 10. Correlation Scatter Plot | Diagrama de dispersión de correlación

### English

The module includes a scatter plot representing daily aligned observations of the two selected variables.

Each plotted point represents a paired observation used in the displayed correlation analysis.

The chart supports visual examination of the direction, dispersion, and possible structure of the association.

A scatter plot alone does not establish environmental causality or statistical significance.

### Español

El módulo incorpora un diagrama de dispersión que representa observaciones diarias alineadas de las dos variables seleccionadas.

Cada punto representa una observación emparejada utilizada en el análisis de correlación mostrado.

La gráfica permite examinar visualmente la dirección, dispersión y posible estructura de la asociación.

Un diagrama de dispersión, por sí solo, no establece causalidad ambiental ni significancia estadística.

---

## 11. Current Analytical Capabilities | Capacidades analíticas actuales

| Capability | Status | Estado |
|---|---|---|
| Descriptive statistics | Available in the interface | Disponible en la interfaz |
| Absolute temporal change | Available in the interface | Disponible en la interfaz |
| Percentage temporal change | Available in the interface | Disponible en la interfaz |
| Trend direction | Available in the interface | Disponible en la interfaz |
| Time-series visualization | Available in the interface | Disponible en la interfaz |
| Representative time-series processing | Reported by the interface | Reportado por la interfaz |
| Pearson correlation | Available in the interface | Disponible en la interfaz |
| Daily aligned observations | Reported by the interface | Reportado por la interfaz |
| Correlation scatter plot | Available in the interface | Disponible en la interfaz |

### English

These capabilities are visible in the reference screenshot.

The exact details of backend processing, data filtering, numerical precision, and statistical validation require examination of the corresponding implementation.

### Español

Estas capacidades aparecen en la captura de referencia.

Los detalles exactos del procesamiento en el backend, filtrado de datos, precisión numérica y validación estadística requieren revisar la implementación correspondiente.

---

## 12. Advanced Analytical Capabilities Under Development | Capacidades analíticas avanzadas en desarrollo

### English

The interface explicitly identifies the following capabilities as pending an analytical service in the backend:

- Cycle analysis.
- Seasonality analysis.
- Fourier analysis.
- Spectral analysis.
- Spectrograms.
- Time-lag analysis.

These methods are not presented as operational functions in the reference screenshot.

### Español

La interfaz identifica expresamente las siguientes capacidades como pendientes de un servicio analítico en el backend:

- Análisis de ciclos.
- Análisis de estacionalidad.
- Análisis de Fourier.
- Análisis espectral.
- Espectrogramas.
- Análisis de retardos temporales.

Estos métodos no se presentan como funciones operativas en la captura de referencia.

---

## 13. Future Fourier and Spectral Analysis | Futuro análisis de Fourier y espectral

### English

Future Fourier-based methods could support the examination of periodic components in validated environmental time series.

Their implementation would require appropriate handling of observation intervals, missing data, sampling frequency, and signal-processing assumptions.

Potential future applications include investigating recurrent temperature variations or other temporal structures in monitoring observations.

No Fourier spectrum, spectrogram, or validated periodicity result is currently documented as operational in this module.

### Español

Los futuros métodos basados en Fourier podrían apoyar el examen de componentes periódicas en series temporales ambientales validadas.

Su implementación requeriría tratar adecuadamente los intervalos de observación, datos faltantes, frecuencia de muestreo y supuestos del procesamiento de señales.

Entre sus posibles aplicaciones futuras se encuentra investigar variaciones recurrentes de temperatura u otras estructuras temporales de las observaciones de monitoreo.

Actualmente no se documenta como operativo ningún espectro de Fourier, espectrograma o resultado de periodicidad validada dentro de este módulo.

---

## 14. Statistical and Scientific Limitations | Limitaciones estadísticas y científicas

### English

The interpretation of the module's results must consider several limitations:

- The displayed trend is based on the first and last observations.
- An ascending trend does not imply continuous growth throughout the interval.
- Pearson correlation measures linear association, not causality.
- A weak correlation does not exclude nonlinear relationships.
- Daily alignment may affect the number and statistical properties of paired observations.
- Representative chart points may differ from the complete dataset.
- Missing observations, measurement quality, and sampling methods may affect interpretation.
- The interface displays an update-pending message in the reference screenshot.
- Advanced spectral and periodicity analysis is not yet documented as operational.

### Español

La interpretación de los resultados del módulo debe considerar varias limitaciones:

- La tendencia mostrada se basa en la primera y última observación.
- Una tendencia ascendente no implica crecimiento continuo durante el intervalo.
- La correlación de Pearson mide asociación lineal, no causalidad.
- Una correlación débil no descarta relaciones no lineales.
- La alineación diaria puede afectar la cantidad y propiedades estadísticas de las observaciones emparejadas.
- Los puntos representativos de la gráfica pueden diferir del conjunto completo de datos.
- Los datos faltantes, calidad de medición y métodos de muestreo pueden afectar la interpretación.
- La interfaz muestra un mensaje de actualización pendiente en la captura de referencia.
- El análisis espectral y de periodicidad avanzado todavía no se documenta como operativo.

---

## 15. Scientific and Environmental Relevance | Relevancia científica y ambiental

### English

The Patterns and Trends module supports the examination of physicochemical variability in lagoon monitoring through statistical summaries, time-series visualization, and correlations between environmental variables.

These tools can contribute to identifying changes that warrant scientific examination, comparing observation periods, and supporting environmental research.

Its outputs should be interpreted as observational statistical evidence rather than proof of specific ecological mechanisms.

### Español

El módulo Patrones y tendencias apoya el examen de la variabilidad fisicoquímica del monitoreo lagunar mediante resúmenes estadísticos, visualización de series temporales y correlaciones entre variables ambientales.

Estas herramientas pueden contribuir a identificar cambios que requieren examen científico, comparar periodos de observación y apoyar la investigación ambiental.

Sus resultados deben interpretarse como evidencia estadística observacional y no como prueba de mecanismos ecológicos específicos.

---

## 16. User Interface | Interfaz de usuario

| Feature | Description | Descripción |
|---|---|---|
| Monitoring filters | Selection of station, lagoon, and analysis period. | Selección de estación, laguna y periodo de análisis. |
| Data source selector | Selection of the source used for the main series and correlation analysis. | Selección de la fuente utilizada para la serie principal y el análisis de correlación. |
| Variable selector | Selection of the main physicochemical variable. | Selección de la variable fisicoquímica principal. |
| Temporal change panel | Displays change direction, absolute variation, and percentage variation. | Presenta dirección, variación absoluta y variación porcentual. |
| Statistical cards | Display descriptive statistics and observation counts. | Presentan estadísticas descriptivas y conteos de observaciones. |
| Temporal chart | Displays the evolution of the selected variable. | Presenta la evolución de la variable seleccionada. |
| Correlation analysis | Displays the Pearson coefficient and aligned-day count. | Presenta el coeficiente de Pearson y el número de días alineados. |
| Scatter plot | Visualizes paired observations used in correlation analysis. | Visualiza observaciones emparejadas utilizadas en el análisis de correlación. |
| Refresh control | Requests updated information from the application. | Solicita información actualizada a la aplicación. |
| Language selector | Interface available in English and Spanish. | Interfaz disponible en inglés y español. |

---

## 17. Functional Development | Desarrollo funcional

### English

The Patterns and Trends module is available in the AQUABOT MAX ECOSYSTEM web application.

Its visible operational functions include monitoring filters, descriptive statistics, absolute and percentage change, temporal visualization, Pearson correlation, and scatter plots.

The reference screenshot documents a temperature time series with 1,344 readings and a Pearson correlation of 0.213 between temperature and dissolved oxygen using 29 aligned days.

Advanced analytical methods, including Fourier analysis, spectra, spectrograms, cycle detection, seasonality, and lag analysis, remain pending backend implementation according to the interface.

### Español

El módulo Patrones y tendencias está disponible en la aplicación web AQUABOT MAX ECOSYSTEM.

Sus funciones operativas visibles incluyen filtros de monitoreo, estadísticas descriptivas, cambio absoluto y porcentual, visualización temporal, correlación de Pearson y diagramas de dispersión.

La captura de referencia documenta una serie temporal de temperatura con 1,344 lecturas y una correlación de Pearson de 0.213 entre temperatura y oxígeno disuelto utilizando 29 días alineados.

Los métodos analíticos avanzados, incluyendo Fourier, espectros, espectrogramas, análisis de ciclos, estacionalidad y retardos, continúan pendientes de implementación en el backend de acuerdo con la interfaz.

---

**AQUABOT MAX ECOSYSTEM**  
**ODEVE — Open Development Ecosystem**
