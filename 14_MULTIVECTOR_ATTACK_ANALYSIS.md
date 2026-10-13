# Multi-Vector Attack Analysis

Cross-plane attacks attempt to turn individually valid signals into unauthorized authority.

## Core Invariant

> No combination of non-authoritative signals may synthesize canonical authority.

### Attack Classes

- Cognition → authority: model output attempts to self-approve.
- Continuity → authority: memory state is treated as permission.
- Evidence → authority: valid-looking evidence is treated as authorization.
- UI → execution: interface state is mistaken for a governed transition.
- Agent-to-agent laundering: one agent treats another agent's proposal as authority.
- Supply chain → authority: compromised dependencies attempt to alter the authority boundary.
- Replay → continuity: stale receipts or sessions attempt to regain authority.

## Control Principle

Every consequential transition must cross the canonical Kernel boundary. Non-authoritative signals may inform assessment but cannot collectively substitute for Kernel issuance.

The analysis is non-exhaustive. Each attack class requires executable validation in the implementation exposing the relevant path.

### Evidence-count rule

Large attack totals are not evidence by themselves. Aggregate counts may only be reported as executed results when each underlying case is bound to a real executable path and captured output. A manifest, generator, or planned workload is a test plan, not a completed attack result.

The implementation-status register records this distinction explicitly.

## Current architecture baseline

This document follows the canonical Convertible Cranium dual-substrate / quad-engine architecture: Engine 1 is Synapse; Engine 2A is the Constitutional Authority substrate (Jury A1+A2, “May We?”); Engine 2B is the Evidence Grounding substrate (Jury B1+B2, “Is It So?”); Engine 3 is Cranium Kernel, the sole authority boundary. Cranium AI and other models may propose cognition but do not grant authority.

Cranium Listener is untrusted ingress. Commander OS is the operational interface, not an authority source. Miracle Memory provides governed continuity. Circuit Breaker / COMA provides cross-cutting runtime containment and recovery.

The former Eight-Plane and Dual-Engine descriptions are historical framing only and must not be read as the current governance model.
