# "DHCProject" 

## Introducción
### Los integrantes de este grupo son Juan Diego Llorente Ortega, Jean Paul Cano Gómez y Daniel Stiven Betancur Rodriguez. El propósito de este proyecto es realizar una simulación del funcionamiento de la asignación de IPs de un DHCP y de la interacción entre clientes y servidores en la misma.


### Cuando se ejecuta el cliente, este se conecta al servidor DHCP para solicitar una dirección IP y obtener otros parámetros de configuración de red, como la máscara de subred y la información del servidor DNS. El servidor lleva un registro de las direcciones IP asignadas para asegurar que cada cliente conectado reciba una IP única.

## Desarrollo
Se hizo uso de la API berkeley para el desarrollo del proyecto. Los archivos .h son utilizados para el almacenamiento e inicialización de variables.
Tanto el cliente como el server tienen la creación de sus sockets respectivos. Se enlazan a sus respectivos puertos y se les asigna la IP, el servidor recibe la dirección y MAC del cliente y responde confirmando la IP así como la máscara y la información del DNS


## Aspectos logrados
### Asignación de IP satisfactoria
### Conexión entre cliente y servidor en un mismo segmento de red.


## Aspectos no logrados
### Conexión entre cliente y servidor entre segmentos de red separados

## Conclusiones
### Este proyecto conllevó muchas dificultades debido al uso pobre del tiempo y por lo tanto no fue posible alcanzar la meta deseada planteada para el mismo, se espera que para futuras entregas la asignación de trabajos sea satisfactoria así como las dudas presentadas durante el desarrollo.

## Referencias
https://pubs.opengroup.org/onlinepubs/007904875/functions/recvfrom.html
https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/VPCs.CreatingVPC.html
https://docs.aws.amazon.com/vpc/latest/userguide/route-table-options.html#route-tables-internet-gateway
