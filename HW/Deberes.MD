# Deberes

## Que significa el simbolo ~

## Crear particiones gpt 

Primero vamos a la terminal y iniciamos como root , una vez que estamos con root ponemos el comando gdisk para comenzar a editar las particiones.

1. Ponemos n (new) para crear una nueva partición

2. Elegimos que posición queremos ponerla

3. Elegimos el tamaño del primer cilindro (Default)

4. Elegimos el tamaño del ultimo ( +105 MB)

5. Ponemos el comando L para mostrar la lista de códigos

6. Ponemos el comando w para salir y guardar.


## Que es watch y como pomerlo a 1 s

Watch es una comando que su función es repetir durante x tiempo un comando o un programa.

Como ponerlo cada 1 s?

Con el siguiente comando :
watch -n 1 df -h > Nombre del archivo

## Que es ionice ?

Establecer el programa io una prioridad por encima de los demas.

## Que es Cnt+z y bg ?

La función del Cnt+z es matar/cerrar el servicio que estas utilizando actualmente , en cambio la función del bg es revivir el servicio pero se pondra en 2 plano y esto permitira el servicio utilizarlo junto a otro( o mientras sigues utilizando la terminal)
