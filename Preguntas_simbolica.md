# Simbólica

## Examen 2019

Varias respuestas por cada pregunta

1. El conocimiento…
    a. Público es comúnmente aceptado y reconocido
    
    b. Semipúblico es de marcado carácter heurístico
    
    c. Privado no es explícito, no está universalmente reconocido, ni es comúnmente aceptado
    
    d. Todas las anteriores son verdaderas

2. Si I es un conjunto de estados iniciales, O es un conjunto de operaciones permitidas y M es un conjunto de metas, tales que la terna [I, O, M] define un espacio de estados determinado, entonces la expresión O: (I->M) es una forma de representar…

    a. La estrategia básica de resolución de problemas 

    b. Un proceso regresivo de encadenamiento de operadores

    c. El encadenamiento progresivo de hipótesis

    d. La búsqueda o el proceso de exploración del espacio de estados

3. Las funciones heurísticas…
    
    a. Tienen carácter numérico y si n es el nodo inicial, entonces h(n) = 0
    
    b. Cuantas más restricciones tengamos en cuenta para su diseño, menos precisa será la heurística
    
    c. Se consideran admisibles si nunca sobreestiman el coste real de alcanzar la meta
    
    d. Si una heurística domina a otra (∀ n, h2(n) >= h1(n)), A* usando h2 expandirá más nodos que usando h1

4. La búsqueda A*…

    a. Evalúa los nodos combinando las funciones g(n) y h(n), es decir, el coste real del mejor camino para alcanzar el nodo n y el coste estimado del camino menos costoso desde el nodo n a la meta

    b. Basada en grafo es óptima si la heurística es admisible 

    c. Se comporta como anchura si g se incrementa en 1, h=0 y los nodos con igual f se ordenan de menos a más reciente

    d. Se comporta como profundidad si g=0, h=0 y los nodos se ordenan de más a menos reciente

5. Los procedimientos de búsqueda en profundidad…

    a. Demandan más recursos computacionales (en términos temporales) que el procedimiento en anchura

    b. Demandan más recursos de memoria que el procedimiento en anchura 

    c. La versión basada en grafo no es completa en espacios de espacios de estados finitos 

    d. Las complejidades espaciales y temporales de la versión basada en grafo están limitadas por el tamaño del espacio de estados

6. Los demons… 
    a. Proporcionan uniones procedimentales entre frames

    b. Son procedimientos que la mayor parte del tiempo están inactivos

    c. Imprimen carácter estático a la representación del conocimiento con frames

    d. Posibilitan la ejecución de rutinas externas
    
7. Si hablamos de sistemas de producción…
    
    a. La base de conocimientos está formada por la base de hechos y el motor de inferencias 
    
    b. Los sistemas dirigidos por los datos son más específicos, porque ejecutarán todas las reglas disponibles en función de la información introducida 
    
    c. La memoria activa almacena todos los cambios de estado de nuestro sistema, de forma que representa siempre nuestro estado actual
    
    d. El motor de inferencias es el responsable de interaccionar con el mundo exterior

8. Cuando una regla se activa, ¿de qué depende su ejecución?

    a. De la estrategia de resolución de conflictos

    b. Del contenido de la memoria activa 

    c. De la estrategia de exploración del espacio de estados

    d. De ninguna de las anteriores

9. El modelo bayesiano
    
    a. Realiza una asunción de independencia para manifestaciones e interpretaciones
    
    b. No asume relaciones de causalidad
    
    c. Las evidencias a favor de una hipótesis no cuentan en la negación de dicha hipótesis
    
    d. Se utiliza en dominios de naturaleza estadística en los que las soluciones no pueden ser unívocamente obtenidas

10. El procedimiento sistemático para la interpretación diferencial en el contexto de un modelo categórico de razonamiento exige la…

    a. Identificación del conjunto de manifestaciones y del conjunto de interpretaciones

    b. Construcción del conjunto completo de complejos de manifestaciones y del conjunto completo de complejos de interpretaciones

    c. Construcción del conjunto completo de complejos manifestación-interpretación

    d. Construcción del a función booleana de interpretaciones


## 2012

