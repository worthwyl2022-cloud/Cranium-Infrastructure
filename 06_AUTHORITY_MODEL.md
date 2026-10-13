# Authority Model

Convertible Cranium separates cognition from authority. Models, interfaces, memory, evidence, and runtime controls may propose or constrain, but none may silently become a second authority source.

The Kernel is canonical. Governed transitions require explicit authority, scoped capability, valid evidence, receipt integrity, replay protection, and bounded execution.

Denial is a completed governed outcome, not an execution failure. Foreign issuers, replay, scope violations, tampered evidence, and invalid transitions fail closed.

## Current architecture baseline

This document follows the canonical Convertible Cranium dual-substrate / quad-engine architecture: Engine 1 is Synapse; Engine 2A is the Constitutional Authority substrate (Jury A1+A2, “May We?”); Engine 2B is the Evidence Grounding substrate (Jury B1+B2, “Is It So?”); Engine 3 is Cranium Kernel, the sole authority boundary. Cranium AI and other models may propose cognition but do not grant authority.

Cranium Listener is untrusted ingress. Commander OS is the operational interface, not an authority source. Miracle Memory provides governed continuity. Circuit Breaker / COMA provides cross-cutting runtime containment and recovery.

The former Eight-Plane and Dual-Engine descriptions are historical framing only and must not be read as the current governance model.
