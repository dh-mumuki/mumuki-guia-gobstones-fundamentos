Algo interesante de nuestros tableros es que en sus celdas podemos poner cualquier cantidad de bolitas de cualquier color.

Por ejemplo, si tenemos este tablero:

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>

y ejecutamos el siguiente programa:

```gobstones
program {
  Poner(Rojo)
  Poner(Rojo)
  Poner(Azul)
  Poner(Verde)
  Poner(Rojo)
}
```

el cabezal colocará en la celda actual tres bolitas rojas, una azul y una verde.

> ¡Escribí este programa en el editor y fijate cómo queda el tablero!