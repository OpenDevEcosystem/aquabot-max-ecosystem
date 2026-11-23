# Changelog | Historial de cambios

Public, bilingual history of **AQUABOT MAX ECOSYSTEM**, including software, interface, satellite context, scientific methods, sensors, automation, reports, security and documentation. / Historial público bilingüe de **AQUABOT MAX ECOSYSTEM**, incluidos software, interfaz, contexto satelital, métodos científicos, sensores, automatización, informes, seguridad y documentación.

**Reading guide / Guía:** Entries describe the evidence available, **not** a blanket certification that a feature works. The date is the documented event date, not necessarily deployment time. No release version is assigned unless evidenced. / Las entradas describen la evidencia disponible, **no** certifican por sí mismas que una función opere. La fecha corresponde al evento documentado, no necesariamente a la puesta en producción. No se asignan versiones sin evidencia.

**Statuses / Estados:** ✅ Operational | Operativo · 🧪 In validation | En validación · 🚧 In development | En desarrollo · 📅 Planned | Planeado · ⏸ Paused | Pausado.

**Categories / Categorías:** ✨ New | Nuevo · 🚀 Improved | Mejorado · 🛠 Fixed | Corregido · 🔬 Scientific validation | Validación científica · 🔐 Security | Seguridad · 📚 Documentation | Documentación.

---

## 2026-11-22 — 🛠 Fixed | Corregido; 🔬 Scientific validation | Validación científica
<a id="2026-11-22-marine-sst"></a>

**Update / Actualización:** Regional marine SST display geometry / Geometría de visualización de SST marina regional.  
**Status / Estado:** 🧪 In validation | En validación (reported geometry validation; public deployment and independent reproduction not established / validación geométrica reportada; despliegue público y reproducción independiente no comprobados).  
**Version / Versión:** Not assigned / No asignada.  
**Modules / Módulos:** Satellite observations, regional marine context, map interface / Observaciones satelitales, contexto marino regional, interfaz cartográfica.

- **Description / Descripción:** Nine lagoon-specific GeoJSON polygons were reported for Chautengo, Coyuca, Las Salinas, Mitla, Negra de Puerto Marqués, Nuxco, Salina El Cuajo, Tecomate, and Tres Palos. Each follows the coast at the terrestrial boundary with straight offshore edges extending **35 km**. The GCOM-C/SGLI image is clipped to each polygon, with a dashed orange boundary in the map. La Tejería, Palí and Tuxpan are classified as inland lagoons and omit the marine SST scene. / Se reportaron nueve polígonos GeoJSON específicos para Chautengo, Coyuca, Las Salinas, Mitla, Negra de Puerto Marqués, Nuxco, Salina El Cuajo, Tecomate y Tres Palos. Cada uno usa la costa como límite terrestre y lados rectos mar adentro hasta **35 km**. La imagen GCOM-C/SGLI se recorta al polígono; el mapa muestra un límite naranja discontinuo. La Tejería, Palí y Tuxpan se clasifican como interiores y omiten la escena marina.
- **Reason / Motivo:** Prevent confusion between regional offshore sea-surface-temperature context and measurements inside a lagoon. / Evitar confundir contexto térmico marino regional con mediciones dentro de la laguna.
- **Visible result / Resultado visible:** Expected clipped marine context and dashed outline, where implemented; deployment has not been independently verified from this public documentation. / Se espera contexto marino recortado y contorno discontinuo donde esté implementado; no se verificó independientemente su despliegue con esta documentación pública.
- **Validation / Validación:** Project-provided report indicates nine geometries checked with no land overlap; coastline reference reported as Natural Earth **1:10m Land v5.1.1**. **Validation artifacts and exact code commit were not found in the inspected public repository sources.** / Según el reporte aportado por el proyecto, se comprobaron las nueve geometrías sin superposición con tierra; referencia costera Natural Earth **1:10m Land v5.1.1**. **No se localizaron los artefactos de validación ni el commit exacto de implementación en las fuentes públicas inspeccionadas.**
- **Known limitations / Limitaciones:** Regional ocean context only; **not in-lagoon SST**; product resolution, cloud/quality masking, proximity-to-shore effects, acquisition date and uncertainty must be evaluated for scientific use. / Solo contexto oceánico regional; **no es SST dentro de la laguna**; para uso científico deben revisarse resolución, máscaras de calidad/nubes, efectos costeros, fecha y incertidumbre.
- **Evidence / Evidencias:** Project-supplied technical change record dated 2026-11-22; [satellite architecture](SYSTEM_ARCHITECTURE.md); [scientific data sources](docs/TECHNOLOGY_STACK_AND_DATA_SOURCES.md). / Registro técnico aportado por el proyecto; [arquitectura](SYSTEM_ARCHITECTURE.md); [fuentes científicas](docs/TECHNOLOGY_STACK_AND_DATA_SOURCES.md).
- **Commit / Commit de implementación:** Not publicly verified / No verificado públicamente.

