# Puntajes:
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

## Priorización de atributos de calidad y trade-offs en arquitectura de software
Prioriza los atributos de calidad según los requerimientos de negocio, entendiendo los trade-offs realizados durante la construcción de arquitecturas en el proyecto y define arquitecturas de software que reflejan estas priorizaciones usando patrones, estilos y tácticas de arquitectura.
- Valoración Actual: (3)
- Nueva Valoración: (3)

### Notas del valorador
Comprende a nivel conceptual los atributos de calidad y empieza a ser consciente de cómo estos se relacionan con las decisiones de arquitectura. Se recomienda formalizar la documentación de trade-offs utilizando ADRs (Architecture Decision Records) y explorar el MCP de Arquitectura de Pragma para validar y documentar las decisiones que ya está tomando en el proyecto.


## Diseño estratégico de arquitectura
Ha diseñado Blueprint de arquitectura
- Valoración Actual: (4)
- Nueva Valoración: (4)

### Notas del valorador


---

# Observabilidad

## Pilares de monitoreo: controla y optimiza métricas y registros empresariales
Entiende la importancia de monitorear y controlar las métricas, eventos, registros y rastreos relevantes para el negocio, para ello ha usado al menos 3 pilares de monitoreo (monitoreo de infraestructura, gestión de logs, APM, RUM, sintético, seguridad, auditoría transaccional, costos).
- Valoración Actual: (3)
- Nueva Valoración: (4)

### Notas del valorador
Ha trabajado con pilares de monitoreo en proyectos reales: gestión de logs, APM con tableros de Grafana, instrumentación con OpenTelemetry, monitoreo de infraestructura con Prometheus/Grafana, y monitoreo sintético con Dynatrace para validar disponibilidad de flujos funcionales. Se recomienda profundizar en los pilares de FinOps/costos, RUM, seguridad y auditoría transaccional.


---

# Seguridad

## Uso efectivo del cifrado simétrico y asimétrico
Entiende, identifica y utiliza según sea necesario el cifrado simétrico y asimétrico, comprendiendo claramente sus diferencias y cuando debe usarse cada uno.
- Valoración Actual: (3)
- Nueva Valoración: (3)

### Notas del valorador
Comprende a nivel conceptual las diferencias entre cifrado simétrico y asimétrico, pero no ha tenido oportunidad de aplicarlo en decisiones de arquitectura. Se recomienda buscar oportunidades donde deba evaluar y seleccionar el tipo de cifrado adecuado según el caso de uso (datos en reposo, datos en tránsito, intercambio de claves, firmas digitales).


## Implementación de principios de seguridad en arquitectura de información y acceso
Ha aplicado en una arquitectura las principales propiedades de la seguridad de información y acceso (integridad, confidencialidad, autorización y autenticación)
- Valoración Actual: (3)
- Nueva Valoración: (4)

### Notas del valorador
Ha participado activamente en la implementación de estrategias de autenticación. Identificó la ausencia de autenticación en los microservicios y lideró la implementación inicial con Cognito, incluyendo la integración con Istio. Posteriormente participó en la migración a Entra ID. Demuestra conciencia de seguridad al cuestionar activamente las definiciones en nuevas integraciones con sistemas externos.


---

# Infraestructura

## Fundamentos de arquitectura de redes para tomar decisiones efectivas en tecnología e infraestructura
Diseña las decisiones de arquitectura que se reflejan en tecnologías / componentes de infraestructura, segmenta claramente las redes (privadas, públicas) y comprende las definiciones de conceptos básicos de redes (CDN, IP, DNS, TCP, UDP, Firewall, VPN, Mascara de red, broadcast, proxy)
- Valoración Actual: (2)
- Nueva Valoración: (2)

### Notas del valorador
Se recomienda revisar la documentación de Alejandría sobre topología de red y los módulos de Terraform de Cloud Ops, así como la charla del chapter sobre arquitectura de red en AWS, para profundizar en los fundamentos y buscar oportunidades de participar en definiciones de arquitectura de infraestructura.


