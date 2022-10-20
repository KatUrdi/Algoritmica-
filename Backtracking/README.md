# Backtracking
Backtracking es una tecnica que se utiliza para resolver problemas de manera recursiva intentando construir una solución de forma incremental, quitando las soluciones que fallan en satisfacer el problema.

Esencialmente, la idea es encontrar la mejor combinación posible, por eso se dice que este tipo de algoritmo es una búsqueda en profundidad (DFS). Durante la búsqueda, si se encuentra una alternativa incorrecta, la búsqueda retrocede hasta el paso anterior y toma la siguiente alternativa. Cuando se han terminado las posibilidades, se vuelve a la elección anterior y se toma al siguiente hijo. Si no hay más alternativas la búsqueda falla. De esta manera, se crea un árbol implícito, en el que cada nodo es un estado de la solución.

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Backtracking-no-backjumping.svg/1200px-Backtracking-no-backjumping.svg.png)
