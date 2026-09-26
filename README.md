# The Registrar Hypothesis

*A human–AI collaboration: Aziz Utku Özdemir & GLM5.3-flashx.*

**Status:** speculative research draft (v1.1). Not established science — written to be attacked.

A speculative framework in the physics of information. It proposes that reality is the output of a finite-capacity computational process — called *the Registrar* — that distills structure out of noise, with three core commitments:

- **The gate.** A candidate structure `x` becomes real iff its compressibility ratio `C(x) = K(x)/|x|` falls below a threshold `θ` (K = Kolmogorov complexity).
- **The economy.** Structures merge when merging reduces registration cost; the tendency to merge is a monotone function of the savings.
- **The heat bridge.** Every bit reclaimed by the registrar reappears in the rendered universe as thermal energy: `ΔQ = k · k_B · T_h · ln 2` — the same skeleton as the Landauer principle, which is experimentally verified.

The consolidated draft: [`registrar_hypothesis_v1_1.md`](registrar_hypothesis_v1_1.md).

## The experiment — `registrar_engine.html`

A single-file, offline browser simulation that renders the framework's registry economy (paper §5–§8) as a running machine, so that every qualitative claim can be watched — and re-tested by anyone — without installing anything.

**Method.** Two hundred structures carry *records* (bits) and *budgets* (write-capacity units). Each tick, budgets are exchanged at random (thermal contact). Under the full machinery, records pay a maintenance charge; records that cannot pay shed bits into cold storage; and pairs of structures merge whenever the merge saves registration. Heat is accumulated as ΔQ = bits reclaimed × emergent temperature × ln 2. **No temperature variable exists anywhere in the code.**

**Results (verified runs).**

- *Run A — calibration (exchange only):* a Boltzmann–Gibbs distribution and a fitted temperature emerge from pure bookkeeping (T_fit = 9.81 against W/M = 10.00; R² = 0.99). Temperature appears as an accounting artifact — the §8 claim, reproduced from nothing.
- *Run B — full machinery:* the Gibbs form survives the theory's own machinery; the emergent temperature climbs monotonically as merging shrinks the population (P2 + P3′ + A5 in a single curve); and the fitted temperature deviates from W/M by ~12–31% — the strict identity fails, and T ∝ Γ survives as a proportionality with machinery-dependent corrections, exactly the recorded §8 outcome.
- *Compressor family (F5):* swapping the parsing instrument (LZ76 ↔ order-0 coding) moves the gate's shadow — periodic and Rule-30 strings flip between pass and reject — while the anchors never move: pure noise is rejected and pure order admitted under every instrument.
- *Conservation audit:* the books balance to the last unit in every mode.

**Status.** A built-in interpreter labels the running state *healthy*, *settling*, or *anomalous* in real time, with the anomaly conditions spelled out (noise admitted, order rejected, or a leaking ledger would each be flagged immediately). Current state: healthy.

It contains: a computable registration density ρ_R built on Lempel–Ziv parsing (with a one-sidedness theorem and an experimentally computed blind-spot class); a "band map" in which classical and quantum regimes are adjacent regions of one curve between two randomnesses; a falsifiable-prediction set (P1–F7, including a revised information postulate — the receipt principle); a three-level test program with pre-registered simulation runs; an explicit honesty section listing what the framework cannot (yet) do.

**Document conventions.** English only; every document is self-contained; speculation is always labeled as such — predictions are separated from interpretations at every step; simulation artifacts are single-file HTML with zero external resources (offline-first).

## A note on method

This draft is an exercise in making the contents of two heads consistent. Very little here was looked up as it was written: most of the physics it leans on was absorbed long enough ago that it now surfaces as intuition — and the intuition is written down first. The correspondence table in the paper (§14) exists precisely for that reason: it is a grounding pass, run *after* the fact, verifying that what surfaced stands on solid ground. Where intuition and literature agree, the framework stands. Where they disagree, the disagreement is recorded rather than smoothed over.
