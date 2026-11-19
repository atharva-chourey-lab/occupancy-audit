# The Brain Does Not Fill the Skull: A 42-Species Occupancy Audit Finds Ruler Chaos, Not a Constant

Neuroanatomy · 2026

Author: Atharva Chourey
Affiliation: Atharva Chourey Lab (independent research lab)

*Manuscript — not yet peer-reviewed.*

**Companion paper:** a second, pre-registered arm of this audit — Burger × Dembitzer on the independent subset (n = 58, median occupancy 0.932), including the audit of the 71-species back-filled block that makes a naive join of the same data appear to confirm the 100% identity — is published as [occupancy-second-arm](https://github.com/atharva-chourey-lab/occupancy-second-arm).

## Abstract

Fossil encephalisation quotients rest on an identity: that endocranial volume (ECV) — the volume inside the skull — equals brain volume, an occupancy of 100%. This paper joins the two literatures that measure the two sides of that identity and computes occupancy directly. Under a pre-registered protocol, we joined endocast volumes (Dembitzer et al., 2022; Waugh & Thewissen, 2021; Sakai et al., 2016) to brain volumes (the Patzke et al., 2015 compilation; the same sources' paired values; Brain Catalogue MRI) for 42 mammal species — a far smaller overlap than either literature suggests. Median occupancy is 0.919 (IQR 0.824–0.973), but only 40.5% of species land inside the 90–100% band the identity implies, and 19.0% exceed 100% — physically impossible values that diagnose ruler mismatch rather than biology. The cleanest arm, 26 species with brain and ECV from the same source, gives a median of 0.920 with none above 100%; a bridge arm pairing modern endocasts with the histology-lineage brain compilation gives a median of 1.010, with 60% of species above 100%. Whole orders sit outside the band (Artiodactyla 0.79, Cetacea 0.79, Perissodactyla 0.84), and the largest modern ECV dataset silently back-calculates endocast volume from brain volume for 149 of its species — an assumed ~90% occupancy wearing a lab coat. Credit where it is due: that occupancy varies and is not 100% is Waugh & Thewissen's (2021) established result — a directly measured range of 33–98%, with the bowhead as their outlier — and this audit builds on their paired table. What the audit adds is the cross-compilation picture, and it is the sharper half: the field's rulers disagree by more than the shortfall itself, and the largest modern ECV dataset's back-calculation is a circularity — an assumed occupancy encoded as if it were a measurement. No single occupancy constant survives contact with the joined data.

*Keywords:* endocranial volume; encephalisation quotient; occupancy; comparative neuroanatomy; measurement; pre-registration

## Key results

- **The rulers disagree by more than the shortfall.** Across the 42-species cross-compilation join, median occupancy is 0.919 and only 40.5% of species land inside the assumed 90–100% band; 19.0% exceed 100% — physically impossible values that diagnose ruler mismatch, not biology. In the bridge arm the mismatch swallows the signal entirely: median 1.010, 60% of species with brains bigger than their skulls. The lion's occupancy is 1.02 on the histology ruler and 0.77 on the MRI ruler. Nothing was trimmed.
- **Circularity, measured: the largest modern ECV dataset assumes the answer.** For its 149 brain-mass species, Dembitzer et al.'s published "Endocast Volume" is back-calculated as brain volume × 1.108 — an assumed ~90.2% occupancy, silently encoded in the dataset the field treats as the measurement. No prior critique of this derivation exists; this audit is its first measurement.
- **Prior art, credited in full:** that occupancy varies and is not ~100% is Waugh & Thewissen's (2021) result — directly measured pairs spanning 33–98%, the bowhead their extreme example. This audit's cleanest arm *is* their paired table (26 species, median 0.920, none above 100%) — a re-summary in statistics they did not report, not new evidence. What has no prior: the cross-compilation medians and band statistics, the per-order arms outside Cetartiodactyla, and both circularity measurements.
- **Whole orders sit outside the band:** Artiodactyla 0.79, Cetacea 0.79, Perissodactyla 0.84 (medians). The bowhead's 0.323 is computed from Waugh & Thewissen's own tabulated pair; the audit's point about it is the narrow, correct one — it does not generalise to its order (beluga 0.792, bottlenose dolphin 0.937, also from their table).
- **Scoped claim:** fossil EQs carry an unacknowledged ruler-dependent error of at least ±10–25% before any biology enters. No per-fossil correction factor and no replacement constant is licensed — that refusal is part of the result.

## Read the paper

- [paper.md](paper.md) — full text (Markdown)
- [paper.pdf](paper.pdf) — full text (PDF)

## Sources and fidelity

Every quantitative claim in the paper is traced to its source file in [SOURCES.md](SOURCES.md). Novelty claims were checked against the published literature before release; where a prior work already held a claim, the paper says so and cites it. *Correction, 2026-11-18: an external review pressed the Waugh & Thewissen (2021) prior — this project's own anchor source. The presentation now leads with what is this audit's (ruler disagreement across compilations, and the circularity measurements) and credits Waugh & Thewissen explicitly as the source of the occupancy-variation result itself. No number changed. The correction is recorded in NOVELTY-ADDENDUM-2026-11-18.md, included in this repository.*

## Licence

This work is licensed under a [Creative Commons Attribution 4.0 International Licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it with attribution to Atharva Chourey, Atharva Chourey Lab.
