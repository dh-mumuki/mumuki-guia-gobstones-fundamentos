Notá que en este problema, si cambiamos el orden en que _llamamos_ (usamos a) `Poner`, el resultado no cambia: siempre nos terminará quedando un tablero con tres bolitas rojas, una azul y una verde.

Por ejemplo, los siguientes dos programas también resuelven este mismo problema:

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