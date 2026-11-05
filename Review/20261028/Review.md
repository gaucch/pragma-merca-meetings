# Información General
- **Valorado:** David Julian
- **Evaluador actual:** Gabriel Andrés Useche Zaldua (2026-10-28)
- **Evaluador anterior:** César Augusto Moncada Calderón (2026-04-16)
- **Chapter:** Arquitectura | **Especialidad:** Soluciones
- **Cuenta:** Ficosha | **Proyecto:** Ficosha - Capa Integración
- **Rol en cuenta:** Arquitecto de Soluciones | **Experiencia en el rol:** 5 años
- **Seniority evaluado:** Advanced
- **Score anterior:** 3.3 (L2) | **Score actual:** 3.5

> **Nota de escala:** La Valoración Anterior corresponde al assessment de abril 2026 con escala Technical 1-5 (1=No lo ha oído, 2=Conoce teóricamente, 3=Lo ha hecho esporádicamente/laboratorio, 4=Buen dominio, 5=Referente). La Nueva Valoración usa la escala Technical from 0 con descripción detallada en la sección de puntajes.

---

# Puntajes (escala nueva — Nueva Valoración):
- (0) Pendiente por valorar
- (0) Nulo o superficial: No tiene idea o el conocimiento es superficial.
- (1) Conceptual: Ha estudiado y comprende a nivel conceptual.
- (2) Explorativo: Comprende conceptualmente y lo ha aplicado, pero sólo en entornos de laboratorio o simulados.
- (3) Práctico esporádico o desactualizado: Lo practica en proyectos reales de manera esporádica, recién comenzó a hacerlo consistentemente o dejó de hacerlo hace más de 2 años.
- (3) Aplicación constante con brechas: la persona implementa de forma consistente pero no tiene el conocimiento conceptual adecuado o incurre en malas prácticas
- (4) Dominio y aplicación consistente: Lo implementa de forma repetida y consistente en proyectos reales, demostrando un sólido dominio. O ya lo domina y pasó a hacerlo de forma esporádica
- (5) Referente y habilitador: Es reconocido como un referente y habilita a otros en su aplicación

---

# Diseño de arquitectura

## Metodologías y frameworks para diseño y evaluación de arquitectura de software
Entiende, aplica y sigue una metodología para el diseño de Arquitectura, toma decisiones de arquitectura y acompaña su salida a producción, comprende y aplica metodologías y framework como ADD, DDD y métodos de evaluación como ATAM y SAAM, también sabe usar event storming.
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (3) Práctico esporádico o desactualizado

### Notas del valorador anterior (César Moncada - Abril 2026)
Profundizar en DDD combinando diseño estratégico y táctico para gestionar software complejo. Profundizar en ATAM y como se lleva a fitness functions de arquitectura, y herramientas que puedan automatizarlo en producción.

### Notas del valorador
Respeta los principios de DDD en el día a día apoyado en el estándar BIAN adoptado por el banco. Cada decisión de nueva integración o servicio incluye un análisis de tradeoffs. Se recomienda apoyarse en el MCP Architect Augmented AI de Pragma, que implementa ADD 3.0 con flujo guiado incluyendo DDD, ASRs, estilos y tácticas, generación de SAD y ADRs, y validación de la arquitectura contra el Framework Pragma. Complementar con fitness functions usando ArchUnit junto al Chapter DevSecOps.


## Aplicación de estilos y tácticas de arquitectura en diversos contextos, incluyendo cloud
Identifica claramente los estilos y tácticas de arquitectura y los ha aplicado en varios contextos, lo cuál debe incluir la nube.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador anterior (César Moncada - Abril 2026)
David en el proyecto actual en Ficosha ha estado trabajando con diferentes estilos y tácticas en AWS.

### Notas del valorador


## Implementación de arquitecturas modernas y escalables con EDA, microservicios y kubernetes
Comprende y aplica EDA, patrones de microservicios, kubernetes y ha aplicado sistemas de procesamiento paralelo.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador anterior (César Moncada - Abril 2026)
David en el proyecto actual en Ficosha ha estado trabajando con diferentes estilos como: EDA, patrones de microservicios, kubernetes.

### Notas del valorador


## Normativas y restricciones sectoriales claves para el cumplimiento empresarial
Conoce la normatividad y restricciones del sector en el que trabaja.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador


