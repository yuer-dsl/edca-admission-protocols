# edca-admission-protocols
Admission-layer protocol specifications for EDCA OS. Defines how human claims are started, instantiated, accepted, rejected, or failed before entering any AI-controlled system.

# EDCA Admission Protocols

This repository defines **admission-layer protocol specifications** for EDCA OS.

Admission protocols govern **whether, how, and under what conditions a claim is allowed to enter an AI-controlled system**.  
They operate *before* any reasoning, decision, or execution occurs.

This repository contains **normative specifications only**.  
It is **not an implementation**, **not a runtime**, and **not a product**.

---

## What is an Admission Protocol?

An admission protocol defines:

- how a claim is **started** (boot),
- how it becomes a **decidable instance** (instantiation),
- under what conditions it may **proceed** (runtime),
- and how it may **fail or be rejected** (failure semantics).

If a claim cannot be rejected in a well-defined way,  
it cannot be safely accepted.

---

## Scope

Admission protocols apply to:

- human-originated claims,
- translated or mediated claims,
- and any expression that seeks entry into an AI-controlled decision path.

They do **not** define reasoning logic, model behavior, or execution outcomes.

---

## Protocols

### Alignment Protocol

- **v3.0** — defines how human claims are legally admitted into EDCA OS  
  (boot, instantiation, runtime constraints, failure semantics)

Historical versions are preserved for reference only.

---

## Relationship to EDCA OS

EDCA OS is a controllable AI operating architecture.

Admission protocols are **external entry contracts** to EDCA OS.  
They define *who may enter*, *under what conditions*, and *when entry must be refused*.

EDCA OS depends on admission protocols.  
Admission protocols do **not** depend on EDCA OS internals.

---

## Status

This repository is under active specification.

No backward compatibility is implied unless explicitly stated.

---

## License

To be defined.
