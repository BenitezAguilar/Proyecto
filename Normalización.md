# Normalización Realizada

## Primera Forma Normal
Aseguré la atomicidad de los datos desglosando el antiguo campo genérico de __Nombre Capitán__ en atributos específicos como __Nombre, 2do Nombre, ApellidoP, ApellidoM y Teléfono__, eliminando así cualquier grupo repetitivo o compuesto dentro de una misma celda.
## Segunda Forma Normal
Al separar la información que no dependía directamente de la embarcación; creé la entidad independiente __Capitán__ con su propia llave primaria __ID__ , lo que garantiza que los datos personales del tripulante tengan una dependencia funcional completa de su propio identificador y ya no estén incrustados como simples atributos de la Embarcación.
## Tercera Forma Normal
Al eliminar las dependencias transitivas, un paso que realicé al extraer la __Especie__ de la entidad __Pescado__ para convertirla en una entidad maestra propia con su propio __ID__ y __Nombre__; de esta manera, logré que cada dato en mi diagrama dependa única y exclusivamente de su llave primaria, eliminando redundancias y protegiendo la integridad de toda la información.
