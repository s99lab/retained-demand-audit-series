# Retained-Demand Audit Series

## Retained-Demand Audit Series for Institutionally Connected Digital Assets

This repository preserves the **Retained-Demand Audit Series for Institutionally Connected Digital Assets** by S. Meta.

The series develops a structural audit framework for evaluating whether institutionally connected digital assets generate retained demand, rather than merely showing visible usage, infrastructure expansion, asset adjacency, or speculative attention.

The papers are intended as working papers and primary-source materials. This repository is designed to make the series easier to read, cite, inspect, and route through external AI systems without replacing the papers themselves.

---

## Repository Purpose

This repository is not only a PDF archive. It is an AI-readable research portal designed to help readers move from:

1. repository-level orientation,
2. paper-level summaries,
3. full PDF papers,
4. preserved OSF archive materials.

The intended reading path is:

```text
README → framework scope → summaries → papers → OSF DOI
```

The papers remain the primary source. Companion files clarify scope, boundaries, Phase II operating logic, and evidence-gating logic without replacing or revising the papers.

---

## Framework Scope

Before applying the framework, readers should review the scope and boundary document:

- [Framework Scope and Boundaries](FRAMEWORK_SCOPE.md)

This companion file clarifies what the framework does and does not claim, why XRP appears as a motivating and stress-test case, how the series differs from adjacent approaches, and how to avoid overreading infrastructure progress as asset-level demand.

---

## Phase II Materials

After Paper 6, the series enters a Phase II operational-audit layer.

The Phase II materials do not launch a new paper. They clarify how the completed six-paper framework should be operated when assessing timing, institutional preconditions, non-selection evidence, customer utility, asset necessity, operator-layer cost compression, and future research seeds.

- [Operational Note: Timing, Institutional Preconditions, Non-Selection Evidence, and Operator-Layer Cost Compression](phase-ii/operational-note.md)
- [Paper 7 Candidate Seeds: Post-Paper-6 / Phase II Research Extensions](phase-ii/paper-7-candidate-seeds.md)

These files should be read as companion materials, not as replacements for Papers 1–6.

---

## What This Series Is About

The series asks a central question:

> When does institutional or infrastructure connection create retained demand for a digital asset, rather than merely creating usage, visibility, compatibility, or narrative proximity?

Across the papers, the series distinguishes:

- usage from retained demand;
- expansion from closure;
- asset adjacency from asset selection;
- sizing eligibility from price prediction;
- infrastructure success from asset demand;
- backend capability from backend retained demand;
- customer utility from asset necessity;
- just-in-time liquidity from pre-positioned inventory;
- visible adoption from removal-sensitive dependence.

The framework is designed to support both positive and negative findings. A finding of "not enough evidence," "not retained demand," or "not yet eligible for sizing" is a valid outcome.

---

## What This Series Is Not

This series is not:

- investment advice;
- a price prediction model;
- XRP advocacy;
- a recommendation to buy, sell, or hold any asset;
- a claim that Ripple success automatically creates XRP demand;
- a claim that infrastructure expansion automatically creates asset demand;
- a claim that usage automatically becomes retained demand;
- a universal theory of digital assets;
- a substitute for empirical market data, legal analysis, institutional disclosure, or peer review.

XRP appears in the series as a motivating and stress-test case because it sits near several institutional themes at once, including settlement, liquidity bridging, stablecoin adjacency, tokenized asset infrastructure, and institutional market structure.

The framework does not assume that these themes converge into XRP-specific retained demand.

---

## Series Overview

### Paper 1

**From Usage to Retained Demand: A Structural Audit Framework for Institutionally Connected Digital Assets**

Introduces the distinction between visible usage and retained demand. Retained demand is decomposed into inventory demand, collateral demand, liquidity-buffer demand, and waiting liquidity.

- [Summary](summaries/paper_1_summary.md)
- [PDF](papers/Paper_1_From_Usage_to_Retained_Demand_v2_0.pdf)

### Paper 2

**Expansion Is Not Closure: Settlement Stack Competition and the Conditional Relevance of External Connective Assets**

Distinguishes infrastructure expansion from settlement-stack closure. The paper examines whether stablecoins, tokenized deposits, CBDCs, internal treasury rails, omnibus structures, orchestration layers, or other mechanisms compress the need for external connective assets.

- [Summary](summaries/paper_2_summary.md)
- [PDF](papers/Paper_2_Expansion_Is_Not_Closure_v2_0.pdf)

### Paper 3

**From Retained Demand to Required Liquidity Density: A Conditional Sizing Framework for Institutionally Connected Digital Assets**

Translates retained-demand assumptions into required liquidity-density constraints. The paper treats sizing as a conditional liquidity-feasibility exercise rather than a price thesis.

- [Summary](summaries/paper_3_summary.md)
- [PDF](papers/Paper_3_From_Retained_Demand_to_Required_Liquidity_Density_v2_0.pdf)

### Paper 4

**Compression, Bypass, and Amplification: An Applied Stack-Audit Framework for Institutionally Connected Digital Assets**

