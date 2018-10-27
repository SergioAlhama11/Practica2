# Insertar Alumno

**ID:**001
**Breve descripción:**El sistema permite insertar un alumno.

**Actores principales:** Profesor.
**Actores secundarios:** Alumno.

**Precondiciones:**
1. El alumno debe tener un DNI válido.
2. El alumno no puede estar introducido de antemano.

**Flujo principal:**
1. Pide los datos del alumno.
2. Se almacenan los datos del alumno en el programa.

**Postcondiciones:**
* El sistema inserta un alumno en la lista.

**Flujos alternativos:**
1. Si el alumno ya estaba en el sistema el programa da error.
2. Si el alumno no tiene un DNI válido el programa da error.
3. Si los identificadores coinciden se soluciona conflicto.
