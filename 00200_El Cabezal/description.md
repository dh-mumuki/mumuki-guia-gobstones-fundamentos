Como notaste en el ejercicio anterior, el tablero generado tenía una **celda** marcada:

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>

¿Por qué ocurre esto? Porque nuestra máquina tiene un **cabezal**, que en todo momento está situado sobre una de las celdas del tablero y puede realizar distintas operaciones sobre ella (paciencia, ya las vamos a conocer :grin:).

Por ejemplo, el siguiente es un tablero de 5x2, con el cabezal en la segunda fila y la cuarta columna.

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>

Algo importante: contamos las filas hacia arriba, y las columnas hacia la derecha. La primera **fila** es la de **abajo** de todo, y la primera **columna** es la de la **izquierda**.

> ¿No te convence esto aún? Presioná Enviar y generaremos un tablero 3x3 con el cabezal en la segunda columna y tercera fila.
