# Autofocus Dofus Retro

Detector simple y eficiente para cambiar automáticamente a la ventana del personaje activo en **Dofus Retro** (Compatible con Fallaster y Allisteria).

## ⚠️ Disclaimer
Este proyecto tiene fines exclusivamente educativos. El uso de herramientas de terceros puede ir en contra de los términos de servicio de Ankama. Úsalo bajo tu propio riesgo.

## 🛠️ Requisitos previos

Para que el script funcione correctamente en Windows, necesitas:

1.  **Python 3.10+** instalado.
2.  **Npcap**
    * [Descargar Npcap aquí](https://npcap.com/#download).
    * *Nota: Durante la instalación, asegúrate de marcar la opción "Install Npcap in WinPcap API-compatible Mode".*
3.  **Permisos de Administrador**: Debes ejecutar la terminal (CMD o PowerShell) como Administrador para que el script tenga acceso a la tarjeta de red.

## Instalación

Clona este repositorio o descarga el archivo `.py` y ejecuta el siguiente comando para instalar las dependencias:

pip install scapy pywin32 psutil

## Uso

Ejecuta el script:

python autofocus_dofus_retro.py

Luego conecta tus personajes en el juego, el script detectará cuándo es tu turno y pondrá la ventana en primer plano.

Para salir escribe stop y presiona Enter.