1. En los métodos en anchura, las regiones del espacio de estados en las que todos los estados individuales tienen el mismo valor de la función heurística, se llaman:
    a. Máximos locales.
    
    b. Mínimos locales.
    
    c. Mesetas. 
    
    d. Crestas.
    
    e. Ninguna de las anteriores es correcta.


2. Las represenraciones estructuradas en las que el conocimiento se representa como una colección estática de hechos, para cuya manipulación se define un conjunto genético y restringido de procedimientos son:
    
    a. Métodos determinísticos
    
    b. Métodos heurísticos.
    
    c. Métodos secuenciales.
    
    d. Métodos declarativos.
    
    e. Métodos procedimentales. 

3. Los métodos procedimentales de representación del conocimiento:

    a. Exigen que las verdades del dominio se almacenen una sola vez. 
    
    b. Obligan a incorporar nuevo conocimiento, sin modificar el ya existente. 
    
    c. No explotan adecuadamente las capacidades inferenciales del sistema. 
    
    d. No permiten trabajar con información de caracter probabilístico. 
    
    e. Permiten explorar distintos modelos y técnicas de razonamiento.

4. Los sistemas inteligentes basados en reglas que operan sobre una base de hechos con mecanismos de emparejamiento que forman parte explícita de su arquitectura, se denominan:

    a. Sistemas de producción.
    
    b. Sitemas expertos.
    
    c. Sistemas basados en conocimiento.
    
    d. Sistemas inferenciales.
    
    e. Sistemas heurísticos.

5. En los sistemas de producción, la estructura que contiene toda la información de naturaleza estática necesaria para resolver un problema concreto, se llama:

    a. Base de conocimientos.
    
    b. Base de hechos.
    
    c. Base de reglas.
    
    d. Memoria activa.
    
    e. Motor de inferencias.

6. En el procedimiento sistemático del razonamiento categórico:

    a. La solución a cualquier problema está en la función de conocimiento.
    
    b. Hay que manipular manifestaciones individuales.
    
    c. La solución siempre es única.
    
    d. La base lógica expandida contiene al conjunto de soluciones potenciales que son compatibles con el conocimiento.
    
    e. La base lógica reducida contiene al conjunto de soluciones potenciales que son compatibles con el conocimiento.


## Preguntas random de por ahí

Varias respuestas cada pregunta


1. Si hablamos de algoritmos de búsqueda en árboles:

    a. La búsqueda primero en anchura es óptima y completa siempre. 
    
    b. La búsqueda de profundidad iterativa se debe usar en espacios de búsqueda en los que se conoce la profundidad de la solución. 

    c. La búsqueda preferente en profundidad es óptima pero no es completa. 
    
    **d. Todas las anteriores son falsas.


2. Si hablamos de sistemas de producción…

    a. La base de conocimientos está formada por la base de reglas y el motor de inferencias.

    b. Los sistemas dirigidos por los datos son más específicos porque ejecutarán todas las reglas disponibles en función de la información introducida.

    c. La memoria activa almacena todos los cambios de estado de nuestro sistema de forma que representa siempre nuestro estado actual.

    d. El motor de inferencias es el responsable de interactuar con el mundo exterior.

3. Las heurísticas: (No se que tiene que ver las heuristicas con las respuestas pero bueno JAJAJAJA)
   
    a. En anchura el tiempo y la memoria crecen exponencialmente con la profundidad de la solución.
 
    b. En profundidad el tiempo crece de forma exponencial pero la memoria crece linealmente con la profundidad de la solución.
 
    c. En profundidad el tiempo y la memoria crecen exponencialmente con la profundidad de la solución.
 
    d. En la búsqueda avara el tiempo y la cantidad de memoria necesaria crece exponencialmente con respecto a la profundidad.
 
    e. En la búsqueda A* la cantidad de memoria necesaria crece exponencialmente con respecto a la profundidad.

4. La eficiencia de un algoritmo de búsqueda depende de los parámetros independientes del dominio de aplicación:

    a.  La profundidad y el criterio de selección de estados.

    b.  El factor de ramificación y el número de bucles.
    
    c.  El factor de ramificación y la profundidad.
    
    d.  El coste de expansión de los nodos y el formalismo de representación usado.

