# SOC-Splunk-Lab
Laboratorio de análisis de logs, consultas SPL en Splunk y mapeo de amenazas con MITRE ATT&amp;CK.

# 🔍 Enterprise SIEM Threat Hunting & SPL Queries Lab (Splunk Enterprise)

## 📌 Resumen Ejecutivo
Este repositorio documenta el desarrollo de consultas avanzadas en **Splunk Search Processing Language (SPL)**, creación de dashboards de seguridad y análisis de eventos de Windows para la detección proactiva de amenazas dentro de un Centro de Operaciones de Seguridad (SOC).

---

## 🛠️ Stack Tecnológico
- **SIEM:** Splunk Enterprise / Splunk Free
- **Fuentes de Datos:** Logs de Windows Server (Sysmon y Windows Security Event Logs)
- **Lenguaje de Consulta:** SPL (Search Processing Language)
- **Marco de Amenazas:** MITRE ATT&CK

---

## 📑 Casos de Uso y Consultas SPL Documentadas
En la carpeta [`/queries/`](./queries/) encontrarás los scripts y consultas estructuradas para:
1. **Detección de Fuerza Bruta (Event Code 4625):** Filtrado y conteo de intentos fallidos de autenticación por IP y usuario.
2. **Monitoreo de Creación de Usuarios (Event Code 4720):** Auditoría de cuentas creadas localmente en Active Directory.
3. **Detección de Modificación de Grupos Privilegiados (Event Code 4732):** Alertas sobre escalación de privilegios hacia administradores.

---

## 🎯 Competencias Clave Validadas
- Dominio de sintaxis y comandos de Splunk SPL (`stats count by`, `timechart`, `eval`, `rex`, `where`).
- Creación de alertas en tiempo real y visualizaciones analíticas.
- Alineación de telemetría con tácticas y técnicas del marco MITRE ATT&CK.
