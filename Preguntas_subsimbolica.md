
## Subsimbólica

### Examen 2022

1. Al recibir las entradas de una neurona artificial, estas se combinan en primer lugar mediante una:

    a. Función de activación 

    b. Regla delta 

    c. Regla de propagación

    d. Función de transferencia

    e. Función de validación 

2. El adaline...

    a. No tiene capas ocultas.

    b. Tiene una función de transferencia de tipo sigmoidal.

    c. No puede ser entrenado con la Regla Delta. 

    d. Es capaz de aprender cualquier relación entrada/salida. 

3. La Regla Delta...

    a. Modifica los pesos en el sentido (signo) del cambio realizado en el ciclo anterior.

    b. Mofifica los pesos en el sentido (signo) opuesto del cambio realizado en el ciclo anterior.

    c. Modifica los pesos en el sentido (signo) de la pendiente del error.

    d. Modifica los pesos en el sentido (signo) opuesto a la pendiente del error.

    e. Todas son falsas. 

4. Al entrenar una RNA, el algoritmo de entrenamiento dice que la modificación de los pesos se debe de multiplicar por una constante llamada...

    a. Momento.

    b. Gradiente. 

    c. Delta.

    d. Tasa de aprendizaje.

    e. Bias. 

5. Si durante el entrenamiento de una RNA, en un ciclo se obtiene un gradiente 0, esto quiere decir:

    a. Se está lejos de un mínimo.

    b. Se está muy cerca de un mínimo, pero no en él.

    c. Se está en un mínimo, y es global.

    d. Se está en un mínimo, pero no se sabe si es el global o uno local.

    e. El error es 0.

6. Las neuronas de la capa de entrada de un perceptrón multicapa...

    a. Aplica la función de transferencia a las entradas que reciben.

    b. Emiten su salida como la suma de las entradas multiplicadas por los pesos.

    c. Emiten su salida como la suma de las entradas multiplicadas por los pesos.

    d. Emiten su salida como el resultado de aplciar la funcón de transferencia a la suma de las entradas multiplicadas por los pesos.

    e. Todas son falsas.

7. El número de neuronas ocultas de un perceptrón multicapa

    a. Lo puede fijar el usuario como quiera.

    b. Depende del problema a resolver.

    c. Debe ser igual al número de neuronas de entrada, y lo puede fijar el usuario como quiera.

    d. Debe ser igual al número de neuronas de entrada, pero depende del problema a resolver.

    e. Debe ser igual al número de neuronas de salida, y lo puede fijar el usuario como quiera.

8. Un perceptrón multicapa tiene la capacidad de separar todos los patrones de entrenamiento de un problema de clasificación con un 100% de acierto cuando estos patrones...

    a. No están entremezclados, tenga el numero de neuronas que tenga. 

    b. Solo cuando son linealmente separables. 

    c. Están clasificados en más de dos clases distintas. 

    d. En cualquier caso, si la red tiene la complejidad suficiente.

9. Si a un perceptrón multicapa entrenado se le presenta un patrón en una zona donde no hubo patrones de entrenamiento

    a. Dará error en su funcionamiento.

    b. Dará una salida de 0 siempre.

    c. Dará una salida de -1 siempre.

    d. Dará una salida de 1 siempre.

    e. Dará una salida arbitraria e imprevisible.

10. Si al entrenar una RNA se utiliza una tasa de aprendizaje muy alta

    a. Se acercará el error con cambios muy pequeños.

    b. Se correrá el riesgo de oscilar en torno al mínimo.

    c. El entrenamento se parará siempre en un mínimo local.

    d. El entrenamiento se parará siempre en un mínimo global.

    e. Se sobreentrenará la red.

11. El hecho de entrenar una RNA mediante un algoritmo de entrenamiento basado en el gradiente descendente tiene el problema de que

    a. Nunca va a encontrar el mínimo global.

    b. Al acercarse a un mínimo, se va a oscilar de un lado a otro, sin lograr pararse en él.

    c. Se va a acercar a un mínimo con incrementos muy pequeños.

    d. Es posible que se quede parado en algún mínimo local.

    e. Va a necesitar un número muy alto de ciclos para alcanzar un error aceptable.