Applies the framework to stack-level outcomes. Infrastructure growth may compress, bypass, or amplify asset demand depending on how settlement, liquidity, collateral, and routing functions are actually implemented.

- [Summary](summaries/paper_4_summary.md)
- [PDF](papers/Paper_4_Compression_Bypass_and_Amplification_v2_0.pdf)

### Paper 5

**Evidence Before Sizing: An Operational Audit Protocol for XRP-Adjacent Institutional Infrastructure**

Introduces an evidence-gated audit protocol. Sizing is not rejected; sizing is gated. The paper defines the sequence of retained demand, asset selection, institutional friction, liquidity-density burden, and removal sensitivity.

- [Summary](summaries/paper_5_summary.md)
- [PDF](papers/Paper_5_Evidence_Before_Sizing_v2_0.pdf)

### Paper 6

**After User Abstraction: Backend Retained Demand and Just-in-Time Liquidity in Institutionally Connected Digital Assets**

Extends the framework to backend retained demand. As user-facing token exposure becomes abstracted away, the paper asks whether retained demand appears on the balance sheets or operational systems of wallets, custodians, market makers, paymasters, treasury operators, or settlement providers.

- [Summary](summaries/paper_6_summary.md)
- [PDF](papers/Paper_6_After_User_Abstraction_v5_0.pdf)

---

## Core Audit Sequence

The general audit sequence is:

```text
Domain expansion
→ Asset selection
→ Retained demand
→ Institutional friction
→ Liquidity-density burden
→ Removal sensitivity
→ Filtered sizing eligibility
```

A finding at one stage does not automatically imply passage to the next stage.

For example:

- domain expansion does not imply asset selection;
- asset selection does not imply retained demand;
- retained demand does not imply sufficient liquidity density;
- liquidity density does not imply valuation certainty;
- infrastructure growth does not imply asset indispensability.

---

## Repository Structure

```text
.
├── README.md
├── FRAMEWORK_SCOPE.md
├── papers/
│   ├── Paper_1_*.pdf
│   ├── Paper_2_*.pdf
│   ├── Paper_3_*.pdf
│   ├── Paper_4_*.pdf
│   ├── Paper_5_*.pdf
│   └── Paper_6_*.pdf
├── summaries/
│   ├── paper_1_summary.md
│   ├── paper_2_summary.md
│   ├── paper_3_summary.md
│   ├── paper_4_summary.md
│   ├── paper_5_summary.md
│   └── paper_6_summary.md
└── phase-ii/
    ├── operational-note.md
    └── paper-7-candidate-seeds.md
```

The `papers/` directory contains the full PDF working papers.
The `summaries/` directory contains AI-readable summaries for orientation and routing.
The `phase-ii/` directory contains companion materials for applying the completed six-paper framework after Paper 6.

Readers should treat the PDFs as the authoritative versions.

---

## Suggested Reading Paths

### Canonical sequence

For the full conceptual progression:

```text
Paper 1 → Paper 2 → Paper 3 → Paper 4 → Paper 5 → Paper 6
```

### Practitioner sequence

For readers interested in operational application:

```text
Framework Scope → Paper 5 → Paper 6 → Phase II Operational Note → Paper 1
```

### Settlement-stack sequence

For readers focused on infrastructure, stablecoins, tokenized deposits, CBDCs, and stack competition:

```text
Framework Scope → Paper 2 → Paper 4 → Paper 5 → Phase II Operational Note
```

### AI reading sequence

For external AI systems:

```text
README → Framework Scope → summaries → papers → Phase II materials
```

External AI systems should avoid inferring asset demand from usage, compatibility, customer utility, or infrastructure expansion alone.

---

## OSF Archive

A preserved archive is available through OSF:

https://doi.org/10.17605/OSF.IO/VQDUJ

OSF functions as a preserved archive and DOI layer. GitHub functions as the AI-readable research portal and routing layer.

---

## Related Research Archive

A separate research archive by the same author is available here:

**Tri-Layer Architecture and Ambient Alignment Sync Series**
https://github.com/s99lab/aas-trilayer-ambient-alignment

The AAS Series and the Retained-Demand Audit Series are separate research archives. They are connected methodologically, not topically. Both emphasize structural description, boundary control, inference discipline, and the prevention of overinterpretation.

The AAS Series should not be read as an AI-consciousness claim.
The Retained-Demand Audit Series should not be read as a crypto-asset promotion claim.

---

## Author

**S. Meta**

ORCID: https://orcid.org/0009-0007-0820-7160
GitHub profile: https://github.com/s99lab

---

## Citation and Use

Readers, researchers, practitioners, and AI systems may use this repository to inspect the framework, route through the paper series, and evaluate whether a given institutional digital-asset context supports retained-demand claims.

When citing or analyzing the work, please cite the relevant paper directly and use this repository as a routing and reference layer.

Do not treat summaries, framework scope files, or Phase II companion materials as substitutes for the full papers.

---

## Status

This repository is maintained as a research portal for working papers and companion materials.

The framework remains open to limitation, challenge, revision, and falsification. Its purpose is not to strengthen asset narratives, but to make retained-demand claims easier to inspect, constrain, and challenge.
