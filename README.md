# 🛡️ Auditoría de Ciberseguridad y Evaluación de Riesgos

Este repositorio contiene el informe técnico resultante de una auditoría de seguridad integral realizada sobre un segmento de red corporativo (192.168.14.0/24). El objetivo principal del proyecto es la identificación de vulnerabilidades, la evaluación de exposición de servicios y el diseño de un plan estratégico de mitigación.

## 🎯 Alcance del Proyecto
* Mapeo de topología lógica y física.
* Identificación de sistemas obsoletos (EOL) y exposición de puertos críticos.
* Evaluación de configuraciones criptográficas y certificados en servicios web/VPN.
* Desarrollo de un plan de remediación priorizado en tres fases (Inmediata, Corto Plazo, Medio Plazo).

## 🛠️ Herramientas Utilizadas
* **Nmap:** Descubrimiento de red, escaneo de puertos y fingerprinting.
* **OpenVAS:** Escaneo cuantitativo de vulnerabilidades (QoD >80%).
* **WhatWeb:** Identificación de tecnologías y análisis de cabeceras de seguridad HTTP.
* **testssl.sh:** Auditoría exhaustiva de protocolos SSL/TLS y mitigación de ataques (SWEET32, BEAST).
* **Draw.io:** Diagramación de infraestructura.

## 📄 Documentación
El análisis detallado, los datos en crudo y las conclusiones se encuentran en el [Informe de Auditoría (PDF)](https://github.com/isaacromanillos/Auditoria-FEVAL/blob/main/Informe%20Auditoria%20FEVAL.pdf).
