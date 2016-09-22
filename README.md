Tarea 4
 
¿Qué es un Patron de Diseño?
Los patrones de diseño son la base para la búsqueda de soluciones a problemas comunes en el desarrollo de software y otros ámbitos referentes al diseño de interacción o interfaces.

 *Un patrón de diseño resulta ser una solución a un problema de diseño. Para que una solución sea considerada un patrón debe poseer ciertas características. Una de ellas es que debe haber comprobado su efectividad resolviendo problemas similares en ocasiones anteriores. Otra es que debe ser reutilizable, lo que significa que es aplicable a diferentes problemas de diseño en distintas circunstancias

*************************************
¿En Que consiste el patron singleton?
Es un patrón de diseño diseñado para restringir la creación de objetos pertenecientes a una clase o el valor de un tipo a un único objeto.

Su intención consiste en garantizar que una clase sólo tenga una instancia y proporcionar un punto de acceso global a ella.

La instrumentación del patrón puede ser delicada en programas con múltiples hilos de ejecución. Si dos hilos de ejecución intentan crear la instancia al mismo tiempo y esta no existe todavía, sólo uno de ellos debe lograr crear el objeto. La solución clásica para este problema es utilizar exclusión mutua en el método de creación de la clase que implementa el patrón.

El patrón singleton provee una única instancia global gracias a que:

1.- La propia clase es responsable de crear la única instancia. 
2.- Permite el acceso global a dicha instancia mediante un método de clase.
3.- Declara el constructor de clase como privado para que no sea instanciable directamente.

***********************************
¿En que consiste el patron Factory? 
consiste en utilizar una clase constructora (al estilo del Abstract Factory) abstracta con unos cuantos métodos definidos y otro(s) abstracto(s): el dedicado a la construcción de objetos de un subtipo de un tipo determinado. Es una simplificación del Abstract Factory, en la que la clase abstracta tiene métodos concretos que usan algunos de los abstractos; según usemos una u otra hija de esta clase abstracta, tendremos uno u otro comportamiento.

***********************************
¿En que consiste el patron Builder?
Es usado para permitir la creación de una variedad de objetos complejos desde un objeto fuente (Producto), el objeto fuente se compone de una variedad de partes que contribuyen individualmente a la creación de cada objeto complejo a través de un conjunto de llamadas a interfaces comunes de la clase Abstract Builder.

El patrón builder es creacional.

A menudo, el patrón builder construye el patrón Composite, un patrón estructural.

Intención: Abstrae el proceso de creación de un objeto complejo, centralizando dicho proceso en un único punto, de tal forma que el mismo proceso de construcción pueda crear representaciones diferentes.

________________
ADB de Android

Las siglas ADB significan Android Debug Bridge y se corresponden con una herramienta de software que nos permite interactuar con nuestro smartphone Android desde un ordenador. Así, por ejemplo, a través de ADB podemos ejecutar comandos para copiar archivos desde el ordenador al teléfono o viceversa, flashear un revocery o el firmware completo e incluso reiniciar el dispositivo en modo recovery. 

El ADB es una parte fundamental del Android Studio, el software para desarrollar aplicaciones en Android. Para obtener el ADB no es necesario instalar Android Studio, algunos desarrolladores de la comunidad nos facilitan el trabajo actualizando periodicamente un paquete muy cómodo con el ADB, fastboot y los drivers (Windows) necesarios.

Lista de comandos más importantes (http://www.androidpit.es/que-es-adb-comandos-mas-importantes)

________________________________________
Para que sirve el operador final en JAVA

__________________________________________________
¿Que Lenguajes soportan Sobre Carga de operadores?
Java, C++, C#, Python.

_____________________________________________________________________________
¿En que consiste la injección de dependencias en desarrollo de software, y por qué es útil utilizarla?

La inyección de dependencias es un patrón de diseño de software usado en la Programación Orientada a Objetos, que trata de solucionar las necesidades de creación de los objetos de una manera práctica, útil, escalable y con una alta versatilidad del código.

Como cualquier patrón de diseño de software trata de solucionar de una manera elegante un problema habitual en el desarrollo de software, por lo que también es idóneo utilizar este patrón en el desarrollo de proyectos a pequeña escala.

Aparte de un patrón de diseño de software, vamos a explicar qué idea hay detrás de ese nombre. Este patrón, como muchos otros, nos ayuda a separar nuestro código por responsabilidades, siendo que en esta ocasión sólo se dedica a organizar el código que tiene que ver con la creación de los objetos.

-- uno de los principios básicos de la programación, y de las buenas prácticas, es la separación del código por responsabilidades. Pues la inyección de dependencias parte de ahí. --
