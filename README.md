# Investigacion Cuda Cores,Threads,Blocks and Grids

##Cuda Cores 
Los núcleos CUDA también son procesadores paralelos que permiten que diferentes procesadores trabajen en los datos simultáneamente. 
La arquitectura NVIDIA CUDA es en la que se basan las tarjetas gráficas de NVIDIA destinadas a realizar el cálculo en paralelo ofreciendo una gran potencia de cálculo en la GPU lo cual permite que el sistema tenga un gran rendimiento. 
En la arquitectura clásica de una tarjeta gráfica podemos encontrar la presencia de dos tipos de procesadores los procesadores de vértices y los procesadores de fragmentos dedicados a tareas distintas e indispensables dentro del cauce gráfico y con repertorios de instrucciones diferentes.
Cada Cuda Cores es capaz de ejecutar instruciones de forma independiente lo que permite que la GPU realicen miles o incluso millones de procesos en paralelo.

##Threads
En sistemas operativos, un hilo o hebra (del inglés thread), proceso ligero o subproceso es una secuencia de tareas encadenadas muy pequeña que puede ser ejecutada por un sistema operativo.
Un proceso es un programa en ejecución, incluyendo el valor del program counter, los registros y las variables. Conceptualmente, cada proceso tiene un hilo (thread) de ejecución que es visto como un CPU virtual.
Los threads en programacion se refiere a unidades mas pequeñas de ejecucion dentro de un proceso cada threads representa una secuencia de instruciones que se ejecuta de manera independiente en la GPU.
Los threads son utiles para dividir una tarea en partes más pequeñas y ejecutarlas simultaneamente para aprovechar al maximo la capacidad de procesamiento de una CPU multicore o multiproceso. 

##Block And Grids

Los Blocks y Grids dentro de la programacion cuda son estruturas que le permiten a los desarrolladores aprovechar la arquitectura paralela de la GPU para acelerar el procesamiento de datos y calculos intencivos.
Blocks: Un blocks es una coleccion de threads que se ejecutan en una GPU estos pueden cooperar y comunicarse entre si atravez de la memoria compartida.
Los threads dentro de un bloque pueden cooperar y comunicarse entre si a través de la memoria compartida. 
