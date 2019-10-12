#Base de datos
El nombre de la base de datos será VENTA_CURSO.
Estructura y descripción de tablas
Esta base de datos estará conformada por las siguientes tablas:
### PERSONA:
 contiene los datos generales de toda persona, además especifica si es estudiante o empleado.
### EMPLEADO: 
contiene la información necesaria del empleado.
### DEPARTAMENTO:
 contiene toda la información de los departamentos en los que trabajan los empleados.
### CURSO:
 contiene toda la información referente a los cursos que se ofertan.
### OFERTA: 
contiene las ofertas de cursos con su respectiva fecha de inicio y profesor. asignado. 
### NIVEL_SUELDO: 
contiene los niveles o grados de sueldo que puede alcanzar el empleado de acuerdo a su productividad.
### INSCRIPCION:
 contiene todas las inscripciones realizadas a los cursos ofertados y que son atendidos por los empleados del departamento de ventas.
### HISTORICO:
 contiene la información histórica de los años trabajados de un empleado dentro de la empresa.
Para acceder y visualizar la estructura de cada una hacer clic aquí.
Relaciones entre tablas
Para establecer las relaciones debe tener en cuenta lo siguiente:
Un empleado puede ser Jefe de ninguno, uno o muchos empleados.
Un departamento está conformado por ninguno, uno o muchos empleados.
En un nivel o grado de sueldo pueden estar comprendidos 0, 1 ó muchos sueldos de los empleados.
Un curso puede estar presente en ninguna, una o muchas ofertas.
Un profesor puede dictar ninguno, uno o más cursos.
Una persona puede estar registrado como empleado ninguna, una o muchas veces.
Un empleado del departamento de ventas puede registrar la inscripción de ninguno, uno o muchos cursos.
Un persona de tipo de estudiante se puede registrar ninguna, una o muchas veces en los cursos.
Una oferta de curso puede estar en 0, 1 o muchas veces inscripciones.
Un empleado puede ser ascendido o irse de la empresa ninguna, una o muchas veces.
Para acceder y visualizar los detalles de las relaciones debe hacer clic aquí.
Vertabelo
Elaborar el diagrama de base de datos de acuerdo a las especificaciones anteriores.
Generar el diccionario de base de datos respectivo.
Generar script respectivo de base de datos.
GitHub
Crear un repositorio en GitHub llamado appVentaCursos con su respectivo archivo Readme.md
Verificar y/o configurar sus datos en Git Bash en su equipo.
En su equipo debe ahora clonar el repositorio previamente creado.
Ingresar a la carpeta del repositorio clonado.
Utilizando git bash vamos a inicializar el control de versiones.
Verificamos el estado de nuestro versionamiento.
Agregar el diccionario de datos al repositorio.
En el archivo Readme agregar la información de: base de datos, tablas y relaciones.
Subir los cambios realizados al repositorio de GitHub.


