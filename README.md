Este repositorio contiene mi configuración personal (rice) para el compositor Sway, además de
algunos scripts y archivos extra.

(Rice basado en el de https://github.com/ezequielgk/Sway-Dotfile)

Dependencias del Sistema
Para que esta configuración funcione correctamente, es necesario instalar los siguientes
paquetes. Las instrucciones están orientadas a Fedora, pero los nombres de los paquetes son
similares en otras distribuciones.

1. Compositor y Ventanas
● Sway: El gestor de ventanas principal.
● Swaybg: Necesario para configurar el fondo de pantalla.
● Swaylock / Swayidle: Para el bloqueo y gestión de energía de la pantalla.
● Xwayland: Para compatibilidad con aplicaciones que no soportan Wayland nativamente.

2. Interfaz y Barra de Estado
● Waybar: La barra de herramientas superior.
● Wofi: Lanzador de aplicaciones (menú de inicio).
● Mako o Dunst: Gestor de notificaciones.

3. Terminal y Utilidades
● Foot: Emulador de terminal (por defecto en la configuración).
● Grim y Slurp: Herramientas para realizar capturas de pantalla.
● Brightnessctl o Light: Para el control de brillo desde el teclado.
● Pactl (pulseaudio-utils): Para el control de volumen.

Instalación rápida en Fedora:
sudo dnf installsway waybar wofi foot swaybg swaylock grim slurp mako brightnessctl pulseaudio-utils
sudo dnf copr enable zhangyi6324/noctalia-shell

Notas Adicionales:
Asegúrate de dar permisos de ejecución a los scripts en la carpeta scritps para que los atajos
de teclado funcionen:
chmod +x ~/DotFiles-y-Otros/scritps/*
