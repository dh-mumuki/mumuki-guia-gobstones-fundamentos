Como te imaginarás, el cabezal no sólo se puede mover hacia el Norte, y un programa puede combinar cualquier tipo de movimientos.

> Escribí un programa que mueva el cabezal dos posiciones hacia el Este y una hacia el Sur, produciendo el siguiente efecto:

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
        head 0 2
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 2 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

Recordá que el comando que mueve el cabezal se llama `Mover` (ni `mOvEr`, ni `mover`, ni `MOVER`). ¡**Respetar la sintaxis es muy importante**! Si no lo hacés, el programá no andará: _buuuu_ :fearful:.
