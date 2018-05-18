Cuando trabajamos en Gobstones, hacemos las cosas en un cierto orden. Por ejemplo, si tenemos este programa:

```gobstones
program {
  Mover(Norte)
  Mover(Este)
}
```

una forma posible de leerlo (llamada **operacional**) es como lo haría una máquina, en orden, de arriba hacia abajo:

1. primero se mueve al norte: `Mover(Norte)`
1. luego se mueve al este: `Mover(Este)`

Y de hecho **se ejecuta de esa forma**. Esto es _cómo_ lo hace.

Pero, los humanos, solemos pensar en función del resultado final, es decir, resaltamos el **objetivo** del programa. Nos importa más _qué_ hace, y no cómo. Esta manera denotacional nos llevaría a decir que, simplemente, **mueve el cabezal al noreste**. 

Por eso hay varias formas de resolver un mismo problema: podemos escribir varios programas que hagan lo mismo (el _qué_), pero que lo hagan de forma diferente (el _cómo_).

> Veamos si entendiste esto: escribí otro programa que haga lo mismo que el de arriba (mover hacia el noreste), pero de manera distinta. **Ojo:** tiene que funcionar en un tablero de 2x2.
