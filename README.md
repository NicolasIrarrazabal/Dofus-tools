# ⚡ Autofocus Dofus Retro

Detector simple y eficiente para cambiar automáticamente a la ventana del personaje activo en **Dofus Retro** (Compatible con Fallaster y Allisteria).

> [!CAUTION]
> **Disclaimer:** Este proyecto tiene fines exclusivamente educativos. El uso de herramientas de terceros puede ir en contra de los términos de servicio de Ankama. Úsalo bajo tu propio riesgo.

---

## 🚀 Descarga y Uso (Versión Ejecutable)
Si no quieres instalar Python, puedes usar la versión lista para usar:

1. Ve a la sección de [**Releases**](https://github.com/TU_USUARIO/TU_REPO/releases/latest).
2. Descarga el archivo `DofusTools.zip`.
3. Descomprime el contenido en una carpeta.
4. **Importante:** Instala **Npcap** (ver sección de requisitos abajo).
5. Ejecuta `DofusTools.exe` como **Administrador**.

---

## 🛠️ Requisitos Previos (Obligatorio)

Para que la herramienta pueda detectar los paquetes de red, necesitas instalar:

* **Npcap:** [Descargar aquí la versión oficial](https://npcap.com/#download).
    * *Nota:* Durante la instalación, **debes** marcar la opción: `"Install Npcap in WinPcap API-compatible Mode"`.

---

## 💻 Ejecución desde el Código Fuente (Para Desarrolladores)

Si prefieres ejecutar el script manualmente, asegúrate de tener **Python 3.10+** instalado.

1. **Instalar dependencias:**
   ```bash
   pip install scapy pywin32 psutil
