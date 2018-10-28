Para el sistema a desarrollar se tienen en cuenta a dos actores: Alumno (Secundario) y Profesor (Principal). El profesor será el usuario que utilice las funciones del sistema, mientras que el alumno es el sujeto de éste.


El profesor podrá almacenar todos los datos de sus alumnos en el sistema y manejarlos a su antojo con éste. Los datos que el sistema permitirá almacenar son los siguientes:

- DNI 


- Nombre


- Apellidos


- Edad


- Curso mas alto matriculado


- Número de grupo


- Condición de líder



#Requisitos Funcionales

El sistema pedirá la introducción de alumnos si es que no los hay. Al introducirlos se deben dar sus datos (Apellidos, Nombre, Dni, Contacto, Dirección, Curso matriculado más alto, Fecha nacimiento, Grupo, Condición de líder). Si éstos ya estaban introducidos, el sistema debe mostrar el error. La prioridad de insertar alumno será 1.


Todo lo introducido debe poder modificarse. La prioridad de modificar alumno será 1.


Aparte de la modificación se debe poder administrar a los líderes de grupo dentro de una función independiente. De tal forma que el sistema permita visionar al líder de cada grupo y borrarlo o reemplazarlo. La prioridad del manejo de líderes será 2.


Todo los alumnos introducidos deben poder listarse alfabéticamente. El sistema mostrará en pantalla la lista y en caso de no haber ninguno lanzará un error. La prioridad de mostrar listado será 2.


Se podrá buscar cualquier alumno en función de diferentes datos. Si ese alumno no estaba introducido el sistema lanzará un error. La prioridad de buscar alumno será 2.


Se dará una función para borrar un alumno seleccionado junto a todos sus registros. La prioridad del borrado es 2.


Se podrá resolver conflictos en caso de coincidencias en datos de identificación.


Todo el registro se podrá almacenar dentro de un archivo binario, con la condición de que haya al menos un alumno registrado, en caso contrario lanzará error para no guardar un archivo en blanco.


El sistema permitirá cargar un archivo exterior para implementarlo en el propio programa, éste deberá tener al menos datos para rellenar a un alumno. Tanto la carga como descarga de archivo binario se tomarán como prioridad 2.






#Requisitos no Funcionales

Debe ser un programa sencillo, cuyo menú sea manejable para una persona que desconozca totalmente el desarrollo del sistema.


Se buscará la eficacia sobe todo, intentando no crear procesos inútiles que entorpezcan el sistema.


En cuanto a rendimiento, el sistema deberá soportar la incersión de hasta 120 alumnos.


El desempeño de la aplicación debe ser impecable, no debe dar problemas a la hora de utilizar sus funciones.


El lenguaje utilizado para la realización del programa será C++.


Toda prueba y desarrollo será realizada bajo el sistema operativo de Linux.
