# Sources Map — The Brain Does Not Fill the Skull (occupancy audit)

Author: Atharva Chourey
Affiliation: Atharva Chourey Lab (independent research lab)

*Manuscript in preparation — not yet peer-reviewed.*

This file maps every key number, verdict and reference in `paper.md` to the source file it was taken from. Nothing in the paper was taken from a source outside this list. Where a source gives a verdict without a number, the paper reports the verdict without a number.

## Primary sources

- `~/workspace/brain-scan-comparison/projects/occupancy-audit/RESULTS.md` — the run record: verdict, join table, headline distribution, per-arm and per-order results, cetacean subset, the two literature findings, excluded sources with reasons, and the "what this licenses / does not license" assessment the paper's §4 follows.
- `~/workspace/brain-scan-comparison/projects/occupancy-audit/PREREGISTRATION.md` (as amended 2026-11-17, amendment written after source inspection, before any join or occupancy computation) — kill conditions K1/K2, source roles and priority rules.
- `~/workspace/brain-scan-comparison/projects/occupancy-audit/outputs/occupancy_joined.csv` — the joined 42-species table behind every distribution in the paper.
- `~/workspace/brain-scan-comparison/projects/occupancy-audit/outputs/summary.json` — machine summary of the join.
- `~/workspace/brain-scan-comparison/projects/occupancy-audit/scripts/build_occupancy.py` — the build script.

## Key numbers and their sources

| Claim in paper | Value | Source file |
|---|---|---|
| Combined join | n = 42 species (K2 floor was 40; margin of two) | RESULTS.md, Verdict + The join |
| Median occupancy (combined) | 0.919 (IQR 0.824–0.973; range 0.323–1.542) | RESULTS.md, Headline distribution |
| Fraction within 90–100% | 40.5% (59.5% outside: 40.5% below 90%, 19.0% above 100%) | RESULTS.md, Verdict + Headline distribution |
| Waugh & Thewissen paired arm | n = 26; median 0.920; IQR 0.845–0.949; 42% below 90%; none above 100% | RESULTS.md, Per arm |
| Dembitzer × Patzke bridge arm | n = 10; median 1.010; 60% above 100% | RESULTS.md, Per arm |
| MRI arm | n = 7; median 0.493; dolphin MRI 515 cm³ vs ~1,477 cm³ compilation; orangutan 186 vs ECV 377 | RESULTS.md, Per arm |
| MRI-vs-Patzke brain spread | human 1.016; lion 0.755; dolphin 0.349 | RESULTS.md, Per arm |
| Lion occupancy by ruler | 1.02 histology (249.0 / 244.4) vs 0.77 MRI (188.1 / 244.4) | RESULTS.md, Per arm |
| Per-order medians | Carnivora 0.921 (n = 17); Primates 1.006 (n = 7); Artiodactyla 0.789 (n = 4); Perissodactyla 0.842 (n = 3); Cetacea 0.792 (n = 3) | RESULTS.md, Per-order medians |
| Diprotodontia values | 0.409 and 0.436 — flagged as MRI-arm artefacts of juvenile specimens | RESULTS.md, Per-order medians |
| Bowhead | occupancy 0.323 (brain 2,980 g; ECV 8,900 cm³); source text says ~40% | RESULTS.md, Cetaceans |
| Beluga / bottlenose dolphin | 0.792 / 0.937 combined (0.958 on Waugh & Thewissen's own brain volume) | RESULTS.md, Cetaceans |
| Dembitzer back-calculation | ECV = brain volume × 1.108 (median; IQR 1.085–1.125) across 149 brain-mass species; assumed occupancy ~90.2%; brain-mass and ECV species sets disjoint | RESULTS.md, Two findings about the literature itself |
| Grey wolf ECV clash | 91.49 ml (Dembitzer) vs 148.94 cm³ (Waugh & Thewissen); 1.63×; naive-join occupancy 1.45 vs 0.890 in-source | RESULTS.md, Two findings about the literature itself |
| Join hole | 124 of Dembitzer's 140 measured-ECV species have no brain volume in any open compilation used | RESULTS.md, The join |
| Excluded sources | Burger et al. 2019 Dryad doi:10.5061/dryad.2r62k7s — gated; Navarrete et al. 2018 Zenodo 10.5281/zenodo.5044936 — no volume table; Smaers et al. 2021 — not pulled; PeerJ 2025 MorphoSource set — not used; isotropic-fractionator masses — not used | RESULTS.md, Sources that did not make it |
| Licensed claim | fossil EQs carry an unacknowledged ruler-dependent error of at least ±10–25% before any biology enters | RESULTS.md, What this licenses |

## Novelty and framing notes

- The paper's headline is deliberately double, per the source record: the 100% identity is false **and** no single replacement constant is licensed. The site copy and abstract carry both halves.
- Occupancy values above 100% are reported as-is, nothing trimmed, and are framed throughout as a ruler-mismatch diagnostic — never as biology.
- The MRI arm is used only as a sensitivity diagnostic; its single (sometimes juvenile or partial) specimens are never presented as species brain volumes.
- Reference entries are given at the detail the source record supports (author, year, role); bibliographic details not present in the record were omitted rather than supplied.
