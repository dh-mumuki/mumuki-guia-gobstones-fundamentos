Ahora que combinamos operaciones, la cosa se pone un poco mas complicada, porque hay que tener **más cuidado con el orden**.

Por ejemplo, mirá el programa que escribiste:

```puppet
program {
  Poner(Rojo)
  Mover(Este)
  Poner(Negro)
}
```

Secuencialmente:

1. pone una roja
1. luego se mueve al este
1. luego pone una negra

Es decir: pone una roja en la posicion inicial, y una negra al este