12. En una RNA, el conjunto de test

    a. Se utiliza para evaluar la capacidad de generalización de la red.

    b. Debe ser linealmente separable. 

    c. Produce la modificación de los pesos mediante el algoritmo correspondiente. 

    d. No produce la modificación de los pesos, pero controla el proceso de entrenamiento y lo para si es necesario.

13. Las técnicas de regularización permiten

    a. Entrenar una RNA hasta alcanzar un error de 0.

    b. Saltar mínimos locales al entrenar una RNA.

    c. Eliminar el ruido del conjunto de entrenamiento.

    d. Resolver problemas de clasificación linelamente separables.

    e. Evitar el sobreentrenamiento al entrenar una RNA.

14. Para usar una RNA para resolver un problema de clasificación con dos clases, sin posibilidad de que un patrón no pertenezca a ninguna de las dos clases, el número de neuronas de salida que hay que usar es:

    a. 1

    b. 2

    c. 3

    d. 4

    e. 5

15. La autoorganización en Sistemas Conexionistas...

    a. Permite que exista un jefe que determine el comprotamiento de los patrones. 

    b. Impide un comportamiento emergente del sistema. 

    c. Facilita que la información se guarde en las neuronas de entrada.

    d. Permite que se obtenga redundancia en los datos.

    e. Todas las anteriores son incorrectas.


16. En la corteza cerebral...

    a. La ubicación espacial de las neuronas constituye un mapa organizado.

    b. Todas las neuronas idénticas realizan la misma función.

    c. La ubicación de las neuronas no es significativa.

    d. Todas las anteriores son correctas.

    e. Todas las anteriores son incorrectas.


17. Si los patrones de entrada de un problema tienen 2 características o atributos, una Growing Cell Structure (GCS) que lo resuelva tendrá...

    a. 1 neurona de entrada.

    b. 2^2 neuronas de entrada.

    c. 6 neuronas de entrada.

    d. 8 neuronas de entrada.

    e. Todas las anteriores son incorrectas.

18. Diferencias entre SOM Y GCS son:

    a. Las GCS no consideran neuronas vecinas a la ganadora.

    b. Un SOM considera un radio de vecindad de diferentes niveles.

    c. Las GCS se consideran solamente vecinas directas de la ganadora.

    d. No hay diferencia en cuestión de vecindario, la diferencia está en la variación dinámica del numero de neuronas de la capa competitiva.

    e. B y C son correctas.

19. Una GCS...

    a. Siempre está orientada a clasificación. 

    b. Permite añadir neuronas en regiones con menos patrones de entrenamiento. 

    c. Tiene una capa de salida formada por diferentes estructuras k-dimensionales básicas a la vez.

    d. No se entrena, sus pesos se construyen a partir de los patrones de entrada.

    e. Todas las anteriores son incorrectas.

20. Los Mapas Autoorganizativos (SOM) tienen normalmente

    a. Una sola capa de entrada, tres o cuatro capas ocultas y una capa de salida.

    b. Una única capa que es de entrada y salida.

    c. Una capa de entrada y una capa de salida.

    d. Una capa de neuronas recurrentes y autoorganizables.

    e. Todas las anteriores son incorrectas.

21. En el aprendizaje no supervisado

    a. Se consiguen grupos con elementos similares dentro del mismo grupo.

    b. La autoorganización de la red permite hallar las clases supervisadas.

    c. Se trabaja con patrones etiquetas con tipo o clase.

    d. Si un patrón de entrada no pertenece a ningún grupo reconocido previamente, se descarta siempre.