## Optimización de la distribución de tráfico
Ha usado API Gateway y balancedores de aplicaciones o de red
- Valoración Actual: (2)
- Nueva Valoración: (3)

### Notas del valorador
Ha trabajado con la configuración de Istio como ingress controller y comprende la importancia del balanceador de carga como punto de entrada para controlar el tráfico. Se recomienda profundizar en las diferencias entre balanceadores de aplicación (ALB) y de red (NLB), y cómo se relacionan con atributos de calidad como escalabilidad y alta disponibilidad.


---

# Documentación

## Diseño de arquitectura con comunicación efectiva y documentación de API
Comunica de manera adecuada y diseña arquitectura que incluye sistemas, personas, componentes, contenedores y relaciones a diferentes públicos mediante diagramas semi-formales (UML o C4) y ha construído la documentación de API sea a nivel web, mobile, backend o integración.
- Valoración Actual: (4)
- Nueva Valoración: (4)

### Notas del valorador
Genera documentación de arquitectura de manera proactiva. Como estrategia de cierre de brechas, se recomienda ir explorando las vistas del SAD que apliquen según cada competencia técnica a fortalecer (vista de información, vista de infraestructura, vista operacional, entre otras) e interactuar con el MCP de Arquitectura de Pragma para validar y complementar los entregables.


---

# Desarrollo

## Implementación efectiva de patrones de diseño GoF o Patrones de mobile
Ha aplicado correctamente los patrones de diseño GoF (creaciones, estructurales y comportamentales) o patrones relacionados con mobile cómo BLoC o Frontend cómo SPA, Redux
- Valoración Actual: (4)
- Nueva Valoración: (4)

### Notas del valorador


## Utilización de protocolos de integración en desarrollo de software
Ha usado al menos 1 protocolo de integración cómo RESTFUL, Grpc o RSocket
- Valoración Actual: (4)
- Nueva Valoración: (4)

### Notas del valorador


---

# DevSecOps

## Práctica de integración continua con pruebas unitarias y automatización de build
Ha aplicado la práctica de integración continua (Continous Integration) haciendo pruebas unitarias adecuadas, test de cobertura, el build de los artefactos requeridos de forma automática y haciendo uso de herramientas de CI.
- Valoración Actual: (2)
- Nueva Valoración: (4)

### Notas del valorador
Ha diseñado, configurado y documentado pipelines de integración y despliegue continuo para múltiples repositorios. Evidencia comprensión del ciclo completo: pruebas unitarias con validación de cobertura, pruebas de mutación, análisis de licenciamiento, escaneo de seguridad (DevSecOps), generación de artefactos, publicación y despliegue a EKS. Propuso e implementó una estrategia de rollback versionando artefactos para recuperación rápida.


---

# Arquitectura de Datos

## Arquitectura de Datos
Da lineamientos de todo el ciclo de vida de la información, qué y cómo deben ser capturados los datos (Captura), dónde y por cuánto tiempo debe permanecer (almacenamiento), cómo debe darse acceso, desde qué recursos y a qué fuentes (gestión), cómo debe visualizarse y presentarse la información a negocio (publicación), cuál debe ser el procedimiento para depurar la información (disposición)
- Valoración Actual: (0)
- Nueva Valoración: (1)

### Notas del valorador
Se recomienda profundizar en el ciclo de vida de la información (captura, almacenamiento, gestión, publicación, disposición) y buscar oportunidades para documentar los dominios de información del proyecto como parte de una vista de información.


## Aplicación de integridad de las transacciones en bases de datos
Ha aplicado (ACID)
- Valoración Actual: (2)
- Nueva Valoración: (2)

### Notas del valorador
Se recomienda complementar el estudio de arquitectura de datos con el teorema CAP, BASE y ACID, y buscar oportunidades para participar en decisiones de selección de motor de base de datos según los requerimientos de consistencia del sistema.


## Implementación de bases de datos SQL y NoSQL.
Ha implementado al menos 1 tipo de bases de datos SQL y 1 NoSQL
- Valoración Actual: (2)
- Nueva Valoración: (2)

### Notas del valorador
Se recomienda ampliar la experiencia práctica con bases de datos NoSQL y participar en decisiones de selección de motor de base de datos según los requerimientos del sistema.

