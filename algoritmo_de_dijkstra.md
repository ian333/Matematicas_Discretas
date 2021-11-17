# Algoritmo de Dijkstra

- EL algoritmo de dijkstra busca la ruta optima o de coste mínimo, de conectar un punto inicial con un punto final.

## Secuencia del algoritmo

- Asignaremos a cada nodo no visitado el valor de infinito.
- Mantendremos un registro de los nodos visitados.
- Calcularemos la distancia a cada nuevo nodo sumándole la distancia anterior.
- Si la distancia nueva calculada es menor que la anterior, la remplazamos si no la ignoramos.
- EL algoritmo finaliza cuando se llega al nodo final.
## Explicación del algoritmo

  Para entenderlo bien tenemos que tener claro que para llegar al punto final que deseamos, iremos por la ruta donde la suma de conectar dos puntos sea menor.

## Ejemplo 

![dijkstra_algorythm](https://upload.wikimedia.org/wikipedia/commons/5/57/Dijkstra_Animation.gif)