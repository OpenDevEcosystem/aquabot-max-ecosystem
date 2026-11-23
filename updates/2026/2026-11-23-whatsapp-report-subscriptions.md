# WhatsApp Environmental Report Subscriptions | Suscripción a informes ambientales por WhatsApp

**AQUABOT MAX ECOSYSTEM**

| Information / Información | Details / Detalles |
|---|---|
| Date / Fecha | 2026-11-23 |
| Category / Categoría | New feature / Nueva funcionalidad |
| Module / Módulo | Environmental Reporting / Reportes ambientales |
| Status / Estado | Operational / Operativo |
| Version / Versión | Not assigned / No asignada |

---

## English

### Overview

AQUABOT MAX ECOSYSTEM introduces a controlled registration and authorization workflow for receiving automated daily environmental monitoring reports through WhatsApp.

This improvement expands access to environmental information for researchers, academic institutions, government agencies, environmental organizations, local communities, and other interested stakeholders.

The registration process incorporates administrative authorization, personal data protection, operational reliability, and traceability.

### New Features

- Public registration form available in the Reports module.
- Explicit acceptance of the privacy notice.
- Unique tracking reference for each submitted request.
- Public request status consultation without exposing personal information.
- Protected administrative review interface.
- Approval, rejection, and suspension of subscriptions.
- Automatic synchronization of approved recipients with the daily report distribution system.
- Preservation of existing manually configured recipients.
- Administrative audit trail.
- Timestamped configuration backups and recovery mechanisms.

### Registration Information

The public form collects:

- Full name.
- Organization or institution.
- Position, profession, or activity.
- Email address.
- WhatsApp number, including country code.
- Municipality or city.
- State or region.
- Country.
- Main purpose of the request.
- Intended use of environmental information.
- Lagoons or environmental topics of interest.
- Explicit consent to the summarized privacy notice.

Submitting a request does not automatically activate a subscription.

### Request Status

| Status | Description |
|---|---|
| Pending | Request received and awaiting administrative review. |
| Approved | Request authorized for daily report distribution. |
| Rejected | Request reviewed and not authorized. |
| Suspended | Previously approved subscription deactivated. |

### Operational Workflow

1. The interested user completes the public registration form.
2. The system validates and registers the request.
3. A unique tracking reference is generated.
4. The request remains pending until administrative review.
5. An authorized administrator evaluates the request.
6. The administrator approves or rejects the subscription.
7. Approved recipients are synchronized with the daily distribution system.
8. Authorized recipients become eligible for the next scheduled report distribution.

### Security and Privacy

The implementation incorporates the following controls:

- Server-side administrative authentication.
- High-entropy administrative credentials.
- Secure credential comparison.
- Server-side input validation.
- Request size restrictions.
- International telephone number validation.
- Honeypot protection against automated submissions.
- Rate limiting.
- Hashed IP information for abuse prevention.
- Public status responses without personal data.
- Temporary administrative session credential storage.

Administrative credentials are not embedded in the public frontend.

Personal information, operational credentials, internal configurations, and administrative records are not published in this repository.

### Reliability and Data Integrity

The approval workflow synchronizes authorized recipients with the existing daily environmental report distribution system.

Before modifying distribution configurations, the system creates timestamped backups.

Both distribution records are updated through temporary writes and safe replacement mechanisms. If either update fails, both records are restored.

Suspension only removes recipients incorporated through the new registration workflow.

Previously configured historical or manual recipients remain protected.

### Audit and Traceability

The administrative workflow maintains records of:

- Submitted requests.
- Privacy consent timestamps.
- Request status.
- Administrative review dates.
- Responsible administrator.
- Internal review notes.
- Status transitions.
- Associated configuration backups.

### Verification

According to the implementation and operational verification reported by the project:

| Verification | Result |
|---|---|
| Public registration form | Passed |
| Registration section visible in Reports | Passed |
| Protected administrative interface | Passed |
| Unauthorized administrative request | HTTP 401 |
| Incomplete registration request | HTTP 400 |
| Nonexistent tracking reference | HTTP 404 |
| Authenticated administrative API | Passed |
| Automated tests | 5 passed |
| Existing recipients preserved | 10 recipients |
| Daily distribution enabled | Confirmed |
| Distribution configuration validation | Passed |

No fictitious registration requests were created in the production environment.

### Known Limitations

- Registration requires administrative authorization.
- Submission does not guarantee approval.
- Delivery depends on the availability of the messaging infrastructure.
- End-to-end delivery to a newly approved production recipient has not been independently verified for this documentation update.

This functionality is intended for environmental report subscriptions, not citizen incident reporting.

---

## Español

### Descripción general

AQUABOT MAX ECOSYSTEM incorpora un procedimiento controlado de registro y autorización para recibir informes diarios automatizados de monitoreo ambiental mediante WhatsApp.

Esta mejora amplía el acceso a la información ambiental para investigadores, instituciones académicas, dependencias gubernamentales, organizaciones ambientales, comunidades locales y otros sectores interesados.

El procedimiento de registro incorpora mecanismos de autorización administrativa, protección de datos personales, confiabilidad operativa y trazabilidad.

### Nuevas funcionalidades

