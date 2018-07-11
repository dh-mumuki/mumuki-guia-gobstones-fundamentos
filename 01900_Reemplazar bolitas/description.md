¿Ya estás entrenado? :muscle:

Pasemos a algo un poco más difícil entonces. Te vamos a dar un tablero de **2x2** (o sea, con 4 celdas) donde cada una de ellas tiene **una bolita roja**.

> Tu tarea es escribir un programa que **reemplace** todas las bolitas rojas por verdes.

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
        size 2 2
        cell 0 0 Rojo 1
        cell 0 1 Rojo 1
        cell 1 0 Rojo 1
        cell 1 1 Rojo 1
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 2 2
        cell 0 0 Verde 1
        cell 0 1 Verde 1
        cell 1 0 Verde 1
        cell 1 1 Verde 1
        head 0 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

**¡Ojo!** Fijate en la representación de arriba: el cabezal debe quedar nuevamente en la posición inicial (0,0) :wink: