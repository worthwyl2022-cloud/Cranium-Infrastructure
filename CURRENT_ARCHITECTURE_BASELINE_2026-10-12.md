# Convertible Cranium: Canonical Architecture Baseline

**Baseline date:** 2026-10-12  
**Status:** Current architecture reference; implementation status remains governed by the individual verification records and gap register.

## Product and authority boundary

**Convertible Cranium** is the umbrella system. Cognition may come from any permitted model or component; authority is not inherited from model output, UI state, memory, consensus, receipt, or attestation. **Cranium Kernel is the sole authority boundary.**

> Cognition may come from anywhere. Authority comes only through Cranium.

## Canonical governed path

1. **Listener:** untrusted ingress. Input is not authority.
2. **Engine 1, Convertible Cranium Synapse:** forms proposals, produces D_A/D_B projections, binds evidence, and commits trace information.
3. **Engine 2A, Constitutional Authority substrate:** Jury A1+A2 evaluate **“May We?”** under their substrate constitution and policy.
4. **Engine 2B, Evidence Grounding substrate:** Jury B1+B2 evaluate **“Is It So?”** under a distinct constitution and policy.
5. **Engine 3, Cranium Kernel:** verifies convergence and lineage. It alone determines whether a proposed transition acquires canonical authority.
6. **Governed execution:** proceeds only after Kernel authorization and emits receipts / lineage evidence.

The two substrates have separate mandates and policies. They are not a voting system, and neither substrate independently issues canonical authority.

## Component boundaries

- **Cranium AI and external models:** cognition and proposals, never authority issuers.
- **Cranium Commander OS:** operational interface for presenting state and initiating governed workflows; not an authority source.
- **Miracle Metacognitive Mapper:** perspective-mapping component; it is not a prefix or alternate name for Convertible Cranium.
- **Miracle Memory:** governed continuity and recovery context.
- **Circuit Breaker / COMA:** cross-cutting containment, interruption, and recovery under its safety contract.
- **Receipts and lineage:** evidence of governed transitions, not sources of authority.

## Evidence discipline

This architecture description defines the intended canonical flow. It does **not** claim every stage is shipped, independently audited, security-certified, patentable, or production-validated. Those claims require separate reproducible implementation evidence. Chromium Edition native x86-64 build, boot, runtime acceptance, and verified-boot gates remain pending until their evidence records say otherwise.

## Historical documents

`CURRENT_ARCHITECTURE_BASELINE_2026-10-02.md` and documents that describe Cranium AI, Synapse, Juror One, and Juror Two as the four engines are historical architecture framing. They must not override this baseline. Their repeated current-baseline notices have been aligned where practical; substantive historical descriptions should be read in context and updated when next edited.
