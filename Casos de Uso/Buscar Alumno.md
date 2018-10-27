# Buscar alumno

**ID:** 005
**Breve descripción:** El sistema permite buscar un alumno.

**Actores principales:** Profesor.
**Actores secundarios:** Alumno.

**Precondiciones:**
1. El alumno a buscar debe existir.

**Flujo principal:**
1. Da a elegir la forma en la que se quiere buscar al alumno: DNI, apellido, equipo.
2. Introduce la forma a buscar.
3. Si se ha elegido DNI, busca al alumno por su DNI.
4. Si se ha elegido apellido, busca al alumno por su apellido.
5. Si se ha elegido equipo, busca a todos los miembros de éste.

**Postcondiciones:**
* EL sistema mostrará por pantalla al alumno buscado.

**Flujos alternativos:**
1. Si el alumno no existe el programa lanza error.
2. Si el grupo no existe el programa lanza error.
3. Si hay varios alumnos con los mismos apellidos da error.
