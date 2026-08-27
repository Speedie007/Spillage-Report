# Sample Conveyor 2/3 — Evidence-to-Reasoning Review V0.1

## Status

**FOCUSED SECOND-PASS REVIEW — OPEN / INSPECTOR CONFIRMATION IN PROGRESS**

This review is deliberately narrower than the original Batch-B visual review and the controlled E/S/A evidence classification.

The original review answered:

> **What condition does each photograph directly show, and how strong is it as inspection evidence?**

This focused review asks:

> **Which engineering relationship does each photograph help the reader understand, and does that relationship justify inclusion or elevation in the V0.6 report body?**

The historical `EVIDENCE_STORY_MATRIX_V0.1.csv` remains unchanged while this subset review is open. Any proposed E/S/A elevation/demotion below is provisional until inspector review is completed.

## Source controls

- `Report-Working/evidence_visual_review_batch_B.md` — original detailed visual review.
- `Report-Working/SpillageReport/EVIDENCE_STORY_MATRIX_V0.1.csv` — current controlled E/S/A classification.
- `Report-Working/evidence_index.md` — current evidence inventory and first-draft candidates.
- `Context/Running_Report_Contextual_Spillage_NotesV4.2.md` and later accepted solution-closure context — current engineering interpretation baseline.

## Evidence boundary — binding

A still photograph may show the instantaneous loading condition, product scale relative to belt geometry, belt position, local containment relationship and accumulated consequence. A still photograph does **not** establish live feed rate, mass-flow rate, rated/design capacity exceedance, duration/frequency of a loading state, or the mechanical root cause of mistracking unless independently verified.

For this review, use **observed loading / geometric carrying condition** rather than treating a photograph as proof of quantitative conveyor overload.

---

# 1. Relationship categories

| Code | Relationship | Review question |
|---|---|---|
| **LG** | Observed loading / geometric carrying condition | Does the image show how much of the available carrying geometry is occupied by product at the captured condition? |
| **PW** | Product size versus belt width | Does the image clearly show the scale relationship between individual manganese-ore lumps and the narrow conveyor belt? |
| **TM** | Tracking / usable carrying margin | Does the image show belt centring or lateral offset that affects the available containment margin? |
| **CL** | Actual lateral containment loss | Does the image show product at or beyond the intended belt carrying path? |
| **CO** | Consequence / accumulated spillage | Does the image show the accumulated result of recurring containment loss around the conveyor? |
| **SG** | Solution / physical geometry | Does the image help explain covers, side structure, belt edge, installation space or where a side-skirt/spill-seal control could act? |

Relationship strength:

- **P — Primary:** one of the strongest images for explaining that relationship.
- **S — Supporting:** materially supports the relationship but should normally be paired with a stronger image.
- **C — Context:** useful orientation/geometry only.
- **—:** the image should not be relied upon for that relationship.

---

# 2. Sample Conveyor 2 — provisional relationship matrix

Current evidence boundary: coarse/lump product occupies a substantial proportion of the narrow belt width and containment loss is directly visible. Significant mistracking is **not** visually established. Photographs do not prove quantitative design-capacity overload or identify the final feed-control method.

