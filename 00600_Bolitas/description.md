Genial :smile:!!!.

Ya entendiste cómo mover el cabezal del tablero usando la operación `Mover` y las direcciones (`Norte`, `Sur`, `Este` y `Oeste`). Vayamos un paso más allá: las **bolitas**.

En cualquier celda de nuestro tablero podemos poner `bolitas`. Las hay de distintos colores:

 * Rojas (`Rojo`)
 * Azules (`Azul`)
 * Negras (`Negro`)
 * Y verdes (`Verde`)

Por ejemplo, este es un tablero con una bolita roja y una negra:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>

Además de moverse, el cabezal también puede poner bolitas en la **celda donde está parado**.  
Para eso contamos con la operación `Poner`, que le dice al cabezal que deposite una bolita del color dado:

```gobstones
program {
  Poner(Rojo)    
}
```

> ¡Probá este programa! Escribí el código en el editor y dale **Enviar** para ver lo que pasa al ejecutarlo sobre este tablero.

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>