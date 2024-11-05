
Ejercicio práctico para alumnos de escuela técnica n° 728 Alfonsina Storni

## ESCUELA DE MUSICA
Una escuela de música necesita una base de datos para gestionar las clases y cursos que ofrecerá. Para esto, el director de la escuela manifiesta que necesitaría almacenar los datos de los alumnos (con sus respectivos niveles de habilidad y tipo de instrumento), y las inscripciones de cada alumno en los cursos en donde se debe especificar si el mismo abonó la inscripción.

Sugiere como estructura de las tablas lo siguiente:

#### MODELADO

- **Alumnos:** id_alumno, apellido, nombre, edad, direccion, telefono, email
- **Cursos:** id_curso, nombre, nivel_habilidad, tipo_instrumento
- **Inscripciones:** id_inscripcion, fecha_insc, abono_inscripcion, id_alumno, id_curso

Realizar el modelado de la base de datos con las correspondientes tablas y relaciones.

El director manifestó que los cursos presentes serán:
- Guitarra Principiante
- Guitarra Intermedio
- Guitarra Avanzado
- Piano Principiante
- Piano Intermedio
- Piano Avanzado
- Armónica Principiante
- Armónica Intermedio
- Armónica Avanzado

El frontend para funcionar necesita las siguientes consultas:

1. Listar todos los alumnos inscriptos en el curso de "Guitarra Intermedio".
2. Mostrar todas las inscripciones realizadas después del 1 de enero de 2024.
3. Contar la cantidad de alumnos que han abonado la inscripción.
4. Listar los cursos disponibles para alumnos avanzados.
5. Listar los nombres y apellidos de los alumnos junto con los nombres de los cursos a los que están inscriptos.
6. Obtener el nombre y apellido de los alumnos que están inscriptos en más de un curso.
7. Mostrar el nombre, curso y la cantidad de alumnos inscriptos en cada curso.
8. Listar los alumnos que no han abonado la inscripción.
9. Obtener los nombres de los cursos que tienen al menos un alumno mayor de 20 años inscripto.
10. Listar el nombre y apellido de los alumnos junto con los nombres de los cursos en los que están inscriptos, pero solo para aquellos que se inscribieron en 2024.

    ### Importante para la entrega:
- El formato puede ser en (.docx), (.pdf) o (.sql)
- La entrega es a través de mail al correo jnicolas.ramos10@gmail.com, y el asunto debe respetar este formato:

    TP_SQL(DDL/DML)_7mo1ra_esc728 – "nombre de los integrantes"

