# Solución del Ejercicio 1: Sector Bancario

## Hallazgos esperados
- Inventario completo de activos críticos (core banking, canales digitales, SWIFT, bases de datos de clientes).
- Mapa de dependencias entre aplicaciones y terceros, incluyendo proveedores de servicios en la nube y procesadores de pago.
- Identificación de amenazas relevantes basadas en MITRE ATT&CK para entornos financieros (p. ej. phishing dirigido, abuso de credenciales, exfiltración de datos).
- Evaluación de los controles existentes (autenticación multifactor, monitoreo de fraude, segregación de funciones) y brechas.

## Riesgos identificados
- Compromiso de credenciales privilegiadas que permita transferencias fraudulentas o manipulación de registros contables.
- Ataques de ransomware contra servidores de pagos con impacto directo en la disponibilidad del servicio y cumplimiento normativo.
- Exfiltración de datos sensibles de clientes con consecuencias regulatorias (PSD2, GDPR) y reputacionales.
- Dependencia crítica de un proveedor externo sin planes de continuidad robustos.

## Mitigaciones recomendadas
- Implementar gestión de acceso privilegiado (PAM) con monitoreo continuo y rotación automática de credenciales.
- Fortalecer la detección de phishing con campañas de concienciación, filtros avanzados y autenticación reforzada.
- Establecer segmentación de red y copias de seguridad inmutables probadas regularmente para mitigar ransomware.
- Formalizar acuerdos de nivel de servicio (SLA) y planes de contingencia con terceros clave; realizar pruebas de recuperación.
- Integrar alertas de comportamiento anómalo en el SIEM y definir procedimientos de respuesta a incidentes coordinados con áreas de negocio.
