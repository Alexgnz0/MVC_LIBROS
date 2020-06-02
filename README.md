# api_muni
Desarrollar un MVC con Laravel 6.0 con las siguientes caracteristicas:

1. Login y register con cuenta de email y nombre de usuario.
2. Conexion con una base de datos relacional (Mysql).
3. ABM de libros con stock (para el frontend puedes usar el stack que prefieras)(bibliotecario).
4. Al estar logueado deberias porder listar los libros con su stock y en caso de que existan unidades disponibles podes alquilarlo (el libro alquilado debe reducir el stock)(usuario).
5.Proteger las rutas con un middleware de autenticacion y de roles(bibliotecario y usuario).
6. El bibliotecario debera poder visualizar los libros alquilados y a que usuario de corresponde.


Pautas

Las tablas deben crearce con migraciones, deberan crearce los modelos de las correspondientes tablas.
Las relaciones deben establecerce dentro de los modelos.
