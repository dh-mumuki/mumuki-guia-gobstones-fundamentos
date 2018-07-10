Cuando trabajamos en Gobstones, hacemos las cosas en un cierto orden. Por ejemplo, pensemos que dado el siguiente tablero inicial, queremos mover el cabezal a la esquina noreste:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 2 2
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

Si tenemos el siguiente programa:

```gobstones
program {
  Mover(Norte)
  Mover(Norte)
  Mover(Este)
  Mover(Este)
}
```

una forma posible de leerlo (llamada **secuencial**) es como lo haría una máquina: en orden, de arriba hacia abajo:

1. primero se mueve al norte: `Mover(Norte)`
1. luego se mueve al norte nuevamente: `Mover(Norte)`
1. luego se mueve al este: `Mover(Este)`
1. y finalmente se mueve al este una vez más: `Mover(Este)`

Y de hecho **se ejecuta de esa forma**.

Pero, los humanos solemos pensar en función del resultado final, es decir, resaltamos el **objetivo** del programa. Nos importa más _qué_ hace, y no tanto el _cómo_ lo hace. Esta forma de pensar nos llevaría a decir, simplemente, **mueve el cabezal a la esquina noreste**. 

Por eso hay varias formas de resolver un mismo problema: podemos escribir varios programas que hagan lo mismo (el _qué_), pero que lo hagan de forma diferente (el _cómo_).

> Veamos si entendiste esto: escribí otro programa que haga lo mismo que el de arriba (mover hacia la esquina noreste), pero de manera distinta. **Ojo:** tiene que funcionar en un tablero de 3x3.