22. En un SOM

    a. Cada neurona de la capa competitiva representa siempre a un sólo patrón de entrada.

    b. Cada neurona de la capa competitiva puede representar a un grupo de patrones de entrada.

    c. Cada neurona de la capa de entrada representa a un prototipo.

    d. Cada neurona de la capa de entrada se conecta con x neuronas y estas x conexiones constituyen un prototipo.

    e. la A y la C son correctas.

23. Si los patrones de entrada tienen diferentes dimensiones, la red más aconsejable para agruparlos es

    a. Un SOM 

    b. Una GNG

    c. Un ADALINE

    d. Una GCS 

    e. Ninguana delas anteriores.

24. Las tasas de aprendizaje para redes GCS son

    a. Las mismas que para redes SOM.

    b. Dos tasas diferenciadas.

    c. Una tasa única de aprendizaje en todos los casos.

    d. La A y la B son correctas.

    e. Ninguna de las anteriores es correcta.


25. Las redes de neuronas con entrenamiento no supervisado

    a. Tienen un fundamento biológico, se basan en la corteza cerebral.

    b. Se llaman así porque su supervisor no sabe supervisarlas.

    c. No son de utilidad actualmente.

    d. la B y la C son correctas.

    e. Ninguna de las anteriores es correcta.


26. El problema del viajante con una SOM

    a. Se resuelve considerando una vecindad lineal.

    b. Se resuelve sin vecindad.

    c. Nunca se puede resolver.

    d. la B y la C son correctas.

    e. Ninguna de las anteriores es correcta.

27. Los trabajo de uno de los siguientes investigadores NO forman parte de la inspiración biológica que se utilizó como base para conformar el cómo funcionan los algoritmos genéticos ¿Cual?

    a. Gregor Mendel

    b. Alfred Wallace

    c. Charles Darwin

    d. John H. Holland

28. Se recomienda y está más justificado el uso de los Algoritmos Genéticos...

    a. En aquellos problemas cuya complejidad permita una solución directa.

    b. En aquellos problemas cuya complejidad no permita una solución directa.

    c. En los problemas resolubres polinomialmente.

    d. Siempre es recomendado su uso.

29. ¿Cual de los siguientes operadores genéticos es el responsable de explotar la información presente en la población?

    a. Clonación.

    b. Cruce.

    c. Mutación.

    d. Remplazo.

    e. Selección.

30. El objetivo del operador de mutación es...

    a. Reducir la diversidad en la población.

    b. Explotar el espacio de búsqueda.

    c. Explotar la información que está en la población.

    d. Seleccionar aquellos individuos que son mejores en función de su función de ajuste.

    e. En un esquema steady-state, decir que individuos deben de desecharse para hacer sitio a los nuevos.

31. ¿Cual de las siguientes afirmaciones es cierta en relación a los algoritmos genéticos?

    a. Las soluciones deben de ser codificadas en forma de árbol.

    b. Las poblaciones grandes favorecen una evolución más rápida.

    c. El esquema de remplazo generacional utiliza menos memoria.

    d. Las funciones de ajuste deben de poder evaluarse en cada individuo de la población.

    e. El criterio de parada debe ser único.

32. "Elitismo" en Algoritmos genéticos

    a. No existe este concepto.

    b. Sólo es aplicable a la Programación Genética.

    c. Es la estrategia de mantener los mejores individuos en la población.

    d. Se encarga de busca los mejores individuos y con ellos generar una nueva población.

    e. La nueva población es generada a partir exclusivamente del mejor individuo.

33. En Algoritmos Genéticos existen las técnicas de selección denominadas:

    a. Profundidad y anchura.

    b. Recombinación puntual y uniforme.

    c. Ruleta y torneo.

    d. Cruce y mutación.

    e. Combinatoria múltiple y estocástica uniforme.


34. En un Algoritmo Genético el término "Generación"

    a. Representa cada ciclo de funcionamiento del algoritmo.

    b. En el mecanismo de gestión "Steady-State" representa el cambio de todos los individuos por los hijos.

    c. Representa seleccionar al mejor individuo de cada población y copiarlo a la siguiente población.

    d. No existe este concepto en Algoritmos Genéticos.

    e. Niguna de las anteriores.

