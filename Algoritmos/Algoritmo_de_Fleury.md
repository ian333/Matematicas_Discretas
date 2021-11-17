# Algoritmo de Fleury

Apuntes de clase

- El algoritmo de **Fleury** nos permite encontrar un ciclo **eureliano**.

- Recuerda que un **ciclo eureliano**, tenia que tener sus vértices con **grado par**, empezar y acabar en el mismo vértice y recorrer **una sola vez** sus conexiones.

## Explicación del algoritmo

- Tenemos que realizar **circuitos o ciclos cerrados** con nuestros vertices.
- Una vez tenemos el primer ciclo, realizamos el segundo **con conexiones que no tenga el primero**.
- Después juntamos los dos ciclos a través del **vértice que tengan en común**.
- Así hasta haber recorrido todas las conexiones sin repetirlas a través de **ciclos cerrados**.
- Cuando juntemos los ciclos que hemos obtenidos lo haremos con los **vértices que compartan los ciclos**.
- Para saber si lo hemos hecho bien, los vértices tienen que aparecer **la mitad de las veces** que el grado de ese mimo vértice, si por ejemplo (f) aparece **dos veces** en la unión de los ciclos su grado debe de ser de **cuatro**.

