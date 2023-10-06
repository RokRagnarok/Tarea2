# Investigacion Cuda Cores,Threads,Blocks and Grids

##Cuda Cores 
Los núcleos CUDA también son procesadores paralelos que permiten que diferentes procesadores trabajen en los datos simultáneamente. 
La arquitectura NVIDIA CUDA es en la que se basan las tarjetas gráficas de NVIDIA destinadas a realizar el cálculo en paralelo ofreciendo una gran potencia de cálculo en la GPU lo cual permite que el sistema tenga un gran rendimiento. 
En la arquitectura clásica de una tarjeta gráfica podemos encontrar la presencia de dos tipos de procesadores los procesadores de vértices y los procesadores de fragmentos dedicados a tareas distintas e indispensables dentro del cauce gráfico y con repertorios de instrucciones diferentes.
Cada Cuda Cores es capaz de ejecutar instruciones de forma independiente lo que permite que la GPU realicen miles o incluso millones de procesos en paralelo.

##Threads
En sistemas operativos un hilo o hebra (del inglés thread), proceso ligero o subproceso es una secuencia de tareas encadenadas muy pequeña que puede ser ejecutada por un sistema operativo.
Un proceso es un programa en ejecución incluyendo el valor del program counter los registros y las variables Conceptualmente cada proceso tiene un hilo (thread) de ejecución que es visto como un CPU virtual.
Los threads en programacion se refiere a unidades mas pequeñas de ejecucion dentro de un proceso cada threads representa una secuencia de instruciones que se ejecuta de manera independiente en la GPU.
Los threads son utiles para dividir una tarea en partes más pequeñas y ejecutarlas simultaneamente para aprovechar al maximo la capacidad de procesamiento de una CPU multicore o multiproceso. 

##Block And Grids

Los Blocks y Grids dentro de la programacion cuda son estruturas que le permiten a los desarrolladores aprovechar la arquitectura paralela de la GPU para acelerar el procesamiento de datos y calculos intencivos.
Blocks: Un blocks es una coleccion de threads que se ejecutan en una GPU estos pueden cooperar y comunicarse entre si atravez de la memoria compartida.
Los threads dentro de un bloque pueden cooperar y comunicarse entre si a través de la memoria compartida. 
En el desarrollo web utilizamos el grid para diseñar la estructura de la web así como el contenido de la página.
El grid es una cuadricula sobre la que se distribuyen los distintos elementos que componen la web.
El bloque de código es un usuario o seccion de código con una o más declaraciones y sentencias. 
Un lenguaje de programación que permite bloques incluyendo bloques anidados dentro de otros bloques es llamado un lenguaje de programación estructurado por bloques.

##Referencias
https://codigofacilito.com/articulos/threads-procesos
https://hardwaresfera.com/articulos/hablamos-profundidad-los-nvidia-cuda-core/
https://www.profesionalreview.com/2018/10/09/que-son-nvidia-cuda-core/
https://www.suratica.es/que-es-un-grid/#:~:text=%C2%BFQu%C3%A9%20es%20un%20Grid%3F&text=En%20el%20desarrollo%20web%20utilizamos,elementos%20que%20componen%20la%20web.
https://es.wikipedia.org/wiki/Bloque_de_c%C3%B3digo#:~:text=El%20bloque%20de%20c%C3%B3digo%20es,de%20programaci%C3%B3n%20estructurado%20por%20bloques.

##Conclucion
En conclucion puedo decir que Cuda es bastante util por el permitir separar y tener varios procesos tanto en GPU como la CPU, los threads o hilos se encargaran de ejecutar distintos tipos de pequeños procesos y dividir una tarea en sub tareas mas pequeñas y por ultimo los block and grids son bastante utiles por el gran aprobechamiento que le da esta a los desarrolladores de codigo de la arquitectura paralela que acelera los procesos en la GPU.
