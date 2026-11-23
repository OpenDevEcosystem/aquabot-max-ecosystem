# Roadmap | Hoja de ruta — AQUABOT MAX ECOSYSTEM

The roadmap reflects **documented evidence and current work priorities**, not promised release dates. / La hoja de ruta refleja **evidencias documentadas y prioridades de trabajo**, no fechas de lanzamiento prometidas.

**Status / Estado:** ✅ Operational | Operativo · 🧪 In validation | En validación · 🚧 In development | En desarrollo · 📅 Planned | Planeado · ⏸ Paused | Pausado.

## Now | Ahora

| Work / Trabajo | Status / Estado | Evidence, next check / Evidencia, siguiente comprobación |
|---|---|---|
| Public environmental PDF archive / Archivo público de informes ambientales PDF | ✅ Operational / Operativo **for archived files / para archivos publicados** | [Archive / Archivo](evidence/environmental-reports/2026/11/) and [commits / commits](https://github.com/OpenDevEcosystem/aquabot-max-ecosystem/commit/b7192c7572990c1475477c0d493b8a9343cbacfc); separately audit uninterrupted automatic publication / auditar por separado publicación automática continua. |
| Bilingual updates navigation / Navegación bilingüe de novedades | ✅ Operational / Operativo **for documentation / documental** | [Updates](updates/README.md), [README](README.md). |
| Nine regional marine SST GeoJSON contexts / Nueve contextos SST marina regional en GeoJSON | 🧪 In validation / En validación | Nine geometries and no-land-overlap check **reported by project**; add reproducible tests, screenshots, deployment evidence and implementation commit / geometrías y revisión sin tierra **reportadas por el proyecto**; adjuntar pruebas reproducibles, capturas, evidencia de despliegue y commit. |
| Security issue in administrative configuration / Problema de seguridad de configuración administrativa | 🚧 In development / En desarrollo **remediation not verified / corrección no verificada** | [Security notice in README](README.md); avoid documenting exploit details or secrets / evitar divulgar explotación o secretos. |
| Status review across platform modules / Revisión de estado de módulos | 🧪 In validation / En validación | [Module index](docs/platform-modules/README.md) distinguishes available features from development; reconcile README's 21 vs index's 22 navigation entries / el índice distingue funciones; conciliar 21 vs 22 entradas de navegación. |

## Next | Siguiente

| Work / Trabajo | Status / Estado | Evidence and exit criterion / Evidencia y criterio de salida |
|---|---|---|
| Reproducible SST geometry and clipping audit / Auditoría reproducible de geometrías y recorte SST | 📅 Planned / Planeado | Store nonsensitive test method, polygon validation output, sample screenshots, reference shoreline version, dataset date / registrar método no sensible, resultados, capturas, costa y fecha del producto. |
| Module-by-module functional evidence / Evidencia funcional por módulo | 📅 Planned / Planeado | Independently check capabilities and label operational vs validation vs development / comprobar cada capacidad y clasificar estado. |
| Report provenance and scheduling evidence / Procedencia de informes y evidencia de programación | 📅 Planned / Planeado | Document safe execution logs, sample publication timestamps, handling of failed runs, data provenance / publicar registros depurados, fechas y manejo de fallos y procedencia. |
| Update publishing discipline / Disciplina de publicación de novedades | 📅 Planned / Planeado | Use PR checklist, CHANGELOG entry and documented Release notes for major verified milestones / usar plantilla PR, CHANGELOG y notas de Release para hitos importantes comprobados. |

## Later | Después

| Work / Trabajo | Status / Estado | Boundary / Alcance |
|---|---|---|
| FFT, spectrogram and advanced signal-analysis functionality / FFT, espectrogramas y análisis avanzado de señales | 📅 Planned / Planeado | [Scientific methodology document](docs/MATHEMATICAL_MODELS_AND_SIGNAL_ANALYSIS.md) says not operationally verified / el documento aclara que no están comprobados como operativos. |
| Euler/differential-equation modeling and environmental predictions / Modelos Euler y predicciones ambientales | 📅 Planned / Planeado | Research methodology, **not validated predictive services** / metodología de investigación, **no servicios predictivos validados**. |
| Further radar/NISAR evaluation / Evaluación adicional radar/NISAR | 📅 Planned / Planeado | Distinguish product exploration from validated operational integration / separar exploración de integración operativa validada. |

## Governance | Reglas de actualización

1. **Do not equate documentation with deployment. / No equiparar documentación con despliegue.**
2. **Do not equate visual checks with scientific validation. / No equiparar revisión visual con validación científica.**
3. **Never publish credentials, internal endpoints or personal contact details. / Nunca publicar credenciales, endpoints internos ni contactos personales.**
4. **Do not change historical PDFs, raw data or scientific evidence. / No modificar PDF históricos, datos originales ni evidencias científicas.**
5. **Move an item to operational only with dated, reproducible evidence. / Cambiar a operativo solo con evidencia fechada y reproducible.**
6. **Document actual versions only when released/tagged. / Documentar versiones solo si fueron lanzadas/etiquetadas.**

[Changelog | Historial](CHANGELOG.md) · [Platform modules | Módulos](docs/platform-modules/README.md)