5. ¿Qué utilidad tienen los demons?

    a. Proporcionan uniones procedimentales entre frames.

    b. Posibilitan ejecutar rutinas externas.

    c. Desencadenan acciones concretas al ejecutarse.

    d. Permiten el control del razonamiento con frames.

6. En cuanto a tipos de reglas:

    a. El tipo IFALL equivale a una anidación AND de las cláusulas de la pregunta.

    b. El tipo IFSOME equivale a una búsqueda exhaustiva de las cláusulas OR de una misma regla.

    c. El tipo IFANY equivale a una búsqueda exhaustiva en las cláusulas OR de una misma regla.

7. El conocimiento heuristico.
   
    a. Se adquiere directamente de la experiencia

    b. Se adquiere, fundamentalmente, a través del estudio y la meditación

    c. No garantiza encontrar soluciones óptimas, pero si permite el hallazgo de soluciones aceptables

    d. Es un conocimiento dificilmente formalizable, fruto de la experiencia y establecido implicitamente

    e. Es un conocimiento explícito obtenido a través de la observación personal

8. El espacio de estados...
   
    a. Permite representar de manera eficaz y eficiente los procesos de búsqueda

    b. Es la descripción dinamica del universo de discurso o dominio de aplicación (NO es dinámica)
    
    c. Es una descripción formal del universo de discurso
    
    d. Es el encargado de verificar la prueba de meta 
    
    e. Incluye un conjunto de operadores que definen operaciones permitidas entre estados


9.  Los procedimientos de búsqueda en anchura...
    
    a. Expanden un nivel completo, y realizan la prueba de meta sobre todos los nodos generados en ese nivel, antes de pasar nivel siguiente
    
    b. No son ni sistemáticos ni eficientes temporalmente
    
    c. En teoria siempre encuentran la mejor solución
    
    d. Son relativamente rápidos, ya que al proceder por niveles generan relativamente pocos nodos
    
    e. Efectúan la prueba de meta después de recorrer caminos completos hasta agotarlos

10. Los métodos de búsqueda en profundidad..

    a. Demandan más recursos computacionales que el procedimiento en anchura

    b. Permiten que la solución se encuentre por casualidad

    c. Demandan menos recursos computacionales que el procedimiento en anchura 

    d. Demandan más recursos de memoria que el procedimiento en anchura 

    e. Si no encuentran una solución por un camino, organizan una vuelta atrás o "backtracking"

11. El método de búsqueda de ascensión a colinas.

    a. Es un método morto(?) anchura-profundidad que utiliza una función heuristica para decidir sobre que nodo hay que realizar el "backtracking"

    b. Utiliza una función heuristica que se aplica sobre un numero de nodos, en principio no determinado, generados en anchura inmediatamente después de haber efectuado la vuelta atrás

    c. Es un procedimiento de resolución de problemas en el cual pueden aparecer situaciones indeseables como maximos (o minimos) locales, mesetas y crestas

    d. Se caracteriza porque nunca puede haber mas de un operador que empareje completamente con nuestro estado actual

    e. Es un procedimiento de búsqueda en anchura casi puro en el que la prueba de meta se aplica después de recorrer un camino completo hasta agotarlo

12. Una región del espacio de estados en la que todos los estados individuales tienen el mismo valor de la función heuristica y, por lo tanto, no ea posible determinar la mejor dirección para continuar se denomina.

    a. Conflicto

    b. Maximo (o minimo) local

    c. Estribación

    d. Cresta

    e. Meseta

13. Geneticamente hablando, la lógica que permite obtener conocimiento nuevo a partir de conocimiento ya existente, mediante procesos preferentemente deductivos, se denomina

    a. Lógica de Proposiciones

    b. Logica de Predicados

    c. Logica de Primer Orden

    d. Logica Formal

    e. Logica No Monotona

