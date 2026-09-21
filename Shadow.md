# Shadow 30-ABR-2026

## Review de crecimiento
Explicación de la sesión.  
Alcance del espacio, cada 6 meses.

Chequeo Team Pragmapowers OK

- Capa de Integración Octubre 2024 - Noviembre 2025
- Canales Digitales Enero 2026
PN
PJ
Backoffice PN y PJ

## Evaluar Brechas de Crecimiento

## Introducción
Re-estimación preventa.
Carlos Participo en la preventa, premmisas.
- Inicio impecable
- Rehuso, ya el cliente pierde credibilidad.
  - Evitar desde preventa estimar rehúso.
- Estimación Jurídico
  - Mapeo de riesgos
  - Documentación de decisiones
  - Argumentos de disminución de porcentaje de rehúso
  - GAP de 600mil dolares en el proyecto, por rehúso.
  - Actualmente no se ha firmado contrato.
  - Inicio impecable siempre se debe tener firmado el contrato.



- MVP Agosto
- Release Enero


- Menú cambia en mobile
  - afecta premisa de rehúso.
  - Navegador mobile, no es totalmente responsive

- Equipo de experiencia de usuario




---

### Diseño de Arquitectura
Deuda técnica --> Documentación de Arquitectura  
Proceso de diseño
- Documentar el Wiki del cliente
- No se tiene SAD, pero si definiciones y decisiones de arquitectura.
- Estándares de arquitectura
- Fecha de entrega en 2 semanas para entrega de SAD.
- No fue lo suficientemente contundente.
- SAD falta refinar y entregar.
  - Se visualiza adelantos del SAD

Dejar trazado en un correo  
- Mapeo de Riesgos - Mapear riesgo de no tener el SAD, y mitigación.
- Motivos de no tener el SAD


Arquetipos
- Comenta sobre tomar arquetipo de Capa de Integración
- Flutter arquetipo de 

Escalabilidad
- Generar inventario de servicios en alta disponibilidad.
  - Replica en otra región de AKS (DRP)
  - Recomendación: Algunos bancos tienen un Activo-Pasivo (No es costo cero, pero es una estrategia de DRP) 
  - NT-28915 - DRP - Replica en otra región de AKS
  - Replica de Data (multi region)
    - Aure SQL Database - Geo Replication
      - Desconoce modelos de sincronización (Revisar)
      - Como se configura el acceso desde los microservicios.
      - Tema regulatorio: Retención data dos años.
      - Core, solo maneja retención de un año.
    - Azure Redis Cache - Geo Replication
    - Azure Cosmos DB - Multi region
      - Tiempos de respuesta, expone sin conocer el servicio.


---
### Observabilidad
Elastic
- Gestionado por el cliente
- En Figma se dejan definidos los tags para observabilidad
  - Guarda en "span" - Mix Panel - Zimperio (solo mobile)
  - Si falla un componente (crash litic)
- Gateways diferentes para Web y Mobile
- Configuración de Elastic (revisar con infraestructura)
  - No modificar nada de Capa de Integración
  - Cesar ya confirmo 
- A nivel técnico se implementa mediante eventos asíncronos.
  - Se saca capa de crosscutting en una líbreria transversal.
  - OJO revisar patrones de observabilidad
    - Jairo lo desconoce

- Sistema de análisis de comportamiento de usuarios
  - Cloudflare?
  - BI catch
    - Genera percepción de seguridad del usuario
    - 

Patrón Observador
- WebJob (tarea programada)
  - Solo de Azure?
  - Tipo trigger cada x horas
  - Esto para pagos programados.
  - 


---
### Seguridad
- Revisar bien responsabilidades de Cloudflare y Fortigate.
- Ojo Cloudflare no es un WAF, es un CDN con funcionalidades de seguridad.
  - Cloudflare protege contra ataques DDoS, pero no ofrece protección completa contra amenazas web como un WAF tradicional.
  - Azure API MAnagement es el gateway de API y Cloudflare quien protege contra ataques DDoS.
- Fortigate es el firewall perimetral, pero no es un WAF.
  - Del clodflare pasa luego a Fortigate, y luego a Azure API Management.
  - Fortigate es responsable de...  (Tener mayor claridad de reponsabilidades de cada uno)


Definiciones de seguridad
- Tokens de aplicación
- PJ
  - Cómo lo van a realizar
  - Entrust tiene la responsabilidad de creación de usuarios.
  - Manejo de roles y permisos
    - Permisos por producto
    - Permisos por funcionalidad

PJ Aceleración 
- Usuario PJ tiene permisos se le agrega un decorado
- Usuario PJ se le aplica filtro funcional
- Evitar código propio en cada MS


---
### Infraestructura
Infra a cargo de mercantil.


### Base de Datos
- Gestión de usuarios
- Movimientos desde el core.
- Datawarehouse (cliente) Pendiente
- Consultas al core (OJO tiempos de respuesta)
  - Propuesta de replicación de data no transaccional fue rechazada.
- Catalogo - Azure App Configuration
  - Configuración de parámetros de negocio?
  - Configuración de parámetros técnicos?
  - Configuración de parámetros de seguridad?
  - Configuración de parámetros de observabilidad?
  - Configuración de parámetros de infraestructura?

- Base de datos relacionales
  - Axure SQL Database
  - Estrategia de Cache
    - Azure Redis Cache - Se accede solo desde Azure Functions

Brechas Kappa y Lambda








---

Recomendaciones
- Temas de documentación SAD
  - Sube
- Desarrollo OK
- DevSecops OK
- Infraestructura OK
- Observabilidad OK
- Seguridad OK

Proximo Calidad, ruta de crecimiento
Propositivo


Preocupación PJ
Humnan in the loop










