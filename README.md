# Automated Network Backup Tool (ANBT)

## Descripción
Este proyecto consiste en un script automatizado desarrollado en Python utilizando la librería **Netmiko**. Su objetivo principal es conectarse de manera segura (vía SSH) a múltiples dispositivos de red (Cisco IOS), extraer sus configuraciones en ejecución (*running-config*) y almacenarlas localmente organizadas por fecha y hora. 

Ideal para administradores de red y especialistas en ciberseguridad que buscan mantener un control de versiones estricto de sus configuraciones de infraestructura digital.

---

## Requisitos del Sistema
Para ejecutar este script de automatización, asegúrate de contar con el siguiente software base:

* **Sistema Operativo:** Ubuntu Linux v22.04 LTS o superior / Windows 11 con WSL2.
* **Lenguaje:** Python v3.10 o superior.
* **Librerías de Python:**
  * `netmiko==4.3.0`
  * `paramiko==3.4.0`

---

## Instrucciones de Instalación

Sigue estos pasos detallados para clonar el repositorio y configurar el entorno virtual:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/tu-usuario/network-automation-tools.git](https://github.com/tu-usuario/network-automation-tools.git)
cd network-automation-tools
