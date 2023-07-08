# Unidad Temática 5 - Implementando Patrones de Diseño

## Preparación para la clase

La preparación para la clase no fue la suficiente porque el texto para leer era demasiado extenso y las actividades  en general eran muy largas.

## Temas de la unidad patrones y antipatrones de diseño

Esta unidad se basa en el estudio de los patrones de diseño y los antipatrones de diseño. Los patrones de diseño son soluciones a problemas comunes en el desarrollo de software, mientras que los antipatrones de diseño son soluciones a problemas comunes que no funcionan o que tienen consecuencias negativas en el desarrollo de software.

## SOLID

SOLID es un acrónimo que representa cinco principios básicos de la programación orientada a objetos y el diseño. Estos principios, cuando se aplican juntos, pretenden hacer que sea más fácil para un programador desarrollar software que sea fácil de mantener y extender. También se considera que los principios promueven la reutilización del código y la facilitación de la comunicación entre los miembros del equipo de desarrollo.

### Principio de responsabilidad única

El principio de responsabilidad única establece que cada clase o módulo en un programa debe tener la responsabilidad de una sola parte de la funcionalidad proporcionada por el software, y esa responsabilidad debe estar completamente encapsulada por la clase. Todos los servicios proporcionados por la clase deben ser coherentes con esa responsabilidad.

### Principio de abierto / cerrado

El principio abierto / cerrado establece que las clases o módulos de un programa deben ser abiertos para su extensión pero cerrados para su modificación. Esto significa que la funcionalidad existente debe ser modificada lo menos posible, y las nuevas funcionalidades deben ser agregadas en lugar de cambiar el código existente.

### Principio de sustitución de Liskov

El principio de sustitución de Liskov establece que los objetos en un programa deben ser reemplazables por instancias de sus subtipos sin alterar la funcionalidad del programa. Esto significa que los objetos deben ser diseñados de tal manera que cualquier propiedad o restricción que se aplique a un objeto en un programa también se aplique a los objetos de sus subtipos, sin que el programador tenga que preocuparse por ello.

### Principio de segregación de interfaz

El principio de segregación de interfaz establece que los clientes de un programa no deben verse obligados a depender de interfaces que no utilizan. Esto significa que los clientes no deben verse obligados a depender de métodos que no utilizan. Este principio se puede aplicar a clases, módulos, paquetes, etc.

### Principio de inversión de dependencia

El principio de inversión de dependencia establece que los módulos de alto nivel no deben depender de módulos de bajo nivel, sino que ambos deben depender de abstracciones. Esto significa que los módulos de alto nivel no deben depender de módulos de bajo nivel, sino que ambos deben depender de abstracciones. Este principio se puede aplicar a clases, módulos, paquetes, etc.

## Patrones estructurales

Los patrones estructurales se centran en cómo se componen las clases y los objetos para formar estructuras más grandes. Los patrones estructurales describen cómo se pueden utilizar las relaciones entre las clases y los objetos para simplificar el diseño y la implementación de un programa.

### Patrón de adaptador

El patrón de adaptador se utiliza para permitir que dos clases que de otro modo no podrían trabajar juntas trabajen juntas mediante la conversión de una interfaz de una clase en otra interfaz que la otra clase espera. El adaptador permite que las clases trabajen juntas sin modificar ninguna de las clases.

### Patrón de puente

El patrón de puente se utiliza para separar la interfaz de una clase de su implementación. Esto permite que la interfaz y la implementación de una clase varíen independientemente.

### Patrón de composición

El patrón de composición se utiliza para crear estructuras de objetos complejas mediante la composición de objetos más simples. El patrón de composición permite que los clientes traten a los objetos individuales y a las composiciones de objetos de la misma manera.

### Patrón de decorador

El patrón de decorador se utiliza para añadir funcionalidad a una clase sin cambiar la clase. El patrón de decorador crea una clase decoradora que envuelve a la clase original. Esto proporciona una forma flexible de añadir funcionalidad a una clase.

### Patrón de fachada

El patrón de fachada se utiliza para proporcionar una interfaz unificada a un conjunto de interfaces en un subsistema. El patrón de fachada define una interfaz de alto nivel que hace que el subsistema sea más fácil de usar.

### Patrón de volante

El patrón de volante se utiliza para reducir el número de objetos que se crean en un programa. El patrón de volante define una clase que contiene un grupo de objetos similares. En lugar de crear un nuevo objeto, el cliente puede solicitar un objeto del volante.

### Patrón de proxy

El patrón de proxy se utiliza para proporcionar un sustituto o marcador de posición para otro objeto. El patrón de proxy define una clase que actúa como un sustituto de otra clase. El proxy se comunica con el objeto real para realizar el trabajo, pero el cliente no necesita saber nada sobre el objeto real.

## Patrones de comportamiento

