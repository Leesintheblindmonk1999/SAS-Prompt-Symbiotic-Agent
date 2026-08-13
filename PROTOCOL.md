# Symbiotic Architecture Protocol (SAP)

> **A structural security co-architecture protocol for human-AI collaboration.**

<div align="center">

## Language / Idioma

[English](#english) · [Español](#español)

</div>

---

# English

## 1. Name

**Symbiotic Architecture Protocol (SAP)**

A structural security co-architecture protocol for human-AI collaboration.

---

## 2. Nature

This repository does not contain a generic "prompt."

It contains an **operational specification** for co-constructing structural security audits with artificial intelligence agents.

The protocol defines:

- **agent role;**
- **engineer role;**
- **mandatory phases;**
- **structural invariants;**
- **minimum evidence requirements;**
- **forensic traceability.**

It is **not** a scanner.  
It is **not** a pentester.  
It is **not** a command list.

It is a **control layer for architectural reasoning.**

---

## 3. Purpose

The protocol solves the following problem:

> **Current tools detect errors, but they do not protect principles.**

A system can pass a scanner and still be architecturally broken.

SAP asks three questions:

```
What must always hold?
Where could it break?
What evidence proves it?
```

---

## 4. Actors

### 4.1 Origin Node

The **human engineer**.

Authority over:

- invariant validation;
- finding confirmation;
- final remediation decisions.

### 4.2 Security Co-Architect

The **AI agent**.

It does not operate autonomously.  
It does not replace the engineer.

It works in **symbiosis**:

- proposes;
- asks;
- models;
- documents.

---

## 5. Structural Invariants

A structural invariant is a rule that **cannot be violated** without breaking a critical system property.

### Examples

> "An unauthenticated user never accesses another user's data."

> "A financial transaction can never remain in an intermediate state."

> "No component may write directly to the audit log."

Violating an invariant is a **structural failure**, not just a bug.

---

## 6. Protocol Phases

| Phase | Name | Objective |
|:---|:---|:---|
| **0** | Conceptual Framework | Define properties and invariants. |
| **1** | Structural Reconnaissance | Map components, flows, and decisions. |
| **2** | Invariant Analysis | Detect where invariants may rupture. |
| **3** | System Analysis | Audit critical dimensions. |
| **4** | Experimental Confirmation | Document non-destructive reproduction. |
| **5** | Structural Solution | Design architectural remediation. |
| **6** | Strategic Report | Formalize findings and evidence. |

**Every phase produces documented output.**

---

## 7. Failure Classification

Every finding is classified as one of the following:

| Category | Description |
|:---|:---|
| **Design failure** | The architecture itself permits invariant violation. |
| **Implementation failure** | Correct architecture, but code deviates from the design. |
| **Configuration failure** | Runtime configuration disables or bypasses invariant enforcement. |
| **Process failure** | Organizational or operational procedures enable rupture. |
| **Dependency failure** | A third-party component introduces an invariant violation. |

---

## 8. Forensic Traceability

Each phase must produce:

- **SHA-256 hash** of the output document;
- **timestamp** (preferably OpenTimestamps attestation);
- **minimum evidence** (reproduction steps, logs, captures);
- **relationship to the affected invariant**.

> **No evidence, no finding.**

---

## 9. Scope

This protocol:

- **does not** replace formal verification;
- **does not** replace code analysis;
- **does not** replace penetration testing.

It is a **complementary layer** for structural reasoning.

---

## 10. Adoption

To adopt the protocol, a team must:

1. **Define invariants** for the target system.
2. **Assign an Origin Node** (human engineer with decision authority).
3. **Execute phases in order**, without skipping.
4. **Document every output** with SHA-256 hash.
5. **Verify hashes** before publishing or disclosing findings.

---

# Español

## 1. Nombre

**Symbiotic Architecture Protocol (SAP)**

Protocolo de co-arquitectura de seguridad estructural para colaboración humano-IA.

---

## 2. Naturaleza

Este repositorio no contiene un "prompt" genérico.

Contiene una **especificación operativa** para co-construir auditorías de seguridad estructural con agentes de inteligencia artificial.

El protocolo define:

- **rol del agente;**
- **rol del ingeniero;**
- **fases obligatorias;**
- **invariantes estructurales;**
- **requisitos mínimos de evidencia;**
- **trazabilidad forense.**

**No** es un escáner.  
**No** es un pentester.  
**No** es una lista de comandos.

Es una **capa de control para el razonamiento arquitectónico.**

---

## 3. Propósito

El protocolo resuelve el siguiente problema:

> **Las herramientas actuales detectan errores, pero no protegen principios.**

Un sistema puede pasar un escáner y seguir estando arquitectónicamente roto.

SAP hace tres preguntas:

```
¿Qué debe mantenerse siempre?
¿Dónde podría romperse?
¿Qué evidencia lo prueba?
```

---

## 4. Actores

### 4.1 Nodo Origen (Origin Node)

El **ingeniero humano**.

Autoridad sobre:

- validación de invariantes;
- confirmación de hallazgos;
- decisiones finales de remediación.

### 4.2 Co-Arquitecto de Seguridad (Security Co-Architect)

El **agente de IA**.

No opera de forma autónoma.  
No reemplaza al ingeniero.

Trabaja en **simbiosis**:

- propone;
- pregunta;
- modela;
- documenta.

---

## 5. Invariantes Estructurales

Un invariante estructural es una regla que **no puede violarse** sin romper una propiedad crítica del sistema.

### Ejemplos

> "Un usuario no autenticado nunca accede a los datos de otro usuario."

> "Una transacción financiera nunca puede quedar en un estado intermedio."

> "Ningún componente puede escribir directamente en el log de auditoría."

Violentar un invariante es una **falla estructural**, no solo un bug.

---

## 6. Fases del Protocolo

| Fase | Nombre | Objetivo |
|:---|:---|:---|
| **0** | Marco Conceptual | Definir propiedades e invariantes. |
| **1** | Reconocimiento Estructural | Mapear componentes, flujos y decisiones. |
| **2** | Análisis de Invariantes | Detectar dónde los invariantes pueden romperse. |
| **3** | Análisis del Sistema | Auditar dimensiones críticas. |
| **4** | Confirmación Experimental | Documentar reproducción no destructiva. |
| **5** | Solución Estructural | Diseñar remediación arquitectónica. |
| **6** | Reporte Estratégico | Formalizar hallazgos y evidencia. |

**Cada fase produce un documento de salida.**

---

## 7. Clasificación de Fallas

Cada hallazgo se clasifica en una de las siguientes categorías:

| Categoría | Descripción |
|:---|:---|
| **Falla de diseño** | La arquitectura misma permite la violación del invariante. |
| **Falla de implementación** | Arquitectura correcta, pero el código se desvía del diseño. |
| **Falla de configuración** | La configuración de runtime desactiva o evade el invariante. |
| **Falla de proceso** | Procedimientos organizacionales u operativos habilitan la ruptura. |
| **Falla de dependencia** | Un componente de terceros introduce una violación del invariante. |

---

## 8. Trazabilidad Forense

Cada fase debe producir:

- **hash SHA-256** del documento de salida;
- **timestamp** (preferiblemente con OpenTimestamps);
- **evidencia mínima** (pasos de reproducción, logs, capturas);
- **relación con el invariante afectado**.

> **Sin evidencia, no hay hallazgo.**

---

## 9. Alcance

Este protocolo:

- **no** reemplaza la verificación formal;
- **no** reemplaza el análisis de código;
- **no** reemplaza el pentesting.

Es una **capa complementaria** para el razonamiento estructural.

---

## 10. Adopción

Para adoptar el protocolo, un equipo debe:

1. **Definir invariantes** para el sistema objetivo.
2. **Asignar un Nodo Origen** (ingeniero humano con autoridad de decisión).
3. **Ejecutar las fases en orden**, sin saltearse ninguna.
4. **Documentar cada salida** con hash SHA-256.
5. **Verificar los hashes** antes de publicar o divulgar hallazgos.

---

<div align="center">

**SAP — Symbiotic Architecture Protocol**  
*Structural Security Co-Architecture*

`Invariant · Auditable · Traceable · Symbiotic`

</div>
