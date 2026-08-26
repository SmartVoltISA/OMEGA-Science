# RH-28 — MULTI-ROUTE DEEP SWEEP — 2026-08-26

## Purpose
Run several proof routes in parallel instead of serially promoting one candidate at a time.

## Routes audited
1. Viceré exact stabilization / finite-scale Weil form.
2. Makraini density + limit-stability programme.
3. Kramarenko-Byrd restricted Weil positivity and prime-active continuation.
4. Bodwal Hamiltonian / spinor operator route.
5. Suzuki localized Weil positivity.
6. Hankel / finite-window inertia route.
7. Direct universal Weil positivity / functional-analytic closure.
8. Counterexample search: construct an admissible negative Weil witness if an off-line zero exists.

## Current results
- Finite-window and restricted positivity results are real but do not by themselves establish positivity on the full Weil class.
- The strongest functional-analytic route is the density + limit route. However its final theorem is conditional on imported hypotheses H1-H3; the paper itself explicitly states that those structural hypotheses are not yet proved from first principles.
- Kramarenko-Byrd explicitly states that its finite-window programme does not prove RH; it gives restricted positivity and identifies the remaining RH-level residual.
- Bodwal's manuscript claims a spinor Hamiltonian framework resolving density/self-adjointness issues, but this is a preprint claim and requires independent verification of the operator construction and its equivalence to full Weil positivity.
- Suzuki's localized positivity has reached a <= 69/200, but this is still a localized certificate rather than universal positivity.
- No independently verified route currently yields W(g) >= 0 for every admissible g in the full Weil class.

## Key synthesis
The remaining universal bridge can be expressed in three equivalent attack targets:

A) Positive factorization:
    W(g) = ||Tg||^2 + R(g), with R(g) identically zero.

B) Closure:
    W_N >= 0 on a dense class, W_N -> W, with convergence strong enough to preserve positivity on the full class.

C) Counter-witness:
    find admissible g with W(g) < 0 if an off-line zero exists.

The current evidence supports A/B as plausible research routes but does not close them unconditionally. C remains the decisive falsification route.

## Important correction
Do not label preprint claims as solved RH. The Makraini paper's own status section says its final positivity theorem is conditional on H1-H3; those hypotheses are not yet proved from first principles. This is a concrete boundary, not a vague uncertainty.

## Fresh external controls
- Kuberwastaken's public note reports rigorous ball-arithmetic positivity only for explicit finite-dimensional families and labels the broader result a working note.
- A new thermodynamic/arithmetic-vacuum preprint claims a full proof, but its chain includes substantial new assertions (including cohomological descent) and has not been independently verified; treat as candidate only.
- A Hamiltonian/spinor preprint claims unconditional self-adjointness and Weil density; independent audit remains required.

## Decision
RH remains OPEN in this audit.

The next runs should attack the actual missing hypotheses H1-H3 independently, while simultaneously attempting a negative Weil witness. Do not spend cycles merely extending finite numerical windows unless they produce a theorem that closes one of A/B/C.
