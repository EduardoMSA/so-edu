## Objetivo
Hacer un planificador de procesos basados en prioridades.
El proceso con mayor prioridad se ejecuta primero.
Si hay dos o mas con prioridades iguales el primero de la lista.

## Herramientas
+ git
+ make
+ gcc

## Conceptos
1) Proceso

2) Planificación de procesos. 
  + Es el mecanismo que el sistema operativo tiene para asignarle el cpu a un proceso.

3) Estados de un procesos
  + UNUSED
  + EMBRYO
  + SLEEPING
  + RUNNABLE
  + RUNNING
  + ZOMBIE

4) Cambio de contexto. 
  + Ocurre cuando el cpu deja de ejecutar un proceso para ejecutar otro.
  + Guardar el Program Counter y la dirección del stack del proceso actual.
  + Restaurar el Program Counter y la dirección del nuevo proceso.

## ¿Qué aprendí?
+ Aprendí como crear una llamada a sistema que establesca una prioridad de un proceso, además se determinó que es un proceso y los estados que pueden tener estos. 

## ¿Cómo se relaciona?
+ Llamadas de sistema
+ Procesos

## [Commit](https://github.com/EduardoMSA/so-edu/commit/7aa3513ab24f39d57a36b033951dd3838c27a1fc)

