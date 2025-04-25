# PROYECTO FINAL 7 - ACCESO A DATOS EN APLICACION NODE
Objetivo:
Desarrollar una aplicacion que ejecute operaciones de consulta y manipulacion de datos utilizando el entorno Node.js de acuerdo a las buenas practicas de la industria.

1.	Hacer uso de Node.JS para el desarrollo.

2.	Crear dentro de la carpeta config, el archivo db.config.js, que posee la configuración a la base de datos; el nombre de ésta es: db_bootcamp.
3.	Dentro de la carpeta models, se encuentran los modelos tanto para el usuario (user.model.js), como para el Bootcamp (bootcamp.model.js)
Los atributos para el usuario son:

•	firstName: cadena de caracteres y campo obligatorio.
•	lastName: cadena de caracteres y campo obligatorio.

•	email: campo obligatorio, y con las siguientes validaciones: formato de correo y que sea único, no repetitivo en la base de datos.
Los atributos para el Bootcamp son:

•	title: cadena de caracteres que define el título del Bootcamp, campo obligatorio.
•	cue: número que define la cantidad de sesiones (CUE) que contiene el Bootcamp, campo obligatorio con las siguientes validaciones: tipo entero con un valor mínimo de 5 CUE y como máximo 10.
•	description: cadena de caracteres que define la descripción o el objetivo del Bootcamp, campo obligatorio.
Y el archivo index.js, donde se define la conexión con sequelize a la base de datos y modelos.


4.	En la carpeta controllers posee los controladores tanto para el usuario (user.controller.js), como para el Bootcamp (bootcamp.controller.js).
Para el usuario, construir los siguientes controladores:

•	Crear y guardar usuarios llamado createUser.
•	Obtener los Bootcamp de un usuario llamado findUserById.

•	Obtener todos los Usuarios incluyendo, los Bootcamp llamado findAll.

•	Actualizar usuario por Id llamado updateUserById.
•	Eliminar un usuario por Id llamado deleteUserById.


Para el Bootcamp, construir los siguientes controladores:

•	Crear y guardar un nuevo Bootcamp llamado createBootcamp.

•	Agregar un Usuario al Bootcamp llamado addUser.

•	Obtener los Bootcamp por id llamado findById.

•	Obtener todos los Usuarios incluyendo los Bootcamp llamado findAll.


5.	Por último, para verificar los modelos y las relaciones con sus métodos, se crea el archivo
server.js, donde hacemos uso de la base de datos, los modelos y los controladores.





