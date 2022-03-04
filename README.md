## Establecer nombre de host

Visualiza el nombre de host del sistema. 
```
hostnamectl
``` 
Cambia el nombre de host asignado.
```
hostnamectl set-hostname new-hostname
``` 
## Instalación de actualizaciones de seguridad
Actualiza la lista de paquetes disponibles y sus versiones definidos en  /etc/apt/sources.list pero no los instala. 
``` 
sudo apt update
``` 
Elimina paquetes antiguos si es necesario para realizar la actualización de paquetes a sus últimas versiones.
``` 
sudo apt full-upgrade
``` 
Es una versión mejorada del comando apt-upgrade. Además de actualizar los paquetes de software existentes, instala y elimina algunos paquetes para satisfacer algunas dependencias.
``` 
sudo apt dist-upgrade 
``` 
Elimina paquetes que se instalaron automáticamente para satisfacer las dependencias de algún paquete y que ya no son necesarios.
```
sudo apt autoremove
``` 
Elimina del caché los paquetes .deb con versiones anteriores a los de los programas instalados.
```
sudo apt autoclean 
```
Reinicia el servidor Linux inmediatamente.
```
sudo reboot now  
```
## Extensiones Gnome 
```
sudo apt install chrome-gnome-shell
```
Las extensiones de Gnome Shell se pueden descargar desde su sitio web oficial usando un navegador web. 

https://extensiones.gnome.org

> Hide top bar 

La barra superior de Gnome puede ocultarse automáticamente como lo hace el panel de base izquierdo a través de una extensión de Gnome Shell.

https://extensions.gnome.org/extension/545/hide-top-bar/

> Custom hot corners extended 

Habilita y configura las funciones de esquinas activas.

https://extensions.gnome.org/extension/1362/custom-hot-corners/

> Clipboard indicator

Agrega un indicador de portapapeles al panel superior y almacena en caché el historial del portapapeles.

https://extensions.gnome.org/extension/779/clipboard-indicator/ 


