# MASS-005 — RG scale invariance check

Date: 2026-08-26
Status: PASS for RG-invariant generated scale; FUNDAMENTAL origin remains UNKNOWN.

## Question
Can a dynamically generated scale remain invariant when the arbitrary renormalization reference scale is changed?

## Minimal test
Use the one-loop beta function:

β(g) = -b g^3,  b=1.

Starting from μ0=1 and g(μ0)=0.7, the RG solution is

1/g(μ)^2 = 1/g(μ0)^2 + 2 b ln(μ/μ0).

Define

Λ = μ exp[-1/(2 b g(μ)^2)].

The test evaluates Λ over μ = 0.01 ... 100.

## Result
Λ = 0.3604477886 for every tested μ to numerical precision.

The value is therefore independent of the arbitrary reference scale μ within this model.

## Interpretation
The generated scale is an RG invariant. This confirms an important part of the dimensional-transmutation mechanism: a dimensionless coupling plus RG flow can define a physical dimensionful scale inside a specified theory.

## Attack / limitation
This does NOT explain the absolute value of the scale from nothing. The model still assumes:
- a specific RG beta function;
- a specified theory and coupling;
- a reference condition g(μ0).

Therefore this experiment does not establish the origin of the RG structure, the initial coupling, spacetime, or the observed physical mass scale.

## Relation to previous chain
MASS-003: classical dimensionless relational model did not generate an intrinsic absolute scale.
MASS-004: dimensional transmutation generated a stable scale under RG flow.
MASS-005: independently checked that the generated scale is invariant under change of arbitrary renormalization reference scale.

## Next question
Can the RG flow/beta function itself emerge from a more primitive relational system, rather than being postulated as part of the theory?

Historical results are retained. This record is additive and does not replace earlier MASS records.
