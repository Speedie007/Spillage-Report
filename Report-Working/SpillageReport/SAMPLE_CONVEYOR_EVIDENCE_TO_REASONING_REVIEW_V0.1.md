# Sample Conveyor 2/3 — Evidence-to-Reasoning Review V0.1

## Status

**FOCUSED SECOND-PASS REVIEW — OPEN / INSPECTOR CONFIRMATION IN PROGRESS**

This review is deliberately narrower than the original Batch-B visual review and the controlled E/S/A evidence classification.

The original review answered:

> **What condition does each photograph directly show, and how strong is it as inspection evidence?**

This focused review asks:

> **Which engineering relationship does each photograph help the reader understand, and does that relationship justify inclusion or elevation in the V0.6 report body?**

The historical `EVIDENCE_STORY_MATRIX_V0.1.csv` remains unchanged while this subset review is open. Any proposed E/S/A elevation/demotion below remains provisional until the full subset review is completed and the inspector approves the final classification changes.

## Source controls

- `Report-Working/evidence_visual_review_batch_B.md` — original detailed visual review.
- `Report-Working/SpillageReport/EVIDENCE_STORY_MATRIX_V0.1.csv` — current controlled E/S/A classification.
- `Report-Working/evidence_index.md` — current evidence inventory and first-draft candidates.
- `Context/Running_Report_Contextual_Spillage_NotesV4.2.md` and later accepted solution-closure context — current engineering interpretation baseline.

## Evidence boundary — binding

A still photograph may show the instantaneous loading condition, product scale relative to belt geometry, belt position, local containment relationship and accumulated consequence. A still photograph does **not** establish live feed rate, mass-flow rate, rated/design capacity exceedance, duration/frequency of a loading state, or the mechanical root cause of mistracking unless independently verified.

For this review, use **observed loading / geometric carrying condition** rather than treating a photograph as proof of quantitative conveyor overload.

Where a photograph supports a belt-offset condition, distinguish:

- **visually supported lateral belt offset at the captured condition**; from
- **persistent/dynamic mistracking**, its magnitude, frequency, load-dependence and mechanical root cause, which require further verification unless independently established.

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

# 2. Sample Conveyor 2 — relationship matrix under inspector review

## 2.1 Revised evidence boundary after REF-004 / REF-005 inspector review

The earlier Batch-B position that significant Sample Conveyor 2 mistracking was not visually established is now **refined** by the focused inspector review.

The complementary `LoadoutStationSample2-REF-004` and `LoadoutStationSample2-REF-005` views show the same local conveyor region from different perspectives. In the shadowed area beneath the cover, the belt is visibly displaced laterally relative to the roller arrangement: a substantial portion of a roller remains exposed rather than being covered by the belt. REF-005 provides the clearer complementary perspective of this same geometry.

Accordingly, the focused review now supports:

> **A lateral belt-offset condition is visually supported at the captured Sample Conveyor 2 condition by the complementary REF-004 / REF-005 image pair.**

This does **not** yet establish:

- the measured magnitude of the offset;
- whether the offset is continuous, intermittent or load-dependent;
- whether it should be characterised as persistent dynamic mistracking throughout operation;
- the initiating mechanical cause of the offset; or
- the relative contribution of tracking, feed quantity, product size, displaced-product congestion or another mechanism.

The images continue to show that coarse/lump product occupies a substantial proportion of the narrow belt width and that product containment loss is directly visible. Photographs do not prove quantitative design-capacity overload or identify the final feed-control method.

| Ref | Current E/S/A | LG | PW | TM | CL | CO | SG | Provisional V0.6 role | Provisional classification action | Review status |
|---|---:|:---:|:---:|:---:|:---:|:---:|:---:|---|---|---|
| **S2-REF-001** | E | C | — | — | S | **P** | C | Principal wider consequence/severity image | Retain **E** | PENDING |
| **S2-REF-002** | A | — | — | — | S | S | C | Alternate consequence image; likely redundant if REF-001/003 used | Retain **A** unless review identifies unique relationship | PENDING |
| **S2-REF-003** | A | — | — | — | S | **P** | C | Strong alternate wide consequence view | Candidate **A → S** / alternate E if it explains extent better than REF-001 | PENDING |
| **S2-REF-004** | E | **P** | **P** | S | S | — | S | Principal product-size-versus-belt-width image **plus supporting belt-offset evidence**; to be read with REF-005 | Retain **E** | **INSPECTOR CONFIRMED / REFINED** |
| **S2-REF-005** | S | **P** | S | **P** | S | — | **P** | Complementary view proving the exposed-roller / lateral belt-position relationship and local entry/cover geometry | **Inspector-supported S → E elevation at subset closure** | **INSPECTOR CONFIRMED / ELEVATION SUPPORTED** |
| **S2-REF-006** | E | S | S | — | **P** | **P** | **P** | Principal entry-zone congestion / containment-loss image; culmination condition requiring causal verification | Retain **E** | **INSPECTOR CONFIRMED / REFINED** |
| **S2-REF-007** | E | **P** | **P** | — | S | — | **P** | Strong combined loading-width-containment-geometry image | Retain **E** | **INSPECTOR CONFIRMED** |
| **S2-REF-008** | S | — | — | — | C | C | C | Lower-structure accumulation with little unique value to the current causal/relationship narrative | **Inspector-supported S → A downgrade at subset closure** | **INSPECTOR CONFIRMED / DOWNGRADE SUPPORTED** |

