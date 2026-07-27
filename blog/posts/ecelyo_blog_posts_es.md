# Artículos de Ecelyo

## Artículo 1: La filosofía detrás de Ecelyo

Cualquier trabajo complejo comparte una característica incómoda: las ideas aparecen de forma continua, mientras que la capacidad para ejecutarlas siempre es limitada. A medida que un proyecto crece, la dificultad deja de consistir en generar nuevas iniciativas y pasa a residir en decidir cuáles deben ejecutarse, en qué orden y cómo evitar que unas interfieran con otras.

La mayoría de las herramientas intentan resolver este problema ofreciendo más flexibilidad. Ecelyo adopta la estrategia contraria: reduce deliberadamente el grado de libertad del sistema para que las decisiones importantes se tomen una sola vez y la ejecución pueda avanzar con la menor fricción posible.

### Una jerarquía orientada al resultado

Ecelyo organiza el trabajo mediante una jerarquía estable:

```text
Sistema → Proyecto → Táctica → Tarea
```

El sistema representa el resultado que se desea entregar. Puede ser una aplicación, un producto, un libro, una investigación o cualquier otro entregable. Una aplicación del ecosistema Apple, por ejemplo, sigue siendo un único sistema aunque se distribuya mediante binarios para iPhone, iPad, macOS y visionOS, porque todos ellos comparten una misma base de conocimiento y se benefician del trabajo realizado sobre ella.

Dentro de ese sistema, un proyecto representa un ámbito de responsabilidad. En una organización puede coincidir con un equipo, aunque esa no sea su definición: también puede corresponder a una plataforma, una aplicación concreta, la documentación o cualquier otro dominio funcional que agrupe trabajo relacionado.

Las tácticas son unidades acotadas de ejecución. Cada una persigue un objetivo único y contiene una secuencia coherente de tareas, desde una tarea inicial que establece el trabajo hasta una tarea final que verifica que el resultado es correcto. Las tareas, por su parte, representan acciones concretas; su significado depende del objetivo de la táctica a la que pertenecen.

Esta relación es exclusiva: una tarea pertenece a una sola táctica, una táctica a un solo proyecto y un proyecto a un solo sistema. Si una tarea deja de compartir el objetivo de su táctica, no se la reubica arbitrariamente; debe reconsiderarse la unidad de trabajo a la que pertenece. La rigidez es intencionada, porque la pérdida de flexibilidad reduce la ambigüedad y hace que el sistema resulte más sencillo de comprender y mantener.

### Capturar es libre; ejecutar es disciplinado

Las ideas surgen de manera continua y en contextos muy distintos: durante una conversación con un cliente, al descubrir un error, mientras se desarrolla una funcionalidad o como consecuencia de una reflexión espontánea. Ecelyo no pretende controlar ese proceso creativo. La metodología reconoce que la captura puede producirse en cualquier momento y desde cualquier lugar; la aplicación interviene cuando una idea entra en el sistema y debe convertirse en trabajo estructurado.

La ejecución, sin embargo, exige disciplina. Cuando ya existe trabajo en curso, una idea nueva no altera automáticamente la prioridad: primero debe terminarse aquello que se había comenzado, salvo que exista una razón explícita para cambiar el plan. De este modo, la libertad de capturar ideas no se convierte en una sucesión interminable de interrupciones.

### Tácticas pequeñas, ciclos que terminan

Las tácticas son deliberadamente pequeñas porque su finalidad no consiste en acumular trabajo, sino en conducirlo hasta un punto de cierre. Cuando una táctica crece sin límite, deja de ser una unidad coherente de ejecución y empieza a retrasar la incorporación de nuevas ideas al flujo de trabajo. Mantenerlas acotadas permite que el sistema renueve con frecuencia sus puntos de decisión y que las nuevas iniciativas no queden atrapadas detrás de proyectos interminables.

### Menos decisiones durante la ejecución

