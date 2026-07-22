<p align="center">
  <img src="asset/flowsignal-icon.svg" alt="FlowSignal" width="110">
</p>

<h1 align="center">FlowSignal Runtime Authority Lab</h1>

<p align="center">
  <strong>Public research, architectural boundary testing and experimental interoperability studies for Runtime Authority.</strong>
</p>

---

## Purpose

The **FlowSignal Runtime Authority Lab** is a public research repository for exploring how Independent Runtime Authority interacts with adjacent enterprise architectural responsibilities.

The lab is intentionally experimental.

It provides a place to document:

- architectural boundary tests;
- implementation-independent interface experiments;
- interoperability studies;
- evidence and execution patterns;
- candidate enhancements;
- open technical questions.

The work published here is intended to test, challenge and refine Runtime Authority through practical architectural investigation.

---

## Relationship to FEAL

The **FlowSignal Enterprise Architecture Library (FEAL)** defines the stable reference architecture for Independent Runtime Authority.

This repository does not replace or modify FEAL.

| Repository | Purpose |
|------------|---------|
| **FEAL** | Canonical architecture, public publications and platform reference architectures |
| **Runtime Authority Lab** | Experimental boundary tests, research notes and implementation studies |

Material published within this lab is **non-normative** unless it is subsequently incorporated into a formal FEAL publication or technical specification.

---

## Research Principles

The lab is guided by the following principles:

- Architectural responsibilities should remain explicit.
- Experiments should preserve implementation independence.
- Product integration should not be confused with architectural interoperability.
- Evidence, Runtime Authority, Execution Enforcement and governance should remain separately identifiable.
- Experimental findings should state their assumptions and limitations.
- A single successful implementation should not be presented as an industry standard.

---

## Repository Structure

```text
boundary-tests/
    Experimental studies examining the seam between Runtime Authority
    and adjacent architectural responsibilities

contracts/
    Experimental handover artefacts and interface proposals

research-notes/
    Non-normative technical and architectural research

candidate-enhancements/
    Potential refinements for future FEAL consideration

assets/
    Diagrams, figures and supporting visual material
```

---

## Boundary-Test Status Model

Each boundary test should use one of the following statuses:

| Status | Meaning |
|--------|---------|
| **Proposed** | Initial research question identified |
| **In Review** | Architecture or artefacts under peer review |
| **Paper Tested** | Contract or boundary tested through representative artefacts |
| **Implementation Tested** | Live systems have exchanged and enforced the contract |
| **Closed** | Test concluded with findings recorded |
| **Superseded** | Replaced by a later test or contract version |

---

## Current Research

| ID | Boundary Test | Status |
|----|---------------|--------|
| **BT-001** | Runtime Authority and Execution Enforcement | In Review |

Additional studies will be added as the research programme develops.

---

## Non-Normative Status

Unless explicitly stated otherwise, all material in this repository is:

- experimental;
- non-normative;
- subject to revision;
- not a completed standard;
- not production implementation guidance;
- not evidence of security certification or conformance.

The purpose of the lab is to expose architectural assumptions and test boundaries before any proposal is promoted into a formal specification.

---

## Contributions and Attribution

External contributions, peer reviews and jointly developed technical notes will preserve clear authorship, attribution and pre-existing intellectual property.

No jointly developed artefact will be published without the agreement of the named contributors.

---

## Main Architecture Library

The canonical FlowSignal Enterprise Architecture Library is available here:

**[FlowSignal Enterprise Architecture Library](https://github.com/grahamb-ai/flowsignal-enterprise-architecture)**

---

## About FlowSignal

FlowSignal develops Independent Runtime Authority as an enterprise architectural capability for autonomous and AI-enabled systems.

**Website:** https://flowsignal.ai

---

## License

Repository licensing does not override contributor-specific authorship, third-party rights, confidentiality obligations or separately identified intellectual property.

---

**Experimental research repository — July 2026**

**Execute with Authority. Defend with Evidence.**
