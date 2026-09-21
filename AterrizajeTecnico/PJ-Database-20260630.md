# Sesión de Entendimiento - Business Person Database

## Dominios de Información

### Domain 1 - Security Profile Domain


#### Reglas de Negocio


### Domain 2 - Corporate Domain
Descripción / scope de este dominio???
- Tabla temporal revisar?

#### Reglas de Negocio - Notas pero se deben aterrizar y confirmar definición  
- Usuario Administrador se crea a traves de Backoffice, no se puede crear desde la app.
- Flujo de activación de una empresa, por ejemplo: 
  - Se crea la empresa en Backoffice
  - Se crea el usuario administrador de la empresa en Backoffice
  - Se envía un correo al usuario administrador con un link para activar su cuenta
  - Una vez creada la contraseña, el usuario administrador puede iniciar sesión en la app y crear usuarios adicionales para su empresa.
- Manejo de estados de la empresa: Activa, Inactiva, Suspendida, Eliminada (eliminación lógica).
- Correo con código de único uso para activar la cuenta del usuario administrador.


### Domain 3 - Authorization Domain
Descripción / scope de este dominio???

- Objeto padre rol
- Puede asociar hasta 4 tipos de perfiles.
  - Cada role puede tener un perfil de cada tipo (4 tipos de perfiles).
- Un aprobador solo puede aprobar lo de otros usuarios, no lo de él mismo.

#### Reglas de Negocio


### Domain 4 - Transaction Limits Domain
Descripción / scope de este dominio???

#### Reglas de Negocio
- Siempre obtiene las cuentas del core, al momento de asignar un role a un usuario.
- No se soportará aprobaciones como en persona natural de cuentas mancomunadas.
- Solo se debe soportar un modelo de autorización por transacción con aprobadores preconfigurados con límites por valor de la transacción.
- Límites de transacción por tipo de transacción definidos por el Banco Mercantil para el segmento de Banca Jurídica.
  - Límites por compañía se establecen con tope máximo teniendo en cuenta los límites establecidos para el segmento de Banca Jurídica.
    - Límites por función se establecen con tope máximo teniendo en cuenta los límites establecidos para la compañía.