## 2.2 REF-004 / REF-005 complementary interpretation — inspector supplied

The two photographs are to be treated as a deliberate pair rather than as independent repetitive images.

### REF-004

The image is dark under the local cover, but the visible geometry supports several relationships simultaneously:

- the manganese lump size is large relative to the narrow belt width;
- smaller pieces remain on the carrying surface while larger pieces are visible outside the intended carrying path;
- the belt is laterally displaced relative to the roller, leaving a substantial part of the roller visibly exposed;
- the reduced usable lateral carrying margin is therefore relevant to the observed product-containment difficulty.

The photograph does not independently prove that the belt offset caused each displaced lump. It does, however, visually support the coexistence of **large product relative to belt width + lateral belt offset + containment loss** at the same inspected location.

### REF-005

REF-005 shows the same location from another perspective and makes the exposed roller / belt-position relationship easier to interpret. It therefore complements REF-004 and strengthens the visual basis for recognising the lateral offset.

For V0.6, REF-004 and REF-005 should be considered as a paired explanatory sequence if page space allows:

> **REF-004 = product-size / narrow-belt / containment relationship with offset visible in context.**  
> **REF-005 = complementary perspective clarifying the exposed-roller / lateral belt-position relationship and local entry/cover geometry.**

This paired role materially increases REF-005's narrative value and supports its provisional elevation from S to E.

## 2.3 REF-006 entry-zone geometry and congestion — inspector supplied

The orange covers visible in REF-006 are the conveyor entry-zone covers/guides associated with controlling product entry from the preceding feeder/chute so that material is directed toward the belt carrying path.

REF-006 shows the entry region heavily congested with displaced product, with accumulated material occupying much of the space beneath/around those covers. This makes the image important for more than general spillage severity: it shows the physical zone in which feed, product size, belt position and containment interact.

### Permissible engineering interpretation

REF-006 is consistent with the **cumulative outcome of one or more interacting mechanisms**, for example:

1. lateral belt offset could reduce available carrying margin and allow product to leave the belt, contributing to local build-up;
2. feed quantity may at times exceed what can be geometrically contained under the actual product-size and belt-position condition;
3. large product relative to the narrow belt may be more susceptible to displacement or escape than smaller fragments;
4. initial displaced large pieces may accumulate and compact within the constrained entry zone;
5. sufficiently severe local product build-up could potentially interfere with belt freedom/position and aggravate an existing offset condition; and
6. an adverse feedback condition is therefore plausible in which containment loss, congestion and belt offset reinforce one another.

### Critical evidence qualification

These possible sequences were **not witnessed dynamically during the inspection** and are not to be presented as proven chronological events.

They are engineering hypotheses derived from the combination of photographed conditions and inspector site knowledge. Their purpose is to define the verification programme required to establish which relationships are real and which corrective actions should therefore be implemented, and in what order.

REF-006 should therefore be used to communicate:

> **The observed end condition is compatible with several interacting feed / product-size / belt-position / containment mechanisms. The audit evidence is sufficient to require those relationships to be tested, but not to prescribe one unverified initiating cause.**

## 2.4 Sample 2 revised narrative chain

The focused review now supports a stronger evidence-led sequence:

> **REF-004 + REF-005 — show the combined product-size / narrow-belt relationship and visually supported lateral belt-offset condition**  
> **REF-007 — reinforces the observed loading / product-size / limited carrying-geometry relationship**  
> **REF-006 — shows the heavily congested entry/guide zone and actual containment failure condition that may represent the cumulative effect of interacting mechanisms**  
> **REF-001 or REF-003 — shows the accumulated wider consequence**

The photographs should drive verification of:

