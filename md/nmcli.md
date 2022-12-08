# Network tools

## 1. Set static ip on your linux device to connect to your LAN using nmcli command.

Para ello vamos a configurar la IP, puerta de enlace y DNS. Importante tener permisos de superusuario.

Para modificar IP:

`nmcli connection modify [Nombre de dispositivo] ipv4.address [IP/CIDR]`

Para modificar puerta de enlace:

`nmcli connection modify [Nombre de dispositivo] ipv4.gateway [Puerta de enlace]`

Para modificar DNS

`nmcli connection modify [Nombre de dispositivo] ipv4.dns [DNS]`

Y para verificar los cambios:

`nmcli`

![](/nmcli1.png)

## 2. Disable the nmcli network interface

Para desactivar un dispositivo de red:
`nmcli connection down [Nombre de dispositivo]`

![](/nmcli2.png)

## 3. Activate the nmcli network interface

Para activar un dispositivo de red:
`nmcli connection up [Nombre de dispositivo]`

![](/nmcli3.png)

## 4. Check with the ip command your configuration

Para comprobar la IP:
`ip addr`

![](/nmcli4.png)

## 5. Do ping to nodes on your network

Commando: 
`ping [IP address]`

![](/nmcli5.png)

## 6. Lists all .txt files in the current directory and then counts those .txt files and saves the output to a new file

Se usaría el comando ls en conjunto con wc.

`. ls *.txt | wc -l > [nombre de archivo saliente].txt`

![](/nmcli6.png)

## 7. Create a file from scratch on linux and include the following information

> This is the file create in linux with some information will be copied to another host in the network

Para crear archivo:
`echo [contenido del archivo] > [nombre del archivo] `

![](/nmcli7.png)
