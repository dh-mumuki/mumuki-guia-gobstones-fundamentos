Ahora que estamos combinando operaciones, y como te comentamos previamente, hay que tener más cuidado con el orden de los comandos.

Teniendo en cuenta esto, contestá... ¿Qué hacen estos programas?

```puppet
program {
  Mover(Este)
  Poner(Rojo)
  Poner(Negro)
}
```

```puppet
program {
  Poner(Negro)
  Mover(Este)
  Poner(Rojo)
}
```



