# Algoritmo de Prim
- **Un algoritmo es una serie de pasos, que seguimos de acuerdo a una lógica y si seguimos los pasos consecutivamente lograremos el objetivo.**
- El algoritmo de Prim lo que nos permite es encontrar el árbol de expansión mínimo, obtendremos el coste mínimo de conectar todos los nodos.
- Importante no se pueden formar ciclos.

## Secuencia del algoritmo de Prim

- Seleccionamos un vértice cualquiera.
- Seleccionamos la conexión de **menor peso** conectada al vértice.
- En cada iteración seleccionamos la arista de menor peso, relacionada con los vértices conectados.
- El algoritmo finaliza cuando todos los vértices están conectados con (n-1) aristas, por ejemplo si tenemos 9 vértices, tendremos 8 conexiones.

## Primer Ejemplo Algritmo de Prim 
![Prim-algorythm](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/PrimAlgDemo.gif/200px-PrimAlgDemo.gif)

## Segundo Ejemplo Algritmo de Prim 

![Prim-algorythm](https://i.stack.imgur.com/gMPmj.gif)