# extended_struct
Extiende la funcionalidad del módulo estándar struct, para aceptar otros formatos numéricos.<br>
<br>
Utiliza el mismo protocolo que el módulo struct para trabajar la conversión la representación binaria y los valores en python, 
es decir se mantienen los mimsos métodos de struct (pack, unpack, calcsize) y el mismo formato de invocación.<br>
<br>
Los formatos e indicadores adicionales son :<br>
<br>
  'F' : Número de punto flotante de 24 bits (IEE754 truncado).<br>
  'M' : Número de punto flotante de 24 bits, formato alternativo de Microchip.<br>
  'g' : Numero de 24 bits (3 bytes), con signo.<br>
  'G' : Numero de 24 bits (3 bytes), sinn signo.<br>
  'j' : Numero de 40 bits (5 bytes), con signo.<br>
  'J' : Numero de 40 bits (5 bytes), con signo.<br>