## Optimización de integración con sistemas externos para objetivos de negocio
Analiza los puntos de integración con sistemas externos o Third-party solutions para aplicar el mecanismo de integración adecuado a la situación, garantizando la compatibilidad y el cumplimiento de los objetivos de negocio.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador


## Gestión y versionamiento efectivo de APIs
Aplica mecanismos para la gestión y versionamiento de APIs.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador


---

# Observabilidad

## Técnicas de monitoreo y registro para proyectos, implementación integral y pilares clave
Ha implementado en algún proyecto métricas, eventos, registros y rastreos relevantes para negocio, adicional 4 pilares de monitoreo (monitoreo de infraestructura, gestión de logs, APM, RUM, sintético, seguridad, auditoría transaccional, costos).
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (3) Práctico esporádico o desactualizado

### Notas del valorador anterior (César Moncada - Abril 2026)
David maneja monitoreo de infraestructura, gestión de logs. Profundizar en APM arquitecturas de referencia para llevarlo a un diseño desde cero en la vista operacional. Profundizar en arquitectura frugal (Costos en diseño, verificación y optimización.). Profundizar en el uso de framework de observabilidad, framework de FinOps de Pragma.

### Notas del valorador
El proyecto cuenta con monitoreo de infraestructura y gestión de logs con CloudWatch y Dynatrace como línea base. Promueve y documenta en el MCP del proyecto los lineamientos de enmascarado de datos sensibles en logs para que el equipo de desarrollo los aplique. Existe configuración de dashboards para el equipo de soporte, aunque no los ha operado directamente. No ha alcanzado los 4 pilares requeridos: RUM no aplica por ser capa media sin frontend, pero faltan APM a nivel de aplicación, FinOps/costos y auditoría transaccional de negocio. Se recomienda revisar el framework de madurez de observabilidad en Alejandría y ejecutar el MCP CloudOps AI de Pragma para evaluar la arquitectura contra el framework de observabilidad.


## Importancia de los KPIs en la salud del proyecto
Comprende la importancia de definir los Key Performance Indicators (KPIs) y su relación con la salud del proyecto.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador


## Optimización de la observabilidad con servicios de IA
Ha aplicado servicios de IA para mejorar los procesos de observabilidad y automatizar actualizaciones y mejoras de observabilidad e infraestructura.
- Valoración Anterior: (0) No evaluado en assessment anterior (era competencia de Master)
- Nueva Valoración: (1) Conceptual

### Notas del valorador
Esta competencia no ha sido abordada en el proyecto. El MCP CloudOps AI de Pragma incluye herramientas de evaluación de observabilidad cloud contra el framework de Pragma. Se recomienda ejecutarlo sobre la arquitectura de Ficosha como primer paso concreto para identificar brechas e iniciar la aplicación de IA en los procesos de observabilidad.


---

# Seguridad

## Mitigación de riesgos de seguridad en arquitecturas: Identificación, gestión y tácticas
Ha diseñado arquitecturas que mitiguen los riesgos de seguridad a los que se enfrenta (al menos los más importantes OWASP Top 10 y STRIDE) y ha usado tácticas para minimizarlos en la arquitectura de solución y aplicación. Identifica los riesgos y los gestiona de manera oportuna.
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (3) Aplicación constante con brechas

### Notas del valorador anterior (César Moncada - Abril 2026)
Profundizar en OWASP Top 10, y los frameworks de OWASP declarados en el framework de seguridad de Pragma para que siempre se tengan en cuenta desde los diseños de arquitectura.

### Notas del valorador
Aplica prácticas de seguridad de forma consistente en el proyecto: gestión de identidad con Cognito OAuth 2.0, cifrado en reposo y en tránsito, protección de datos sensibles en logs y gestión centralizada de credenciales. Genera propuestas de gobierno de seguridad para el banco. La brecha es que estas prácticas no parten explícitamente de OWASP Top 10 o STRIDE como marco de referencia desde el diseño. Se recomienda revisar el framework de seguridad de Pragma y usar el MCP Architect Augmented AI para validar la arquitectura de Ficosha identificando hallazgos de seguridad por criticidad, complementándolo con el MCP SAST AI para la validación OWASP Top 10 a nivel de código y pipelines.


---

# Infraestructura

