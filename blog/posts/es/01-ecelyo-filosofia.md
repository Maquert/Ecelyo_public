# La filosofía detrás de Ecelyo

Cualquier trabajo complejo comparte una característica incómoda: las ideas aparecen de forma continua, mientras que la capacidad para ejecutarlas siempre es limitada. A medida que un ***proyecto*** crece, la dificultad deja de consistir en generar nuevas iniciativas y pasa a residir en decidir cuáles deben ejecutarse, en qué orden y cómo evitar que unas interfieran con otras.

La mayoría de las herramientas intentan resolver este problema ofreciendo más flexibilidad. Ecelyo adopta la estrategia contraria: reduce deliberadamente el grado de libertad del ***sistema*** para que las decisiones importantes se tomen una sola vez y la ejecución pueda avanzar con la menor fricción posible.

## Una jerarquía orientada al resultado

En Ecelyo se organiza el trabajo mediante una jerarquía estable:

*Sistema* → *Proyecto* → ***Táctica*** → ***Tarea***

El *sistema* representa el resultado que se desea entregar. Puede ser una aplicación, un producto, un libro, una investigación o cualquier otro entregable.

> [!NOTE]
> **Ejemplo**
>
> Una aplicación del ecosistema Apple sigue siendo un único *sistema* aunque se distribuya mediante binarios para iPhone, iPad, macOS y visionOS, porque todos ellos comparten una misma base de conocimiento y se benefician del trabajo realizado sobre ella.

Dentro de ese *sistema*, un *proyecto* representa un **ámbito de responsabilidad**. En una organización este concepto puede coincidir con el de equipo, aunque esa no sea su definición. También puede corresponder a una plataforma, una aplicación concreta, documentación o cualquier otro dominio funcional que agrupe trabajo relacionado.

Las *tácticas* son unidades acotadas de **ejecución**. Cada una persigue un **objetivo único** y contiene una **secuencia** coherente de *tareas*, desde una *tarea* inicial que establece el trabajo hasta una *tarea* final que verifica que el resultado es correcto. Las *tareas*, por su parte, representan acciones concretas; su significado depende del objetivo de la *táctica* a la que pertenecen.

Esta relación es exclusiva: una *tarea* pertenece a una sola *táctica*, una *táctica* a un solo *proyecto* y un *proyecto* a un solo *sistema*. Si una *tarea* deja de compartir el objetivo de su *táctica*, no se la reubica arbitrariamente; debe reconsiderarse la unidad de trabajo a la que pertenece. La **rigidez es intencionada**, porque la pérdida de flexibilidad reduce la ambigüedad y hace que el *sistema* resulte más sencillo de comprender y mantener.

## La captura de tareas ha de ser libre; la ejecución, disciplinada

**Las ideas surgen de manera continua** y en contextos muy distintos: durante una conversación con un cliente, al descubrir un error, mientras se desarrolla una funcionalidad o como consecuencia de una reflexión espontánea. Ecelyo no pretende controlar ese proceso creativo. La metodología reconoce que la captura puede producirse en cualquier momento y desde cualquier lugar; la aplicación interviene cuando una idea entra en el *sistema* y debe convertirse en trabajo estructurado.

**La ejecución**, sin embargo, **exige disciplina**. Cuando ya existe trabajo en curso, una idea nueva no altera automáticamente la prioridad: primero debe terminarse aquello que se había comenzado, salvo que exista una razón explícita para cambiar el plan. De este modo, la libertad de capturar ideas no se convierte en una sucesión interminable de interrupciones.

### Tácticas pequeñas, ciclos que terminan

Las *tácticas* son deliberadamente pequeñas porque su **finalidad** no consiste en acumular trabajo, sino en **conducirlo hasta un punto de cierre**. Cuando una *táctica* crece sin límite, deja de ser una unidad coherente de ejecución y empieza a retrasar la incorporación de nuevas ideas al flujo de trabajo. Mantenerlas acotadas permite que el *sistema* renueve con frecuencia sus puntos de decisión y que las nuevas iniciativas no queden atrapadas detrás de *proyectos* interminables.

## Menos decisiones durante la ejecución

Una consecuencia importante de esta estructura es que reduce la cantidad de decisiones necesarias mientras se trabaja. Cuando un humano o un agente comienza una *tarea*, no debería tener que reconstruir continuamente qué debe hacer a continuación: la prioridad, las dependencias, la *táctica* y el estado del trabajo ya proporcionan ese contexto. **La ejecución debe emerger del flujo, no de decisiones repetidas.**

Ecelyo no intenta reducir el número de ideas; **intenta reducir cuánto tiempo una buena idea queda esperando.** Para lograrlo, no basta con estructurar el trabajo: también hay que ordenar su avance. Las *tácticas* son pequeñas, coherentes y secuenciales por defecto; **el paralelismo aparece cuando la estructura lo hace explícito.** Así, personas y agentes pueden avanzar a la vez sin pisarse, coordinándose mediante una estructura compartida en lugar de conversaciones constantes.

## Impresiones y mi opinión personal

**Esta metodología surge de mi propia experiencia**, después de años trabajando en auténticas epopeyas que tardaban mucho en comenzar —porque abarcaban demasiado y había que dejarlo todo muy bien atado— y, por supuesto, mucho en acabar, si es que acababan y no se quedaban a medias. Para mí, la productividad efectiva solo se obtiene cuando se produce algo como resultado de nuestro esfuerzo; no surge por el proceso en sí. Foco en las tareas, sin tratar de procrastinar pero tampoco de abarcar al mismo tiempo más de lo que lo nuestro cerebro permite.

Han pasado por delante de mí decenas de proyectos, mejor o peor definidos, que quedaban a medio terminar por un cambio brusco de prioridades o, simplemente, porque su definición y ejecución se alargaban lo suficiente como para volverse aparentemente irrelevantes. En el mundo del desarrollo de software, que es el que mejor conozco, el trabajo inacabado, además de frustrante, deja cicatrices que tarde o temprano terminan impactando negativamente en las nuevas ideas que van surgiendo: más base de código que mantener, más complejidad en las tareas futuras —que han de conservar tanto el producto nuevo como aquel que quedó inacabado— y una carga cognitiva que se agrava con el ir y venir de los miembros de un equipo, que viven con el desconocimiento y el temor constantes de romper productos que, sin saberlo, están inacabados y nunca fueron eliminados.

No sé si a ti te pasa como a mí: **las ideas me circulan mucho más rápido que lo que tardo en ejecutarlas** —y no digamos en compilarlas— y, tan pronto como me encuentro en mitad de una tarea, ya tengo ganas de probar algo nuevo o de arreglar algo molesto.

**Ecelyo** es, sencillamente, una **metodología** que añade una **disciplina sencilla** a mi flujo de trabajo y que consigo sostener mediante una aplicación que me sirve de arnés, para no olvidar que, para mí, **son más importantes los pequeños logros del día a día**: dar siempre un paso más hacia delante y aprovechar cada pequeño avance para mejorar el rumbo. 

Es **mejor algo terminado, aunque no sea óptimo, que algo perfecto pero dejado a medias**.
