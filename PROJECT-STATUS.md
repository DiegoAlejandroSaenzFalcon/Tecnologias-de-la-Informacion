# PROJECT-STATUS.md

## Estado del repositorio

**Fecha de auditoría:** 2026-10-06  
**Estado:** AUDIT_CORRECTIONS_IN_PROGRESS

Este archivo registra el estado documental y de gobierno del repositorio. No constituye evidencia de que cada guía haya sido ejecutada, probada o certificada.

## Alcance de la auditoría

Se revisaron:

- identidad, visibilidad y propósito del repositorio;
- licencia y afirmaciones del README;
- instrucciones para agentes;
- política de seguridad;
- marcador defensivo;
- llms.txt;
- configuración de MkDocs;
- workflows de GitHub Actions;
- referencias conocidas a la autoridad central y rutas locales obsoletas.

## Hallazgos corregidos en esta rama

- README: licencia reconciliada con GPL-3.0 y alcance educativo aclarado.
- README: se eliminó la presentación del material como sustituto o equivalente de la certificación oficial.
- README: visibilidad de Soluciona reconciliada con el estado público actual.
- AGENTS.md: autoridad centralizada en Directivas-de-Seguridad y eliminadas instrucciones locales que intentaban gobernar rutas del equipo.
- SECURITY.md: autoridad y reglas locales reconciliadas.
- HONEYTOKEN.md: convertido en marcador defensivo pasivo, sin instrucciones de autorrevelación.
- llms.txt: referencia central actualizada a Directivas-de-Seguridad.

## Pendientes antes de cerrar la auditoría

1. Consolidar el workflow de documentación y ejecutar una construcción estricta de MkDocs antes del despliegue.
2. Eliminar el workflow `.github/workflows/test.yml`, que actualmente es un duplicado sin pruebas reales.
3. Verificar navegación y enlaces internos del sitio.
4. Rebuscar referencias obsoletas a repositorios, rutas y autoridades anteriores.
5. Verificar el PR y el estado de `main` después del merge.
6. Actualizar el registro de auditorías en Directivas-de-Seguridad solo después de verificar el cierre.

## Criterio de cierre

La auditoría solo puede pasar a **VERIFIED / EVIDENCED / DOCUMENTED** cuando las correcciones estén en `main`, la documentación y workflows estén verificados, y exista evidencia del commit/PR final.
