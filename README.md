[README.md](https://github.com/user-attachments/files/26800355/README.md)
# 🎓 Proyecto de Título — Implementación de Medidas de Ciberseguridad para la Protección de Datos en Nestlé Corporativo

**Institución:** IACC Instituto Profesional  
**Asignatura:** Taller de Integración en Seguridad de Datos  
**Autor:** Gerald Vega Soto  
**Carrera:** Técnico Profesional en Ciberseguridad  
**Año:** 2025  
**Duración:** 8 semanas  

---

## 📌 Descripción general

Proyecto de investigación aplicada desarrollado durante 8 semanas, enfocado en identificar vulnerabilidades de seguridad reales en el **edificio corporativo de Nestlé Chile** (piso 9) y proponer un plan de mejora integral que proteja los datos sensibles de la organización.

El proyecto nació de una experiencia directa: como técnico en telecomunicaciones de la empresa **Inteldata**, tuve acceso al piso corporativo de Nestlé durante una remodelación, lo que me permitió identificar brechas de seguridad reales que difícilmente se detectan desde el exterior.

---

## 🔍 Problema identificado

El edificio corporativo de Nestlé Chile concentra información altamente sensible: datos financieros, proyectos de innovación, propiedad intelectual y datos personales de gerencia. Durante el trabajo en terreno se detectaron **3 vulnerabilidades críticas**:

| # | Vulnerabilidad | Riesgo |
|---|---|---|
| 1 | Equipos corporativos (laptops, tablets) sin seguridad en oficina de gerente general durante presencia de personal externo | Acceso físico a datos críticos — afecta triada CIA |
| 2 | Credenciales de acceso no recuperadas al finalizar turno de trabajo externo | Credenciales funcionales extraviadas, acceso no autorizado potencial |
| 3 | Guardia de seguridad que abandonó su puesto al término de turno sin relevo, dejando al personal externo solo en área corporativa sin monitoreo | Ausencia total de supervisión en área crítica |

---

## 🎯 Objetivo general

Implementar medidas de ciberseguridad para proteger los datos sensibles de Nestlé, minimizando riesgos de ataques cibernéticos y garantizando la integridad de la información corporativa mediante el fortalecimiento del control de acceso físico y digital.

## 🎯 Objetivos específicos

- Analizar vulnerabilidades existentes en la infraestructura de seguridad de Nestlé
- Diseñar una propuesta de mejora en hardware, software y capacitación del personal
- Implementar herramientas de detección y prevención de intrusiones
- Evaluar el desempeño del sistema tras la implementación de las mejoras
- Capacitar al personal en técnicas de prevención contra ataques de ingeniería social

---

## 🛡️ Propuesta de solución

### Hardware propuesto
| Dispositivo | Modelo | Función |
|---|---|---|
| Servidor de seguridad | HP ProLiant DL380 Gen10 | Almacenamiento de logs y gestión de accesos |
| Firewall NGFW | Fortinet FortiGate 100F | Filtrado de paquetes y protección perimetral |
| Cámaras IP | Hikvision DS-2CD2145FWD-I | Monitoreo continuo de áreas corporativas |
| Control biométrico | ZKTeco SpeedFace-V5L | Autenticación por reconocimiento facial |
| Switch administrable | Cisco Catalyst 9200 | Segmentación de red corporativa |

### Software propuesto
| Herramienta | Función |
|---|---|
| Splunk Enterprise Security | SIEM — monitoreo y análisis de incidentes |
| Palo Alto Networks VM-Series | Firewall en redes virtualizadas |
| CrowdStrike Falcon | Antivirus y EDR |
| OpenVPN | Acceso remoto cifrado |
| Snort | IDS/IPS — monitoreo de tráfico sospechoso |

### Medidas organizacionales
- Control de acceso biométrico en puntos críticos del edificio
- Protocolo estricto de asignación y recuperación de credenciales
- Supervisión continua en cambios de turno
- Capacitaciones periódicas en ingeniería social (tailgating, pretexting, piggybacking)
- Aislamiento de dispositivos corporativos durante presencia de personal externo

---

## 📊 Resultados obtenidos

| Indicador | Resultado |
|---|---|
| Reducción de intentos de acceso no autorizado | 80% |
| Mejora en seguridad de accesos físicos (biometría) | 95% |
| Reducción de susceptibilidad al phishing | 60% |
| Personal de seguridad aún vulnerable a ingeniería social | 30% (requiere refuerzo) |

---

## 📐 Metodología

- **Tipo de investigación:** Mixta (cuantitativa + cualitativa)
- **Diseño:** No experimental — estudio de caso
- **Técnicas:** Observación directa, entrevistas, análisis documental, simulación de ataques de ingeniería social
- **Normativas de referencia:** ISO 27001, GDPR, modelo CIA (Confidencialidad, Integridad, Disponibilidad)

---

## 📁 Archivos del proyecto

| Archivo | Descripción |
|---|---|
| `Gerald_Vega_Ciberseguridad_Nestle.pptx` | Presentación final del proyecto |
| `Gerald_Vega_Guion_Ajustado.docx` | Guión de presentación |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_1.pdf` | Semana 1: Contextualización y selección del problema |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_2.pdf` | Semana 2: Planteamiento del problema y objetivos |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_3.pdf` | Semana 3: Marco teórico y vulnerabilidades detectadas |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_4.pdf` | Semana 4: Especificaciones y carta Gantt |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_5.pdf` | Semana 5: Propuesta de mejora — hardware y software |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_6.pdf` | Semana 6: Pruebas y correcciones del sistema |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_7.pdf` | Semana 7: Análisis de resultados y recomendaciones |
| `GERALD_VEGA-SEGURIDAD_DE_DATOS-SEMANA_8.pdf` | Semana 8: Informe final consolidado |

---

## 💡 Lecciones aprendidas

- Las vulnerabilidades de **seguridad física** son tan críticas como las digitales, y muchas veces se pasan por alto en auditorías convencionales.
- La **ingeniería social** (tailgating, pretexting, piggybacking) representa un vector de ataque real y activo que requiere capacitación constante, no solo tecnología.
- La seguridad integrada (física + digital + humana) es el único enfoque que protege efectivamente la triada CIA en entornos corporativos.
- El monitoreo continuo y los protocolos de cambio de turno son puntos críticos frecuentemente descuidados.

---

## 🔗 Conceptos clave abordados

`Ingeniería social` · `Tailgating` · `Modelo CIA` · `ISO 27001` · `NGFW` · `IDS/IPS` · `SIEM` · `Control biométrico` · `Segmentación de red` · `Pentesting` · `Análisis de riesgos`
