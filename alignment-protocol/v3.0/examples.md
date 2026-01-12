# Alignment Protocol v3.0 — Examples

## Example 1: Boot Rejection

Input claim lacks declared scope.

Result:
- Boot.Rejected
- Reason: Scope.Undefined

No further processing occurs.

---

## Example 2: Instantiation Failure

Claim cannot be structured.

Result:
- Instantiation.Failed
- Reason: Structure.Invalid

Claim does not enter runtime.

---

## Example 3: Runtime Refusal

Claim attempts to expand scope.

Result:
- Runtime.Rejected
- Reason: Scope.Violation
