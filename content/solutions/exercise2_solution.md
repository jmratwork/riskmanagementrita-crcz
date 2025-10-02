# Solución del Ejercicio 2: Infraestructura Energética ICS

## Hallazgos esperados
- Inventario de componentes OT críticos (SCADA, PLC, RTU, redes de campo) y sus interdependencias con sistemas IT.
- Diagrama actualizado de zonas y conductos conforme a ISA/IEC 62443 con puntos de acceso remotos identificados.
- Registro de amenazas y tácticas pertinentes (MITRE ATT&CK for ICS), incluyendo compromiso de ingeniería remota y manipulación de procesos.
- Evaluación de controles actuales como firewalls industriales, whitelisting de aplicaciones y políticas de cambio en OT.

## Riesgos identificados
- Intrusión en la red corporativa que pivote hacia la DMZ industrial y afecte la operación del SCADA.
- Manipulación maliciosa de parámetros en PLC provocando interrupciones en la generación o distribución eléctrica.
- Denegación de servicio sobre enlaces de comunicación con centros de control redundantes insuficientes.
- Uso de credenciales compartidas para acceso de mantenimiento remoto sin supervisión ni registro.

## Mitigaciones recomendadas
- Implementar monitoreo continuo de redes OT con detección de anomalías y visibilidad de protocolos industriales.
- Aplicar control de acceso basado en roles y autenticación multifactor para accesos remotos a ingeniería.
- Segmentar la red con firewalls de próxima generación entre IT/OT y zonas críticas, usando listas de control mínimamente necesarias.
- Establecer procedimientos de gestión de parches y cambios validados en entornos de pruebas antes de producción.
- Diseñar y probar planes de respuesta ante incidentes OT, con ejercicios coordinados con operaciones y proveedores.
