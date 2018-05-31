Como podés ver a continuación, el nuevo tablero que generamos tiene una **celda** marcada:

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>

*¿Por qué ocurre esto?* Porque en nuestro tablero vamos a tener una máquina que tiene un **cabezal** que en todo momento está situado sobre una de las celdas del tablero y nos permite realizar distintas operaciones sobre ella (paciencia, ya las vamos a conocer :grin:).

Algo importante: fijate que contamos las filas desde abajo hacia arriba, y las columnas desde la izquierda hacia la derecha. La primera **fila** es la de **abajo** de todo, y la primera **columna** es la de la **izquierda**.
*Pero además*, si prestás atención vas a ver que la primera fila es la **cero**, y la primera columna también es la **cero**. Esto es así porque en todos los lenguajes de programación *siempre* empezamos a contar desde el **cero**.

Por ejemplo, el siguiente es un tablero de 5x2, con el cabezal en la segunda fila (fila número 1) y la cuarta columna (columna número 3).

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>



> ¿No te convence esto aún? Presioná **Continuar** y empezaremos a trabajar con un tablero de 3 celdas de ancho x 3 celdas de alto.
