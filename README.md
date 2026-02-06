# Entrega_Hito1_Motomania
Esta es la primera entrega del Hito 1 - Versión BETA
1️⃣ Iniciar XAMPP

Abre XAMPP Control Panel.

Arranca los módulos:

Apache → para el servidor web

MySQL → para la base de datos

Verifica que ambos estén en verde ✅

2️⃣ Importar la Base de Datos

Abre tu navegador y entra a phpMyAdmin (http://localhost/phpmyadmin).

Crea una base de datos nueva llamada motomania (si no existe).

Importa el archivo motomania.sql que contiene las tablas y datos de prueba.

Ahora tu base de datos tiene:

users → usuarios

routes → rutas de moto

clubs → clubs disponibles

user_clubs → relación usuarios-clubs

3️⃣ Abrir Visual Studio Code

Abre la carpeta raíz del proyecto en VS Code.

Abre la terminal integrada (`Ctrl + ``)

4️⃣ Ejecutar el Backend

En la terminal, ve a la carpeta donde está tu backend (app.js). Por ejemplo:

cd backend


Arranca el servidor:

node app.js


Verás un mensaje como:

🚀 SERVIDOR LISTO en http://localhost:3000
👉 La ruta de login es: http://localhost:3000/api/auth/login


Esto significa que tu backend ya está escuchando peticiones del frontend.

5️⃣ Abrir el Frontend

Haz click derecho sobre index.html y selecciona Open with Live Server.

Se abrirá el login en tu navegador.

6️⃣ Iniciar Sesión

Usuario de prueba:

Email: fso0001@alu.medac.es

Contraseña: 1234

Tras iniciar sesión, se guarda el token en localStorage y te redirige a routes.html o clubs.html.

7️⃣ Explorar la Aplicación

Mapas y Rutas:

Verás rutas predefinidas con trazados reales (Sevilla-Málaga, Madrid-Galicia, etc.).

Crear nuevas rutas haciendo clic en el mapa y guardarlas en la base de datos.

Clubs y Comunidad:

Listado de clubs disponibles.

Unirse a clubs con un clic.

Ver los clubs a los que ya perteneces.

Todo se guarda automáticamente en la base de datos.

8️⃣ Tips Finales

Si borras localStorage, tendrás que iniciar sesión de nuevo.

Usa Chrome o Edge para mejor compatibilidad.

Asegúrate de que XAMPP y Node.js estén corriendo antes de abrir el frontend.