| Ref | Current E/S/A | LG | PW | TM | CL | CO | SG | Provisional V0.6 role | Provisional classification action | Review status |
|---|---:|:---:|:---:|:---:|:---:|:---:|:---:|---|---|---|
| **S2-REF-001** | E | C | — | — | S | **P** | C | Principal wider consequence/severity image | Retain **E** | PENDING |
| **S2-REF-002** | A | — | — | — | S | S | C | Alternate consequence image; likely redundant if REF-001/003 used | Retain **A** unless review identifies unique relationship | PENDING |
| **S2-REF-003** | A | — | — | — | S | **P** | C | Strong alternate wide consequence view | Candidate **S** / alternate E if it explains extent better than REF-001 | PENDING |
| **S2-REF-004** | E | **P** | **P** | — | S | — | S | Principal product-size-versus-narrow-belt / geometric loading image | Retain **E** | PENDING |
| **S2-REF-005** | S | **P** | S | — | S | — | **P** | Loaded-belt + cover/side-geometry image; potentially important bridge to investigation/solution | **Candidate elevation S → E** | PENDING |
| **S2-REF-006** | E | S | S | — | **P** | S | **P** | Principal local containment-loss / enclosure-relationship image | Retain **E** | PENDING |
| **S2-REF-007** | E | **P** | **P** | — | S | — | **P** | Strong combined loading-width-containment-geometry image | Retain **E** | PENDING |
| **S2-REF-008** | S | — | — | — | S | S | C | Secondary lower-structure consequence | Retain **S** / appendix candidate if body becomes dense | PENDING |

## Sample 2 provisional narrative chain

> **REF-004 / REF-007 — show product scale and occupied carrying width**  
> **REF-005 — show the loaded-belt and local physical geometry that constrains the carrying zone / future control arrangement**  
> **REF-006 — show actual product outside the intended carrying path**  
> **REF-001 or REF-003 — show the accumulated consequence**

The photographs should drive verification of actual feed quantity/variation, product-size distribution, loading geometry and usable carrying width. They do not establish significant Sample 2 mistracking or quantitative rated-capacity overload.

---

# 3. Sample Conveyor 3 — provisional relationship matrix

Current evidence boundary: substantial solid/lump-product spillage and the same narrow-belt/product-size issue are directly supported. Lateral belt offset/mistracking is visually supported but unmeasured. Photographs do not establish the mechanical root cause of the mistracking.

| Ref | Current E/S/A | LG | PW | TM | CL | CO | SG | Provisional V0.6 role | Provisional classification action | Review status |
|---|---:|:---:|:---:|:---:|:---:|:---:|:---:|---|---|---|
| **S3-REF-001** | A | C | — | — | — | — | **P** | General installation/topology; useful if reader needs physical orientation before solution discussion | Retain **A**, possible S if geometry becomes necessary in body | PENDING |
| **S3-REF-002** | E | S | S | — | **P** | **P** | S | Principal local coarse-product containment-loss image | Retain **E** | PENDING |
| **S3-REF-003** | S | S | S | S | S | S | S | Interaction image linking loaded belt, local spill and asymmetric geometry | **Candidate elevation S → E** if visual review confirms it bridges the three mechanisms clearly | PENDING |
| **S3-REF-004** | A | S | S | S | S | S | S | Alternate interaction image | **Candidate A → S**; elevate further only if stronger/clearer than REF-003 | PENDING |
| **S3-REF-005** | E | **P** | **P** | S | S | S | S | Principal product-size-versus-narrow-belt image | Retain **E** | PENDING |
| **S3-REF-006** | E | **P** | **P** | S | S | S | **P** | Strong combined loading + lateral-position + local geometry image | Retain **E** | PENDING |
| **S3-REF-007** | E | S | S | S | **P** | S | **P** | Product concentrated/lodged beside carrying path; strong bridge to side containment | Retain **E** | PENDING |
| **S3-REF-008** | A | — | — | — | S | **P** | C | Alternate consequence/extent view | Candidate **A → S** only if it adds distinct spatial consequence | PENDING |
| **S3-REF-009** | A | S | S | — | S | — | **P** | Local edge/containment geometry; possible solution-geometry support | **Candidate A → S** if it clarifies skirt/spill-seal placement better than current E images | PENDING |
| **S3-REF-010** | A | — | — | C | — | — | **P** | Drive/end-station orientation and mechanical inspection context | Retain **A** unless required for tracking-correction explanation | PENDING |
| **S3-REF-011** | S | S | S | — | S | S | C | Loaded belt + product below; secondary mechanism/consequence bridge | Retain **S** | PENDING |
| **S3-REF-012** | E | — | — | — | S | **P** | C | Principal wider consequence/severity image on grating/access | Retain **E** | PENDING |
| **S3-REF-013** | E | — | — | **P** | — | — | **P** | Principal belt-offset / reduced usable carrying-margin evidence | Retain **E** | PENDING |

