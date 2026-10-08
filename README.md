# Calculadora Básica en Kotlin

Una aplicación de consola interactiva desarrollada en Kotlin que permite realizar operaciones aritméticas básicas de forma continua, gestionando la validación de entradas de usuario y previniendo errores en tiempo de ejecución (como la división o el cálculo de resto por cero).

---

## 🚀 Características

* **Operaciones disponibles:**
  * Suma (`+`)
  * Resta (`-`)
  * Multiplicación (`*`)
  * División (`/`) con control de división por cero
  * Cálculo de módulo/resto (`%`) con control de residuo entre cero
* **Validación de entradas:** Controla que el usuario ingrese números válidos tanto en la selección del menú como en los operandos (evita fallos por `InputMismatchException`).
* **Bucle interactivo:** El menú se mantiene en ejecución de manera continua hasta seleccionar explícitamente la opción de salir (opción 6).

---

## 🛠️ Requisitos Previos

* **Java Development Kit (JDK):** Versión 8 o superior.
* **Kotlin Compiler (`kotlinc`)** o un IDE compatible, como IntelliJ IDEA.

---

## 💻 Compilación y Ejecución

### Desde IntelliJ IDEA

1. Abre el proyecto en el IDE.
2. Abre el archivo fuente (`Calculadora.kt`).
3. Haz clic en el icono verde de reproducción (**Run**) situado en el margen junto a la función `fun main()`.

