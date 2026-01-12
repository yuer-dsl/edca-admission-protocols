# Alignment Protocol v3.0 — Validation Checklist

This document defines the minimum conditions required to claim
**Alignment Protocol v3.0 compliance**.

Failure of any mandatory item invalidates compliance.

---

## Preconditions

- Existence of a decision aggregation point
- Ability to refuse claims without exception
- Minimal audit capability

---

## Boot Validation

- Protocol attempts are explicitly detected
- Non-start conditions are decidable
- Rejection is structured

---

## Instantiation Validation

- Claims are structured
- Instance IDs are generated
- Origins are declared

---

## Runtime Validation

- No uninstantiated claims proceed
- Execution is instance-bound
- Behavior is reproducible

---

## Failure Validation

- Failures are classified
- No silent fallback is allowed
- Failure does not equal error

---

## Compatibility Mode

Compatibility MUST be explicit.
Compatibility MUST NOT claim full compliance.
