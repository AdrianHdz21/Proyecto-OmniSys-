*Nota: Para ejectutar el archivo se necesita la aplicacion Netbeans para ejecutar*

04/04/2024
--

Se realizó la primera carga del archivo de versiones, que incluye el diseño inicial de las interfaces según lo planificado. Además, se agregaron funcionalidades básicas a cada interfaz, aunque estas aún no están completamente operativas.

En la interfaz de ingreso, se programó la conexión con la base de datos, lo que nos permitirá realizar pruebas y validar el funcionamiento de las diferentes funcionalidades del sistema.

Se incluyó la biblioteca "mssql-jdbc-12.6.1.jre11" necesaria para la conexión con la base de datos, que proporciona los medios para establecer una comunicación efectiva con la base de datos y acceder y manipular los datos almacenados en ella desde la aplicación.

16/04/2024
--

Se modificaron diversos componentes de todas las interfaces (TextFields, JComboBox, JLabels, etc.), para que cumplan con los requisitos previstos.

Se programaron la mayoría de los módulos de cada interfaz, lo que resultó en el correcto funcionamiento y uso en primera instancia.

Se implementó el código para la creación de usuarios desde la interfaz de Gestión de Usuarios, pero surgió un conflicto debido a la instancia de la base de datos utilizada, relacionado con cuestiones de seguridad. Se trabajará en la resolución de este error para futuras versiones.

22/04/2024
--
Se completó la programación de los módulos del sistema y se realizaron pruebas para garantizar que no haya errores o defectos en el funcionamiento.

Se resolvió con éxito el conflicto en el funcionamiento de la creación de usuarios, relacionado con la instancia de la base de datos.

Se realizaron modificaciones en iconos, fuentes, colores y tamaños de todos los elementos visuales del sistema para hacerlo más atractivo y comprensible para el usuario final.

04/05/2024
--
Se agregaron las funciones de recuperación de contraseña y registro de nuevos usuarios como opciones en la interfaz de Ingreso.

Para la función de recuperación de contraseña, se implementó el envío mediante correo electrónico utilizando una API gratuita y los archivos .Jars correspondientes.

Se agregó la función de registro de nuevos usuarios por parte del administrador, que envía sus credenciales a través del correo electrónico.

Se han añadido nuevos componentes a la interfaz de búsqueda, ahora accesible a través del UsuarioID, lo que garantiza una integración completa de todas las interfaces.

Se ha actualizado la generación del ticket, incluyendo información adicional y realizando mejoras en otros aspectos.

Se ha implementado una validación de contraseñas para prevenir errores del usuario en el servidor al crear contraseñas que no cumplan con los requisitos establecidos (más de 8 caracteres).

Con todas estas modificaciones, se completó la última fase de programación del proyecto.

* NOTA: Se agregan las librerias necesarias para el correcto funcionamiento del sistema *
  --

