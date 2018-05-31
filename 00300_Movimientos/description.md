En este ejercicio vamos a aprender una de las órdenes que podemos darle a la máquina: **mover el cabezal**. Para eso, le indicaremos al cabezal la dirección en la que tiene que moverse usando los puntos cardinales:

* Norte (arriba)
* Sur (abajo)
* Este (derecha)
* Oeste (izquierda)


Por ejemplo, partiendo de un tablero **inicial** vacío, podemos fácilmente escribir un programa que mueva el cabezal una posición hacia el **Norte**:

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
        head 0 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

El **código** del programa que logra esto (es decir, el **texto** de la solución que le daremos a la computadora) es el siguiente:

```gobstones
program {
  Mover(Norte)
}
```

**Ojo** :eyes:  
¡Fijate que siempre escribimos las direcciones con la inicial en mayúscula!

> ¿No nos creés? Escribí el código anterior en el editor y dale **Enviar**.