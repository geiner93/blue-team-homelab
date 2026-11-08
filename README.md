🛡️ Blue Team Homelab

Laboratorio personal para aprender operaciones de seguridad (SOC): monitoreo, detección y respuesta a incidentes.

## Arquitectura

| Componente | Detalle |
| --- | --- |
| Anfitrión | Windows · Ryzen 7 · 24 GB RAM |
| SIEM | Wazuh 4.14 (todo en uno) en Ubuntu Server 24.04 (VirtualBox, 4 CPU, 8 GB RAM) |
| Red | Adaptador puente (Internet) + red solo-anfitrión con IP fija 192.168.56.10 |
| Visibilidad | Agente de Wazuh + Sysmon en Windows *(semana 2)* |

![Dashboard de Wazuh](img/dashboard-wazuh.png)

## Avance

- [x] **Semana 1:** instalación del SIEM → [01-instalacion.md](01-instalacion.md)
- [ ] **Semana 2:** agente de Wazuh y Sysmon en Windows
- [ ] **Semana 3:** primeras detecciones y monitoreo de integridad de archivos

## Problemas resueltos

Diagnóstico y solución de los problemas reales que encontré → [problemas.md](problemas.md)

## Herramientas

Wazuh · Ubuntu Server · VirtualBox · SSH · tmux · netplan · Sysmon

## Sobre mí

Estoy formándome como analista SOC (Blue Team).
