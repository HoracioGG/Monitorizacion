# Monitorización de Procesos

En esta sección se abordan herramientas para monitorizar los procesos de un sistema Linux.

## 1. Comando `ps`

El comando `ps` muestra una instantánea de los procesos en ejecución.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/ps.png)

### Sintaxis

`ps [opciones]`

Opciones:

- ps a: Muestra todos los procesos de la sesión actual, incluidos los de otros usuarios.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/ps-a.png)

- ps aux: Lista todos los procesos en ejecución junto con información detallada (usuario, PID, CPU, memoria, etc.).

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/ps-aux.png)

- ps -C <nombre_proceso>: Filtra y muestra información de un proceso específico.

## 2. Comando `top` 

El comando `top` permite monitorizar el sistema en tiempo real, mostrando una vista dinámica de los procesos en ejecución y su consumo de recursos.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/Top.png)

### Sintaxis

- top T: Cambia la visualización de los procesos al tiempo acumulado.
- top M: Cambia la vista al uso de memoria.
- top P: Ordena los procesos según el uso de CPU.
- top q: Salir del programa.
- top k: Termina un proceso especificando su PID.

## 3. Comando `htop`

El comando `htop` es una versión mejorada de top, con una interfaz más amigable e interactiva.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/htop.png)

### Sintaxis

`htop [opciones]`

Opciones:

- htop -u : Muestra los procesos de un usuario específico.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/htop-u.png)

- htop --tree: Muestra los procesos en formato de árbol.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/htop--tree.png)

- htop -p <PID1,PID2>: Filtra por varios PIDs.

![](https://github.com/HoracioGG/Monitorizacion/blob/main/img/htop-p.png)

Atajos de teclado:

- F2: Configuración.
- F3: Búsqueda de procesos.
- F5: Vista en árbol.
- F9: Terminar un proceso.


[🔙 Volver al inicio](https://github.com/HoracioGG/Monitorizacion/blob/main/README.md)
