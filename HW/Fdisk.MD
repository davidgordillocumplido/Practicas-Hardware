# FDisk : como crear una partición

## Definición y función 

-Es un software que se puede instalar en diferentes sistemas operativos ,el cual permite dividir en forma lógica un disco duro, siendo denominado este nuevo espacio como partición. La descripción de las particiones se guarda en la tabla de particiones que se localiza en el sector 0 de cada disco.

## Como crear una partición y una swap


_Ponemos el comando dd if=/dev/zero of=/mnt/512MiB.swap bs=1024 count=524288 para crear un archivo_


Lo primero que tenemos que hacer es ir a la terminal y entrar como root

A continuación ponemos el comando fdisk -1 para ver las particiones y nos pondra si queremos una nueva, para crearla tenemos que seguir estos pasos :

N -> Crear una nueva partición

E o P -> Para crear una extended o una primaria

Nos pedira en que posición la queremos ( 1-4 ) la dejamos default, tambien nos pedira que tamaño queremos el primer cilindro y el ultimo , el primero lo dejamos default y el ultimo le ponemos +105M

Y así hasta crear las 3 primarias y 1 extended y al final nos saldra un mensaje para crear la swap.

Ponemos el comando w para salir y guardar.


