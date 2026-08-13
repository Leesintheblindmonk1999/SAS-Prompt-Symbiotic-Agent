# Security Policy / Política de Seguridad

<div align="center">

**[English](#english) · [Español](#español)**

</div>

---

# English

## 1. Reporting a Security Issue

If you discover a security vulnerability or structural issue within the Symbiotic Architecture Protocol (SAP), its implementations, or its documentation:

**Email:** `duranteg2@gmail.com`

Please include the following in your report:

- **Description:** A clear explanation of the issue.
- **Impact:** Which system property or structural invariant is affected.
- **Reproduction:** Steps to reproduce, if applicable.
- **Evidence:** Logs, screenshots, or traces (sanitized if necessary).
- **Suggested Fix:** Optional, but welcome.

Do **not** open a public issue for security vulnerabilities.

## 2. Coordinated Disclosure Policy

This project follows a coordinated disclosure model:

| Phase | Timeline | Action |
|:---|:---|:---|
| **Acknowledgment** | Within 7 days | We confirm receipt of your report. |
| **Assessment** | Within 30 days | We validate the issue and determine impact. |
| **Remediation** | Within 90 days | We develop and test a fix or structural remediation. |
| **Disclosure** | After agreement | We publish findings jointly, crediting the reporter. |

We will not take legal action against researchers who:

- Act in good faith.
- Follow this policy.
- Do not cause harm to users or data.

## 3. Scope

The following are **in scope**:

- The operational protocol specification (`en/`, `es/`, `protocol.md`).
- The forensic traceability mechanisms (SHA-256, OpenTimestamps integration).
- The case study and example invariants.
- The paper and its formal definitions.

The following are **out of scope**:

- Third-party dependencies (report to their maintainers).
- Systems audited using SAP (report to their respective owners).
- Theoretical disagreements with the methodology (use discussions instead).

## 4. Rules of Engagement

- **Non-destructive testing only.** Do not exploit vulnerabilities to access data, disrupt services, or degrade performance.
- **No brute force.** Do not use automated tools to overwhelm infrastructure.
- **No social engineering.** This policy covers technical vulnerabilities only.
- **Respect privacy.** Do not access, modify, or delete data belonging to others.
- **No public disclosure before agreement.** Wait for mutual agreement before publishing findings.

## 5. Recognition

We will publicly credit researchers who report valid security issues, unless they request anonymity.

---

# Español

## 1. Reportar un Problema de Seguridad

Si descubrís una vulnerabilidad de seguridad o un problema estructural dentro del Symbiotic Architecture Protocol (SAP), sus implementaciones, o su documentación:

**Email:** `duranteg2@gmail.com`

Por favor incluí lo siguiente en tu reporte:

- **Descripción:** Una explicación clara del problema.
- **Impacto:** Qué propiedad del sistema o invariante estructural se ve afectado.
- **Reproducción:** Pasos para reproducir, si aplica.
- **Evidencia:** Logs, capturas de pantalla, o trazas (sanitizadas si es necesario).
- **Sugerencia de corrección:** Opcional, pero bienvenida.

**No** abras un issue público para vulnerabilidades de seguridad.

## 2. Política de Divulgación Coordinada

Este proyecto sigue un modelo de divulgación coordinada:

| Fase | Plazo | Acción |
|:---|:---|:---|
| **Acuse de recibo** | Dentro de 7 días | Confirmamos la recepción de tu reporte. |
| **Evaluación** | Dentro de 30 días | Validamos el problema y determinamos el impacto. |
| **Remediación** | Dentro de 90 días | Desarrollamos y probamos una corrección o remediación estructural. |
| **Divulgación** | Después de acuerdo | Publicamos los hallazgos conjuntamente, acreditando al reportante. |

No tomaremos acciones legales contra investigadores que:

- Actúen de buena fe.
- Sigan esta política.
- No causen daño a usuarios o datos.

## 3. Alcance

Lo siguiente está **dentro del alcance**:

- La especificación operativa del protocolo (`en/`, `es/`, `protocol.md`).
- Los mecanismos de trazabilidad forense (integración SHA-256, OpenTimestamps).
- El caso de estudio y los invariantes de ejemplo.
- El paper y sus definiciones formales.

Lo siguiente está **fuera del alcance**:

- Dependencias de terceros (reportar a sus mantenedores).
- Sistemas auditados usando SAP (reportar a sus respectivos dueños).
- Desacuerdos teóricos con la metodología (usar discusiones en su lugar).

## 4. Reglas de Interacción

- **Solo pruebas no destructivas.** No explotar vulnerabilidades para acceder a datos, interrumpir servicios, o degradar el rendimiento.
- **Sin fuerza bruta.** No usar herramientas automatizadas para saturar la infraestructura.
- **Sin ingeniería social.** Esta política cubre solo vulnerabilidades técnicas.
- **Respetar la privacidad.** No acceder, modificar, o eliminar datos ajenos.
- **Sin divulgación pública antes de acuerdo.** Esperar el acuerdo mutuo antes de publicar hallazgos.

## 5. Reconocimiento

Acreditaremos públicamente a los investigadores que reporten problemas de seguridad válidos, a menos que soliciten el anonimato.

---

<div align="center">

**SAP — Symbiotic Architecture Protocol**

`Responsible · Coordinated · Traceable`

</div>
