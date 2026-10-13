# Práctica de Hilos - Programación Concurrente

Este repositorio contiene la implementación y comparación de diferentes enfoques para la programación concurrente en Java, utilizando como problema base la suma de los elementos de un arreglo de manera secuencial y paralela.

## Estructura del Repositorio

El proyecto se compone de los siguientes archivos fuente:

* **`SumaArreglo.java`**: Versión secuencial base que recorre el arreglo y acumula sus elementos en una sola variable.
* **`SumaArregloThread.java`**: Versión concurrente donde cada hilo hereda directamente de la clase `Thread` y sobrescribe el método `run()`.
* **`SumaArregloRunnable.java`**: Versión concurrente donde las tareas implementan la interfaz `Runnable` y se ejecutan mediante objetos `Thread` separados.
* **`SumaArregloCallable.java`**: Versión avanzada que utiliza la interfaz genérica `Callable<Integer>`, administrada mediante un `ExecutorService` (pool de hilos) y objetos `Future` para recuperar los resultados de manera directa.

---

## Compilación y Ejecución de los Programas

Para compilar y ejecutar cualquiera de los programas, abre una terminal en la carpeta raíz del repositorio y utiliza los siguientes comandos:

### 1. Solución Secuencial
* **Compilación:**
  ```bash
  javac SumaArreglo.java