Los patrones de comportamiento se centran en cómo se comunican las clases y los objetos entre sí. Los patrones de comportamiento describen cómo se pueden utilizar las relaciones entre las clases y los objetos para simplificar el diseño y la implementación de un programa.

### Patrón de cadena de responsabilidad

El patrón de cadena de responsabilidad se utiliza para permitir que más de un objeto tenga la oportunidad de manejar una solicitud. El patrón de cadena de responsabilidad crea una cadena de objetos que pueden manejar una solicitud. El cliente envía la solicitud a la cadena, y la cadena pasa la solicitud a los objetos de la cadena hasta que se maneja la solicitud.

### Patrón de comando

El patrón de comando se utiliza para encapsular una solicitud como un objeto. El patrón de comando crea un objeto que contiene toda la información necesaria para ejecutar una solicitud. Esto permite que las solicitudes se retrasen, se encole o se registren.

### Patrón de mediator

El patrón de mediator se utiliza para reducir las dependencias entre las clases que se comunican entre sí. El patrón de mediator define un objeto que encapsula cómo se comunican las clases. Esto permite que las clases se comuniquen entre sí sin conocer los detalles de la implementación de las otras clases.

### Patrón de observador

El patrón de observador se utiliza para notificar a los objetos de los cambios en el estado de otros objetos. El patrón de observador define una relación uno a muchos entre los objetos. Cuando un objeto cambia de estado, notifica a todos los objetos que dependen de él.

### Patrón de estado

El patrón de estado se utiliza para cambiar el comportamiento de un objeto cuando cambia su estado interno. El patrón de estado define una clase para cada estado de un objeto. Cuando el estado de un objeto cambia, el objeto cambia de una clase a otra.

### Patrón de estrategia

El patrón de estrategia se utiliza para permitir que un objeto cambie su comportamiento en tiempo de ejecución. El patrón de estrategia define una familia de algoritmos, encapsula cada algoritmo y los hace intercambiables. Esto permite que el algoritmo utilizado por un objeto varíe en tiempo de ejecución.

### Patrón de plantilla

El patrón de plantilla se utiliza para definir el esqueleto de un algoritmo en una operación, dejando que las subclases redefinan ciertos pasos del algoritmo sin cambiar su estructura. El patrón de plantilla define una clase que contiene un esqueleto de algoritmo. Los pasos del algoritmo se definen como métodos abstractos. Las subclases redefinen los métodos abstractos para implementar el algoritmo.

### Patrón de visitante

El patrón de visitante se utiliza para separar un algoritmo de la estructura de un objeto en el que opera. El patrón de visitante define una clase de visitante que encapsula un algoritmo. El objeto en el que opera el algoritmo proporciona una interfaz para aceptar el visitante.

## Patrones de creación

Los patrones de creación se centran en cómo se crean las clases y los objetos. Los patrones de creación describen cómo se pueden utilizar las relaciones entre las clases y los objetos para simplificar el diseño y la implementación de un programa.

### Patrón de constructor

El patrón de constructor se utiliza para crear objetos complejos paso a paso. El patrón de constructor define una clase para cada paso de la construcción. El director controla el proceso de construcción.

### Patrón de fábrica

El patrón de fábrica se utiliza para crear objetos sin especificar la clase exacta del objeto que se creará. El patrón de fábrica define una interfaz para crear un objeto, pero deja que las subclases decidan qué clase instanciar. El método de fábrica se utiliza para crear el objeto.

### Patrón de prototipo

El patrón de prototipo se utiliza para crear objetos duplicando un prototipo. El patrón de prototipo define un prototipo de objeto que se duplica para crear un nuevo objeto. El nuevo objeto puede ser modificado antes de que se utilice.

### Patrón de singleton

El patrón de singleton se utiliza para asegurarse de que sólo se crea una instancia de una clase. El patrón de singleton define una clase con un método que crea una instancia de la clase si aún no existe una instancia. Si ya existe una instancia, devuelve una referencia a esa instancia.

# Apreciaciones de la unidad temática

## Utilización de patrones

Los patrones de diseño nos permiten resolver problemas comunes en el desarrollo de software. Ya que son soluciones probadas que nos permiten tener que redescrubrir la rueda cada vez que nos enfrentamos a un problema.
Sin embargo aplicarlos todo el tiempo conlleva que el código se vuelva más complejo y difícil de mantener. Por lo que es importante saber cuando aplicarlos y cuando no. No es necesario aplicarlos todo el tiempo, pero si es importante conocerlos y saber cuando aplicarlos.

## Reflexión del aprendizaje

Siento que lo aprendido a lo largo del curso, nos mostró una faceta que habíamos explorado en programación 2, pero quizás por la falta experiencia no le habíamos prestado tanta atención como ahora. La verdad es que me gustó mucho el curso, y me gustaría seguir aprendiendo más sobre el tema, de manera personal, para poder aplicarlo en mi vida profesional, cosa que venía haciendo pero quizas sin conocer el trasfondo del tema.