## Optimizando atributos de calidad según el Well Architected Framework
Define claramente estrategias de infraestructura a nivel de OnPremises, Serverless, IaaS, PaaS, SaaS para mejorar los atributos de calidad que expresa el Well Architected Framework.
- Valoración Anterior: (3) Lo ha hecho esporádicamente / laboratorio
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador anterior (César Moncada - Abril 2026)
Ejecutar un WAR de forma experimental para entender su uso, y qué es importante de esas reviews. Con el fin de interiorizar para reflejarlo siempre en los diseños de arquitectura.

### Notas del valorador
Aplica consideraciones del Well Architected Framework al sustentar decisiones de arquitectura, especialmente en costo y confiabilidad: evalúa el impacto económico de nuevos servicios usando la calculadora de AWS (POC de GuardDuty), y levanta riesgos de estabilidad como la propuesta de ambiente UAT para proteger las integraciones con terceros. La aplicación es implícita y no parte de un proceso estructurado de WAR. Se recomienda ejecutar un WAR experimental sobre la arquitectura actual de Ficosha para documentar formalmente las decisiones y oportunidades de mejora.


## Implementación de infraestructura como código en la nube
Ha implementado IaC de al menos dos servicios de alguna nube.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (3) Práctico esporádico o desactualizado

### Notas del valorador anterior (César Moncada - Abril 2026)
David está tomando todo el tema de IaC desde Terraform.

### Notas del valorador
Coordina con el equipo de infraestructura la provisión de componentes en AWS, genera diagramas de componentes y da lineamientos técnicos para que el equipo de infra construya el código Terraform. Está estudiando la certificación de Terraform por iniciativa propia y comprende la estructura de un plan. La brecha es que no escribe ni ejecuta código IaC directamente en el proyecto. Se recomienda explorar activamente los repositorios Terraform del proyecto, revisar la ejecución de al menos dos pipelines de aprovisionamiento, y proponer mejoras concretas en la IaC existente apoyándose en lo aprendido para la certificación.


---

# Documentación

## Generación de artefactos y comunicación efectiva en presentaciones de negocio
Estructura y genera artefactos a través de presentaciones de negocio y técnicas de presentación (presentaciones efectivas, AIDA, Modelos de persuasión) que permitan identificar claramente las decisiones, vistas y diseño general del sistema. Tiene claro cómo documentar para satisfacer los puntos de vista con vistas, modelos y perspectivas y/o C4. Su comunicación y documentación es clara para cualquier Stakeholder.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador anterior (César Moncada - Abril 2026)
David en Ficosha está usando C4 en sus tres primeros niveles. Y ha trabajado en la diagramación de despliegue en AWS.

### Notas del valorador


---

# Desarrollo

## Guía para liderar desarrollos con microservicios y programación reactiva
Desarrolla o lidera desarrollos con patrones de microservicios explícitos, microfrontend (apps o web), comprende el manifiesto reactivo y los principios básicos de programación reactiva (responsivo, extensible, mantenible, resiliente, elástico, orientado a mensajes), patrón CQRS, patrones y mecanismos de integración.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador


## Experiencia en desarrollo y calidad de código para proyectos web y móviles
Ha aplicado lenguajes de programación, revisiones de código asegurando la calidad del proyecto, crea y ajusta los estándares de desarrollo del proyecto conforme sea necesario ya sea (Integración o Backend y Frontend Web o mobile) o (Frontend y Mobile).
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (3) Práctico esporádico o desactualizado

### Notas del valorador anterior (César Moncada - Abril 2026)
Profundizar en arquitectura front y mobile.

### Notas del valorador
El proyecto cuenta con SonarCube y Fluid Attacks para análisis de código. Define estándares de desarrollo para el equipo: control de mensajes de error y gestión de dependencias. Apoya al equipo en la resolución de dudas técnicas de código y genera especificaciones detalladas que guían la implementación. No tiene experiencia en arquitecturas frontend o mobile. Se recomienda profundizar en arquitectura front y mobile.


---

# DevSecOps

## Optimización de entrega y despliegue mediante estrategias de branching y feature toggle
Ha aplicado entrega continua (Continous Delivery), estrategias de branching, estrategias de despliegue o técnicas como feature toggle en sus proyectos, lo que facilita la entrega y el despliegue de componentes.
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (3) Aplicación constante con brechas

