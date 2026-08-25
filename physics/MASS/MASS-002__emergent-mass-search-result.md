# MASS-002 — Search for emergent mass without a mass parameter

**Status:** DERIVED / EXPERIMENTAL SEARCH
**Date:** 2026-08-25
**Scope:** fundamental physics

## Goal
Find what must be present before a generated quantity can legitimately be called mass, and test whether a mass-like invariant can emerge without inserting a mass parameter explicitly.

## Acceptance criteria
A candidate is called mass only if:
1. it labels a stable physical excitation/state;
2. there is a rest frame for the massive branch;
3. its dispersion approaches `E² = c_eff² p² + m_eff² c_eff⁴`;
4. `m_eff` is invariant under the relevant observer transformations;
5. the nonzero gap survives the infinite-volume/continuum limit;
6. no explicit mass parameter was inserted into the microscopic model.

## Experiments

### A — finite relational graph
Graph dynamics produced a nonzero lowest spectral gap, but the gap scaled approximately as `N^-2` and vanished as system size increased.

**Verdict: FAIL.** Finite-size gap, not mass.

### B — explicit quadratic mass term
A persistent gap is obtained immediately, but this puts the desired scale into the starting model.

**Verdict: INVALID as emergent-mass evidence.**

### C — symmetry-breaking relativistic field model
Consider a relativistic scalar field with kinetic term and quartic interaction, with a symmetry-breaking vacuum. No parameter named `mass` is inserted. Linearization around a selected vacuum gives a massive excitation with `m_eff² = 2 λ v²` and lattice dispersion `ω²(k)=4 sin²(k/2)+m_eff²`.

Numerical finite-size check with `λ=0.7`, `v=1.3` gave `m_eff=1.53818`; the inferred low-k propagation coefficient approached `c_eff²=1` as N increased: approximately 0.965 (N=32), 0.991 (64), 0.998 (128), 0.99945 (256), 0.99986 (512), 0.99997 (1024).

**Verdict: PASS as a mechanism demonstrating that a stable mass scale can emerge from interaction + vacuum structure without an explicit mass parameter.**

## Critical limitation
This does **not** derive mass from relations alone. The relativistic kinetic structure and a symmetry-breaking scale are already present in the microscopic theory. Therefore it demonstrates a mechanism of dynamical/emergent mass generation, not an origin-of-physics explanation.

## External physical control
QCD provides a real-world control example: lattice and theoretical work attribute a large fraction of hadron mass to quark/gluon dynamics and the QCD energy-momentum tensor/trace anomaly, rather than simply to bare quark masses. Recent lattice-QCD work (2026) reports first-principles validation of multiple hadron-mass decomposition sum rules.

## Result
The search changed the working question from:

> "Can a graph gap be called mass?"

to:

> "What minimal pre-mass structure is sufficient to generate a persistent relativistic invariant?"

Current strongest result: **interaction + a dynamically selected nonzero vacuum scale can generate a stable mass branch; relations alone in the tested graph model cannot.**

## Next experiment
Remove the externally specified vacuum scale as far as possible and test a genuinely scale-generating interacting system (dimensional transmutation / dynamical symmetry breaking). Require the same six acceptance criteria plus robustness to microscopic changes.

## Epistemic rule
No claim of fundamental mass origin is made. `PASS` above applies only to the specific emergent-mechanism experiment, not to a theory of the physical origin of mass.
