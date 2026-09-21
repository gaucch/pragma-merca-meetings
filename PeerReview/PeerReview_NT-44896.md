# Peer Review - Diseño de Arquitectura NT-44896

## Gestión en Jira
- Desagregar siempre en subtareas para estructurar el esfuerzo y mantener trazabilidad del avance del diseño.
- Previo a la entrega a Mercantil, registrar en el campo Notas de la issue el link a la Wiki.
- Realizar el peer review antes de entregar al cliente para evitar reprocesos en el flujo de aprobación.

## Diseño de Arquitectura

### Documentación
- La tabla de versionamiento debe incluir siempre: número de versión, canal y BFF Service.
- En la firma del servicio BFF, documentar únicamente los endpoints expuestos por el BFF. No incluir endpoints de capa de integración.
- Validar que todos los links referenciados funcionen correctamente:
  - Falta link al repositorio BFF.
  - Los links a los artefactos `.draw` y `.yaml` están rotos.

### Definición de Flujos Transaccionales
- En Azure App Configuration, respetar el orden de los parámetros: producto origen, tipo de producto origen, producto destino, tipo de producto destino, valor de la transacción, moneda de la transacción y timestamp.

### Definición de Endpoints
- Evitar siglas en español y redundancia en la URI, considerando que ya contiene el dominio de negocio.
- Actualizar las URLs de Cloudflare a las nuevas definidas por canal y ambiente.

### Diagramas
- Evitar cruce de líneas; reorganizar componentes si es necesario.
- En el diagrama de despliegue: la comunicación desde AKS hacia servicios de Microsoft Azure va por Private Link.
- En el diagrama de secuencia: el evento de auditoría se dispara a nivel de la transacción, no como dependencia del evento de notificación al cliente.
