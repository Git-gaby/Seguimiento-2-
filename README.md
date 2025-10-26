# 📘 Seguimiento-2.1 — README

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Collections](https://img.shields.io/badge/Module-collections-yellow)
![Status](https://img.shields.io/badge/Estado-Completo-success)

---

## 🎯 Objetivo

Este repositorio acompaña el cuaderno **`Seguimiento-2.ipynb`**. El propósito del trabajo es **practicar y demostrar conceptos de estructuras de datos en Python**, mediante ejemplos interactivos y explicaciones detalladas.

Se trabajan los siguientes temas:

* 🔹 Conjuntos (`set`)
* 🔹 Diccionarios (`dict`)
* 🔹 Comprensión de listas (básicas, anidadas y con filtrado/mapeo)
* 🔹 Listas como pilas (`Stack`)
* 🔹 Colas usando `collections.deque` (`Queue`)

El objetivo general es comprender **cómo funcionan internamente las estructuras de datos** y aplicar su lógica a problemas reales.

---

## 🧠 Breve descripción de los ejercicios realizados

1. **🧩 Conjuntos – Feibert**
   Creación de conjuntos, verificación de pertenencia y operaciones básicas.
   Conceptos: no duplicados, eficiencia en búsquedas, operaciones matemáticas.

2. **📚 Diccionarios**
   Construcción y manipulación de diccionarios y listas de diccionarios.
   Acceso, modificación, eliminación de claves, y métodos útiles (`keys()`, `values()`, `items()`).

3. **🧮 Comprensión de Listas Anidadas**
   Creación de listas complejas en una sola línea.
   Ejemplo: **transposición de matrices** usando comprensión y `zip(*)`.

4. **🔥 Ejemplo Avanzado de Comprensión (Mapeo y Filtrado)**
   Filtrar temperaturas mayores a 20°C y convertirlas a Fahrenheit con una sola expresión.

5. **📦 Listas como Pilas (Stack)**
   Implementación de una clase `Pila` orientada a objetos.
   Incluye métodos `apilar()`, `desapilar()`, `ver_tope()`, `esta_vacia()`, `tamano()` y dunder methods.
   Ejemplo práctico: invertir palabras.

6. **🍔 Colas como Listas (Queue)**
   Uso de `collections.deque` para un **sistema de gestión de pedidos de restaurante**.
   Operaciones FIFO: agregar, procesar y mostrar estado de pedidos.

---

## ⚙️ Requerimientos y dependencias

📦 **Versión recomendada:** Python 3.8 o superior

🧰 **Librerías estándar utilizadas:**

* `collections`
* `time`
* `random`

🧪 **Entorno sugerido:** Jupyter Notebook o JupyterLab.

```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate     # Windows
pip install jupyter
```

---

## ▶️ Instrucciones para ejecutar el contenido

1. **Clonar o descargar el proyecto:**

   ```bash
   git clone https://github.com/Git-gaby/seguimiento-2.git
   cd seguimiento-2
   ```

2. **Abrir el notebook:**

   ```bash
   jupyter notebook Seguimiento-2.ipynb
   ```

3. **Ejecutar las celdas:**
   Usa `Shift + Enter` en cada celda para ver los resultados paso a paso.

4. **Ejecutar como script (opcional):**

   ```bash
   jupyter nbconvert --to script Seguimiento-2.ipynb
   python Seguimiento-2.py
   ```

---

## 📂 Estructura del proyecto

```
/ (raíz del proyecto)
├─ Seguimiento-2.ipynb
├─ README.md
├─ requirements.txt   # opcional
└─ ejemplos/          # scripts derivados del cuaderno
```

---

## 👨‍💻 Autor

**Gabriel**
🌐 [GitHub: Git-gaby](https://github.com/Git-gaby)
💡 Estudiante de Ingeniería Ambiental — apasionado por la programación, la automatización y la gestión de datos.

---

📌 *Este proyecto forma parte del curso de Python y estructuras de datos, demostrando buenas prácticas de documentación y claridad de código.*