Una consecuencia importante de esta estructura es que reduce la cantidad de decisiones necesarias mientras se trabaja. Cuando un humano o un agente comienza una tarea, no debería tener que reconstruir continuamente qué debe hacer a continuación: la prioridad, las dependencias, la táctica y el estado del trabajo ya proporcionan ese contexto. La ejecución debe emerger del flujo, no de decisiones repetidas.

Ecelyo no intenta reducir el número de ideas; intenta reducir cuánto tiempo una buena idea permanece esperando. Para lograrlo, no basta con estructurar el trabajo: también hay que ordenar su avance. Las tácticas son pequeñas, coherentes y secuenciales por defecto; el paralelismo aparece cuando la estructura lo hace explícito. Así, personas y agentes pueden avanzar a la vez sin pisarse, coordinándose mediante una estructura compartida en lugar de conversaciones constantes.

## Artículo 2: Coordinar humanos y agentes mediante flujos de trabajo explícitos

Organizar el trabajo de una persona es un problema distinto de coordinar el trabajo simultáneo de varias personas y agentes. Cuando varios actores colaboran sobre un mismo sistema, una tarea aislada no proporciona suficiente contexto: dos agentes pueden modificar el mismo componente, una persona puede comenzar un trabajo que depende de otro aún no terminado o varias iniciativas pueden acabar duplicándose.

Ecelyo responde a este problema tratando la unidad de coordinación no como una tarea suelta, sino como el flujo completo de una táctica.

### El tablero de ruta

El tablero de ruta representa explícitamente la secuencia de trabajo. Las tareas no forman una lista indiferenciada, sino un flujo dirigido en el que cada tarea tiene una predecesora, salvo la tarea inicial, y una sucesora, salvo la tarea de validación. Esta estructura convierte la táctica en una historia completa: comienza definiendo o preparando el trabajo, avanza mediante acciones relacionadas y termina verificando el resultado.

La secuencialidad constituye el caso base porque protege la coherencia. Si dos tareas dependen entre sí o son suficientemente parecidas como para interferirse, ejecutarlas simultáneamente introduce riesgos innecesarios. La dependencia queda representada en el propio sistema, de modo que el siguiente actor puede comenzar cuando el anterior haya dejado disponible su resultado.

### El paralelismo emerge de la estructura

Una tarea puede tener varias hijas. Cuando eso ocurre, el flujo se ramifica y las ramas pueden ejecutarse en paralelo, siempre que su independencia esté justificada por el diseño de la táctica. El paralelismo no se improvisa por entusiasmo ni se decide únicamente porque haya varios agentes disponibles: aparece cuando el grafo de tareas demuestra que varias líneas de trabajo pueden avanzar sin bloquearse ni pisarse.

La estructura, por tanto, no limita la colaboración; la hace segura. En lugar de exigir conversaciones constantes para coordinar cada movimiento, ofrece a los actores un contexto común que indica qué puede comenzar, qué debe esperar y qué resultado se espera de cada tarea.

### Una tarea preparada para ser ejecutada

Una idea puede capturarse de manera preliminar, pero no debería entrar en el flujo de ejecución mientras conserve ambigüedades esenciales. Antes de que un humano o un agente la tome, debe refinarse hasta convertirse en una tarea autoexplicativa: debe pertenecer a una táctica concreta, tener una prioridad, comenzar en estado dependiente cuando así lo exija su posición en el flujo y contener la información necesaria para actuar sin reconstruir las intenciones de quien la creó.

El refinamiento no tiene por qué ser perfecto desde el primer momento; puede recibir ajustes posteriores. Lo importante es que el trabajo que se ofrece para ejecución sea suficientemente claro como para que el actor no tenga que interpretar lo más importante ni decidir por su cuenta qué significa realmente la tarea.

### La siguiente tarea no se elige desde cero

Cuando un agente recibe la instrucción de tomar la siguiente tarea, no necesita recibir además una orden detallada sobre cuál debe escoger. El sistema puede determinarla a partir de la prioridad, el estado, las dependencias y la posición de cada tarea dentro de su táctica. Así, el agente puede concentrarse en ejecutar, mientras que las decisiones de planificación se toman en el diseño y el mantenimiento del flujo.

