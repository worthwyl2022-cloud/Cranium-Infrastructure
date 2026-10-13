# Convertible Cranium Architecture

## Dual-Substrate / Quad-Engine Architecture

Convertible Cranium is a governed-intelligence infrastructure architecture designed to separate cognition, assessment, independent governance review, and canonical authority while binding continuity, execution, recovery, and evidence to explicit governance boundaries.

### Current architecture baseline

The current canonical architecture is Dual-Substrate / Quad-Engine. The earlier Dual-Engine and Eight-Plane descriptions are historical framing and must not be used as the current governance model.

#### Four engines across two distinct governance substrates

1. **Engine 1, Convertible Cranium Synapse:** forms proposals, produces the D_A/D_B projections, binds evidence, and commits trace information.
2. **Engine 2A, Constitutional Authority substrate:** Jury A1+A2 evaluate “May We?” under the substrate's own constitution and policy.
3. **Engine 2B, Evidence Grounding substrate:** Jury B1+B2 evaluate “Is It So?” under a distinct constitution and policy.
4. **Engine 3, Cranium Kernel:** verifies convergence and lineage and is the sole authority boundary.

Cranium AI and other models can supply cognitive proposals. They are not the four engines and cannot grant authority. The two substrates remain distinct; neither substitutes for the Kernel.

#### Authority boundary

The Convertible Cranium Kernel is the sole canonical authority source. No engine, juror, UI, memory record, runtime state, receipt, external attestation, or consensus can create or substitute for Kernel authority.

#### Operational and safety surfaces

- Commander OS is the operational control surface.
- Cranium Listener is untrusted ingress and must not be treated as an authority source.
- Miracle Memory provides governed continuity, contradiction handling, quarantine, identity, journal, and recovery context.
- Circuit Breaker / COMA provides cross-cutting runtime containment, checkpoint rollback, fencing, and bounded recovery.
- Receipts / attestation provide evidence of governed transitions and provenance; they do not issue authority.

#### Governed path

Listener (untrusted ingress) → Engine 1: Synapse (proposal, D_A/D_B projections, evidence binding, trace commitment) → Engine 2A: Constitutional Authority (“May We?”) and Engine 2B: Evidence Grounding (“Is It So?”) → Engine 3: Cranium Kernel (convergence and lineage verification; sole authority boundary) → governed execution → receipts / lineage → Miracle Memory

Circuit Breaker / COMA may interrupt or roll back the runtime path according to its explicit safety contract. It does not become a second authority source.

#### Historical terminology

The former Eight-Plane model remains useful as a historical subsystem taxonomy. The former Dual-Engine model remains useful as an earlier conceptual distinction between cognition and authority. Neither is the current canonical architecture.

## Architecture thesis

Cognition may propose. Constitutional authority and evidence grounding evaluate distinct questions. Only Cranium Kernel can issue canonical authority.

The architecture is deliberately resistant to authority emergence through composition. A persuasive model output, favorable evidence, two agreeing jurors, a UI state, a memory record, an external attestation, or a runtime signal cannot become authority merely by being combined.

## Acquisition boundary

The canonical Kernel implementation remains separately maintained. The acquisition-facing repository documents the architecture and evidence boundary without implying transfer of all underlying platform IP, future improvements, private assets, or third-party rights.

See the authority flow, threat model, verification record, and IP/product boundary for detailed evidence and limitations.
