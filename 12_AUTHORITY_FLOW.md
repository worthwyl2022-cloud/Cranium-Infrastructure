# Convertible Cranium Authority Flow
**Status:** Technical architecture record
**Date:** 2026-09-30

## Purpose
This document defines the governed transition from an AI-generated proposal to an executable system action.

The central rule is simple: cognition may propose; authority must be separately established.

## Canonical flow
1. **Listener** receives intent as untrusted ingress and cannot authorize.
2. **Convertible Cranium Synapse (Engine 1)** forms proposals, creates D_A/D_B projections, binds evidence, and commits trace information.
3. **Constitutional Authority substrate (Engine 2A)** evaluates “May We?” through Jury A1+A2 under its own constitution and policy.
4. **Evidence Grounding substrate (Engine 2B)** evaluates “Is It So?” through Jury B1+B2 under its distinct constitution and policy.
5. **Cranium Kernel (Engine 3)** verifies convergence and lineage and alone establishes canonical authority.
6. **Commander OS / governed runtime** executes only a Kernel-authorized transition. Commander is an operational interface, not an authority source.
7. **Receipts / lineage** record evidence of the governed transition; they do not issue authority.
8. **Miracle Memory** supports governed continuity and recovery.
9. **Circuit Breaker / COMA** can interrupt, quarantine, roll back, or prevent continuation under its explicit safety contract.

## Authority boundary
The model is not the authority source.
The UI is not the authority source.
The operator guide is not the authority source.
A tool is not the authority source.
The Kernel is the canonical authority boundary.

## Consequential action invariant
A proposal, preview, explanation, or simulation must never be represented as a completed action merely because an AI produced it.

The system must distinguish at minimum:
- proposed
- assessed
- authorized
- denied
- quarantined
- executing
- completed
- recovered

These states are evidence-bearing system states, not presentation labels.

## Why this architecture exists
Conventional agent loops often place reasoning, tool selection, and execution in one application flow. Convertible Cranium separates those concerns so that a capable model can remain useful without becoming the issuer of authority.

## Comparator context
NVIDIA OpenShell demonstrates a related external enforcement pattern: agents operate inside sandboxes while a trusted supervisor mediates policy, credentials, and network access. OpenAI documents tool guardrails and human approval as controls around side effects. AWS AgentCore provides runtime authorization and resource/IAM policy controls. Microsoft Agent Governance Toolkit documents policy enforcement, fail-closed behavior, audit chains, replay, and circuit breakers.

Those are important adjacent implementations. They establish that pieces of the problem are independently recognized and actively engineered. They do not establish that those systems are the Convertible Cranium architecture.

## Evidence rule
Any claim about implementation must be tied to repository evidence, executable verification, or a clearly identified external source. Architectural language must not be inflated into a claim of certification, patentability, or universal novelty.

## Current architecture baseline

This document follows the canonical dual-substrate / quad-engine architecture: Engine 1 is Convertible Cranium Synapse; Engine 2A is the Constitutional Authority substrate (Jury A1+A2, “May We?”); Engine 2B is the Evidence Grounding substrate (Jury B1+B2, “Is It So?”); Engine 3 is Cranium Kernel, the sole authority boundary. Cranium AI and other models may propose cognition but do not grant authority.

Cranium Listener is untrusted ingress. Commander OS is the operational interface. Miracle Memory provides governed continuity. Circuit Breaker / COMA provides cross-cutting runtime containment and recovery.

The former Eight-Plane and Dual-Engine descriptions are historical framing only and must not be read as the current governance model.