- Formulario público de registro disponible en el módulo Reportes.
- Aceptación explícita del aviso de privacidad.
- Folio único de seguimiento para cada solicitud.
- Consulta pública del estado de la solicitud sin exposición de datos personales.
- Interfaz administrativa protegida.
- Aprobación, rechazo y suspensión de suscripciones.
- Sincronización automática de destinatarios autorizados con el sistema de distribución diaria.
- Conservación de los destinatarios previamente configurados de forma manual.
- Registro de auditoría administrativa.
- Respaldos de configuración con fecha y hora y mecanismos de recuperación.

### Información solicitada

El formulario público recopila:

- Nombre completo.
- Organización o institución.
- Cargo, profesión o actividad.
- Correo electrónico.
- Número de WhatsApp con código de país.
- Municipio o ciudad.
- Estado o región.
- País.
- Propósito principal de la solicitud.
- Uso previsto de la información ambiental.
- Lagunas o temas ambientales de interés.
- Consentimiento explícito del aviso de privacidad resumido.

El envío de una solicitud no activa automáticamente la suscripción.

### Estados de las solicitudes

| Estado | Descripción |
|---|---|
| Pendiente | Solicitud recibida y en espera de revisión administrativa. |
| Aprobada | Solicitud autorizada para recibir los informes diarios. |
| Rechazada | Solicitud revisada y no autorizada. |
| Suspendida | Suscripción previamente aprobada que ha sido desactivada. |

### Flujo operativo

1. La persona interesada completa el formulario público.
2. El sistema valida y registra la solicitud.
3. Se genera un folio único de seguimiento.
4. La solicitud permanece pendiente de revisión administrativa.
5. Un administrador autorizado evalúa la solicitud.
6. El administrador aprueba o rechaza la suscripción.
7. Los destinatarios aprobados se sincronizan con el sistema de distribución diaria.
8. Los destinatarios autorizados quedan habilitados para la siguiente distribución programada de informes.

### Seguridad y privacidad

La implementación incorpora los siguientes controles:

- Autenticación administrativa del lado del servidor.
- Credenciales administrativas de alta entropía.
- Comparación segura de credenciales.
- Validación de datos del lado del servidor.
- Restricciones en el tamaño de las solicitudes.
- Validación internacional de números telefónicos.
- Protección honeypot contra solicitudes automatizadas.
- Limitación de frecuencia de solicitudes.
- Uso de hashes de direcciones IP para prevenir abusos.
- Respuestas públicas de consulta sin datos personales.
- Almacenamiento temporal de credenciales durante la sesión administrativa.

Las credenciales administrativas no están incorporadas en el frontend público.

La información personal, las credenciales operativas, las configuraciones internas y los registros administrativos no se publican en este repositorio.

### Confiabilidad e integridad de los datos

El procedimiento de aprobación sincroniza los destinatarios autorizados con el sistema existente de distribución diaria de informes ambientales.

Antes de modificar las configuraciones de distribución, el sistema genera respaldos identificados mediante fecha y hora.

Los dos registros de distribución se actualizan mediante escrituras temporales y mecanismos de reemplazo seguro. Si alguna actualización falla, ambos registros son restaurados.

La suspensión únicamente elimina destinatarios incorporados mediante el nuevo procedimiento de registro.

Los destinatarios históricos o configurados manualmente permanecen protegidos.

### Auditoría y trazabilidad

El procedimiento administrativo conserva registros de:

- Solicitudes recibidas.
- Fecha y hora del consentimiento de privacidad.
- Estado de la solicitud.
- Fecha de revisión administrativa.
- Administrador responsable.
- Observaciones internas.
- Cambios de estado.
- Respaldos de configuración asociados.

### Verificación

De acuerdo con los resultados de implementación y verificación operativa reportados por el proyecto:

| Verificación | Resultado |
|---|---|
| Formulario público de registro | Correcto |
| Sección de registro visible en Reportes | Correcto |
| Interfaz administrativa protegida | Correcto |
| Solicitud administrativa no autorizada | HTTP 401 |
| Solicitud de registro incompleta | HTTP 400 |
| Folio inexistente | HTTP 404 |
| API administrativa autenticada | Correcto |
| Pruebas automatizadas | 5 aprobadas |
| Destinatarios existentes conservados | 10 destinatarios |
| Distribución diaria habilitada | Confirmado |
| Validación de configuración de distribución | Correcto |

No se generaron solicitudes ficticias en el entorno de producción.

### Limitaciones conocidas

- El registro requiere autorización administrativa.
- El envío de una solicitud no garantiza su aprobación.
- La entrega depende de la disponibilidad de la infraestructura de mensajería.
- La entrega de extremo a extremo a un nuevo destinatario aprobado en producción no ha sido verificada independientemente para esta actualización documental.

Esta funcionalidad está destinada a la suscripción a informes ambientales y no a la recepción de denuncias o reportes ciudadanos.

---

## Related Documentation | Documentación relacionada

- [AQUABOT MAX ECOSYSTEM](../../README.md)
- [Changelog / Registro de cambios](../../CHANGELOG.md)
- [System Architecture / Arquitectura del sistema](../../SYSTEM_ARCHITECTURE.md)
- [Reports Module / Módulo Reportes](../../docs/platform-modules/reports/README.md)
- [Updates / Novedades](../README.md)

---

**AQUABOT MAX ECOSYSTEM**

*From Space to Water | Del espacio al agua*

IoT · Satellite Remote Sensing · Water Quality Monitoring · Environmental Intelligence
