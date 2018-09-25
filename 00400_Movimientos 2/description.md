Entendamos qué es lo que acabamos de hacer. Aunque no lo creas, acabamos de **escribir un programa**.

Todo programa tiene una sección de código donde se declaran los comandos (acciones) que queremos que la máquina realice. Al *correr* un programa, se *ejecutan* los comandos, y obtenemos un *resultado*. 

En el lenguaje `Gobstones` esta sección de código se denomina `program`. En esta sección se van a correr los comandos que queremos que la máquina realice sobre el tablero **inicial** y cuyo resultado visualizaremos en el tablero **final**.

La sintaxis del `program` en `Gobstones` es bastante simple:

1. escribimos una línea (renglón) que diga `program` (en minúscula), seguido de una llave de apertura: `{`
1. a continuación, los comandos: uno en cada línea
1. y finalmente, una última llave que cierra la que abrimos anteriormente: `}`

Algunos ejemplos de `program`s:

<table class= "table" style="width:100%">
  <tbody>
  <tr>
    <td style="text-align: left">  
      <pre class="highlight gobstones"><code><span class="kr">program </span>{
}</code></pre>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: left">
No hace nada
    </td>
  </tr>
  <tr>
    <td style="text-align: left">  
      <pre class="highlight gobstones"><code><span class="kr">program </span>{
  Mover(Norte)
}</code></pre>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: left">
Mueve el cabezal una posición hacia el norte
    </td>
  </tr>
  <tr>
    <td style="text-align: left">  
      <pre class="highlight gobstones"><code><span class="kr">program </span>{
  Mover(Norte)
  Mover(Norte)
}</code></pre>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: left">
Mueve el cabezal dos posiciones hacia el norte
    </td>
  </tr>
  <tbody>
</table>



> Sabiendo ésto, escribí un programa que mueva el cabezal tres veces hacia el norte, en un tablero de 2x4 con el cabezal en el origen (la celda de abajo a la izquierda):

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
