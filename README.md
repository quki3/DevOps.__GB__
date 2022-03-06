# DevOps.__GB__

- Un DevOps se asegura de que el código corra configurando servidores, redes, infraestructura del internet y más. Se encarga de que las máquinas funcionen y puedan dar el servicio escrito por los desarrolladores.

- Un DevOps es un superhéroe, se encarga que desde el momento en que se escribe el código hasta cuando corre en el dispositivo de nuestros clientes, todo el proceso sea seguro, automatizado y con prácticas de calidad.

- Pruebas automatizadas: Las unit test que deberías estar escribiendo.
- Continuous Integration: Automatiza los procesos de calidad.
- Continuous Delivery: Se trata de enviar continuamente código a nuestros cliente.
- Monitoreo y logging: Es la forma de saber qué es lo que sucede dentro de nuestro programa y detectar problemas oportunamente.
- Microservicios: Separa las funcionalidades de la aplicaciones en servicios independientes.
- Comunicación y colaboración: Muy importante en la cultura DevOps.
<a href = "https://aws.amazon.com/devops/what-is-devops/">documentacion</a>


Uno de los puntos más complejos del desarrollo de Software es la estimación. En esta clase me gustaría abordar qué herramientas Gitlab nos ofrece para poder estimar la cantidad de trabajo que un issue requiere, qué ventajas tiene agregar pesos a los issues y algunas de las buenas prácticas relacionadas con este ejercicio.

Gitlab ofrece la funcionalidad de agregar pesos a los issues. Estos pesos se representan de manera numérica (con el límite de que los números deben poderse representar en 4-bytes). Los pesos aparecen en el menú derecho del Issue, junto al nombre del issue en la lista de issues y sirven para determinar la cantidad de trabajo ejecutado en los Burndown Charts de los Milestones.

Ahora bien, estimar es algo difícil. Para los desarrolladores de software es una de las tareas –quizá la tarea más difícil– de nuestro trabajo. Se deben tomar en cuenta muchísimos factores, muchos de ellos desconocidos, para tomar decisiones que afectarán al resto del equipo y a la compañía misma. Por eso, muchos desarrolladores y product owners son reacios a estimar; pero hay que recordar que la estimación es tan solo eso: un estimado. No es un juramento de sangre ni una declaración solemne ante autoridad judicial. En pocas palabras, jamás trabajes fines de semana y vacaciones para cumplir un estimado.

No obstante lo anterior, existen un par de buenas prácticas que te ayudarán a ser más preciso y ayudar a los product owners a priorizar el trabajo pendiente.

El primer punto que debes tener en cuenta es que la estimación es un trabajo de equipo. Es importante que diversos equipos de trabajo colaboren en la estimación. Los Desarrolladores, Diseñadores, Product Managers, etc. tienen diversas perspectivas sobre lo que implica desarrollar una nueva funcionalidad. Cuando la estimación se realiza tomando en cuenta estas perspectivas existe una mayor probabilidad de que la estimación se acerque a la realidad.

Otro punto importante es que las estimaciones funcionan mejor cuando son relativas. Es decir es mejor encontrar un trabajo relativamente sencillo en el que todo el equipo se encuentre de acuerdo y estimar a partir de ese punto. Por ejemplo, si todo el equipo está de acuerdo en que añadir verificación a los campos de un formulario es un 2, entonces estimemos con base en ese acuerdo.

Es importante recordar que cuando estimamos, es buena práctica tener un sistema de estimación en el que el equipo esté de acuerdo. Un ejemplo muy usado en la industria son los puntos Fibonacci. Es decir, se utiliza la secuencia de Fibonacci para asignar pesos a issues (1, 2, 3, 5, 8, 13, etc.). Otra forma, es utilizar tallas de camisas (S, M, L, XL, XXL, etc.). En todo caso, lo importante es que el equipo entienda estos sistemas y los adopte en sus prácticas.

Por último, cuando incluímos a varios miembros del equipo en la estimación es importante que sus opiniones no se vean sesgadas por el resto de sus compañeros. Por eso, una práctica que me gusta mucho es la de jugar “Estimation Poker”. En esta modalidad de estimación, todo el equipo tiene barajas que representan los puntos y cuando se pone a discusión un issue, los miembros del equipo revelan su estimado con las barajas. Si todos están de acuerdo, perfecto. Pero si existen grandes discrepancias es momento de escuchar y de volver a evaluar con la nueva información que nos ha sido proporcionada. En todo caso, lo importante es mejorar con el paso de los sprints y que las estimaciones, quizá nunca perfectas, sean lo más realistas posibles.