### Notas del valorador anterior (César Moncada - Abril 2026)
Profundizar en modelamiento de soluciones de DevSecOps.

### Notas del valorador
El proyecto cuenta con entrega continua del ambiente de desarrollo a stage, con aprobación manual para paso a producción a través de GitLab. Define los lineamientos y necesidades para la creación de nuevos pipelines, con el equipo de infraestructura ejecutando la implementación. No ha modelado soluciones DevSecOps desde el diseño de arquitectura. Se recomienda incluir las vistas de despliegue y operacional en los diseños de arquitectura, y apoyarse en el MCP CloudOps AI de Pragma para la gobernanza de IaC.


## Análisis exhaustivo de seguridad en el desarrollo de software y la infraestructura como código
Comprende automatización de escaneo de dependencias, análisis de contenedores, escaneo de secretos, análisis dinámico de seguridad, lo anterior incluyendo IaC.
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (3) Aplicación constante con brechas

### Notas del valorador anterior (César Moncada - Abril 2026)
Profundizar en modelamiento de soluciones de DevSecOps.

### Notas del valorador
El proyecto cuenta con SonarCube, Fluid Attacks y Dependency Track para análisis de código, y aplica Secret Manager como estándar para gestión de credenciales. No ha modelado desde el diseño de arquitectura la cobertura completa de seguridad en el ciclo de desarrollo: escaneo de contenedores, secret scanning y seguridad en IaC. Se recomienda adoptar el MCP SAST AI de Pragma, que incluye Semgrep, Checkov para IaC, Trivy y OSV para contenedores y dependencias, y Detect-secrets, todo integrable en los asistentes de IA del equipo.


---

# Arquitectura de Datos

## Implementación de sistemas distribuidos con patrones de caché
Ha aplicado sistemas de datos distribuidos, patrones de Cache.
- Valoración Anterior: (4) Buen dominio del tema
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador


## Disponibilidad BASE y teorema CAP en bases de datos para perspectivas críticas
Ha aplicado disponibilidad (BASE) ante fallas de las particiones y (Teorema CAP) en bases de datos.
- Valoración Anterior: (2) Conoce teóricamente, sin práctica
- Nueva Valoración: (4) Dominio y aplicación consistente

### Notas del valorador anterior (César Moncada - Abril 2026)
Profundizar en BASE y ACID y al final eso como se ve reflejado en las reglas que defino en el diseño arquitectura.

### Notas del valorador
Aplica el teorema CAP y conceptos de consistencia con criterio técnico. Usa Redis para garantizar que cada evento crítico (como un desembolso de préstamo) se procese exactamente una vez, rechazando duplicados. En la funcionalidad de puntos de lealtad implementó invalidación de caché automática al detectar una redención o reversión, garantizando que el cliente siempre vea el saldo actualizado. Aplica transacciones atómicas (ACID) para garantizar consistencia en escrituras de múltiples tablas del módulo de gestión documental.


---

# Team Pragmapowers

## TeamPP - No trago entero (nivel 4)
4 - Demuestra un desarrollo fuerte y natural de los comportamientos del TeamPP "No trago entero".
- Valoración Anterior: (4) Tiene valoración y su resultado es el instanciado en tu mapa o superior
- Nueva Valoración: (4) Tiene valoración y su resultado es el instanciado en tu mapa o superior

### Notas del valorador


## TeamPP - Comunicación efectiva (nivel 4)
4 - Demuestra un desarrollo fuerte y natural de los comportamientos del TeamPP "Comunicación efectiva".
- Valoración Anterior: (4) Tiene valoración y su resultado es el instanciado en tu mapa o superior
- Nueva Valoración: (4) Tiene valoración y su resultado es el instanciado en tu mapa o superior

### Notas del valorador


## TeamPP - Pilotos de nuestro destino (nivel 4)
4 - Demuestra un desarrollo fuerte y natural de los comportamientos del TeamPP "Pilotos de nuestro destino".
- Valoración Anterior: (4) Tiene valoración y su resultado es el instanciado en tu mapa o superior
- Nueva Valoración: (4) Tiene valoración y su resultado es el instanciado en tu mapa o superior

### Notas del valorador


---

# Notas resultado general de la Review

## Nota del valorador anterior (César Moncada - Abril 2026)
David Julian ha cerrado varias brechas, se recomienda continuar trabajando en los siguientes temas:

