# The Brain Does Not Fill the Skull: A 42-Species Occupancy Audit Finds Ruler Chaos, Not a Constant

Author: Atharva Chourey
Affiliation: Atharva Chourey Lab (independent research lab)

*Manuscript in preparation — not yet peer-reviewed.*

## Abstract

Fossil encephalisation quotients rest on an identity: that endocranial volume (ECV) — the volume inside the skull — equals brain volume, an occupancy of 100%. This paper joins the two literatures that measure the two sides of that identity and computes occupancy directly. Under a pre-registered protocol, we joined endocast volumes (Dembitzer et al., 2022; Waugh & Thewissen, 2021; Sakai et al., 2016) to brain volumes (the Patzke et al., 2015 compilation; the same sources' paired values; Brain Catalogue MRI) for 42 mammal species — a far smaller overlap than either literature suggests. Median occupancy is 0.919 (IQR 0.824–0.973), but only 40.5% of species land inside the 90–100% band the identity implies, and 19.0% exceed 100% — physically impossible values that diagnose ruler mismatch rather than biology. The cleanest arm, 26 species with brain and ECV from the same source, gives a median of 0.920 with none above 100%; a bridge arm pairing modern endocasts with the histology-lineage brain compilation gives a median of 1.010, with 60% of species above 100%. Whole orders sit outside the band (Artiodactyla 0.79, Cetacea 0.79, Perissodactyla 0.84), and the largest modern ECV dataset silently back-calculates endocast volume from brain volume for 149 of its species — an assumed ~90% occupancy wearing a lab coat. Credit where it is due: that occupancy varies and is not 100% is Waugh & Thewissen's (2021) established result — a directly measured range of 33–98%, with the bowhead as their outlier — and this audit builds on their paired table. What the audit adds is the cross-compilation picture, and it is the sharper half: the field's rulers disagree by more than the shortfall itself, and the largest modern ECV dataset's back-calculation is a circularity — an assumed occupancy encoded as if it were a measurement. No single occupancy constant survives contact with the joined data.

*Keywords:* endocranial volume; encephalisation quotient; occupancy; comparative neuroanatomy; measurement; pre-registration

## 1. Introduction: an identity the fossil record cannot check

An encephalisation quotient is a ratio, and its denominator-side input for any fossil is an endocast: the volume of the cranial cavity, measured from the skull. To turn that into a brain volume, the standard practice assumes the identity ECV = brain volume — occupancy 100%. Extant-species work sometimes applies a folk correction (endocasts "run 8–12% large"), but the fossil literature has no paired brain to check either number against: the assumption is load-bearing and untestable *in the material it is applied to*.

It is testable in extant material, where both rulers exist. Two literatures measure the two sides: endocast studies report ECVs for large species sets, and brain compilations report brain volumes or masses for large species sets. What neither does is join the other. This paper performs that join under a pre-registered protocol, with fixed source priorities and two registered kill conditions, and computes the occupancy distribution directly.

One boundary must be drawn before the results. That occupancy varies across mammals and is not 100% is not this paper's discovery: Waugh & Thewissen (2021) established it on directly measured pairs — the brain fills approximately 33–98% of the cranial cavity, the bowhead is their extreme example and their word "outlier" — rejected the equate-ECV-with-brain-mass assumption in print, and published an allometric correction equation. Their S1 Table is this audit's cleanest arm and its anchor. What no prior work contains is the cross-compilation join itself — what happens when the compilations the field actually uses are joined to each other — and an audit of those compilations' internal derivations. Those are this paper's claims, and the second arm (occupancy-second-arm) extends them to the Burger canon.

The headline is double, and both halves matter. First, on the joined data the identity fails as a constant: median occupancy is 0.919, whole orders sit at 0.79–0.84, and the bowhead — computed from Waugh & Thewissen's own tabulated pair — sits at 0.323. Second, and less comfortably, the measurement system cannot currently deliver a replacement constant: 19.0% of joined species return occupancies above 100%, which is not biology but ruler disagreement, and the disagreement between the field's brain rulers is larger than the occupancy shortfall itself. The havoc is ruler chaos, not one clean number.

## 2. Methods

### 2.1 Sources and join rules

The audit was run on 2026-11-17 under a pre-registration amended the same day — the amendment written after source inspection, before any join or occupancy computation. Sources, with their registered roles:

| Source | Role | Species in | In combined join |
|---|---|---|---|
| Dembitzer et al. 2022, Method = "Volume" only | ECV (skull ruler) | 140 extant | 16 |
| Waugh & Thewissen 2021, S1 Table | paired brain + ECV | 26 | 23 |
| Sakai et al. 2016, Table 1 | felid ECV | 13 | 3 |
| Patzke et al. 2015 clean table | brain volumes | 357 | 17 as brain source |
| Brain Catalogue MRI | brain volumes (sensitivity) | 12 | 4 as brain source |

ECV priority was Dembitzer > Waugh & Thewissen > Sakai; brain priority was Patzke > Waugh & Thewissen > MRI, per the amendment. The combined join is **n = 42 species** with both rulers. Analysis arms: Dembitzer×Patzke bridge n = 10; Waugh & Thewissen paired n = 26; Sakai×Patzke n = 2; MRI-brain arm n = 7.

Two registered kill conditions governed the verdict. **K1** (≥90% of species within 90–100% occupancy and no clade structure) did **not** fire: only 40.5% of joined species land within 90–100%, and four orders with ≥3 species have medians outside the band. **K2** (join < 40 species) did **not** fire — by a margin of two species. That margin is uncomfortably thin, and its composition matters (§2.2): this is not the 291-species audit the target imagined, because the two big compilations barely overlap.

### 2.2 The join's biggest hole

124 of Dembitzer et al.'s 140 measured-ECV species — nearly all of its marsupial block (Diprotodontia) and most of its artiodactyls — have no brain volume in any open compilation we could use. Dembitzer measured skulls nobody ever weighed a brain for, and the Patzke/Stephan lineage weighed brains nobody ever measured a skull for. The two literatures pass each other by. The 42-species join is what survives of the intended audit, and every number below is scoped to it.

### 2.3 Sources that did not make it

Four candidate sources were excluded, each for a stated reason. Burger et al. 2019 (Dryad doi:10.5061/dryad.2r62k7s) is **gated**: Dryad's API now demands a bearer token for file download, the public file-stream route sits behind an anti-bot validation wall, and no Wayback copy of the file exists; Patzke-lineage masses were substituted as the ecosystem's brain ruler, as recorded in the amendment. Navarrete et al. 2018 is **not openly tabulated**: the Zenodo mirror (10.5281/zenodo.5044936) holds raw and processed scan archives (7.1 GB / 19.5 GB) but no volume table. Smaers et al. 2021 extant rows were not pulled (no ungated file-level route located in this run), and the PeerJ 2025 MorphoSource endocast set was not used (3D models behind per-project download; no openly tabulated species-level ECV table). Isotropic-fractionator whole-brain masses were not used: no open union table exists, and per the pre-registration partial-structure masses were not summed into brain masses.

## 3. Results

### 3.1 The headline distribution

Across the combined join (n = 42), median occupancy is **0.919** (IQR 0.824–0.973; range 0.323–1.542). The fraction outside the 90–100% band is **59.5%**: 40.5% of species fall below 90%, and **19.0% sit above 100%** — physically impossible values, reported as-is with nothing trimmed. They are the pre-registered ruler-mismatch diagnostic: a species cannot have more brain than skull, so every value above 1.0 is a measurement of the rulers, not of the animal.

### 3.2 Per arm: the answer depends on the ruler pair

- **Waugh & Thewissen paired (n = 26; same-source brain + ECV — the cleanest data):** median **0.920**, IQR 0.845–0.949, 42% below 90%, **none above 100%**. This is the arm to quote for the central tendency: the folk "endocasts run 8–12% large" correction is about right *for the median*.
- **Dembitzer × Patzke bridge (n = 10):** median **1.010**, with **60% of species above 100%**. The histology-lineage brain ruler (Stephan/Reep via Patzke) reads so large against modern endocast ECVs that the majority of bridge species have brains bigger than their skulls. This is the Two Rulers offset surfacing inside the occupancy question: on this ruler pair, "occupancy" is unmeasurable — the ruler gap swallows it.
- **MRI arm (n = 7):** median **0.493**. The Brain Catalogue's single specimens — several juvenile or partial (dolphin MRI brain 515 cm³ against a ~1,477 cm³ compilation value; orangutan 186 cm³ vs ECV 377 cm³) — cannot serve as species brain volumes, and we do not use them as such; the arm is reported as a sensitivity diagnostic. The three species with both MRI and Patzke brain values show the spread directly: human 1.016, lion 0.755, dolphin 0.349. For the lion, occupancy is **1.02** on the histology brain ruler (249.0 / Sakai ECV 244.4) and **0.77** on the MRI brain ruler (188.1 / 244.4) — one species, two rulers, two different answers to the same question.

### 3.3 Per-order medians

| Order | n | Median | IQR | Note |
|---|---|---|---|---|
| Carnivora | 17 | 0.921 | 0.903–0.959 | tightest large order |
| Primates | 7 | 1.006 | 0.937–1.015 | >100% median is a histology-ruler artefact (bridge arm) |
| Artiodactyla | 4 | 0.789 | 0.713–0.877 | all below the folk band |
| Perissodactyla | 3 | 0.842 | 0.841–0.867 | all three below 90% |
| Cetacea | 3 | 0.792 | — | spread is the story (§3.4) |

Small orders are listed individually in the joined table; Diprotodontia's two species (0.409 and 0.436) are MRI-arm artefacts of juvenile catalogue specimens, not marsupial biology — flagged, not hidden.

### 3.4 Cetaceans, explicitly

The pre-registered cetacean subset joins three species, all through Waugh & Thewissen's S1 Table. The **bowhead (*Balaena mysticetus*)** has occupancy **0.323**, computed from Waugh & Thewissen's own tabulated pair (brain 2,980 g, ECV 8,900 cm³); their text says ~40%, their table's numbers give 32% — either way, extreme. The **beluga (*Delphinapterus leucas*)** sits at **0.792**, and the **bottlenose dolphin (*Tursiops truncatus*)** at **0.937** in the combined join (0.958 on Waugh & Thewissen's own brain volume). So the bowhead does not generalise: it is an outlier within its own order, not the cetacean condition. "Cetaceans have half-empty skulls" is false as a clade statement on the only paired data that exist; "the bowhead's brain fills a third of its cranial cavity, and nobody knows the distribution across the other ~90 cetacean species" is the true one.

