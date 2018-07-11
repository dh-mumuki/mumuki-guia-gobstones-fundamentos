Moraleja: ¡no hacen lo mismo! Cambiar el orden nos cambió el qué.

El primer programa 

```puppet
program {
  Mover(Este)
  Poner(Rojo)
  Poner(Negro)
}
```
secuencialmente:

se mueve al este
luego pone una bolita roja
luego pone una bolita negra
Es decir: pone una bolita roja y una bolita negra al este de la posición inicial.


```puppet
program {
  Poner(Negro)
  Mover(Este)
  Poner(Rojo)
}
```
secuencialmente:

Pone una bolita negra
se mueve al este
luego pone una bolita roja
Es decir: pone una bolita negra en la posición inicial y una bolita roja al este de la bolita negra.