## Sample 3 provisional narrative chain

> **REF-005 / REF-006 — show product size and occupied narrow-belt carrying width**  
> **REF-013 — show lateral belt offset and reduced usable carrying margin**  
> **REF-003 / REF-006 / REF-007 — show the interaction between loading, belt position and local containment**  
> **REF-002 — show actual local containment loss**  
> **REF-012 — show accumulated consequence**

This evidence supports the sequence: verify feed/loading conditions; quantify and correct the confirmed tracking/alignment condition; establish the resulting usable carrying geometry; then detail the residual side-skirt/spill-seal containment arrangement.

---

# 4. Candidate classification changes requiring inspector review

The following are the first candidates for elevation because their narrative role is potentially stronger now than when the original matrix was built:

1. **S2-REF-005 — S → E candidate**  
   Reason: may provide the missing bridge between observed loading and the actual cover/side geometry in which feed and containment must be understood.
2. **S2-REF-003 — A → S candidate / alternate E**  
   Reason: may be a stronger wider consequence image than currently credited; needs direct comparison with REF-001.
3. **S3-REF-003 — S → E candidate**  
   Reason: may visually connect loaded-belt condition, local product loss and asymmetric belt/roller relationship in one frame.
4. **S3-REF-004 — A → S candidate**  
   Reason: similar interaction value; determine whether it adds anything not already better shown by REF-003/006.
5. **S3-REF-008 — A → S candidate**  
   Reason: possible distinct consequence/extent view; retain only if it adds spatial understanding beyond REF-012.
6. **S3-REF-009 — A → S candidate**  
   Reason: possible strong physical-geometry image for explaining the later side-skirt/spill-seal control.

No controlled E/S/A change is to be applied until this review is completed.

---

# 5. Inspector review workflow

For each photograph, confirm or amend:

1. **What does the photograph actually show that matters to the engineering story?**
2. **Which relationship code(s) does it demonstrate most clearly?**
3. **Is it duplicative, or does it add a unique step in the reader's reasoning?**
4. **Should it be body-essential (E), supporting (S), or appendix/reference (A) for V0.6?**
5. **What conclusion may the reader reasonably draw from it?**
6. **What conclusion must the reader NOT draw from it?**
7. **Does it create or refine a verification/action item?**

Review sequence:

- **Pass 1 — Sample Conveyor 2: REF-001 through REF-008**
- **Pass 2 — Sample Conveyor 3: REF-001 through REF-013**
- **Pass 3 — cross-image narrative sequencing / duplicates / final E/S/A proposals**
- **Pass 4 — update subset record, controlled evidence matrix if approved, current context and V0.6 integration notes**

---

# 6. Target report narrative after review

## Sample Conveyor 2

> **Observed loading/product scale → available narrow-belt carrying geometry → direct containment loss → accumulated consequence → verify feed/geometric capacity relationship → correct identified primary contributors → install suitable side-skirt/spill-seal containment → prove performance.**

Tracking at Sample 2 is to be verified, not presumed defective.

## Sample Conveyor 3

> **Observed loading/product scale → narrow carrying geometry + confirmed lateral belt offset → reduced usable containment margin → direct containment loss → accumulated consequence → verify/correct feed + tracking → establish usable carrying geometry → install suitable side-skirt/spill-seal containment → prove performance.**

The tracking magnitude and root cause remain to be established quantitatively.

---

**REVIEW CONTROL:** This file is an open working subset review. It does not supersede the original evidence matrix until the inspector completes the photo-by-photo confirmation and approves the resulting classification/narrative changes.