### 3.5 Two findings about the literature itself

**The largest modern ECV dataset assumes the answer for 44% of its species.** Dembitzer et al.'s supplement holds brain-mass records and endocast-volume records for *disjoint* species sets (zero overlap). For the 149 brain-mass species, the published "Endocast Volume" is back-calculated: ECV = brain volume × **1.108** (median; IQR 1.085–1.125, verified across all 149). That is an assumed occupancy of ~90.2%, silently encoded — the folk correction, wearing a lab coat. Any study reading those rows as skull measurements inherits the assumption it might be trying to test. (The supplement's MOESM2 and MOESM4 agree on every shared ECV; the duplication is benign.)

**The skull rulers also disagree with each other.** Grey wolf ECV is 91.49 ml in Dembitzer et al. and 148.94 cm³ in Waugh & Thewissen — a 1.63× spread for one species, which manufactures a nonsense occupancy of 1.45 if joined naively (in Waugh & Thewissen's own pairing, the wolf is 0.890). Species-mean ECV from different specimen sets is not a stable constant at the precision this literature argues at.

## 4. Discussion: what this licenses, and what it does not

Licensed: "The brain does not fill the skull. In the only same-source paired dataset, median occupancy is 92% with an IQR of 85–95%; whole orders sit at 79–84%; the bowhead sits at 32%; and the field's two brain rulers disagree by more than the effect, so fossil EQs carry an unacknowledged ruler-dependent error of at least ±10–25% before any biology enters."

Not licensed: any per-fossil correction factor; any cetacean-wide occupancy claim; and any occupancy number quoted without its ruler pair attached. The audit's second headline is a warning against its own first one: a single replacement constant — not 100%, not the folk 88–92%, not this paper's 0.919 — would repeat the original error with a new number. Occupancy is a distribution across species and a function of which rulers measured it, and the joined data support nothing tidier.

Declared limits: the join is 42 species, two above its own registered kill floor, and heavily weighted to Carnivora (17 of 42); the bridge arm's >100% values are a ruler artefact by construction and are used only as a diagnostic; the MRI arm's specimens are single, sometimes juvenile or partial, and are never used as species values; and four candidate sources (§2.3) could not be included, two of them for access reasons that are themselves part of the record.

## 5. Data and code availability

The build script (`scripts/build_occupancy.py`), the joined table (`outputs/occupancy_joined.csv`) and the machine summary (`outputs/summary.json`) are retained in the lab's project record for this study, together with the pre-registration and its amendment. Source datasets are those cited in §2.1 and §2.3, each openly available except where the record states a gate.

## References

- Dembitzer et al. (2022). Mammal endocranial-volume dataset (Method = "Volume" subset used here).
- Waugh, D. A. & Thewissen, J. G. M. (2021). Paired brain and endocranial volumes, S1 Table.
- Sakai et al. (2016). Felid endocranial volumes, Table 1.
- Patzke et al. (2015). Comparative brain-volume compilation (clean table; 357 species).
- Burger et al. (2019). Dryad dataset, doi:10.5061/dryad.2r62k7s (gated at time of audit; not used).
- Navarrete et al. (2018). Primate brain scan archives, Zenodo 10.5281/zenodo.5044936 (no volume table; not used).
- Smaers et al. (2021). Extant brain-size dataset (not pulled; no ungated file-level route located).
- Atharva Chourey Lab (2026). *Shrinkage-corrected histological compilation values average ~1.6× MRI-atlas values: an audit of a comparative neuroanatomy archive.* Manuscript, Atharva Chourey Lab. https://github.com/atharva-chourey-lab/lost-atlas