---

# Notas resultado general de la Review

# Líder del Chapter de Arquitectura
Al final, es importante recomendaciones que veo, pero igual mira si son pertinentes:
- Certificación AWS Arquitectura
- Documentar lo que le pueda faltar de la solución completa, teniendo como base lo que debería tener documentado en una arquitectura de solución (Descripción General de la Solución, Propósito y Alcance de la Solución, Restricciones de la Solución, Suposiciones, Riesgos del proyecto, Contexto de Negocio, Capacidades del Negocio, Business Model Canvas / Value Proposition, KPIs, Stakeholders, Vista Funcional, Dominios y Plan de Arquitectura de Servicio, Dominios Core, Dominios Soporte/Dominios Genéricos, Service Blueprint, Características de Arquitectura (Atributos de Calidad), Key ADR (Registros de Decisiones de Arquitectura), Vistas de Arquitectura, Vista de Contexto (Nivel 1), Vista de Información (Datos), Vista de Integración, Vista de Infraestructura, Vista de Despliegue, Vista Operacional, Vista de Seguridad, Vista de Aplicación (Nivel 2/3 - Componentes), Vista de Procesos del Sistema, Gestión de Deuda Técnica, Lenguaje Ubicuo (Glosario)), claro documentar lo necesario y que aplique y sea valioso. Ver: https://alejandria.pragma.co/es/private/conocimiento-aplicado/Documentacion/kc-cc/SAD
- Importante documentar las decisiones, que entienda cómo se tomaron y por que, y las que le ha tocado tomar en el proyecto como LT
- Observabilidad + Seguridad de la información (Confidencialidad / Data sensible)
En resumen Jaime está llevando lo que puede desde su rol de LT, pero tiene madera, avanza llevando a la práctica todo lo que va aprendiendo y hasta donde lo permita bancolombia

# Notas resultado Final de la Review

## Notas del Chapter de Arquitectura

Jaime ha demostrado crecimiento y cierre de brechas desde su rol de líder técnico que desempeña actualmente en la cuenta, aplicando prácticas de arquitectura que le han permitido fortalecer competencias del rol de arquitecto. Se destaca:
- DevSecOps: Diseñó pipelines de CI/CD completos incluyendo pruebas, cobertura, escaneo de seguridad, despliegue a EKS y propuso estrategia de rollback.
- Observabilidad: Ha trabajado con gestión de logs, APM, OpenTelemetry, monitoreo de infraestructura y sintético.
- Seguridad: Participó activamente en la propuesta e implementación de autenticación con Cognito/Istio y migración a Entra ID.

Oportunidades de mejora y recomendaciones:
- Explorar las vistas del SAD según cada competencia a fortalecer del mapa de crecimiento:
    - Vista de Información (arquitectura de datos, ciclo de vida de la información)
    - Vista de Infraestructura (topología de red, balanceadores ALB/NLB)
    - Vista Operacional (pilares de observabilidad: FinOps/costos, RUM, seguridad, auditoría transaccional)
    - Vista de Seguridad (cifrado según caso de uso)
    - Key ADR (formalizar decisiones de arquitectura)
- Utilizar el MCP de Arquitectura de Pragma para generar, validar y complementar los entregables.
- Estudiar teorema CAP, BASE y ACID para decisiones de selección de base de datos.
- Se recomienda presentar la certificación AWS Solutions Architect - Associate.

Recursos recomendados:
- SAD: https://alejandria.pragma.co/es/private/conocimiento-aplicado/Documentacion/kc-cc/SAD
- Frameworks de madurez: https://alejandria.pragma.co/es/private/Procesos/Proceso-Soluci%C3%B3n-Problemas/frameworks-madurez
- MCP Arquitectura: https://alejandria.pragma.co/es/private/conocimiento-aplicado/inteligencia-artificial/kc-cc/frameworks-llms/sopp/mcps/architect-augmented-ai
- Topología de red en Alejandría: https://alejandria.pragma.co/es/private/conocimiento-aplicado/infraestructura/kc-cc/networking/linea-base-networking
