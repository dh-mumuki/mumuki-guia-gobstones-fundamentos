Entendamos qué es lo que acabamos de hacer: escribir un programa.

Todo programa tiene exactamente un `program`: una sección del código que declara los comandos (acciones) que queremos que la máquina realice sobre el tablero **inicial**. Al **ejecutar** un programa obtendremos un tablero **final**.

La sintaxis de un `program` es bastante simple:

1. escribimos una línea (renglón) que diga `program`, seguido de una llave de apertura: `{`
1. a continuación, los comandos: uno por línea
1. y finalmente, una última llave que cierra la que abrimos anteriormente `}`

Algunos ejemplos de `program`s:


```gobstones
program {
}
```

(no hace nada)


```gobstones
program {
  Mover(Norte)
}
```

(mueve el cabezal una posición hacia el norte)

```gobstones
program {
  Mover(Norte)
  Mover(Norte)
}
```

(mueve el cabezal dos posiciones hacia el norte)

> Sabiendo ésto, escribí un programa que en un tablero de 2x4 con el cabezal en el origen (la celda de abajo a la izquierda), mueva el cabezal tres veces hacia el norte:

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
        size 2 4
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 4
        head 0 3
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
