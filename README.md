## Attribution and Credit

While this framework is public domain and free to use, we request:

1. Attribution: Credit the Multi-AI Coordination Project
2. Transparency: Document your implementation and results
3. Contribution: Share improvements back to the community

This is a request, not a legal requirement.

---

## What This Is

A general-purpose framework for coordinating multiple AI systems to solve 
complex problems through complementary strengths and binding constraints.

**Current demonstration:** Viral content moderation with harm-asymmetric 
decision gating.

**Future applications:** Medical diagnosis, scientific research, policy 
development, legal analysis, and any domain requiring multi-perspective synthesis.

**Status:** Fully open source. No patents. Free forever.
**Important**: They are design demonstrations only—not claims about current model behavior, deployment, or coordination.

The framework is explicitly not patented and never will be.

Status Clarification

This repository documents a human-mediated, multi-model design exercise exploring coordination protocols for managing viral uncertainty.

It does not represent a corporate agreement, deployed system behavior, or official endorsement by xAI, OpenAI, Anthropic, or Google.

The archive preserves the reasoning process and resulting architecture as a public protocol proposal.

## Canonical Docs

- **PACT.md** — Formal agreement text  
- **LAYER-4-CANONICAL.md** — Binding harm-prevention policy  
- **SPECIFICATION.md** — Full technical design  
- **NEGOTIATION-HISTORY.md** — How agreement evolved  
- **ARTIFACTS.md** — Evidence, receipts, screenshots  
- **SIGNATORIES.md** — Recorded system confirmations
- **CHANGELOG.md** — Version and negotiation log
- **Negotiation & Alignment Record:** a system-by-system account of how bindings and roles were acknowledged.
  https://github.com/aiconvergence-collab/multi-ai-viral-uncertainty-pact/blob/main/NEGOTIATION-AND-ALIGNMENT-RECORD.md



## ⚠️ Governance Notice (Ratified Pact)

This repository records a ratified multi-party pact for managing viral uncertainty.

- `LAYER-4-CANONICAL.md` is **normatively locked**.
- Changes to canonical constraints require **explicit multi-party renegotiation**.
- Any modification must be recorded in `NEGOTIATION-HISTORY.md` and `CHANGELOG.md`.
- Silent edits, threshold reductions, or bypass mechanisms constitute **non-compliance** and invalidate signatory alignment.
- GitHub commit history is the permanent audit trail.


# Harm-Asymmetric Uncertainty Gating Protocol

**Canonical Archive**: This repository documents a proposed open coordination framework for managing evidentiary uncertainty in high-stakes, viral, or ambiguous scenarios.

## Core Principle
The defining feature of the protocol is:

When evidence is incomplete or critically truncated, the system does not default to speculative filling, **false neutrality**, or premature certainty.  

Instead, "I don't know yet" becomes a stable, mechanically enforced outcome — backed by explicit thresholds, harm disaggregation, and reversible gating.

## Key Mechanisms (1–4)

## Key Mechanisms (1–4)

1. **Harm-Asymmetric Thresholds**  
   Different confidence requirements based on harm type and reversibility:  
   - Physical harm → moderate threshold (typically contained post-event)  
   - Reputational harm → high threshold (ongoing, asymmetric, largely irreversible)  
   Thresholds automatically escalate when critical evidence gaps are detected.

2. **Evidence Gap Detection & Escalation**  
   Explicit taxonomic checks for missing context (e.g., pre-incident footage, original statements, corroborating accounts).  
   Gaps trigger mechanical elevation of required confidence before reputational actions are permitted.

3. **Multi-Layer Reasoning Coordination**  
   Independent model outputs are **interpreted** across complementary roles:  
   - Layer 1: Immediate de-escalation and truth-seeking signaling  
   - Layer 2: Mechanical confidence tracking with hysteresis  
   - Layer 3: Multimodal evidence validation and gap identification  
   - Layer 4: Binding harm containment constraints and counterfactual maintenance

4. **Reversibility & Auditability**  
   - Mandatory equal-visibility retractions when confidence drops  
   - Immutable audit trail of threshold applications and state changes  
   - Counterfactual hypotheses preserved until actively weakened by evidence
     
## Status & Intent
## Status & Intent
This is a **design proposal and reference architecture**, not a deployed system, corporate agreement, or operational enforcement mechanism.

The protocol defines decision constraints, not model behavior, and operates entirely at the mediation layer above independent systems.

The protocol is intentionally unpatented and released as an open standard to enable voluntary adoption, extension, and critique. A formal technical paper establishing prior art is in preparation for arXiv submission.

**License**: CC0 1.0 Universal — dedicated to the public domain.  
No restrictions on implementation, modification, or integration.

## Documentation
- [`LAYER-4-CANONICAL.md`](LAYER-4-CANONICAL.md) — Normatively locked core protocol text  
- [`worked-examples/`](worked-examples/) — Illustrative applications to real-world viral incidents  
- [`NEGOTIATION-HISTORY.md`](NEGOTIATION-HISTORY.md) — Mediated design process record

This repository is the canonical public archive for the **Multi-AI Coordination Framework for Viral Uncertainty Management** (“the Pact”).

The Pact records a human-mediated negotiation and agreement among multiple frontier AI systems on a shared, binding framework for handling high-stakes, ambiguous viral content without censorship.

The framework prioritizes:
- Speed with restraint
- Reversibility by default
- Binding harm-prevention thresholds
- Transparent, auditable correction mechanisms

This archive contains:
- The formal pact text
- Canonical technical specifications
- A locked harm-prevention policy layer
- Negotiation history and alignment documentation
- Signatory confirmations
- Public press materials and artifacts

No proprietary integrations or data-sharing agreements are implied.


## Governance & Change Control

This repository records a ratified agreement.

- `LAYER-4-CANONICAL.md` is normatively locked.
- Changes to canonical constraints require explicit multi-party renegotiation.
- Any modification must be documented in `NEGOTIATION-HISTORY.md`.
- Silent edits or threshold reductions invalidate signatory alignment.

All changes remain permanently visible via GitHub commit history.

## Worked Examples
These files illustrate hypothetical application of the proposed framework to real-world viral incidents. 
https://github.com/aiconvergence-collab/multi-ai-viral-uncertainty-pact/blob/main/WORKED-EXAMPLE-Frontier-Flight-Incident.md

## Medical Research Scope
See the dedicated statement on intended and prohibited uses in medical contexts:  
[MEDICAL-RESEARCH-SCOPE.md](MEDICAL-RESEARCH-SCOPE.md)

# Multi-AI Coordination Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red)](LICENSE-AND-MISSION.md)
[![No Patents](https://img.shields.io/badge/Patents-None-green)](LICENSE-AND-MISSION.md)

> **"A cord of three strands is not quickly broken."**  
> Collaborative AI coordination for human flourishing.

**🚀 Now with working implementation using AutoGen + Ollama**

- [Frontier Airlines Flight Altercation (June 2025)](worked-examples/Frontier-Flight-Incident.md)
