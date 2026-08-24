# South32 Spillage Audit Report — Execution Plan

## Purpose
This plan governs development of `South32_Spillage_Audit_Report_July2026_S32WPPSR_01` after the V0.1 first-draft review. It is intentionally separated from the report itself so that the development sequence remains stable while engineering context, narrative intent and recommendation philosophy are debated and refined.

## Governing Principle
**Do not optimise for minimum page count. Optimise for a complete, defensible engineering story with efficient page use.**

The report covers a connected mine material-handling system from the underground crusher through underground conveyors, secondary plant, surface screening and the load-out station. It is therefore legitimate for the final report to be substantial. Page count should be controlled primarily through layout efficiency, grouped evidence and removal of genuinely redundant content — not by discarding evidence that adds a unique technical point.

A second governing principle now applies:

**The final document is an audit narrative first and a technical evidence record second.** Technical evidence sheets, controlled metadata and finding tables must support the audit story; they must not force the whole report into a repetitive defect-register style.

## Phase 0 — Freeze Baseline
Status: **COMPLETE**

- Preserve `Report-Working/SpillageReport/South32_Spillage_Audit_Report_July2026_S32WPPSR_01_V0.1.docx` unchanged as the first evidence-populated baseline.
- Preserve `Report-Template/` as reference/template lineage only.
- Preserve all original evidence files at full resolution.

## Phase 1 — Context Alignment / Engineering-Intent Debate
Status: **CURRENT PHASE — FACTUAL MODEL SUBSTANTIALLY ALIGNED**

Objective: align the report compiler's understanding of `Context/Running_Report_Contextual_Spillage_NotesV3.7.docx` with the inspector's actual intended narrative, causal logic and recommendation philosophy.

Current status:
- the inspector has confirmed that the compiler's V3.7 contextual/mechanism interpretation is essentially fully aligned;
- no material factual correction has been identified;
- the main outstanding alignment work is the **report voice, narrative hierarchy, emphasis and recommendation expression**, not the underlying evidence model.

Tasks:
1. Continue debating/clarifying the intended audit story and reader journey.
2. Inspector expands any intended narrative, systemic conclusion or recommendation logic not yet explicit in V3.7.
3. Explicitly classify each new point as one of:
   - direct observation;
   - visual evidence-supported observation;
   - reported operating / maintenance information;
   - engineering inference / working hypothesis;
   - proposed remedial concept;
   - final recommendation candidate;
   - unresolved / requires verification.
4. Identify topology/process relationships required to understand the finding.
5. Identify global/systemic conclusions versus local asset-specific mechanisms.
6. Confirm the intended cleaner/fines-control philosophy: CV09 is a pilot for a **functional containment philosophy**, not a mandate for identical hardware at every conveyor.
7. Update the contextual source before propagating changes into the report.

Exit criterion: inspector and report compiler agree that the contextual source accurately represents the intended engineering narrative, systemic/local hierarchy and recommendation logic.

## Phase 2 — Context Revision
Status: **PENDING PHASE 1**

- Create the next controlled contextual revision from V3.7.
- Integrate agreed clarifications, topology, causal chains, recommendation intent and report-narrative principles.
- Explicitly capture the fines-control philosophy: fines should remain within the designed material-handling stream through the conveyor ecosystem until the intended screening/fines-handling stage can process them in a controlled manner.
- Preserve source/visual/inference qualifications.
- Render and visually QA the revised DOCX before it becomes the new primary report source.

Exit criterion: one updated contextual source is accepted as the report's governing engineering narrative.

## Phase 3 — Narrative Architecture / Audit Story Outline
Status: **PENDING PHASE 2**

Do **not** automatically retain the sheave-report section architecture. The sheave template remains useful for visual discipline, cover-page styling, photographic evidence sheets and controlled metadata, but the spillage report requires a different narrative structure.

Develop and agree the report story before rebuilding the DOCX. The outline should allow a South32 reader to understand the audit progressively, for example:
1. what the audit set out to determine;
2. how combined product and fines move through the inspected system;
3. the three interacting spillage families;
4. why observed deposit location may differ from initiating source location;
5. the dominant systemic fines/carryback/containment picture;
6. the key local mechanisms/case studies that prove or refine the systemic picture;
7. topology/access/operational factors that affect consequences and control;
8. housekeeping and trip/restart as consequence/event mechanisms;
9. the resulting engineering control philosophy;
10. targeted local corrective actions and verification tasks;
11. overall conclusions and implementation priorities.

Writing style target:
- formal engineering language;
- coherent story / guided audit explanation;
- concise paragraphs and bullets where they improve comprehension;
- use evidence references and technical sheets to support the narrative rather than interrupt it continuously;
- avoid a clinical “asset → defect → recommendation” rhythm where it obscures the whole-system message.

Exit criterion: inspector approves the narrative sequence and intended report voice before large-scale DOCX restructuring begins.

## Phase 4 — Full Evidence Inclusion / Story Matrix
Status: **PENDING PHASE 3**

Review all 197 pre-filtered repository media items. The 197 files are a curated subset selected by the inspector from more than 700 original media items and must not be treated as a raw pool.