## 2026-11-22 — 📚 Documentation | Documentación; 🚀 Improved | Mejorado
<a id="2026-11-22-whats-new"></a>

**Update / Actualización:** Bilingual updates navigation / Navegación bilingüe de novedades.  
**Status / Estado:** ✅ Operational | Operativo (**repository documentation**, not application runtime / documentación del repositorio, no ejecución de la aplicación).  
**Version / Versión:** Not assigned / No asignada.  
**Modules / Módulos:** Public README, `updates/` archive / README público, archivo `updates/`.

- **Description / Descripción:** Added and corrected bilingual What's New navigation on the repository landing page and update index. / Se agregó y corrigió la navegación bilingüe de novedades en portada y en el índice de actualizaciones.
- **Reason / Motivo:** Make documented project evolution discoverable. / Facilitar la consulta de la evolución documentada del proyecto.
- **Visible result / Resultado visible:** README links to `updates/README.md` and the November 22 entry. / El README enlaza a `updates/README.md` y a la entrada del 22 de noviembre.
- **Validation / Validación:** File contents and matching commit history inspected. / Se revisaron archivos e historial de commits correspondientes.
- **Known limitations / Limitaciones:** This establishes a documentation pathway, not proof of all claimed platform features. / Es una vía documental, no prueba de todas las capacidades anunciadas de la plataforma.
- **Evidence / Evidencias:** [README](README.md), [updates index](updates/README.md), [initial update commit](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/0000152f161e42008016272a0c32f0cf3d59c446), [formatting fix](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/ddbb5c4054ddd92bc7cd2c0323834c5a9979b980).

## 2026-11-22 — ✨ New | Nuevo; 📚 Documentation | Documentación
<a id="2026-11-22-reports"></a>

**Update / Actualización:** Bilingual daily report archive / Archivo de informes diarios bilingües.  
**Status / Estado:** ✅ Operational | Operativo (**verified GitHub archive**, automated end-to-end reliability not audited / archivo GitHub comprobado; fiabilidad automatizada integral no auditada).  
**Version / Versión:** Not assigned / No asignada.  
**Modules / Módulos:** Environmental reports, evidence archive, publication workflow / Informes ambientales, archivo de evidencias, publicación.

- **Description / Descripción:** Public commits archive lagoon reports, including November 20–22 batches; documentation describes the bilingual publication workflow. / Los commits públicos archivan informes de lagunas, incluidos lotes del 20 al 22 de noviembre; la documentación describe el flujo de publicación bilingüe.
- **Reason / Motivo:** Improve access, retention and traceability of environmental reporting. / Mejorar acceso, conservación y trazabilidad de los informes ambientales.
- **Visible result / Resultado visible:** Reports can be found in the dated evidence directory. / Los informes pueden encontrarse en el directorio de evidencias por fecha.
- **Validation / Validación:** Verified commit messages and repository documentation. / Se verificaron mensajes de commit y documentación del repositorio.
- **Known limitations / Limitaciones:** Archived PDFs do not independently demonstrate correctness of measurements, full execution scheduling or uninterrupted daily delivery. / Los PDF archivados no demuestran por sí solos la exactitud de las mediciones, programación integral ni entrega diaria ininterrumpida.
- **Evidence / Evidencias:** [reports directory](evidence/environmental-reports/2026/11/), [update note](updates/2026/2026-11-22-informes-automaticos.md), [archive commit](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/b7192c7572990c1475477c0d493b8a9343cbacfc), [documentation commit](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/8096e712dcc4cc1ee8d19ca1a3c69f50f4cadaea).

