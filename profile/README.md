# GarAI Labs

<p align="center">
  <img src="profile/img/gar-banner.png" alt="GarAI Labs Banner" width="800px">
</p>

**An evidence-gated machine-learning research lab for market microstructure.**

We design and validate prediction systems whose epistemics are load-bearing: capacity earned by prequential compression, emission earned by sequential evidence, edge earned against placebos, and every constant earned by theorem or citation. 

---

### Core Philosophy

Most quantitative models fail because of unearned capacity (overfitting complex models) or unearned confidence (predicting through regime shifts). We build substrates that fail loudly rather than silently.

> [!IMPORTANT]
> **Silence is the default.** 
> Every prediction must clear a rigorous statistical gauntlet. If the evidence does not support action, the system stays silent. A recorded *nothing* is progress; a fabricated *something* is poison.

---

### Key Research & Substrates

#### 🌌 GAIA (Microstructure Specialist)
Our primary active research project is **GAIA**, an online learning time-series specialist that learns dynamically over streaming OHLCV bars.

* 📄 **[Research Paper Draft](https://github.com/GarAI-Labs/gaia-public/blob/main/paper/Research-Draft.md)** — Fully detailed academic overview of the substrate design, E1 Crucible validation, and negative feature results.
* 📐 **[Architecture Specification](https://github.com/GarAI-Labs/gaia-public/blob/main/ARCHITECTURE.md)** — Architectural blueprint detailing the 7-stage data purification cascade, 9-rung model ladder, and gated serving mechanisms.
* 📊 **[Experiment Ledger](https://github.com/GarAI-Labs/gaia-public/blob/main/experiments/LEDGER.md)** — Our open, append-only ledger recording all milestones, measurements, and negative results with equal care.

---

### Technical Pillars

```
                     ┌──────────────────┐
                     │    THE RAZOR     │
                     │  Prequential MDL │
                     └────────┬─────────┘
                              │ Capacity is earned
                              ▼
                     ┌──────────────────┐
                     │    SPRT GATE     │
                     │  Wald Sequential │
                     └────────┬─────────┘
                              │ Emission is earned
                              ▼
                     ┌──────────────────┐
                     │  DRIFT SENTINEL  │
                     │  Input-Space PH  │
                     └──────────────────┘
```

1. **Capacity via Prequential MDL (The Razor):** 
   A ladder of nine model classes (from simple running constants up to Neural ODEs) competes online. The Razor unseats an incumbent only when a challenger compresses the data significantly better over a sliding window, breaking ties toward simpler models.
2. **Emission via Sequential Gating (SPRT):** 
   Wald’s Sequential Probability Ratio Test compounds evidence across bars to honor a precision floor. The horizon is dynamic, and predictions are gated until the statistics justify action.
3. **Exchangeability via Drift Sentinel:** 
   Protects the system from out-of-distribution regime shifts by monitoring the input feature space. If feature z-scores drift, a Page-Hinkley quarantine is triggered instantly, enforcing silence before the first mislabeled event resolves.

---

### Open & Falsifiable Science

We do not claim secret market-beating formulas. We validate our instruments on synthetic **planted-truth worlds** where the ground-truth edge is mathematically known. Our public codebases contain zero hidden parameters, no grid-search validations, and are designed to fail clearly on noisy regimes.

<p align="center">
  <img src="profile/img/gar-hero.png" alt="GarAI Labs Logo Concept" width="200px">
</p>
