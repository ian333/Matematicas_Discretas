# Algoritmo de Kruskal
Encuentra el árbol de **expansión mínima**, enfocándose en las conexiones.

1. Encontramos la conexión con **menor coste**.
2. Repetimos la misma iteración. buscamos la otra **conexión con menos costo** obviando la de la anterior iteración.
3. Debemos tener cuidado con no elegir una conexión que nos cree un **ciclo**.