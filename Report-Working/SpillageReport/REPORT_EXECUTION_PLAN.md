# South32 Spillage Audit Report — Execution Plan

## Purpose
This plan governs development of `South32_Spillage_Audit_Report_July2026_S32WPPSR_01` after the V0.1 first-draft review. It is intentionally separated from the report itself so that the development sequence remains stable while engineering context is debated and refined.

## Governing Principle
**Do not optimise for minimum page count. Optimise for a complete, defensible engineering story with efficient page use.**

The report covers a connected mine material-handling system from the underground crusher through underground conveyors, secondary plant, surface screening and the load-out station. It is therefore legitimate for the final report to be substantial. Page count should be controlled primarily through layout efficiency, grouped evidence and removal of genuinely redundant content — not by discarding evidence that adds a unique technical point.

## Phase 0 — Freeze Baseline
Status: **COMPLETE**

- Preserve `Report-Working/SpillageReport/South32_Spillage_Audit_Report_July2026_S32WPPSR_01_V0.1.docx` unchanged as the first evidence-populated baseline.
- Preserve `Report-Template/` as reference/template lineage only.
- Preserve all original evidence files at full resolution.

## Phase 1 — Context Alignment / Engineering-Intent Debate
Status: **CURRENT PHASE**

Objective: align the report compiler's understanding of `Context/Running_Report_Contextual_Spillage_NotesV3.7.docx` with the inspector's actual intended narrative, causal logic and recommendation philosophy.

Tasks:
1. Explain the current V3.7 contextual model in plain engineering terms.
2. Inspector corrects, expands or re-prioritises the interpretation.
3. Debate each disputed point until a common fact/interpretation/recommendation state is established.
4. Explicitly classify each new point as one of:
   - direct observation;
   - visual evidence-supported observation;
   - reported operating / maintenance information;
   - engineering inference / working hypothesis;
   - proposed remedial concept;
   - final recommendation candidate;
   - unresolved / requires verification.
5. Identify topology/process relationships required to understand the finding.
6. Identify global/systemic conclusions versus local asset-specific mechanisms.
7. Update the contextual source before propagating changes into the report.

Exit criterion: inspector and report compiler agree that the contextual source accurately represents the intended engineering narrative and recommendation logic.

## Phase 2 — Context Revision
Status: **PENDING PHASE 1**

- Create the next controlled contextual revision from V3.7.
- Integrate agreed clarifications, topology, causal chains and recommendation intent.
- Preserve source/visual/inference qualifications.
- Render and visually QA the revised DOCX before it becomes the new primary report source.

Exit criterion: one updated contextual source is accepted as the report's governing engineering narrative.

## Phase 3 — Full Evidence Inclusion / Story Matrix
Status: **PENDING PHASE 2**

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

## Phase 4 — Prototype Section 16 Evidence Module
Status: **PENDING PHASE 3**

Develop one complex asset as the layout prototype before revising all 23 groups. Recommended candidates: Screens, CV09 or Sample Conveyor 3.

Prototype requirements:
- retain the clean ISS/sheave-report Photographic Evidence Sheet look and engineering discipline;
- asset summary flows into evidence without unnecessary forced blank space;
- optional `System Context / Topology / Process Relationship` row;
- shared finding-level metadata once per technical story;
- multiple images per evidence sheet where appropriate;
- canonical evidence ID under every photo;
- legible captions and image detail;
- one `Observation / Engineering Assessment / Recommended Action` block per technical story where appropriate;
- deliberate page-break control so tables/images do not split badly;
- support full-width hero image, side-by-side portraits, stacked landscapes or 2x2 context grids according to evidence need.

Exit criterion: inspector approves evidence density, readability, metadata and visual hierarchy.

## Phase 5 — Rebuild Section 16 Across All Assets
Status: **PENDING PHASE 4**

Apply the approved module architecture to all 23 asset/evidence groups.

Key rule: one photograph does not automatically equal one page. One technical story should use the evidence density required to explain that story clearly.

Complex assets may contain multiple sub-stories, e.g.:
- Screens: water escape / corrosion / damaged supports;
- L1: belt contact / concrete deterioration / steel deterioration;
- CV09: cleaner geometry / wet consequence / active fallout;
- Sample Conveyor 3: mistracking / loading-vs-belt-width / containment loss;
- U4: mistracking / one-side product loss / custom cleaner.

Exit criterion: Section 16 contains the agreed evidence story with efficient page use and no loss of important detail.

## Phase 6 — Recommendation and Narrative Expansion
Status: **PENDING PHASE 5**

- Expand asset narratives where restored evidence supports additional engineering detail.
- Finalise global/systemic recommendation logic and asset-specific recommendations.
- Maintain distinction between immediate corrective action, verification task, design-development concept and final implementation recommendation.
- Ensure Section 19/20 conclusions trace directly to Section 16 evidence and the updated contextual source.
- Add conceptual drawings where they materially improve understanding, including CV09 and Sample Conveyor containment concepts.

Exit criterion: findings, engineering assessment, recommendations and conclusion form one consistent evidence-to-action chain.

## Phase 7 — Document-Wide Layout and Styling Polish
Status: **PENDING PHASE 6**

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

Exit criterion: report looks as polished and controlled as the prior ISS sheave-report series while retaining its own spillage-audit identity.

## Phase 8 — Engineering Review and Issue Closure
Status: **PENDING**

- Complete ratings / finding priorities only once suitable decision criteria are agreed.
- Resolve or explicitly carry forward outstanding measurements / inspections / structural reviews.
- Perform full technical consistency review.
- Perform full render/visual QA of every page.
- Produce final controlled Word/PDF issue package when approved.

## Current Hold Point
**Do not proceed into Phase 3 or modify V0.1 until Phase 1 context alignment is complete.**

All new engineering interpretations generated during the debate phase should first be captured in the contextual source and `report_running_notes.md`, then propagated into the formal report in a controlled later pass.
