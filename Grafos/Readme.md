<div align="center">

# Algoritmo Kruskal  

 <div align="left">
 
 ### Definición   
El algoritmo de Kruskal es un algoritmo de árbol mínimo que toma un grafo como entrada y encuentra el subconjunto de aristas de ese grafo que

forme un árbol que incluya todos los vértices
tiene la mínima suma de pesos entre todos los árboles que se pueden formar a partir del grafo
Entra dentro de una clase de algoritmos llamados codiciosos que encuentran el óptimo local con la esperanza de encontrar un óptimo global.

Empezamos por las aristas de menor peso y seguimos añadiendo aristas hasta llegar a nuestro objetivo.

Los pasos para implementar el algoritmo de Kruskal son los siguientes:

Ordenar todas las aristas de menor a mayor peso
Tomar la arista de menor peso y añadirla al árbol de distribución. Si al añadir la arista se crea un ciclo, se rechaza esta arista.
Seguir añadiendo aristas hasta llegar a todos los vértices.
<div align="center">

# Algoritmo PRIM  

 <div align="left">
 
 ### Definición
El algoritmo de Prim es un algoritmo de árbol mínimo que toma un grafo como entrada y encuentra el subconjunto de aristas de ese grafo que

forme un árbol que incluya todos los vértices
tiene la mínima suma de pesos entre todos los árboles que se pueden formar a partir del grafo
Entra dentro de una clase de algoritmos llamados codiciosos que encuentran el óptimo local con la esperanza de encontrar un óptimo global.

Empezamos por un vértice y seguimos añadiendo aristas con el menor peso hasta alcanzar nuestro objetivo.

Los pasos para implementar el algoritmo de Prim son los siguientes:

Inicializar el árbol de expansión mínima con un vértice elegido al azar.
Encontrar todas las aristas que conectan el árbol con nuevos vértices, encontrar el mínimo y añadirlo al árbol
Seguir repitiendo el paso 2 hasta obtener un árbol de spanning mínimo
