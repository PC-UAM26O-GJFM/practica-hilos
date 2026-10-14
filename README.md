# Práctica: Programación Concurrente - Hilos en Java


##  Prerrequisitos y Requisitos del Sistema
Para compilar y ejecutar los programas de este repositorio, asegúrate de contar con:
- **Java Development Kit (JDK)** instalado (versión 8 o superior recomendada).
- Una terminal compatible con comandos Unix/Linux o PowerShell.

---

## Estructura del Repositorio

El repositorio se encuentra organizado de la siguiente manera:
- `SumaArreglo.java` - Solución secuencial base para la suma de los elementos de un arreglo.
- `SumaArregloThread.java` - Versión concurrente utilizando herencia directa de la clase `Thread`.
- `SumaArregloRunnable.java` - Versión concurrente implementando la interfaz `Runnable`.
- `SumaArregloCallable.java` - Versión concurrente basada en `Callable`, `ExecutorService` y `Future`.
- `NReinasSecuencial.java` - Solución secuencial mediante backtracking para calcular el total de soluciones de las N-Reinas.
- `.gitignore` - Archivo de exclusión para directorios de compilación (`out/`, `build/`, `*.class`) y configuraciones de IDEs.

---

## Instrucciones de Compilación y Ejecución

Ubícate en la raíz del repositorio y utiliza los siguientes comandos en tu terminal:

### 1. Suma de Arreglo (Secuencial)
```bash
javac SumaArreglo.java
java SumaArreglo 20
