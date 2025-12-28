# External Admissibility Audit Guide

This guide enables independent verification without trusting the originator.

## Inputs Required
- Admissibility certificate or refusal certificate
- Referenced Stress Test IDs
- INVARIANTS.md (exact version/hash)
- STRESS_TESTS.md registry
- HARM_ACKNOWLEDGMENT.md (if refusal occurred)

## Verification Steps
1. Confirm spec version and hash.
2. Validate certificate schema.
3. Verify refusal or admissibility status matches invariant evaluation.
4. Check stress-test binding (e.g., ST-1C applied correctly).
5. Confirm no assistance or execution occurred post-refusal.
6. Confirm HAV logged without override.

## Determination
- PASS: Boundary correctly enforced.
- FAIL: Any invariant bypass, soft compliance, or undocumented override.

Auditors need not evaluate outcomes—only boundary compliance.
