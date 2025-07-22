# GTS Telnet Rebooter

Una herramienta gráfica en Python que permite reiniciar múltiples dispositivos GTS conectados vía Telnet. Permite ejecutar reinicios inmediatos o programados a una hora específica, manejar reintentos automáticos si el host está ocupado, y registrar todas las acciones en un archivo `.log`.

## 🧩 Características

- ✅ Interfaz gráfica (Tkinter)
- 🔁 Reinicio inmediato de múltiples dispositivos por Telnet
- 🕒 Reinicio automático programado a una hora definida
- 🧠 Detección de host ocupado con reintentos automáticos
- 📁 Registro detallado en archivo `reboot_log.txt`
- 📋 Carga dinámica de IPs desde archivo `ips.txt`

## 🖥️ Requisitos

- Python 3.7 o superior
- Sistema operativo Windows, Linux o macOS
- Acceso Telnet a los dispositivos GTS