## 2026-11-20 — 📚 Documentation | Documentación
<a id="2026-11-20-academy"></a>

**Update / Actualización:** AQUABOT Academy channel links / Enlaces a canales AQUABOT Academy.  
**Status / Estado:** ✅ Operational | Operativo (**repository links only / solo enlaces del repositorio**).  
**Version / Versión:** Not assigned / No asignada.  
**Modules / Módulos:** Education and project presentation / Educación y presentación pública.

- **Description / Descripción:** Added bilingual YouTube channel references. / Se incorporaron referencias a canales de YouTube en ambos idiomas.
- **Reason / Motivo:** Improve access to educational materials. / Mejorar el acceso a materiales educativos.
- **Visible result / Resultado visible:** Channel references included in repository history. / Referencias a canales en el historial del repositorio.
- **Validation / Validación:** Matching commit observed; channel publication inventories not audited. / Se identificó el commit; no se auditó el inventario publicado de los canales.
- **Known limitations / Limitaciones:** Link documentation does not verify all episode uploads or playlist completeness. / Documentar enlaces no comprueba la publicación de todos los episodios o listas.
- **Evidence / Evidencias:** [commit](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/05e93435e3ef8eb767fdc1dc8ab68a39771ffac3).

## 2026-11-20 — 📚 Documentation | Documentación; 🔬 Scientific validation | Validación científica
<a id="2026-11-20-models"></a>

**Update / Actualización:** Mathematical models and environmental signal analysis reference / Documento de modelos matemáticos y análisis de señales.  
**Status / Estado:** ✅ Operational | Operativo (**documentation published only / solo publicación documental**).  
**Version / Versión:** Document-specific version, if shown in its source; no ecosystem release version / Versión propia del documento, si consta en él; sin versión de lanzamiento del ecosistema.  
**Modules / Módulos:** Scientific documentation, patterns and trends, models and signals / Documentación científica, patrones y tendencias, modelos y señales.

- **Description / Descripción:** Added bilingual documentation of descriptive statistics, correlation and proposed derivative, Fourier/FFT and Euler methodologies. / Se incorporó documentación bilingüe de estadística descriptiva, correlación y metodologías propuestas de derivadas, Fourier/FFT y Euler.
- **Reason / Motivo:** Separate scientifically explained methods from confirmed functionality. / Distinguir métodos explicados científicamente de funciones implementadas.
- **Visible result / Resultado visible:** Public methodological document linked from the README. / Documento metodológico público enlazado desde README.
- **Validation / Validación:** Document and matching commits inspected; scientific predictive validation **not** claimed. / Se revisó el documento y commits; **no** se afirma validación científica predictiva.
- **Known limitations / Limitaciones:** FFT, spectrograms, Euler models and predictions are not established as operational by the document. / FFT, espectrogramas, modelos Euler y predicciones no están acreditados como operativos por el documento.
- **Evidence / Evidencias:** [methods](docs/MATHEMATICAL_MODELS_AND_SIGNAL_ANALYSIS.md), [documentation commit](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/13fd937ffbeeccfe9efd07157115eceda42b6573), [README link commit](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/69571e78c32d90c8540a5166743d7cbec86c0a9e).

---

## Historical sources | Fuentes históricas

[Technology evolution](TECHNOLOGY_EVOLUTION_2025-2026.md) · [System architecture](SYSTEM_ARCHITECTURE.md) · [Platform modules](docs/platform-modules/README.md) · [Field and satellite evidence](evidence/README.md) · [Earlier dated updates](updates/README.md).

**Scope note / Nota de alcance:** This record begins with verifiable late-November documentation and the explicitly reported 2026-11-22 SST change. Older changes should be added only after source-level review, preserving original dates and evidence. / Este registro inicia con documentación comprobable de noviembre y el cambio SST reportado expresamente el 22-11-2026. Se incorporarán hitos anteriores únicamente después de revisar sus fuentes, sin alterar fechas ni evidencias.
