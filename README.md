# Trabajo Final SDNV

Trabajo final de la materia SDNV - Universidad Politécnica de Madrid (ETSIT)

AUTORES: José Cassinelli, Israel Vásques y Andrés Muracciole

![Escenario del trabajo](https://github.com/amuracciole/FinalWork_SDNV/blob/master/Img_escenario.png)

## Objetivo: 
Desarrollo de un escenario virtual con VNX que emule una red residencial con su router virtualizado, con soporte de QoS implementado mediante SDN con Ryu y router/firewall virtual implementado con VyOS.

## Tareas a realizar: 
1- Crear escenario virtual VNX

2- Gestión de QoS en la frontera de la red de acceso (BRG y VNF:QoS)

    h1: 10 Mbps de bajada y 5 Mbps de subida

    h2: 4 Mbps de bajada y 4 Mbps de subida

3- Configuración del router VyOS:

    - IPv4

    - NAT y DHCP para IPv4

4- Firewall en VyOS

    - Filtrar conexiones entrantes salvo: HTTP/HTTPS para h1 y SSH para h2

    - Todo tráfico saliente permitido

5- Acceso a Internet

6- Soporte IPv6

7- DHCP para IPv6

8- VyOS WebGUI

9- Interpretar las tablas de flujos de QoS

10- Segunda red residencial

## Documentación de interés: 

[Manual_VyOS](https://wiki.vyos.net/wiki/User_Guide)

[RyU_QoS](https://osrg.github.io/ryu-book/en/html/rest_qos.html)