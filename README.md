# Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football

Repositorio para mi Trabajo de Fin de Máster: **Aprendizaje profundo por refuerzo en el entorno Google Football**, correspondiente al Máster Profesional de Ingeniería Informática de la Universidad de Granada.

* Autor: Ángel Murcia Díaz
* Director: Juan Gómez Romero [Github](https://github.com/jgromero)

## Resumen del proyecto

En este proyecto se realiza una investigación acerca de una rama de la *Inteligencia artificial*: el *Aprendizaje por Refuerzo*, tanto de forma teórica como práctica, aprendiendo los conceptos clave, el funcionamiento de este tipo de aprendizaje y profundizando concretamente en el *Aprendizaje por Refuerzo Profundo*, es decir, un tipo de *Aprendizaje por Refuerzo* que utiliza *Redes Neuronales Convolucionales*. Estudiando al detalle el funcionamiento de algunos de los algoritmos existentes de este campo. 

El entorno de *Aprendizaje por Refuerzo* que se utiliza de forma práctica es el nuevo entorno de aprendizaje por refuerzo de Google: *Google Research Football Environment*, de forma resumida un entorno de *Aprendizaje por Refuerzo* novedoso en el que los agentes aspiran a dominar el deporte más popular del mundo: el fútbol, el entorno proporciona varios componentes cruciales: un motor de juego altamente optimizado, un conjunto exigente de problemas de investigación y un conjunto de escenarios de *Aprendizaje por Refuerzo* progresivamente más difíciles. Por lo que en este proyecto se realiza un análisis completo acerca de este entorno, que abarca desde el funcionamiento interno del entorno hasta las diferentes formas en que se pueden entrenar agentes para ponerlos a funcionar en el mismo.

De forma resumida, **los objetivos del proyecto consisten en comprobar como funcionan diferentes algoritmos de *Aprendizaje por Refuerzo Profundo* sobre los diferentes escenarios del entorno *Google Research Football Environment* y en comprobar si utilizar el aprendizaje progresivo funciona mejor que utilizar un aprendizaje normal**, refiriéndose a *Aprendizaje Progresivo* como un tipo de aprendizaje que comienza en escenarios más sencillos del entorno para acabar concluyendo en los escenarios más complejos del entorno. Para este fin, se realiza un proceso experimental, el cuál esta estudiado y creado a conciencia para conseguir los objetivos planteados.

Este proceso experimental está precedido de una serie de pruebas iniciales, que se utilizan para analizar y comprobar en primera persona como funciona el entorno, así como para ajustar algunos de los parámetros de los algoritmos a utilizar. El proceso experimental se separa en dos partes: proceso experimental básico donde se comprueba el funcionamiento de los diferentes algoritmos en los diferentes escenarios del entorno y proceso experimental avanzado donde se comprueba si el *Aprendizaje Progresivo* es eficaz.

## Código del proyecto

El código de este proyecto está realizado en Cuadernos de Jupyter Nootebook, por lo que el código mezcla celdas de código python con celdas de texto explicativo en formato Markdown, el código se puede encontrar en se puede encontrar en la carpeta "src", está separado en:

* Código correspondiente a la experimentación básica: [Proceso_Experimental_Basico.ipynb](https://github.com/NSInductus/Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football/blob/main/src/Proceso_Experimental_Basico.ipynb).
* Código correspondiente a la experimentación avanzada: [Proceso_Experimental_Avanzado.ipynb](https://github.com/NSInductus/Aprendizaje-profundo-por-refuerzo-en-el-entorno-Google-Football/blob/main/src/Proceso_Experimental_Avanzado.ipynb).

## Resultados del proceso experimental

Los resultados conseguidos de la ejecución completa del proceso experimental se pueden en el siguiente link de mega: ["Link"](https://mega.nz/file/f8VXma4Y#7fKXME5BaxI3ZEdnLV22_yikCO4n9yY4bKL0IpsWpaQ).

Destacar que estos resultados están separados en: resultados de la experimentación básica y resultados de la experimentación avanzada.

## Memoria del proyecto

La memoria del proyecto está escrita utilizando LaTex, en ella se explica de forma detallada todo el desarrollo del proyecto, corresponde con [memoria.pdf]().

Destacar que al final de la memoria existe un anexo de informática con la intención de que el lector pueda de una forma sencilla lanzar el entorno y también realizar algunas de las pruebas del proceso experimental si lo desea.

## Vídeos del proyecto

Se han realizado una serie de vídeos para que de forma gráfica se pueda comprobar como funciona el entorno renderizado.

* Vídeo que muestra los diferentes escenarios del entorno: [Link](https://www.youtube.com/watch?v=_hj5TU9MNTE).
* Vídeo que muestra el proceso de entrenamiento de un agente en el escenario de 11 contra 11: [Link](https://www.youtube.com/watch?v=rUzpmJPS7zM).
* Vídeo que muestra a un agente en el entorno de 11 contra 11 después de haber sido entrendo utilizando *Aprendizaje Progresivo*: [Link](https://www.youtube.com/watch?v=iMC6nC8ZguY).