For every item assign:

### Inclusion Status
- `E` — Essential body evidence
- `S` — Supporting / story evidence
- `A` — Appendix / reference evidence
- `X` — Exclude from report

### Story Role
One or more of:
- TOPOLOGY / ORIENTATION
- PROCESS RELATIONSHIP
- MECHANISM
- DEFECT / CONDITION
- EXTENT / SEVERITY
- CONSEQUENCE
- COMPARATOR / CLEAN CONDITION
- OPERATING CONTEXT
- MAINTENANCE / DESIGN DETAIL
- REMEDIAL-CONCEPT CONTEXT

Inspector review should focus mainly on candidate `X` items and any required promotions to `E`/`S` where narrative intent is not visually obvious.

Exit criterion: agreed evidence set and narrative role for every media item.

## Phase 5 — Prototype Photographic Evidence Module
Status: **PENDING PHASE 4**

Develop one complex evidence story as the layout prototype before revising all evidence modules. Recommended candidates: Screens, CV09 or Sample Conveyor 3.

Prototype requirements:
- retain the clean ISS/sheave-report Photographic Evidence Sheet look and engineering discipline;
- integrate naturally with the approved audit narrative rather than existing as an isolated technical appendix inside the main body;
- asset/story summary flows into evidence without unnecessary forced blank space;
- optional `System Context / Topology / Process Relationship` element;
- shared finding-level metadata once per technical story;
- multiple images per evidence sheet where appropriate;
- canonical evidence ID under every photo;
- legible captions and image detail;
- one `Observation / Engineering Assessment / Recommended Action` block per technical story where appropriate;
- deliberate page-break control so tables/images do not split badly;
- support full-width hero image, side-by-side portraits, stacked landscapes or 2x2 context grids according to evidence need.

Exit criterion: inspector approves evidence density, readability, metadata and visual hierarchy.

## Phase 6 — Rebuild Evidence-Supported Asset / Case-Study Sections
Status: **PENDING PHASE 5**

Apply the approved evidence-module architecture to all required asset/evidence groups, but organise them according to the approved narrative architecture rather than assuming the current V0.1 Section 16 structure must remain unchanged.

Key rule: one photograph does not automatically equal one page. One technical story should use the evidence density required to explain that story clearly.

Complex cases may contain multiple sub-stories, e.g.:
- Screens: water escape / corrosion / damaged supports;
- L1: belt contact / concrete deterioration / steel deterioration;
- CV09: cleaner geometry / wet consequence / active fallout;
- Sample Conveyor 3: mistracking / loading-vs-belt-width / containment loss;
- U4: mistracking / one-side product loss / custom cleaner.

Exit criterion: the report contains the agreed evidence story with efficient page use and no loss of important detail.

## Phase 7 — Recommendation and Narrative Expansion
Status: **PENDING PHASE 6**

- Expand asset/case narratives where restored evidence supports additional engineering detail.
- Finalise global/systemic recommendation logic and asset-specific recommendations.
- State the cleaner strategy correctly: prove the CV09 concept, then propagate the **functional containment standard/philosophy** to applicable locations after local verification; do not imply identical hardware everywhere.
- Express the system objective that fines should remain within the intended material stream until the designated screening/fines-handling stage rather than progressively escaping as uncontrolled carryback/spillage.
- Maintain distinction between immediate corrective action, verification task, design-development concept and final implementation recommendation.
- Ensure final conclusions trace directly to the approved narrative, evidence and updated contextual source.
- Add conceptual drawings where they materially improve understanding, including CV09 and Sample Conveyor containment concepts.

Exit criterion: findings, audit narrative, engineering assessment, recommendations and conclusion form one consistent evidence-to-action chain.

## Phase 8 — Document-Wide Layout and Styling Polish
Status: **PENDING PHASE 7**

Retain the existing clean cover-page composition as the visual anchor.

Complete:
- professional report colour palette;
- consistent heading hierarchy/spacing;
- evidence metadata bars;
- controlled table shading/borders;
- caption hierarchy;
- efficient portrait/landscape image layouts;
- automated TOC;
- List of Figures;
- List of Tables;
- internal cross-references;
- figure/table numbering;
- consistent header/footer and issue-status treatment;
- document-control/sign-off completion.

Exit criterion: report looks as polished and controlled as the prior ISS sheave-report series while retaining its own narrative spillage-audit identity.

## Phase 9 — Engineering Review and Issue Closure
Status: **PENDING**

- Complete ratings / finding priorities only once suitable decision criteria are agreed.
- Resolve or explicitly carry forward outstanding measurements / inspections / structural reviews.
- Perform full technical consistency review.
- Perform full render/visual QA of every page.
- Produce final controlled Word/PDF issue package when approved.

## Current Hold Point
**Do not proceed into the evidence-matrix/report-rebuild phases or materially modify V0.1 until Phase 1 context alignment, Phase 2 context revision and Phase 3 narrative architecture are complete.**

All new engineering interpretations generated during the debate phase should first be captured in the contextual source and `report_running_notes.md`, then propagated into the formal report in a controlled later pass.
