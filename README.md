#Proyecto Final - Wikipedia
## Descripción
El proyecto se basa en una wikipedia capaz de crear paginas web, cuenta con funciones de registro, los datos que se almacenaran en la base de datos para guardar y editar los archivos
#Aplicación Web con AJAX y Docker

---

## Integrantes
- Ysabel Alejandra Zambrano Cruz

---

## Descripción de Pantallas
### 1. **Pantalla Principal**
   - Permite al usuario visualizar el autor y una breve descripcion de la pagina.
   - El usuario puede observar los metodos emplados en la creacion de la pagina.

### 2. **Pantalla Idenntificacion**
   - El usuario podra acceder a su cuenta. Inicio de sesion
   - Usuari y contraseñas ubicados anteriormente en la base de datos.

### 3. **Pantalla de Creacion de cuenta**
   - Funcionalidades:
     - Username: Unico username por usuario.
     - Firstname: Identificacion de usuario.
     - Lastname: Identificacion de usuario.
     - Password: Seguriad de la cuenta,
---


## Explicación del Uso de AJAX
- **Crear**: El formulario envía datos al servidor mediante AJAX (`POST`) para añadir nuevos registros sin recargar la página.
- **Leer**: Los datos se cargan desde el servidor usando `GET`, presentados con una tabla.
- **Actualizar**: Los datos modificados en el formulario se envían al servidor usando `PUT`.
- **Eliminar**: AJAX envía una solicitud `DELETE` para eliminar registros seleccionados.

---

## Explicación del Uso de Variables de Sesión
Las variables de sesión se utilizan para:
1. **Usuario**:
   - Identificar al usuario cada inicio de sesión.
   - Proteger rutas.
2. **Persistencia de Datos**:
   - Guardar datos temporales.
3. **Seguridad**:
   - Validar el rol del usuario para permitir o restringir el acceso a ciertas funcionalidades.
