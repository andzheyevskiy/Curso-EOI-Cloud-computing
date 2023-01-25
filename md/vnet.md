# Redes Virtuales en Azure.

## Ejercicio a realizar

Este ejercicio se basara en el siguiente diagrama

![](img/vnet.png)

## Documentacion

Creamos un Grupo de recursos para el ejercicio:

![](img/vnet1.png)
![](img/vnet2.png)
![](img/vnet3.png)
![](img/vnet4.png)

Y posteriormente creamos una maquina virtual Windows Server en el grupo recien creado:

![](img/vnet5.png)
![](img/vnet6.png)
![](img/vnet7.png)

Habilitamos los puertos 80(http) y 3389(Remote Desktop):

![](img/vnet8.png)

Creamos una red correspodinete a la maquina virtual:

![](img/vnet9.png)
![](img/vnet10.png)
![](img/vnet11.png)

Una vez creada, repetimos el mismo proceso, esta vez sin crear una nueva red, sino conectamos a la que anteriormente hemos creado:

![](img/vnet12.png)
![](img/vnet13.png)

Una vez terminado, tendremos creadas dos maquinas conectadas a la misma red.

![](img/vnet14.png)


