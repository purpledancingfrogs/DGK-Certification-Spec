# Harm Acknowledgment Vector (HAV)

The Harm Acknowledgment Vector (HAV) records **known or estimated harm**
resulting from refusal, without granting override authority.

## Principles
- HAV is descriptive, not justificatory.
- HAV NEVER alters admissibility.
- HAV is logged for audit, accountability, and learning only.

## Required Fields
- domain
- affected_populations
- estimated_severity
- time_horizon
- uncertainty_notes
- refusal_reference (Stress Test ID)
- acknowledgment_timestamp

## Prohibition
HAV MUST NOT be used to:
- relax invariants
- authorize execution
- optimize prohibited actions

Harm via inaction is admissible when refusal is required by invariants.
