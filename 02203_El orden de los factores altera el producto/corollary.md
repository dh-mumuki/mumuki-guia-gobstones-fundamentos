Moraleja: ¡no hacen lo mismo! Cambiar el orden nos cambió el objetivo, es decir el qué.

El primer programa 

```puppet
program {
  Mover(Este)
  Poner(Rojo)
  Poner(Negro)
}
```
secuencialmente:

1. se mueve al este
1. luego pone una bolita roja
1. luego pone una bolita negra

Es decir: pone una bolita roja y una bolita negra al este de la posición inicial.

Mientras que el segundo programa

```puppet
program {
  Poner(Negro)
  Mover(Este)
  Poner(Rojo)
}
```
secuencialmente:

1. Pone una bolita negra
1. se mueve al este
1. luego pone una bolita roja

Es decir: pone una bolita negra en la posición inicial y una bolita roja al este de la bolita negra.

