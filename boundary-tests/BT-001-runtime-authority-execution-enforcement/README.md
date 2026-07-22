# BT-001 — Runtime Authority and Execution Enforcement

**Status:** In Review  
**Classification:** Public research placeholder  
**Normative status:** Non-normative  
**Date opened:** July 2026

## Research Question

Can Runtime Authority and Execution Enforcement interoperate through a minimal, signed handover artefact while remaining independently responsible, independently governed and independently auditable?

## Architectural Responsibilities

### Runtime Authority

Determines whether delegated institutional authority remains legitimately exercisable for a specific proposed consequential action, at a specific moment, under current institutional conditions.

### Execution Enforcement

Consumes a valid Runtime Authority determination at the action boundary, enforces the result fail-closed and records what did or did not execute.

## Boundary Principle

> Runtime Authority does not enforce execution.  
> Execution Enforcement does not determine institutional authority.

## Current Scope

The initial paper exercise examines:

- a minimal signed handover artefact;
- binding to a canonical proposed action;
- ALLOW, ESCALATE and REFUSE outcomes;
- validity windows;
- issuer and audience binding;
- explicit verification keys;
- independent evidence chains;
- execution pre-records and post-records.

## Current Status

A draft paper exercise has been completed using representative artefacts.

No live systems have yet been connected.

No production keys, workloads or security claims are included.

The detailed note will be published only after authorship, attribution, intellectual-property treatment and public-release terms have been agreed by the contributors.

## Contributors

To be confirmed before publication.
