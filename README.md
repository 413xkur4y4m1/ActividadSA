# Proyecto de Arquitectura Empresarial

Practica de control de versiones para demostrar el uso de ramas, commits, merges, resolucion de conflictos, tags y documentacion tecnica.

## Tipo de servicio web
Este proyecto utiliza arquitectura REST.

## Justificacion
Se eligio REST porque:
- Es mas ligero que SOAP.
- Usa HTTP de forma directa.
- Facilita la integracion con aplicaciones web y moviles.
- Tiene buen rendimiento en escenarios comunes de negocio.

## Control de versiones
- `main`: linea principal estable (trunk).
- `feature/*`: ramas de desarrollo para nuevas funcionalidades.
- `tags/releases`: versiones cerradas del proyecto (por ejemplo `v1.0`).

## Flujo de trabajo aplicado
- Desarrollo inicial en `main` con estructura base del repositorio.
- Implementacion de cambios en ramas `feature`.
- Integracion de cambios mediante merge.
- Simulacion y resolucion de conflicto de codigo.

## Integracion continua
GitHub Actions permite automatizar tareas como pruebas, validacion de calidad de codigo y despliegue continuo del servicio, mejorando la trazabilidad y mantenimiento del proyecto.
