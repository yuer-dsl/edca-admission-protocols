# Alignment Protocol v3.0 — Lifecycle

## 1. Boot

Determines whether a protocol attempt is valid.

A system MUST be able to decide:
- Boot.Accepted
- Boot.Rejected
- Boot.NotApplicable

Implicit continuation is forbidden.

---

## 2. Instantiation

Transforms an accepted claim into a **decidable instance**.

Instantiation MUST produce:
- a unique instance identifier
- a declared scope
- a declared origin

Uninstantiated claims MUST NOT proceed.

---

## 3. Runtime

Only instantiated claims may enter runtime.

During runtime:
- no implicit context may be added
- claim scope MUST remain stable
- execution MUST be traceable to the instance

---

## 4. Failure Semantics

Failure is a valid terminal state.

Failures MUST:
- be explicit
- be classified
- not trigger fallback execution

Failure is not an error.
Failure is a decision.
