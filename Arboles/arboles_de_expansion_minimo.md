# Arbol de Expansion Minimo
- Un Arbol  deExpansion es donde tenemos
- Un árbol de expansión es donde tenemos todos los nodos conectados entre si, pero tenemos un numero asociado a cada conexión.
- Ese número representa una unidad, un recurso o un coste que debemos asumir para conectar los nodos entre si.
- Cuando buscamos el nodo de expansión mínimo, lo que estamos buscando es como conectar todos los nodos entre si y que cueste lo mínimo posible.


## Algoritmo para hallar el árbol de expansión mínimo

1. Elegiremos un nodo cualquiera para que sea nuestro nodo raiz.
2. Una vez tenemos el nodo raíz buscaremos las conexiones a es nodo y elegiremos la conexión con menor coste.
3. Seguiremos repitiendo este proceso hasta conectar todos los nodos, siempre eligiendo la conexión con el valor mas pequeño.
4. Es importante que cuando estemos conectando los nodos entre si, no se vayan a producir ciclos o rutas cerradas, porque no serviría el algoritmo.

Cuando ya tenemos el **árbol de expansión mínimo** ya podemos representarlo empezando por el nodo raíz que seleccionamos.

El coste total de nuestro árbol de expansión mínimo sera la **suma de todas las conexiones seleccionadas**.

