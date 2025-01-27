# Monitorización en red
Aquí detallarás herramientas como `tcpdump`, `tcptrack`, `iptraf-ng` y `netstat`.

## 1. Comando `tcpdump`

El comando `tcpdump` captura y analiza el tráfico de red.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/tcp.png)

### Sintaxis

`sudo tcpdump [opciones]`

Opciones:

- -i <nombre_interfaz>: Especifica la interfaz de red.
- port : Filtra por un puerto específico.

## 2. Comando `tcptrack`

`tcptrack` muestra conexiones TCP activas en tiempo real.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/tcptrack.png)

### Sintaxis

`sudo tcptrack -i <nombre_interfaz>`


## 3. Comando `iptraf-ng`

`iptraf-ng` Es una herramienta interactiva para ver estadísticas detalladas del tráfico de red.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/iptraf.png)

### Sintaxis

`sudo iptraf-ng`

## 4. Comando `netstat`

`netstat` muestra conexiones de red, sockets y estadísticas.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/netstat.png)

### Sintaxis

`netstat [opciones]`

Opciones:

- -a: Muestra todas las conexiones y puertos.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/netstat-a.png)

- -n: Muestra direcciones en formato numérico.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/netstat-n.png)

- -tp: Lista procesos asociados a conexiones TCP.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/netstat-tp.png)



[🔙 Volver al inicio](https://github.com/HoracioGG/Monitorizacion/blob/main/README.md)