- Profundizar en DDD combinando diseño estratégico y táctico para gestionar software complejo. Profundizar en ATAM y como se lleva a fitness functions de arquitectura, y herramientas que puedan automatizarlo en producción.
- Profundizar en APM arquitecturas de referencia para llevarlo a un diseño desde cero en la vista operacional. Profundizar en arquitectura frugal (Costos en diseño, verificación y optimización.). Profundizar en el uso de framework de observabilidad, framework de FinOps de Pragma.
- Profundizar en OWASP Top 10, y los frameworks de OWASP declarados en el framework de seguridad de Pragma para que siempre se tengan en cuenta desde los diseños de arquitectura.
- Ejecutar un WAR de forma experimental para entender su uso, y qué es importante de esas reviews. Con el fin de interiorizar para reflejarlo siempre en los diseños de arquitectura.
- Profundizar en arquitectura front y mobile.
- Profundizar en modelamiento de soluciones de DevSecOps.
- Profundizar en BASE y ACID y al final eso como se ve reflejado en las reglas que defino en el diseño arquitectura.

Y profundiza en todo esto, para llevarlo a tu conocimiento y entiendas todo lo que tenemos ya desde Pragma:

- Frameworks de madurez: https://alejandria.pragma.co/es/private/Procesos/Proceso-Soluci%C3%B3n-Problemas/frameworks-madurez
- Instructivo Diseño Arquitectura: https://drive.google.com/file/d/1x9397OVNURROrVCfBDhxXwqJ7Bhu0dKI/view?usp=sharing
- Arquitecturas de referencia: https://alejandria.pragma.co/es/private/Procesos/Proceso-Soluci%C3%B3n-Problemas/Arquitecturas-Referencia
- IA Generativa Pragma: https://alejandria.pragma.co/es/private/conocimiento-aplicado/inteligencia-artificial/kc-cc/gen-ai

Trabajar en los logros de Pragma, ya que no ha realizado ningún punto hasta el momento.

**Resultado:** Aprobado _(Gina María Quintero Arredondo - Abril 2026)_

## Líder del Chapter de Arquitectura


---

# Notas resultado Final de la Review

## Notas del Chapter de Arquitectura

Julián ha demostrado crecimiento y cierre de brechas en esta review. Se destaca:
- BASE/CAP y ACID: cerró la brecha identificada en la review anterior con aplicaciones concretas — Redis para idempotencia de eventos, invalidación de caché en puntos de lealtad y transacciones atómicas en el módulo de gestión documental.
- Well Architected Framework: evalúa costos y confiabilidad desde el diseño usando la calculadora de AWS y levanta riesgos de estabilidad en el proyecto.
- Seguridad: aplica prácticas consistentes de gestión de identidad, cifrado y protección de datos.

Oportunidades de mejora y recomendaciones:
- Formalizar el uso de ADD, DDD y ATAM apoyándose en el MCP Architect Augmented AI de Pragma.
- Completar los pilares de observabilidad pendientes (APM, FinOps, auditoría transaccional) usando el MCP CloudOps AI y el agente Analista FinOps.
- Incorporar OWASP Top 10 y STRIDE desde el diseño de arquitectura, apoyándose en el MCP SAST AI.
- Incluir las vistas de despliegue y operacional en los diseños de arquitectura del proyecto.
- Profundizar en arquitectura front y mobile.
- Se recomienda obtener la certificación AWS Solutions Architect.

Recursos recomendados:
- MCP Architect Augmented AI: https://alejandria.pragma.co/es/private/conocimiento-aplicado/inteligencia-artificial/kc-cc/frameworks-llms/sopp/mcps/architect-augmented-ai
- MCP CloudOps AI: https://alejandria.pragma.co/es/private/conocimiento-aplicado/inteligencia-artificial/kc-cc/frameworks-llms/sopp/mcps/cloudops-ai
- MCP SAST AI: https://alejandria.pragma.co/es/private/conocimiento-aplicado/inteligencia-artificial/kc-cc/frameworks-llms/sopp/mcps/sast-ai
- Frameworks de madurez (observabilidad y seguridad): https://alejandria.pragma.co/es/private/Procesos/Proceso-Soluci%C3%B3n-Problemas/frameworks-madurez
