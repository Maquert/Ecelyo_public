# Coordinar humanos y agentes mediante flujos de trabajo explícitos

Organizar el trabajo de una persona es un problema distinto de coordinar el trabajo simultáneo de varias personas y agentes. Cuando varios actores colaboran sobre un mismo sistema, una tarea aislada no proporciona suficiente contexto: dos agentes pueden modificar el mismo componente, una persona puede comenzar un trabajo que depende de otro aún no terminado o varias iniciativas pueden acabar duplicándose.

Ecelyo responde a este problema tratando la unidad de coordinación no como una tarea suelta, sino como el flujo completo de una táctica.

## El tablero de ruta

El tablero de ruta representa explícitamente la secuencia de trabajo. Las tareas no forman una lista indiferenciada, sino un flujo dirigido en el que cada tarea tiene una predecesora, salvo la tarea inicial, y una sucesora, salvo la tarea de validación. Esta estructura convierte la táctica en una historia completa: comienza definiendo o preparando el trabajo, avanza mediante acciones relacionadas y termina verificando el resultado.

La secuencialidad constituye el caso base porque protege la coherencia. Si dos tareas dependen entre sí o son suficientemente parecidas como para interferirse, ejecutarlas simultáneamente introduce riesgos innecesarios. La dependencia queda representada en el propio sistema, de modo que el siguiente actor puede comenzar cuando el anterior haya dejado disponible su resultado.

## El paralelismo emerge de la estructura

Una tarea puede tener varias hijas. Cuando eso ocurre, el flujo se ramifica y las ramas pueden ejecutarse en paralelo, siempre que su independencia esté justificada por el diseño de la táctica. El paralelismo no se improvisa por entusiasmo ni se decide únicamente porque haya varios agentes disponibles: aparece cuando el grafo de tareas demuestra que varias líneas de trabajo pueden avanzar sin bloquearse ni pisarse.

La estructura, por tanto, no limita la colaboración; la hace segura. En lugar de exigir conversaciones constantes para coordinar cada movimiento, ofrece a los actores un contexto común que indica qué puede comenzar, qué debe esperar y qué resultado se espera de cada tarea.

## Una tarea preparada para ser ejecutada

Una idea puede capturarse de manera preliminar, pero no debería entrar en el flujo de ejecución mientras conserve ambigüedades esenciales. Antes de que un humano o un agente la tome, debe refinarse hasta convertirse en una tarea autoexplicativa: debe pertenecer a una táctica concreta, tener una prioridad, comenzar en estado dependiente cuando así lo exija su posición en el flujo y contener la información necesaria para actuar sin reconstruir las intenciones de quien la creó.

El refinamiento no tiene por qué ser perfecto desde el primer momento; puede recibir ajustes posteriores. Lo importante es que el trabajo que se ofrece para ejecución sea suficientemente claro como para que el actor no tenga que interpretar lo más importante ni decidir por su cuenta qué significa realmente la tarea.

## La siguiente tarea no se elige desde cero

Cuando un agente recibe la instrucción de tomar la siguiente tarea, no necesita recibir además una orden detallada sobre cuál debe escoger. El sistema puede determinarla a partir de la prioridad, el estado, las dependencias y la posición de cada tarea dentro de su táctica. Así, el agente puede concentrarse en ejecutar, mientras que las decisiones de planificación se toman en el diseño y el mantenimiento del flujo.

El flujo no elimina la necesidad de decidir; sitúa las decisiones en los lugares adecuados. Se decide al definir el objetivo, al refinar una tarea, al establecer una dependencia o al abrir una bifurcación. Una vez que esas decisiones han quedado expresadas, la ejecución puede avanzar con menor carga cognitiva y con menos posibilidades de conflicto.
