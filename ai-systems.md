# Sistemas inteligentes

[← Volver al mapa](./README.md)

## Qué resuelvo

Diseño asistentes que reconocen intención, consultan información, usan
herramientas y saben cuándo devolver el control a una persona. La IA no vive
aislada: forma parte de un sistema operativo con límites claros.

## Implementaciones seleccionadas

### Mobibot AI · producción

Orquestación conversacional para atención y soporte. Conecta las solicitudes de
clientes con capacidades operativas mediante una aplicación intermedia
separada. Incluye transferencia a equipos humanos y acciones vinculadas con
dispositivos físicos.

### Voz realtime · implementada, pendiente de aprobación

La experiencia de voz en tiempo real está construida y fue probada en un canal
controlado. Su disponibilidad comercial depende del visto bueno de dirección;
no se presenta como una función activa para clientes.

### Jit De Flou Assistant · transición

Asistente propio en refactor hacia una arquitectura serverless para sustituir
la ejecución permanente de un servidor por funciones bajo demanda.

### TopBot · histórico

Primer sistema conversacional propio: JavaScript y Node.js sobre Google Cloud.
Nació como una automatización de seguimiento comercial y abrió la transición
hacia desarrollo, APIs e infraestructura.

## Decisiones y trade-offs

- Separar la conversación de las integraciones críticas.
- Mantener validación humana para acciones sobre dispositivos físicos.
- Distinguir una capacidad implementada de una capacidad aprobada para operar.
- Diseñar módulos reemplazables para que una función pueda retirarse sin
  interrumpir el núcleo.

## Evidencia pública segura

- Sistemas conversacionales en producción.
- Integración entre IA, datos operativos, soporte humano y telemetría.
- Implementación realtime probada en entorno controlado.
- Sin código propietario, prompts operativos, payloads ni datos de clientes.