35. La denominación "Steady-State" en términos de un Algoritmo Genético es

    a. El mecanismo mediante el cual se mantiene a los mejores individuos en una población.

    b. Un tipo de gestión de la población de individuos. En este tipo también hay que especificar el tipo de sustitución de individuos.

    c. Una forma de crear la piblación de descendientes antes de eliminar la ponlación de los padres y pasar a la siguiente generación.

    d. Una forma de combinar los Algoritmos Genéticos con técnicas de optimización local.

    e. No existe esta palabra en estos sistemas.

36. En Programación Genética, 

    a. No se puede aplicar la operación genética de cruce sobre los individuos de la polblación.

    b. La codificación del problema nunca se puede realizar en términos similares a la programación, no se puede representar individuo como un conjutno de instrucciones 
    generadas en un lenguaje de programación.

    c. No se puede aplicar la estrategia elitista igual que en los Algoritmos Genéticos, hay que adaptarla a esta nueva técnica.

    d. El algoritmo de evolución de la población de individuos es igual al de los Algoritmos Genéticos.

    e. No se permite la generación automática de programas como mecanismo de solución de un determinado problema.

37. El "hill climbing" con respecto a las técnicas de Computación Evolutiva

    a. Mejora los individuos para acelerar que se encuentre un óptimo local.

    b. Es una técnica para mejorar la generación de la población inicial.

    c. Se aplica a un solo individuo de cada generación.

    d. No se puede aplicar si se está usando elitismo.

    e. Es una técnica de cruce que funciona mejor que el de dos puntos.

38. ¿Cuál de las siguiente afirmaciones es cierta a cerca de la función de fitness?

    a. La programación genética no utiliza este elemento que está solo presente en los Algoritmos Genéticos

    b. Se evalúa solo sobre el mejor individuo de la población.

    c. Sirve para determinar cuáles son los mejores individuos de la población.

    d. Se ejecuta sobre la población como un todo para hacer competir a las soluciones unas contra otras.

    e. Es la función que marca cuando se cambia de una generación a la siguiente.

39. En los algoritmos de sustitución para nuevos individuos

    a. La sustitución de peores es la más rápida y, por tanto, la mejor.

    b. La sustitución de padres es la mejor porque al escoger entre padres e hijos no se pierde variabilidad.

    c. Lo mejor es no sustituir y que la población crezca indefinidamente para que haya más variabilidad.

    d. La sustitución de parecidos hace que la evolución avance muy despacio porque todos se van a parecer.

    e. La mejor opción es utilizar las tres técnicas, peores, padres y parecidos a la vez. 

40.	En un Algoribno Genético
    a. Si la tasa de mutación es cero, el algoritmo funciona porque el cruce hace que haya evolución

    b. Si la tasa de cruce es cero, la mutación hace que todos los individuos acumulen demasiados cambios.

    c. Si la tasa de cruce es cero, la mutación genera variabilidad y el algoritmo de selección hace que haya evolución.

    d. Si la tasa de cruce y evolución son cero, el algoritmo de selección prevalece y hace que haya evolución

    e. Es imposible que el cruce y /o la mutación sean cero



### Examen 2019 

(Solo las no repetidas)

1. La palabra "fitness" en terminos de un Algoritmo Genético es 

    a. No existe esta palabra en estos sistemas.

    b. Una forma o función de evaluación de los individuos en términos de conveniencia o adaptación.

    c. Una operación genética que cambia lo composición de los descendientes.

    d. Una forma de crear una población de soluciones.

    e. Una técnica que permite evaluar la complejidad computacional de cada individuo de la población.

2. En una simulación de un Algoritmo Genético, 

    a. Al principio interesa que el ratio de mutación sea alto.

    b. Al principio interesa que el ratio de cruce sea alto.

    c. Los ratios de cruce y mutación deben ser iguales.

    d. El ratio de mutación puede ser cero.

    e. Dan igual los valores de cruce y mutación siemore qe la selección sea por ruleta.

