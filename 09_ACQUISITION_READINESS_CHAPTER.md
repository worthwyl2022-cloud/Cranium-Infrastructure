## Acquisition Readiness Summary
Convertible Cranium is ready for external diligence review at the binder and governance-substrate level, with one material implementation boundary still open: actual ChromiumOS x86-64 build, boot, runtime validation, and verified-boot evidence.
The acquisition record distinguishes:
- **PASS:** supported by the identified documented/executable evidence.
- **PENDING:** the gate exists but required evidence has not yet been produced.
- **NOT CLAIMED:** a stronger assurance level is outside the evidence established here.
The ChromiumOS pending gate must remain visible until an actual image is built and runtime-validated. Documentation cannot substitute for boot evidence. Humanity has spent decades learning this and then repeatedly pretending otherwise.
## Acceptance Rule
External reviewers may treat this binder as a structured diligence corpus. Material claims should be independently validated against source repositories, revisions, artifacts, executable tests, and runtime behavior before transaction or technical-assurance reliance.

## Current architecture baseline

This document follows the canonical Convertible Cranium dual-substrate / quad-engine architecture: Engine 1 is Synapse; Engine 2A is the Constitutional Authority substrate (Jury A1+A2, “May We?”); Engine 2B is the Evidence Grounding substrate (Jury B1+B2, “Is It So?”); Engine 3 is Cranium Kernel, the sole authority boundary. Cranium AI and other models may propose cognition but do not grant authority.

Cranium Listener is untrusted ingress. Commander OS is the operational interface, not an authority source. Miracle Memory provides governed continuity. Circuit Breaker / COMA provides cross-cutting runtime containment and recovery.

The former Eight-Plane and Dual-Engine descriptions are historical framing only and must not be read as the current governance model.
