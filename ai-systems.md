# Sistemas inteligentes

[← Volver al mapa](./README.md)

## Qué resuelvo

Diseño asistentes que reconocen intención, consultan información, usan
herramientas y saben cuándo devolver el control a una persona. La IA no vive
aislada: forma parte de un sistema de operación del negocio con límites claros.

Los estados de los proyectos de Mobilec corresponden a mi etapa laboral allí,
ya concluida; no describen mantenimiento actual a mi cargo.

## Implementaciones seleccionadas

### Mobibot AI · producción

Orquestación conversacional para atención y soporte. Conecta las solicitudes de
clientes con capacidades operativas mediante una aplicación intermedia
separada. Incluye transferencia a equipos humanos y acciones vinculadas con
dispositivos físicos.

### Voz realtime · implementada, pendiente de aprobación

Al concluir mi etapa en Mobilec, la experiencia de voz estaba implementada y
probada en un entorno controlado, pendiente de aprobación para uso comercial.

### Flou · operativo

Agente virtual de Jit De Flou conectado a una bandeja de atención que permite
tomar las conversaciones y continuarlas personalmente. El sitio, el agente y
la bandeja están publicados y operativos.

### TopBot · histórico

Primer sistema conversacional propio: JavaScript y Node.js sobre Google Cloud.
Nació como una automatización de seguimiento comercial y abrió la transición
hacia desarrollo, APIs e infraestructura.

## Decisiones y trade-offs

- Separar la conversación de las integraciones críticas.
- Mantener validación humana para acciones sobre dispositivos físicos.
- Distinguir una capacidad implementada de una capacidad aprobada para operar.
- Permitir desactivar capacidades opcionales, como voz o monitoreo proactivo,
  sin detener el núcleo conversacional. Este alcance no implica tolerancia a
  fallos de todos los componentes críticos.

## Evidencia pública segura

- Sistemas conversacionales en producción.
- Integración entre IA, datos operativos, soporte humano y telemetría.
- Implementación realtime probada en entorno controlado.
- Sin código propietario, prompts operativos, payloads ni datos de clientes.
