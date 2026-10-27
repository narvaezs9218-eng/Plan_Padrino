# Plan_Padrino
Integrabntes : Sebastian Narvaez, Andres Rojas, Cristian Clavijo, Micol Franco, Andres Lozano

# 📚 Estructura de Datos: Pilas y Colas (Stack & Queue)

Repositorio de apoyo académico para la clase de **Estructuras de Datos** (Primer Semestre). Este espacio contiene la guía metodológica para docentes y los materiales didácticos diseñados para comprender de forma práctica y visual la diferencia fundamental entre los comportamientos **LIFO** (Last In, First Out) y **FIFO** (First In, First Out)[cite: 1, 5].

---

## 📂 Contenido del Repositorio

*   **`Guion_Docente_Pilas_y_Colas.pdf`**: Guion detallado de la clase de 2 horas estructurado en bloques de tiempo (gancho, teoría, demos de código, ejercicios y cierre)[cite: 1, 4].
*   **`La_cafeteria_del_caos.pdf`**: Actividad lúdica en parejas (sin computador) con papel, lápiz y tarjetas para simular flujos de pilas y colas antes de pasar a la programación[cite: 5].
*   **`ClasePilasColas.java`**: Código base en Java utilizado para las demostraciones prácticas en clase[cite: 1].

---

## ⏱️ Estructura de la Clase (Plan de 2 Horas)

| Minutos | Bloque | Descripción |
| :--- | :--- | :--- |
| **00 - 10** | **Gancho** | Preguntas y ejemplos cotidianos (Ej. Ctrl+Z vs. Fila de banco)[cite: 1]. |
| **10 - 40** | **Pila (LIFO)** | Explicación teórica, operaciones (`push`, `pop`, `peek`) y demo de código[cite: 1, 2]. |
| **40 - 50** | **Invertir Palabra** | Ejercicio práctico individual aplicando propiedades de las pilas[cite: 1, 2]. |
| **50 - 60** | **Descanso** | Pausa activa[cite: 1]. |
| **60 - 85** | **Cola (FIFO)** | Explicación teórica, operaciones (`enqueue`, `dequeue`) y comparación con pilas[cite: 1, 3]. |
| **85 - 110** | **Actividad Práctica** | Dinámica de tarjetas con paréntesis balanceados y código[cite: 1, 3]. |
| **110 - 120** | **Cierre** | Resumen conceptual y boleto de salida[cite: 1, 4]. |

---

## ⚙️ Conceptos Clave

*   **Pila (Stack - LIFO):** El último elemento en entrar es el primero en salir. Sus operaciones principales son:
    *   `push(item)`: Agrega un elemento a la cima[cite: 2].
    *   `pop()`: Retira y devuelve el elemento de la cima[cite: 2].
    *   `peek()`: Consulta el elemento de la cima sin retirarlo[cite: 2].
*   **Cola (Queue - FIFO):** El primer elemento en entrar es el primero en salir. Sus operaciones principales son:
    *   `enqueue(item)`: Agrega un elemento al final de la fila[cite: 3].
    *   `dequeue()`: Retira y devuelve el elemento del frente[cite: 3].
    *   `peek()`: Consulta quién es el siguiente en la fila sin sacarlo[cite: 3].

---

## 🚀 Actividad Destacada: "La Cafetería del Caos"

Antes de escribir código, se implementa una dinámica manual en parejas dividida en tres rondas[cite: 5]:
1.  **Ronda 1 (Pila):** Simulación de una bandeja de platos vertical para registrar el comportamiento LIFO y predecir extracciones[cite: 5, 6].
2.  **Ronda 2 (Cola):** Simulación de una fila de clientes horizontal para entender el flujo FIFO[cite: 5, 6].
3.  **Ronda 3 (El Error):** Análisis de excepciones al intentar extraer elementos de una estructura vacía, justificando el uso previo de validaciones como `isEmpty()`[cite: 5, 8].

---

## 🛠️ Requisitos Técnicos
*   Kit de desarrollo Java (JDK 8 o superior).
*   Entorno de desarrollo o editor de código de preferencia (VS Code, IntelliJ, etc.).

---
*Desarrollado con fines educativos para la enseñanza de Estructuras de Datos.*
