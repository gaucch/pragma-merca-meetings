# Daily Discovery Team
## Objetivo
Sincronizar al equipo diariamente para asegurar el avance hacia el objetivo del sprint, identificar oportunamente riesgos e impedimentos, y alinear los esfuerzos individuales con el resultado esperado del equipo.

## Preparación previa
Cada integrante del equipo dedica entre 5 y 10 minutos antes de la reunión para:
- Analizar el trabajo realizado el día anterior.
- Definir el plan de trabajo del día.
- Identificar riesgos, bloqueos o desviaciones.
- Tomar notas si es necesario para comunicar de forma clara y consciente durante la daily.

## Inicio de la reunión
- La persona responsable de la daily comparte pantalla.
- Se presenta el Sprint Backlog del equipo.
- Se recuerda el objetivo del sprint para mantener el foco.

## Sincronización del equipo
Cada integrante responde de manera breve y concreta:
1. Compromiso anterior
   ¿Logré cumplir con el objetivo del día anterior? (Sí / No)
   Si la respuesta es No, mencionar los riesgos o impedimentos que limitaron el avance.
2. Objetivo del día
   ¿Cuál es mi objetivo de hoy y cómo contribuye al objetivo del sprint?
3. Impedimentos
   ¿Tengo alguna situación que me impida avanzar hacia el resultado esperado?
   Si existe un impedimento, debe estar registrado en Jira usando la plantilla de impedimentos.
4. Necesidad de apoyo
   ¿Necesito ayuda para continuar con mi trabajo?
   Identificar claramente a quién: PO, LT, Scrum Master o compañero del equipo. (Seguir la guía de pedidos efectivos)

---
# 2026-09-18 Daily Discovery Team
## 1. Compromiso anterior
**¿Logré cumplir con el objetivo del día anterior?** No
- Item 1

## 2. Objetivo del día
- Item 1

## 3. Impedimentos
Ninguno identificado

## 4. Necesidad de apoyo
No requiero apoyo en este momento

---
# 2026-09-17 Daily Discovery Team
## 1. Compromiso anterior
**¿Logré cumplir con el objetivo del día anterior?** No
- Realizar la revisión a los comentarios de las arquitecturas

## 2. Objetivo del día
- Responder comentarios o realizar ajustes según corresponda.
- Nuevo endpoint para ejecución de transacciones mediante ACTIONS

## 3. Impedimentos
Ninguno identificado

## 4. Necesidad de apoyo
No requiero apoyo en este momento

## 5. Otros temas
- Se genera Run Book por parte de Jairo Duarte
  - Pendiente socialización en comit
---
# 2026-03-23 Daily Discovery Team

## 1. Compromiso anterior
**¿Logré cumplir con el objetivo del día anterior?** No

El objetivo del viernes era alcanzar un 80% del diseño de arquitectura para el orquestador final de contraseña. Se logró avanzar entre un 40%-45%, quedando en la finalización del diagrama de despliegue. Las razones del desvío fueron:

- **Revisión de problemática de headers:** En horas de la mañana se revisó en conjunto con el equipo de desarrollo una problemática en el manejo de headers. Mediante revisión de código se identificó que en la implementación de los microservicios se estaba realizando una transformación a un mapa de strings, generando la pérdida del soporte de case-insensitive para los headers de acuerdo a la especificación HTTP (RFC 9110). Una vez identificada la causa se delegó al equipo de desarrollo la solución.
- **Creación de issues en Jira:** Se generaron 9 issues de tipo Tarea Técnica para el equipo de desarrollo cubriendo: la solución del soporte de headers como case-insensitive y el aseguramiento en los 9 desarrollos de agregar todos los headers definidos en el estándar con las validaciones de obligatoriedad (incluyendo obligatoriedad condicional).
- **Verificación de corrección y ajuste de arquitectura:** En la tarde se verificó la corrección de case-insensitive en uno de los repositorios. Adicionalmente se modificó la arquitectura NT-27346_ValidarChallengeEntrust para contemplar un header requerido por capa de integración en las APIs orquestadas para validar el challenge.

## 2. Objetivo del día
- Dar foco en la mañana a avanzar en el diseño de arquitectura del orquestador final de contraseña (finalizar diagrama de despliegue).
- Modificar la arquitectura del modelo de base de datos para soportar el contador utilizado para calcular el flag que permite indicar al front si se visualiza o no la modal de afiliación token, y definir mediante el patrón globe-style cómo se debe mantener la información en la cache.

### Riesgo identificado
El avance en la tarde se verá impactado por reunión de planning y reunión de refinamiento que ocupan prácticamente toda la tarde.

## 3. Impedimentos
Ninguno identificado

## 4. Necesidad de apoyo
No requiero apoyo en este momento

---
# 2026-01-29 Daily Discovery Team

## 1. Compromiso anterior
**¿Logré cumplir con el objetivo del día anterior?** Sí

### Avances realizados:
- Redefinición de la plantilla de documentación completada
- Base del diagrama de contexto de BFF establecida
- Diagrama de despliegue estructurado (orientado al diseño de cada BFF desde API Management hacia abajo)
- Diagrama de secuencia finalizado basado en:
  - Arquetipo imperative
  - Librería de crosscutting modularizada

## 2. Objetivo del día
- Finalizar la especificación de la firma del servicio de creación y actualización de perfiles de usuario en Braze
- Dar inicio al siguiente diseño de arquitectura

## 3. Impedimentos
Ninguno identificado

## 4. Necesidad de apoyo
No requiero apoyo en este momento

---
# 2026-01-28 Daily Discovery Team


---
# 2026-01-28 Daily Discovery Team

- Diagrama de despliegue del BFF.
  - <p style="color: red;">Validar valor agregado de mantener el diagrama de infraestructura en cada diseño.</p>

    - Desventajas:
       - Alta redundancia: La mayoría de desarrollos comparten la misma infraestructura base (AKS, APIM, Key Vault, etc.)
       - Mantenimiento costoso: Cada cambio en infraestructura requiere actualizar múltiples documentos
       - Ruido documental: Dificulta identificar qué es realmente específico de cada desarrollo
    - Tal vez sea mejor tener un diagrama de despliegue o enfocado mas a la arquitectura propia del microservicio en donde se de foco a:
      - Mapear artefactos de software (ejecutables, librerías, contenedores) a nodos físicos (servidores, clusters, dispositivos)
      - Mostrar configuraciones específicas de despliegue por ambiente
      - Documentar dependencias de infraestructura particulares de cada desarrollo
      - Guiar el proceso de CI/CD y despliegue

- Diagrama de Secuencia.
---

- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test
- Test



