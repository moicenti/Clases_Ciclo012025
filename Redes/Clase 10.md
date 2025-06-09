[[Redes]]

Clase A 0 - 127 / 8

Red 8 bits
Host 24 bits

El /8 dice que tiene 8 unos al inicio de la mascara de red

Clase B tiene un /16 porque tiene 16 bits de 1 en la mascara de red va de 128 a 191 

Clase C máscara de red de /24 (192- 223)

Clase D Tiene 4 bits de red al inicio y 28 de host(224-239)

Unicast: Proceso de enviar paquetes de un dispositivo a otro unico receptor

Broadcast: Porceso de enviar parquetes de un dispositivo a todos los de la red

MultiCast: Proceso de enviar paquetes a varios receptores selectos.

CLase E: 4 bits obligatorios en 1 ( 240-255)

**Formulas de subneteo**

2^m  -2
m= la cantidad de 0 en la máscara de red

195.3.5.0 ip de red
195.3.5.255 ip de broadcast

Formula de las redes que podemos tener

2^n-R

R bits que s eencuentran reservados
n cantidad de bits encendidos

**Ejercicio**

130.10.5.0/16

ES clase B y queremos 6 subredes 

2³>=6

hay que cambiar 3 bits

11111111.11111111.**111**00000.00000000
255.255.224.0/19

los nuevos host 

2¹³-2 = 8,190

el salto sería 256-224 = 32 de salto


