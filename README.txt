README - Eglys Pastelería (prototipo web simple)

Estructura de archivos:
- ingreso.html        -> pantalla de inicio de sesión
- registro.html      -> pantalla para crear cuenta
- servicio.html      -> seleccionar Tortas o Eventos
- producto.html      -> lista de tortas (seleccionar suma al carrito)
- evento.html        -> lista de eventos
- detalle-pedido.html-> ver carrito y confirmar pedido
- estilos.css        -> estilos compartidos
- main.js            -> lógica JS (registro, login, carrito)
- img/               -> carpeta opcional con imágenes

Cómo ejecutar:
1. Abre la carpeta del proyecto en Visual Studio Code.
2. Instala la extensión Live Server (opcional).
3. Haz clic derecho en cualquier archivo HTML y selecciona "Open with Live Server", o abre el archivo en el navegador (doble clic).
4. Regístrate en "registro.html", luego ingresa en "ingreso.html".
5. Selecciona servicios, agrega productos y confirma pedido.

Notas:
- Los datos se guardan en localStorage del navegador (simulación). No hay base de datos real.
- Para ver datos guardados: abre DevTools (F12) > Application > Local Storage.
- Si deseas reiniciar todo: en DevTools > Application > Clear Storage o borra los items 'users', 'cart', 'orders', 'currentUser' en localStorage.

Soporte:
- Si deseas que conecte el proyecto a una base de datos o cree una versión con servidor (Node.js / PHP), dime y te explico el siguiente paso.
