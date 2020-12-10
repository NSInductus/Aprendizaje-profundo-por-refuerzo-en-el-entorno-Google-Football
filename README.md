# Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football

Repositorio para mi Trabajo de Fin de Máster: **Aprendizaje profundo por refuerzo en el entorno Google Football**, correspondiente al Máster Profesional de Ingeniería Informática de la Universidad de Granada.

* Autor: Ángel Murcia Díaz
* Director: Juan Gómez Romero [Github](https://github.com/jgromero)

## Resumen del proyecto

En este trabajo se ha realizado una investigación acerca de una rama de la *Inteligencia artificial*, el *Aprendizaje por Refuerzo, tanto de forma teórica como práctica. El objetivo que persigue el proyecto es doble: por un parte, estudiar los fundamentos teóricos de los algoritmos de *Aprendizaje por Refuerzo Profundo*, un tipo de *Aprendizaje por Refuerzo* que utiliza *Redes Neuronales*; por otra, comprobar si es posible aplicar estos algoritmos para realizar *Aprendizaje Progresivo* (*curriculum learning*, en inglés) en problemas que se organizan en niveles de dificultad creciente.

Para ello, en primer lugar se ha llevado a cabo una extensa revisión del marco teórico del *Aprendizaje por Refuerzo Profundo*, estudiando los conceptos clave, los algoritmos propuestos en los últimos años y las implementaciones públicas disponibles. En segundo lugar, se han implementado y ejecutado una serie de experimentos utilizando el entorno virtual *Google Research Football*, que simula un partido de fútbol y permite controlar a los jugadores como si se tratara de un videojuego. 

Las conclusiones más importantes del trabajo son: (1) que los algoritmos de *Aprendizaje por Refuerzo Profundo* son muy útiles incluso en problemas con espacios de estados y acciones complejos, (2) que el *Aprendizaje Progresivo* es más rápido y efectivo que el aprendizaje desde cero, incluso cuando las tareas más complejas no contienen completamente a las más simples.

## Código del proyecto

El código de este proyecto está realizado en Cuadernos de Jupyter Nootebook, por lo que el código mezcla celdas de código python con celdas de texto explicativo en formato Markdown, el código se puede encontrar en se puede encontrar en la carpeta "src", está separado en:

* Código correspondiente a la experimentación básica: [Proceso_Experimental_Basico.ipynb](https://github.com/NSInductus/Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football/blob/main/src/Proceso_Experimental_Basico.ipynb).
* Código correspondiente a la experimentación avanzada: [Proceso_Experimental_Avanzado.ipynb](https://github.com/NSInductus/Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football/blob/main/src/Proceso_Experimental_Avanzado.ipynb).

## Resultados del proceso experimental

Los resultados conseguidos de la ejecución completa del proceso experimental se pueden en el siguiente link de mega: ["Link"](https://mega.nz/file/f8VXma4Y#7fKXME5BaxI3ZEdnLV22_yikCO4n9yY4bKL0IpsWpaQ).

Destacar que estos resultados están separados en: resultados de la experimentación básica y resultados de la experimentación avanzada.

## Memoria del proyecto

La memoria del proyecto está escrita utilizando LaTex, en ella se explica de forma detallada todo el desarrollo del proyecto, corresponde con [memoria.pdf](https://github.com/NSInductus/Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football/blob/main/doc/memoria.pdf).

Destacar que al final de la memoria existe un anexo de informática con la intención de que el lector pueda de una forma sencilla lanzar el entorno y también realizar algunas de las pruebas del proceso experimental si lo desea.

## Vídeos del proyecto

Se han realizado una serie de vídeos para que de forma gráfica se pueda comprobar como funciona el entorno renderizado.

* Vídeo que muestra los diferentes escenarios del entorno: [Link](https://www.youtube.com/watch?v=_hj5TU9MNTE).
* Vídeo que muestra el proceso de entrenamiento de un agente en el escenario de 11 contra 11: [Link](https://www.youtube.com/watch?v=rUzpmJPS7zM).
* Vídeo que muestra a un agente en el entorno de 11 contra 11 después de haber sido entrendo utilizando *Aprendizaje Progresivo*: [Link](https://www.youtube.com/watch?v=iMC6nC8ZguY).