3. En los individuos de un sistema de Programación Genética,...

    a. Los terminales son operadores.

    b. No puede haber nunca operadores aritméticos como nodos del árbol.

    c. Los terminales pueden ser constantes o variables.

    d. Los nodos pueden ser también terminales.

    e. Los nodos son siempre valores constantes.

4. La técnica de Algoritmos Genéticos
   
    a. No funciona bien cuando existen múltiples mínimos locales en el espacio de búsqueda.

    b. Permite resolver problemas en espacios de búsqueda donde existen múltiples mínimos locales.

    c. Presenta problemas cuando el espacio de búsqueda es poco convexo y muy variado.

    d. Es una técnica de búsqueda exhaustiva de soluciones denominada "técnica determinística".

    e. Sólo permite realizar regresión simbólica y búsqueda de máximos o de mínimo en funciones en 1 o 2 variables.

5. Las redes de neuronas recurrentes son aquellas que...

    a. Usan varias técnicas recurrentes para construir un patrón.

    b. Permiten determinar los patrones de entrada de manera recurrente.

    c. Puede tener conexiones hacia neuronas de capas anteriores, misma capa o consigo mismas.

    d. La A y la B son correctas.

    e. Ninguna de las anteriores es correcta.

## Examen 2012

1. ¿Qué modelo de neurona artificial fue desarrollado por Widrow y Hoff?

    a. Adaline

    b. Perceptrón.

    c. Cognitrón.

    d. Neocognitrón.

2. ¿Cuál de las siguientes no es una propiedad de las RNAs?

    a. Aprendizaje automático.

    b. Tolerancia a fallos y ruidos.

    c. Procesamiento en paralelo.

    d. Todas las anteriores son propiedades de las RNAs.

3. ¿Quienes proponen el modelo de neurona artificial seguido en clase?

    a. McCulloch y Pits.

    b. Hebb y Rochester.

    c. Anderson y Grossberg.

    d. Camilo Golgi y Williams.

4. ¿Cuál de los siguientes casos es adecuado para la resolución con sistemas conexionistas?

    a. Problemas no abordados eficientemente con otras técnicas

    b. Necesidad de respuesta en tiempo real

    c. Las dos anteriores

    d. Ninguna de las anteriores

5. ¿Cuál es la etapa de la metodología en la que por primer momento hay que ponerse en el ordenador a implementar los requerimientos específicos iniciales de nuestro problema?

    a. primera etapa, identificación del problema

    b. análisis y elección de la topología, el modelo, aprendizaje y otros parámetros

    c. preparación de los datos de entrada y salida de nuestro sistema

    d. etapa de construcción de la RNA

6. ¿Cuál de los siguientes no es un factor principal a tener en cuenta a la hora de construir una RNA?

    a. Tamaño de la red.

    b. Rapidez de la red.

    c. Funciones de los EPs.

    d. Todos son factores a tener en cuenta.

7. ¿Qué provoca el sobreentrenamiento?

    a. Perdemos capacidad de generalización.

    b. Mejora el rendimiento de la RNA.

    c. Nada, es como si la red cesara de entrenar.

    d. Ninguna de las anteriores.

8. ¿Cuál es el objetivo del proceso de entrenamiento de una RNA?

    a. Que la RNA memorice los casos de entrenamiento.

    b. Que la RNA no aprenda.

    c. Que la RNA no sea capaz de generalizar.

    d. Que la RNA aprenda, generalice y no memorice los casos de entrenamiento.

9. La tasa de aprendizaje:

    a. Debe ser elevada al final para que aprenda rápido cuando se esté acercando a la convergencia.

    b. Es conveniente que sea variable en las distintas fases del entrenamiento.

    c. Debe ser pequeña para que no oscile a ambos lados del valor de convergencia adecuado.

    d. Debe ser elevado en todo caso.
