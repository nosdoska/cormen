# Algoritmos

Informalmente un algoritmo es un procedimiento computacional que toma un valor, o un conjunto de valores, como _entrada_, produce un valor o un conjunto de valores, como _salida_.

Es una secuencia de pasos computacionales que transforma un input, en output.

Por ejemplo, querer ordenar de menor a mayor una secuencia de números:
  - Input: [45, 39, 2, 74, 84, 81, 92]
  - Output: [2, 39, 45, 74, 81, 84, 92]

En general, la _instancia del problema_ consiste en el input necesario para calcular la solución del problema.

Un algoritmo es **correcto** si, por cada instancia de un input, devuelve el output correcto.

Un algoritmo correcto **resuelve** el problema computacional.

La estructura de datos es una forma de ordenar y guardar data con el propósito de facilitar el acceso y su posible modificación.

Algoritmos llamados NP-Complete, son problemas cuyas soluciones no son totalmente eficientes. Se sabe que no tienen una solución eficiente, pero tampoco se desmiente que pueda existir alguna.

## Ejercicios

#### 1. Give a real-world example that requires sorting or a real-world example that requires computing a convex hull.

  * Sorting:
    - Ordenar una página de productos por su precio de menor a mayor
    - Ordenar una lista de pacientes por estado de gravedad y edad, a medida que vayan llegando a una sala de urgencias

  * Envolvente Convexa [1]:
    - Dado un conjunto de direcciones, verificar si todas ellas pertenecen a un mismo sector


#### 2. Other than speed, what other measures of efficiency might one use in a real-world setting?

  * El tiempo que la solución en ejecutarse

#### 3. Select a data structure that you have seen previously, and discuss its strengths and limitations.
  
  ##### Array:

  * Fortalezas:
    - Es relativamente sencillo de implementar en lenguajes modernos
    - No existe complejidad de tiempo al insertar elementos al inicio, mitad o final de un array
  
  * Limitaciones:
    - Ninguna?

#### 4. How are the shortest-path and traveling-salesman problems given above similar? How are they different?

  * Son similares en que necesitan una manera eficiente para encontrar una distancia mínima entre dos puntos.
  * Son diferentes en que el problema de "shortest path" solo necesita encontrar la distancia mínima entre dos puntos, mientras que el problema de "traveling-salesman", es entre dos puntos, pero teniendo en cuenta intersecciones.

#### 5. Come up with a real-world problem in which only the best solution will do. Then come up with one in which a solution that is “approximately” the best is good enough.
  
  * 

---

- [1] https://es.wikipedia.org/wiki/Envolvente_convexa
- [1.1] https://es.wikipedia.org/wiki/Convexidad