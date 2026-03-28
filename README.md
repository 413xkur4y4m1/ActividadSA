# Proyecto de Arquitectura Empresarial

Práctica de control de versiones para demostrar el uso de ramas, commits, merges, resolución de conflictos, tags y documentación técnica.

## Tipo de servicio web
Este proyecto utiliza arquitectura REST.

## Justificación
Se eligió REST porque:
- Es más ligero que SOAP.
- Usa HTTP de forma directa.
- Facilita la integración con aplicaciones web y móviles.
- Tiene buen rendimiento en escenarios comunes de negocio.

## Control de versiones
- `main`: línea principal estable (trunk).
- `feature/*`: ramas de desarrollo para nuevas funcionalidades.
- `tags/releases`: versiones cerradas del proyecto (por ejemplo `v1.0`).

## Flujo de trabajo aplicado
- Desarrollo inicial en `main` con estructura base del repositorio.
- Implementación de cambios en ramas `feature`.
- Integración de cambios mediante merge.
- Simulación y resolución de conflicto de código.

## Integración continua
GitHub Actions permite automatizar tareas como pruebas, validación de calidad de código y despliegue continuo del servicio, mejorando la trazabilidad y mantenimiento del proyecto.
