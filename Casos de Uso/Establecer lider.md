# Establecer un lider

**ID:** 006
**Breve descripción:** El sistema establece a un alumno como líder de un grupo.

**Actores principales:** Profesor.
**Actores secundarios:** Alumno.

**Precondiciones:**
1. El alumno debe existir.
2. El grupo debe existir
3. El alumno debe formar parte de ese grupo.

**Flujo principal:**
1. Pide el grupo al que se le quiere establecer el líder.
2. Pide el nombre del alumno.
3. Busca al alumno
4. Modifica el estado de líder del alumno.
3. Guarda a ese alumno como líder del grupo al que pertenece.


**Postcondiciones:**
* El sistema otorga la característica de líder al alumno.

**Flujos alternativos:**
1. Si el grupo no existe el sistema lanza error.
2. Si el alumno no existe el sistema lanza error.
3. Si el grupo ya tenía otro líder, lo sobrescribe. 