- actual feed quantity and variation/surge behaviour;
- product-size distribution relative to usable belt width;
- actual loading distribution/centring at the entry zone;
- belt tracking/offset magnitude, persistence and load-dependence;
- head/tail/roller/tension/alignment conditions relevant to tracking;
- whether displaced/compacted product is interfering with belt freedom or contributing to offset;
- the usable carrying geometry after primary conditions are corrected; and
- whether residual containment duty then warrants side-skirt/spill-seal installation and over what extent.

The evidence does not yet establish which of those variables is the initiating cause.

## 2.5 Corrective-action sequencing principle emerging from Sample 2

The current evidence supports a **diagnostic sequence rather than a single predetermined fix**:

1. establish the actual feed quantity/variation and product-size distribution;
2. quantify the observed lateral belt offset and determine its mechanical/operational cause;
3. inspect the entry/guide area for displaced-product congestion and any belt interference;
4. correct confirmed tracking/alignment/interference defects;
5. determine whether feed quantity, product size or loading distribution requires restriction/control relative to the available belt carrying geometry;
6. reassess the conveyor under representative operating conditions after those primary corrections;
7. establish the residual containment duty; and
8. where required, install an appropriate belt-compatible side-skirt/spill-seal arrangement based on the W10 functional principle, adapted to the Sample Conveyor geometry.

Possible outcomes remain open by design. For example, satisfactory performance may require a combination of tracking correction, product-size/feed control and skirting; alternatively, correction of the dominant primary conditions may materially reduce the residual containment duty. The audit should not prejudge that result before verification.

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

# 4. Candidate classification changes requiring inspector review / closure

## Sample Conveyor 2

1. **S2-REF-005 — S → E — inspector-supported elevation**  
   Reason: complementary to REF-004 and provides the clearest supporting view of the exposed roller / lateral belt-position relationship while also explaining the entry/cover geometry.
2. **S2-REF-003 — A → S candidate / alternate E — still pending**  
   Reason: may be a stronger wider consequence image than currently credited; needs direct comparison with REF-001.
3. **S2-REF-008 — S → A — inspector-supported downgrade**  
   Reason: does not materially advance the current product-size / loading / tracking / containment reasoning and can remain appendix/reference evidence.

## Sample Conveyor 3

4. **S3-REF-003 — S → E candidate**  
   Reason: may visually connect loaded-belt condition, local product loss and asymmetric belt/roller relationship in one frame.
5. **S3-REF-004 — A → S candidate**  
   Reason: similar interaction value; determine whether it adds anything not already better shown by REF-003/006.
6. **S3-REF-008 — A → S candidate**  
   Reason: possible distinct consequence/extent view; retain only if it adds spatial understanding beyond REF-012.
7. **S3-REF-009 — A → S candidate**  
   Reason: possible strong physical-geometry image for explaining the later side-skirt/spill-seal control.

No controlled E/S/A change is to be applied to `EVIDENCE_STORY_MATRIX_V0.1.csv` until the full subset review is completed.

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

- **Pass 1 — Sample Conveyor 2: REF-001 through REF-008 — IN PROGRESS; REF-004 through REF-008 reviewed**
- **Pass 2 — Sample Conveyor 3: REF-001 through REF-013**
- **Pass 3 — cross-image narrative sequencing / duplicates / final E/S/A proposals**
- **Pass 4 — update subset record, controlled evidence matrix if approved, current context and V0.6 integration notes**

---

# 6. Target report narrative after review

## Sample Conveyor 2 — revised working target

> **Observed loading/product scale + visually supported lateral belt offset → reduced usable narrow-belt carrying margin → entry-zone congestion / direct containment loss → accumulated consequence → verify feed/product-size/tracking/interference relationships → correct confirmed primary contributors in the appropriate sequence → determine residual containment duty → install suitable side-skirt/spill-seal containment where required → prove performance under representative operation.**

The lateral belt offset is visually supported by REF-004/005, but its magnitude, persistence and initiating cause remain to be established.

## Sample Conveyor 3

> **Observed loading/product scale → narrow carrying geometry + confirmed lateral belt offset → reduced usable containment margin → direct containment loss → accumulated consequence → verify/correct feed + tracking → establish usable carrying geometry → install suitable side-skirt/spill-seal containment → prove performance.**

The tracking magnitude and root cause remain to be established quantitatively.

---

**REVIEW CONTROL:** This file is an open working subset review. It does not supersede the original evidence matrix until the inspector completes the photo-by-photo confirmation and approves the resulting classification/narrative changes.
