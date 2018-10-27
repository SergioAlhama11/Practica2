# Modificar Alumno

**ID:** 002
**Breve descripción:** El sistema permite modificar un alumno.

**Actores principales:** Profesor.
**Actores secundarios:** Alumno.

**Precondiciones:**
1. El alumno debe existir.

**Flujo principal:**
1. Pide los datos del alumno.
2. Busca al alumno
3. Comprueba que el alumno está registrado.
4. Pide los datos nuevos para modificar el alumno.
5. Se almacenan los datos modificados.

**Postcondiciones:**
* El sistema modifica un alumno en la lista.

**Flujos alternativos:**
1. Si el alumno no existe el programa lanza un error.
2. Si los nuevos datos no son válidos el programa lanza un error.
