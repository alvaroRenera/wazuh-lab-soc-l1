🛡️ Laboratorio SOC L1 con Wazuh

Autor: Álvaro Gonzalez Olivares
Rol objetivo: Analista SOC Nivel 1 (Blue Team)
Objetivo del repositorio: Documentar prácticas reales con Wazuh orientadas a la monitorización, clasificación y análisis inicial de alertas.

🎯 Objetivos del laboratorio

Instalar y configurar un entorno básico de Wazuh (manager + agent).

Analizar alertas frecuentes en un SOC L1:

Fuerza bruta SSH

Escaneo de puertos

Malware detectado

Cambios sospechosos en el sistema

Documentar los pasos de investigación siguiendo buenas prácticas SOC.

Crear informes claros y técnicos sobre cada alerta.

🧰 Herramientas utilizadas

Wazuh (SIEM / XDR)

Kibana / Wazuh Dashboard

Linux (Ubuntu/Debian)

Windows 10/11 (agente opcional)

VirusTotal

Shodan

Wireshark

📁 Estructura del repositorio
```
wazuh-lab-soc-l1/
  ├── README.md
  ├── setup/
  │     └── guia_instalacion.md
  ├── alertas/
  │     ├── brute_force_ssh.md
  │     ├── port_scanning.md
  │     └── malware_detectado.md
  └── evidencias/
        ├── capturas-alertas/
        └── logs-ejemplo/
```

🔔 Alertas analizadas en este laboratorio

Brute Force SSH

Port Scanning

Malware Detectado

Cada alerta incluye:

Descripción

Logs relevantes

Clasificación (TP/FP)

Pasos de investigación

Recomendaciones
