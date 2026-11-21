# Parking Manager — Documentación

Documentación en Markdown del TFG, agrupada en la organización [core-parking](https://github.com/core-parking).

## Repositorios

- [parking-service](https://github.com/core-parking/parking-service): microservicio de gestión de parkings.
- `docs`: casos de uso y documentación del proyecto.
- Segundo microservicio: pendiente de crear y concretar su alcance.

Cada microservicio mantiene su propio historial, ramas y versiones. Este repositorio de documentación tiene un historial independiente.

## Casos de uso

El borrador inicial está reunido en [Parking Service — Alcance y casos de uso](casos-de-uso/PARKING-SERVICE.md): incluye decisiones propuestas, esquemas, 16 casos de uso, DoR, criterios de aceptación y DoD, alineados con la arquitectura hexagonal modular. Está pendiente de revisión por Julio y el tutor. La [plantilla](casos-de-uso/PLANTILLA.md) sigue disponible para futuras fichas individuales.

Propuesta inicial pendiente de validar:

- El operador registra un parking con su ubicación y capacidad.
- El operador gestiona las plazas disponibles y fuera de servicio.
- El operador consulta las plazas libres y ocupadas de un parking.
- El operador registra la entrada de un vehículo si hay disponibilidad.
- El operador registra la salida de un vehículo y libera su plaza.
- El operador consulta los vehículos presentes y el historial de estancias.
- El operador consulta estadísticas de ocupación y estancias.

## Ampliación de la documentación

Se incorporarán `arquitectura/` para decisiones y diagramas, y `seguimiento/` para reuniones y entregas cuando escribamos esos documentos.

## Forma de trabajo

Tanto Docs como los microservicios se desarrollan mediante ramas `feature/...` desde `develop` y PR hacia `develop`. Las pruebas y revisiones se realizan en las ramas de trabajo y sus PR, y la validación conjunta se realiza en `develop`. Las entregas verificadas se integran en `main` y se etiquetan; `main` se reserva para releases. Cada servicio mantiene su versión independiente. Las entregas globales documentarán las versiones concretas de los servicios.

La estructura inicial de este repositorio se ha creado en `main`. Las siguientes modificaciones de documentación se propondrán mediante ramas y PR.
