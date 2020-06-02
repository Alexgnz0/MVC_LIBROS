#MVC_MCC

Desarrollar un MVC con Laravel 6.0 con las siguientes características:

Login y register con cuenta de email y nombre de usuario.

Conexión con una base de datos relacional (Mysql).

ABM de libros con stock (para el frontend puedes usar el stack que prefieras)(bibliotecario).

Al estar logueado deberías poder listar los libros con su stock y en caso de que existan unidades disponibles podes alquilarlo (el libro alquilado debe reducir el stock)(usuario).

Proteger las rutas con un middleware de autenticación y de roles(bibliotecario y usuario).

El bibliotecario deberá poder visualizar los libros alquilados y a que usuario de corresponde.

Pautas

Las tablas deben crearse con migraciones, deberán crearse los modelos de las correspondientes tablas. Las relaciones deben establecerse dentro de los modelos.
