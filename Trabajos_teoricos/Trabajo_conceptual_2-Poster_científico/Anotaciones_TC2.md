# Links de Interés
- [How the Testing Manifesto is going to change development](https://www.techtarget.com/searchsoftwarequality/opinion/How-the-Testing-Manifesto-is-going-to-change-development)
- [The Testing Manifesto (en pdf, es una propuesta)](https://www.pixelgrill.com/testing-manifesto/)
- [TESTING MANIFESTO Values & Principles](https://gearsoftesting.org/software-testing-manifesto.html)
- [Manifesto for Agile Software Testing](https://testingmanifesto.com/)

# Manifiesto: 
We are uncovering better ways of testing by doing it and helping others to do it. Through this work we have come to value:  
Testing throughout over testing at the end

Preventing bugs over finding bugs

Testing understanding over checking functionality

Building the best system over breaking the system

Collective responsibility for quality over individual responsibility

That is, while there is value in the items on the right, we value the items on the left more.

# Anotaciones de la clase
- [Link a la clase de Testing Agil](https://www.youtube.com/watch?v=hKoJBlhxuN8)
## Manifiesto
El proceso de testing tradicional no encaja en agil. Entonces se trata de reformular los conceptos del testing tradicional.   
Se dice entonces que en testing agil, es una actividad y no una fase. Se dice que atraviesa el proceso porque se hace en conjunto con el desarrollo.   
El foco está en prevenir los Bugs y no en encontrarlos (algo clave en el testing tradicional). Es muy disruptivo.   
Entender el testing (la funcionalidad) por sobre chequear la funcionalidad. Eso que se resuelve con un checklist se debe automatizar. Se trata de automatizar lo que más se pueda. Es decir, la verificación se automatiza.   
En el agilismo, los tester ayudan a construir el mejor sistema posible y no tratan de romperlo   
El testing es responsabilidad de todos el equipo y no solo del tester. El rol del tester puede ser cubierto por el PO o desarrolladores. Es decir, el rol lo llena quién se necesite que lo llene.   


## Contexto
Hacer comparación de filosofía y diferencias entre testing agil y tradicional

## Principios
Son 9.   
Cada uno responde a los principios del manifiesto ágil. Y también se relaciona a los valores   
Tiempo de feedback: se busca que sea el menor posible al igual que el tiempo de correcciones.  

## Otros Temas   
- Son fáciles de implementar. Pero no así los valores, en la organización.   
- Testing exploratorio, es un enfoque que se usa desde el lugar del trabajo que hará el testing.   
- TDD está más relacionada con el desarrollo. Permite hacer testing en todo el proceso. No es algo que hago al final. El enfoque es probar primero   
- Rol y Competencias del tester y comparación con el testing tradicional.   
- Desafíos Culturales.   
- Cuadrantes del Testing Ágil.
- Pirámide del Testing (por Mike Cohn también) -> Agile trata de reducir el testing manual al mínimo.
- Qué puede automatizarse.

# Resumen Capítulo 1 de Agile Testing

## Introduccion
En esta etapa se explica la visión general del testing Ágil desde el propio Manifiesto Ágil y comparandolo con la visión tradicional. El enfoque de un equipo como unidad es central para la actitud hacia la calidad y el testing.   

## Valores Agiles
Recordando lo ya visto en el manifiesto ágil, los valores promovidos en este se centran en entregar pequeños pedazos de valor de negocio en ciclos extremadamente cortos de releases.   

Individuals and interactions over processes and tools   
Working software over comprehensive documentation   
Customer collaboration over contract negotiation   
Responding to change over following a plan   

## Qué se entiende por "Agile testing"
Todos los miembros del Equipo Ágil estan enfocados en entregar un producto de alta calidad que provea de valor de negocio. Los testers ágiles aseguran que el equipo entrega la calidad que los clientes necesitan y no es que solo realizan tareas de testing.   
Por testing ágil se refiere a tests enfocados al negocio que los definen las características y las funcionalidades que desean los expertos del negocio. Testing agil también incluye críticas al producto y enfocarse en descrubrir que es aquello que le falta. Incluye todo después de testing unitario y de componentes: testing funcional, de sistema, de carga, de performance, de seguridad, de estrés, de usabilidad, exploratorio, end-to-end y aceptación de usuario. Aunque todos estos tipos de tests se pueden usar en cualquier tipo de proyecto y no solo ágil.   
Lo importante es testear el producto con un plan de aprendizaje sobre la marcha y dejar que esa información guíe el testing, lo cual está en linea con software funcionando y respuesta al cambio (del manifiesto). 

## Roles y Actividades en un Equipo Ágil
Está el equipo del cliente,  que incluye los expertos del negocio, product ownders, expertos de dominio, product managers, analistas de negocio, etc... Ellos escriben las historias o sets de características que debe entregar el equipo de desarrollo. Ellos se comunican y colaboran con el equipo de desarrollo a lo largo de cada iteración.    
El developer team se encuentran los developers que son todos aquellos involucrados en eentregar el código. Los principios ágiles incentivan a que los miembros del equipo se ocupen de multiples actividades, es decir, cualquiera puede hacer cualquier tarea. No hay expertos pero debe definirse que especialidades se van a necesitar en el proyecto.    
Los clientes y el developer team deben trabajar juntos en todo momento Idealmente actuando como un solo equipo con un objetivo en común y eso es, entregar valor a la organización. Los testers tienen un pie en ambos mundos, entendiendo el punto de vista del cliente, como también la complejidad técnica de la implementación. Debe haber alguien \(como tester\) que ayude a escribir las pruebas de usuarios a los clientes.    
\(ver grafico de interaction roles pagina 8 del libro\)    

## Cómo es Testing Ágil diferente?
En el testing tradicional el foco está en asegurarse de que todos los requerimientos especificados se entreguen en el producto final. Si no está todo terminado para la fecha de entrega progrmada, entonces se pospone el release. Los testers estudian los requerimientos para escribir sus planes de testing y esperan a que les sea entregado el trabajo. El testing en este enfoque se suele meter hacia el final, no pudiendo dedicarle tanto tiempo como a la escritura de código.    
Los equipos ágiles, trabajan de cerca con el negocio para tener un entendimiento detallado de los requerimientos. Están enfocados al valor que pueden entregar. Los testers no esperan a que les llegue el trabajo sino que tratan de ayudar a lo largo de todo el ciclo de desarrollo. En este enfoque el testing se hace a penas se termina un incremento y siempre se testea porque sino una US no está completa.    