14. Señale las respuestas correctas

    a. En logica formal, una aseveración es un axioma si podemos demostrar que se deduce a partir de otras aseveraciones que se sabe que son ciertas

    b. En logica formal, un axioma es una aseveración podemos demostrar que se deduce a partir de otros axiomas que se sabe que son ciertos

    c. En logica formal, una inferencia es cierta si podemos demostrar que se deduce a partir de otros simbolos que no sabe que son ciertos

    d. En logica formal, una fórmula atómica es cierta si podemos demostrar que se deduce a partir de otras inferencias que se sabe que son ciertas

    e. En logica formal, una aseveración es cierta si podemos demostrar que se deduce a partir de otras aseveraciones que se sabe que son ciertas

15. Los sistemas de producción...

    a. Son sistemas inteligentes basados en reglas

    b. Representan el conocimiento declarativo como reglas, y el procedimental como frames

    c. Incorpora de forma explicita en su estructura los mecanismos de emparejamiento

    d. Representar el conocimiento procedimental como reglas, y el declarativo como frames

    e. Incorpora de forma implicita en su estructura los mecanismos de emparejamiento 


16. En relación con los sistemas de producción...
    
    a. En los sistemas dirigidos por los datos las inferencias se obtienen cuando los antecedentes de una (o mas) de sus reglas se emparejan con (al menos) una parte de los hechos que describen el estado actual
    
    b. En los sistemas dirigidos por los objetivos las inferencias se obtienen cuando los antecedentes de una (o más) de sus reglas se emparejan con (al menos) una parte de los hechos que describen el estado actual
    
    c. En los sistemas dirigidos por los datos la meta se alcanza mediante un proceso evocativo en el que, de forma recursiva, se establecen los antecedentes de las metas como submetas de orden inferior
    
    d. En los sistemas dirigidos por los objetivos la meta se alcanza mediante un proceso evocativo en el que de forma recursiva, se establecen los antecedentes de las metas como submetas de orden inferior
    
    e. En los sistemas dirigidos por los objetivos antecedentes y consecuentes son aserciones sobre los datos


18. En los sistemas de producción, la entidad que describe el universo de discurso que se quiere modelar se denomina...
    
    a. Base de reglas
    
    b. Memoria activa
    
    c. Motor de inferencias
    
    d. Base de conocimientos
    
    e. Base de hechos


19. El motor de inferencias de un sistema de producción...

    a. Interactua con el mundo exterior a través de la base de hechos

    b. Reconoce y activa las reglas en función de los criterios de activación elegidos

    c. Interactua con el mundo exterior a través de la base reglas

    d. Interactua con el mundo exterior a traves de la base de conocimientos

    e. Contiene los mecanismos necesarios para examinar la memoria activa y determinar que reglas deben ejecutarse


20. En los sistemas de producción, las hipótesis de trabajo y las metas o submetas que todavía no han sido establecidas, forman parte de..
    
    a. La base de conocimientos
    
    b. La base de reglas
    
    c. La base de hechos
    
    d. La memoria activa
    
    e. El motor de inferencias

21. Cuando un proceso inferencial se detiene, la memoria activa contiene una descripción del estado final del problema, que incluye...

    a. Datos
    
    b. Hechos
    
    c. Reglas activas
    
    d. Reglas ejecutadas
    
    e. Hipotesis


23. En el motor de inferencias, el programa secuencial cuya mision es determinar el siguiente paso que debe ejecutarse, se denomina..
    
    a. Emparejador

    b. Elicitador
    
    c. Intérprete
    
    d. Cotejador
    
    e. Compilador

24. El ciclo basico de un sistema de producción esta constituido por las fases de...
    
    a. Diferenciación
    
    b. Decision
    
    c. Selección de reglas
    
    d. Acción
    
    e. Ejecución de reglas


25. La Restricción es una tarea de la fase de..
    
    a. Activación
    
    b. Equiparación
    
    c. Cotejo
    
    d. Acción
    
    e. Decisión

26. La ejecución de las reglas seleccionadas, en la fase de acción, concluye con...

    a. El proceso inferencial

    b. La verificación de si continuar o no el proceso ciclico
    
    c. El proceso evocativo
    
    d. El marcaje de las estructuras utilizadas
    
    e. La actualización de la memoria activa