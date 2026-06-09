# 🛡️ SOC-SIEM-Lab: Detección de Amenazas y Monitoreo de Endpoints

## 📝 Descripción del Proyecto
Este repositorio contiene el despliegue, configuración y pruebas de concepto de un entorno SIEM centralizado utilizando **Wazuh**. El objetivo de este laboratorio es demostrar capacidades de ingeniería de detección mediante la ingesta de logs, creación de reglas personalizadas y la simulación/análisis de ataques reales alineados con el marco de **MITRE ATT&CK**.

---

## 🏗️ Arquitectura del Laboratorio
El entorno está diseñado de forma modular y consta de los siguientes componentes:

*   **Wazuh Manager, Indexer & Dashboard:** Desplegados de forma centralizada.
*   **Monitoreo Endpoint Windows:** Agente Wazuh + Sysmon para visibilidad profunda del sistema operativo.

```text
    [ Endpoint Windows ] (Wazuh Agent + Sysmon) ───► [ Wazuh Server ] ──► [ Wazuh Dashboard ]

---
## 🚀 Estado Actual del Proyecto
- [x] Despliegue de Wazuh Server/Manager.
- [x] Integración de alertas en tiempo real con **Discord**.
- [x] Despliegue de agentes en endpoints Windows.
- [ ] Reglas de detección personalizadas (Custom Rules). *(Próximamente)*
