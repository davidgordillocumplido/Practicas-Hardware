# MBR

## 2. Que es MBR?

Un registro de arranque principal, conocido también como registro de arranque maestro es
el primer sector de un dispositivo de almacenamiento de datos, como un disco duro. 
 

## 1. Que contiene MBR en la pista cero?
 
-Código de máquina ( PESO = 446 bytes ) : Es el sistema de códigos directamente interpretable por un circuito microprogramable

-Tabla de particiones ( PESO = 64 bytes ) : Se define a partir de las particiones primarias , en ellas se almacena información básica
 sobre la partición : si es arrancable , si no lo es, el formato , el tamaño y el sector.

-Firma de unidad arrancable ; 55h AAh en hexadecimal ( PESO = 2 bytes )
 
 Total de bytes en la pista cero : 512 bytes**
 
