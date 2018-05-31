Notá que en este problema, si cambiamos el orden de las instrucciones, el resultado no cambia: siempre nos terminará quedando un tablero con tres bolitas rojas, una azul y una verde.

Por ejemplo, los siguientes dos programas también generan este mismo resultado:

```gobstones
program {
  Poner(Rojo)
  Poner(Rojo)
  Poner(Rojo)
  Poner(Verde)
  Poner(Azul)
}
```

```gobstones
program {
  Poner(Rojo)
  Poner(Azul)
  Poner(Rojo)
  Poner(Verde)
  Poner(Rojo)
}
```