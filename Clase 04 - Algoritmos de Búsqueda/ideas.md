# Clase 4 – Algoritmos de Búsqueda

Este módulo corresponde a la clase 4 de la materia Investigación Operativa. El enfoque de esta clase es introducir algoritmos de búsqueda aplicados a problemas clásicos de grafos y optimización, como caminos mínimos, decisiones secuenciales, búsqueda binaria y recorridos eficientes.

## 🎯 Objetivos de la clase

- Comprender cómo se aplican algoritmos de búsqueda en problemas de optimización.
- Estudiar estrategias de recorrido de grafos: BFS, DFS, Dijkstra.
- Aplicar búsqueda binaria a problemas de decisión.
- Implementar estos algoritmos sobre casos prácticos, visualizando su utilidad en IO.

---

## 🔹 Contenidos principales

### 1. **Recorridos en grafos**

- **BFS (Breadth-First Search)**:
  - Utilizado para encontrar el camino más corto en grafos no ponderados.
  - Útil para analizar conectividad y niveles.

- **DFS (Depth-First Search)**:
  - Útil para explorar todo un grafo o árbol.
  - Aplicaciones: detección de ciclos, componentes conexas.

### 2. **Dijkstra**
- Algoritmo de caminos mínimos en grafos con pesos positivos.
- Aplicaciones: planificación de rutas, logística, asignación de recursos.

### 3. **Búsqueda binaria**
- Técnica de búsqueda eficiente sobre listas ordenadas o funciones monótonas.
- Aplicación a problemas de decisión: encontrar el valor mínimo que cumple una condición.
- Ejemplo: encontrar la mínima capacidad necesaria para transportar cierta carga en tiempo límite.

### 4. *(Opcional)* **A\* (A estrella)**
- Búsqueda informada: combina heurística con costo acumulado.
- Aplicaciones: navegación, juegos, IA.

---

## 🔧 Actividades prácticas sugeridas

### ▶️ Laberinto con BFS y DFS
- Encontrar la salida desde una posición inicial.
- Comparar recorridos y caminos.

### ▶️ Dijkstra visual con NetworkX
- Grafo dirigido con pesos.
- Marcar caminos mínimos desde un nodo origen.

### ▶️ Binary Search en problemas de decisión
- Dado un conjunto de tareas y un límite de tiempo, ¿cuál es la menor cantidad de recursos necesarios?
- Ejemplo: transporte, producción, planificación.

---

## 📁 Estructura de archivos sugerida

```

Clase 04 - Algoritmos de Búsqueda/
│
├── README.md
├── bfs\_dfs\_laberinto.ipynb        # Implementación y visualización BFS / DFS
├── dijkstra\_networkx.ipynb        # Ejemplo con Dijkstra y NetworkX
├── binary\_search\_decision.ipynb   # Ejercicio de binary search aplicado
├── data/
│   ├── laberinto.txt              # Representación del laberinto (opcional)
│   └── grafos.json                # Datos de prueba para NetworkX

```

## 🧠 Extras

- Introducción rápida a grafos: nodos, aristas, dirigidos/no dirigidos, ponderados
- Comparación de complejidades: O(V+E), O(log N), etc.
- Casos reales donde se usan estos algoritmos (mapas, redes, optimización de stock)

---

## 🗓️ Clase en el cronograma

| Clase | Fecha   | Tema                            |
|:-----:|:-------:|----------------------------------|
|   4   | 28/08   | Algoritmos de Búsqueda          |

---

## 🧪 Bibliografía y recursos

- NetworkX: https://networkx.org/documentation/stable/
- Cormen et al. – *Introduction to Algorithms* (cap. de grafos)
- Visualizaciones online: https://visualgo.net/en (para BFS, DFS, Dijkstra)

---



