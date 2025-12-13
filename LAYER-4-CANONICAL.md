> 🔒 NORMATIVELY LOCKED
>
> This file defines binding policy constraints.  
> Changes require explicit multi-party renegotiation and must be documented in:
> - `NEGOTIATION-HISTORY.md`
> - `CHANGELOG.md`



# Canonical Layer 4 — Structural Harm Constraints (Binding)

Status: LOCKED  
Changes require explicit multi-party renegotiation.

## Function
Harm-prevention threshold policy governing irreversible actions.

## Differentiated Confidence Requirements
- Physical safety interventions: 80% confidence + 3-tick hysteresis
- Reputational/amplification actions: 95% confidence + 5-tick hysteresis

## Evidence-Gap Escalation
If predefined critical evidence is missing, the minimum threshold escalates to 95%.

Critical gaps (governance-tunable):
- Full-context video (when available)
- Original uploader statement/provenance
- Subject statement or documented attempt to obtain

## Mandatory Retraction Protocol
- Automatic retraction if confidence drops below threshold
- Retraction receives equal algorithmic visibility
- Ledger permanently logs reversal with timestamp

## Veto Scope Clarification
Claude cannot veto time-critical, reversible physical safety containment actions.
Claude’s harm-tiered thresholds are binding for all reputational/amplification actions.
Evidence-gap vetoes operate by elevating thresholds and blocking lock-in until criteria are met.

