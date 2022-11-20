# Gestión Escuela de Topografía de Madrid

Se ha creado una base de datos para llevar las calificaciones de las asignaturas de los alumnos de primer curso de la Escuela de Topografía de Madrid. La tabla creada tiene los siguientes campos

- DNI varchar (20).
- Apellidos varchar (255).
- Nombre varchar (50).
- Direccion varchar (255).
- Ciudad varchar (50).
- Provincia varchar (50).
- Comunidad varchar (50).
- Codigo integer.
- Asignatura varchar(50).
- Nota double.

Además la información que se aporta es:

- DNI es un identificador único del alumno; lo mismo que {Apellidos, Nombre}.
- Ciudad es el nombre de la ciudad de residencia (único)
- Provincia es el nombre de la provincia de residencia (único)
- Com_Aut es el nombre de la Comunidad Autónoma de residencia (único)
- Codigo es el código de una asignatura (único). Asignatura es el nombre de la asignatura (único)
- Asignatura es el nombre de la asignatura (único)
- Nota es la nota que el alumno ha obtenido en la asignatura
- Codigo, Asignatura y Nota se escriben en el mismo orden en los campos correspondientes

Ejemplo de datos de la tabla:

(Con claves candidatas)

![<>](img/Captura%20de%20pantalla%202022-11-20%20212306.png)

### - 1ºra forma normal. Se dividen las filas para formar datos atómicos 

![<>](img/Captura%20de%20pantalla%202022-11-20%20212339.png)

### - Se separa en varias tablas para evitar la repetción

![<>](img/Captura%20de%20pantalla%202022-11-20%20212413.png)
