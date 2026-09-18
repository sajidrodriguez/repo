# Datos e integraciones

[← Volver al mapa](./README.md)

## Qué resuelvo

Conecto servicios externos sin entregarles la autoridad total sobre los datos o
la operación. Diseño capas que validan, normalizan y vuelven utilizable la
información para distintas áreas del negocio.

Los estados de los proyectos de Mobilec corresponden a mi etapa laboral allí,
ya concluida; no describen mantenimiento actual a mi cargo.

## Implementaciones seleccionadas

### Mobilec Hub · producción

Middleware seguro y aislado que media entre la experiencia conversacional y
las integraciones críticas. Centraliza validaciones y permite que el resto del
sistema evolucione sin exponer directamente los servicios operativos.

### Fuente operativa común · producción

Capa de datos propia que consolida información procedente de distintos
proveedores. Reduce acoplamiento, conserva una representación coherente y
permite sustituir servicios sin perder continuidad conceptual.

### Mobilec Data · soporte arquitectónico

Proyecto paralelo utilizado para comprender, ordenar y resolver el tránsito de
datos que después sostuvo la arquitectura de Mobilec Hub.

## Decisiones y trade-offs

- Proteger las integraciones críticas fuera del canal conversacional.
- Unificar información externa antes de convertirla en operación.
- Exponer únicamente las capacidades mínimas necesarias entre componentes.
- Favorecer independencia progresiva de proveedores sin exigir una migración
  total para obtener valor.

## Frontera pública

Este documento explica decisiones profesionales. Omite nombres de tablas,
endpoints, credenciales, reglas internas, configuraciones de red y cualquier
dato que permita reconstruir la topología de producción.