El flujo no elimina la necesidad de decidir; sitúa las decisiones en los lugares adecuados. Se decide al definir el objetivo, al refinar una tarea, al establecer una dependencia o al abrir una bifurcación. Una vez que esas decisiones han quedado expresadas, la ejecución puede avanzar con menor carga cognitiva y con menos posibilidades de conflicto.

## Artículo 3: La aplicación como materialización de la metodología

La aplicación de Ecelyo no define la metodología; la metodología define la aplicación. Cada pantalla, cada tablero y cada regla de interacción existe para hacer visible una decisión conceptual: la jerarquía, la secuencia, la prioridad, la responsabilidad y la verificación no son explicaciones añadidas al producto, sino propiedades que el producto debe expresar.

### Una navegación que refleja la jerarquía

La navegación sigue la relación entre sistema, proyecto, táctica y tarea. El sistema permite entender qué resultado se está construyendo; los proyectos separan los ámbitos de responsabilidad; las tácticas presentan unidades coherentes de ejecución; y las tareas muestran las acciones concretas que hacen avanzar cada objetivo. Al conservar la pertenencia exclusiva, la aplicación evita que el mismo trabajo adquiera significados contradictorios en distintos lugares.

### El tablero de ruta como representación del flujo

El tablero de ruta no es simplemente otra forma de ordenar tarjetas. Su finalidad es mostrar qué tareas dependen de otras, dónde puede continuar el trabajo y en qué puntos se abre una ejecución paralela. La interfaz convierte las dependencias en una estructura visible, de manera que un humano o un agente pueda comprender el orden de ejecución sin tener que inferirlo a partir de conversaciones o de una lista extensa.

### Prioridad y selección del trabajo

La aplicación debe hacer visible qué trabajo está en curso, qué puede comenzar y qué debería cerrarse antes de abrir un nuevo frente. La prioridad no se entiende como una clasificación decorativa, sino como una señal que participa en la selección del siguiente trabajo ejecutable. El objetivo es que el actor pueda tomar la siguiente tarea con el contexto suficiente y sin tener que reconstruir manualmente todo el plan.

### Actores y responsabilidades

El diccionario de actores proporciona un lenguaje común para la colaboración entre personas y agentes. Cada actor tiene un papel definido, unas responsabilidades reconocibles y un lugar dentro del proceso de ejecución. Esta distinción evita que todos hagan de todo y permite asignar el trabajo de manera explícita, especialmente cuando varias líneas de trabajo avanzan en paralelo.

### La captura queda fuera; la estructuración queda dentro

Las ideas nacen fuera de la aplicación, en conversaciones, reuniones, documentos, incidencias o intercambios con clientes y agentes. Ecelyo no pretende sustituir ese proceso creativo ni imponer un único mecanismo para producir ideas. Su responsabilidad comienza cuando una idea se incorpora al sistema: a partir de ese momento debe quedar suficientemente estructurada para que pueda convertirse en trabajo ejecutable.

La interfaz, por tanto, no intenta enseñar una metodología mediante instrucciones abstractas. Hace que la metodología sea visible en la forma de organizar el trabajo, establecer dependencias, asignar responsabilidades, seleccionar prioridades y comprobar resultados. La aplicación no es el origen de las reglas; es la consecuencia de haberlas tomado en serio.

### Conclusión

Ecelyo transforma una filosofía de trabajo en una estructura operativa. La jerarquía limita la ambigüedad, las tácticas acotadas permiten cerrar ciclos, el tablero de ruta ordena el avance, las dependencias hacen posible el paralelismo seguro y el diccionario de actores coordina a quienes participan en la ejecución. La interfaz reúne esas decisiones para que el sistema pueda guiar el trabajo sin exigir que cada actor vuelva a decidirlo todo desde cero.
