# 🚚 DeliveryExpress

### Taller de Colecciones y Genéricos en Java

**DeliveryExpress** es un proyecto académico desarrollado en Java que simula la gestión de pedidos de un servicio de domicilios.
El objetivo principal es aplicar y demostrar el uso correcto de **colecciones del framework Java** y **genéricos**, a través de un caso práctico sencillo.

---

## 👥 Integrantes

* Valery Nickol Rosero Molina
* Johan David Delgado Delgado
* Juan Matabanchoy

---

## 🎯 Objetivo del proyecto

* Comprender el uso de **listas, conjuntos y mapas** en Java.
* Aplicar **genéricos** para crear código reutilizable y flexible.
* Analizar el comportamiento y ventajas de cada estructura de datos.
* Simular un flujo básico de pedidos en consola.

---

## ⚙️ Tecnologías utilizadas

* ☕ **Java**
* 📦 Colecciones:

  * `ArrayList`
  * `LinkedList`
  * `HashSet`
  * `HashMap`
* 🧬 **Genéricos**
* 🧪 Programación en consola

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/Valery-Rosero/DeliveryExpress.git
```

2. Compilar el proyecto:

```bash
javac -d bin src/main/java/**/*.java
```

3. Ejecutar la aplicación:

```bash
java -cp bin app.Main
```

---

## 🧩 Explicación por componentes

### 🔹 Parte A – Listas

* **ArrayList**

  * Almacena los pedidos en orden de inserción.
  * Acceso rápido a elementos por índice.

* **LinkedList**

  * Más eficiente para inserciones y eliminaciones al inicio de la lista.
  * Ideal para flujos dinámicos de pedidos.

---

### 🔹 Parte B – HashSet

* Elimina automáticamente pedidos duplicados.
* Utiliza `equals()` y `hashCode()`.
* No mantiene el orden de inserción.

---

### 🔹 Parte C – HashMap

* Asocia pedidos a clientes.
* Permite búsquedas rápidas por clave.
* Facilita el cálculo de totales por cliente.

---

### 🔹 Parte D – Genéricos

* Implementación de un método genérico `filtrar`.
* Funciona con cualquier tipo de dato.
* Uso de `Predicate` para criterios de filtrado flexibles.

---

## 📌 Alcance del proyecto

* Aplicación de consola
* Enfoque académico
* No incluye interfaz gráfica
* No maneja persistencia de datos

---

## 📚 Contexto académico

Proyecto desarrollado como parte de un **taller universitario**, enfocado en reforzar conceptos fundamentales de **estructuras de datos y genéricos en Java**.
