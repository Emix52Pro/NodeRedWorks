<table style="width:100%">
  <tr>
    <th>Variable</th> 
    <th>Valor</th>
  </tr>
  <tr>
    <td style="text-align:center">X</td>
    <td style="text-align:center">{{msg.payload.ACCELEROMETER.values[0] | number:3}}</td> 
  </tr>
 
  <tr>
    <td style="text-align:center">Y</td>
    <td style="text-align:center">{{msg.payload.ACCELEROMETER.values[1] | number:3}}</td> 
  </tr>

  <tr>
    <td style="text-align:center">Z</td>
    <td style="text-align:center">{{msg.payload.ACCELEROMETER.values[2] | number:3}}</td> 
  </tr>
</table>
