# Alignment Protocol v3.0 — Specification

## Purpose

Alignment Protocol v3.0 defines **how human claims are legally admitted into EDCA OS**.

The protocol governs *entry*, not reasoning.

A claim that fails this protocol **must not** enter any AI-controlled decision path.

---

## Design Principles

1. **Admission precedes intelligence**
2. **Rejection is a first-class outcome**
3. **Failure is a semantic result, not an exception**
4. **All admitted claims must be instantiable and auditable**
5. **No implicit context is allowed**

---

## Claim Definition

A *claim* is any expression that seeks to:

- trigger reasoning,
- influence a decision,
- or enter an AI-controlled execution path.

Claims may originate from humans or from translated / mediated systems.

---

## Protocol Stages

Alignment Protocol v3.0 consists of four mandatory stages:

1. Boot
2. Instantiation
3. Runtime
4. Failure Semantics

Each stage is independently decidable and explicitly terminable.

---

## Normative Requirement

> If a system cannot clearly explain  
> **why a claim was rejected**,  
> it must not accept that claim.
