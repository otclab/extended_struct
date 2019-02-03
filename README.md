# extended_struct
Extiende la funcionalidad del módulo estándar struct, para aceptar otros formatos numéricos.

Utiliza el mismo protocolo que el módulo struct para trabajar la conversión la representación binaria y los valores en python, 
es decir se mantienen los mimsos métodos de struct (pack, unpack, calcsize) y el mismo formato de invocación.

Los formatos e indicadores adicionales son :

  'F' : Número de punto flotante de 24 bits (IEE754 truncado).
  'M' : Número de punto flotante de 24 bits, formato alternativo de Microchip.
  'g' : Numero de 24 bits (3 bytes), con signo.
  'G' : Numero de 24 bits (3 bytes), sinn signo.
  'j' : Numero de 40 bits (5 bytes), con signo.
  'J' : Numero de 40 bits (5 bytes), con signo.
