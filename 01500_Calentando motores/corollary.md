Ahora que combinamos operaciones, la cosa se pone un poco mas complicada, porque hay que tener **más cuidado con el orden**.

Mirá el programa que escribiste:

```puppet
program {
  Poner(Rojo)
  Mover(Este)
  Poner(Negro)
}
```

Secuencialmente:

1. pone una bolita roja
1. luego se mueve al este
1. luego pone una bolita negra

Es decir: pone una bolita roja en la posicion inicial, y una bolita negra al este


