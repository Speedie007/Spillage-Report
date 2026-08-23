# Spillage Report — Running Working Notes

## Working Status
- Repository: `Speedie007/Spillage-Report`
- Branch: `main`
- Primary contextual source: `Context/Running_Report_Contextual_Spillage_NotesV3.docx`
- Questionnaire source records: `Context/Questionaires/Running_Report_Contextual_Spillage_Questionnaire_ResponseV1.docx` and `Context/Questionaires/Running_Report_Contextual_Spillage_Questionnaire_ResponseV2.docx`
- Report baseline template: `Report-Template/ISS_Sheave_Inspection_Report_Master_Template_v2.1_Polished.docx`
- Evidence root: `Evidence/`
- Evidence register: `Report-Working/evidence_index.md`

## Current Development Stage
The contextual investigation and Questionnaire V1/V2 integration are substantially complete. The repository-level evidence inventory is now complete: 23 evidence groups containing 197 media files (189 photographs and 8 videos) are registered in `evidence_index.md`. The next phase is the section-by-section visual evidence review, followed by adaptation of the existing sheave-report template for the combined-product spillage report and preparation of the first populated working draft.

## Evidence Handling Rules
- Preserve original evidence files at full resolution; do not overwrite or recompress master evidence.
- Treat the reference identifier used in the contextual notes (for example `CV09-REF-003`) as the canonical evidence ID.
- Where repository filename spelling/case differs from the canonical reference, record the mapping in `Report-Working/evidence_index.md` rather than silently changing the evidence identity.
- Distinguish direct visual evidence, reported information, engineering interpretation, and unverified hypotheses.
- Only report conclusions that are supported by the contextual notes and/or inspected evidence.
- Report-ready image copies may be resized/compressed later after final image selection; the repository originals remain the master evidence.

## Known Filename / Evidence Mapping Items
- U4 video naming has been corrected: repository file is now `Evidence/Underground/U4-Tripper/UGU4-REF-010.MP4`, matching the canonical contextual reference `UGU4-REF-010`.
- CV09 video filenames use mixed case (`Cv09-Ref-006.mp4`, `Cv09-Ref-007.mp4`, `Cv09-Ref-008.mp4`); canonical report references remain `CV09-REF-006` through `CV09-REF-008`. The evidence index records the mapping.
- `LoadoutStationL2-REF-005` exists as both a `.jpg` and `.mp4`. Until deliberately renumbered, any citation must distinguish the media type / exact path.
- Additional U4 cleaner evidence identified in Questionnaire V2: `UGU4-REF-011` and `UGU4-REF-012`.

## Important Engineering Qualification Rules
- Similar scraper-design deficiencies at conveyors not directly inspected remain an engineering inference based on common discharge geometry and common carryback behaviour; they are not to be stated as directly observed defects at every conveyor.
- Sample Conveyor 2 mistracking remains unconfirmed and requires verification.
- Sample Conveyor 3 severe lateral offset is visually evident, but approximate percentage loss of usable belt width remains a visual estimate unless measured.
- L3 tail-end offset/mistracking is observed; its direct causal contribution to current spillage remains to be confirmed.
- Screen water leakage is directly observed during normal operation; the exact equipment-level cause remains unconfirmed because close inspection during operation was not possible.
- Cut/damaged screen supports are directly observed; the reason for the cuts remains unconfirmed and any installation-clearance explanation is a working hypothesis only.

## Evidence Inventory Status
- Evidence groups: **23**
- Total media files: **197**
- Photographs: **189**
- Videos: **8**
- File inventory: **COMPLETE**
- Visual evidence classification: **PENDING**
- Report image selection / captions: **PENDING**

## Next Planned Work
1. Review visual evidence section-by-section, prioritising CV06, CV09, Sample Conveyors 2 and 3, Screens, L1 and U4 Tripper Car.
2. Cross-check each evidence reference against Contextual Notes V3 and update `evidence_index.md` with Direct / Supporting / Context-only classification.
3. Select the strongest report photographs and draft evidence-based captions.
4. Review and adapt the sheave report template for the new report structure.
5. Build the first populated working report draft using the contextual notes and selected evidence.
6. Develop the proposed CV09 scraper/chute and Sample Conveyor side-skirt contextual illustrations after reviewing the actual equipment geometry.

## Repository Write / Inventory Milestones
- GitHub write access confirmed by successful update of this file on 2026-08-23.
- U4 video filename normalised to `UGU4-REF-010.MP4` in commit `c2f1ca40b18fac8d7f0c8fbb649992f4063102fe`.
- Initial evidence inventory populated in `evidence_index.md` in commit `eb3bbf52d6f1a421e1d4c2fd4d9f63e557467249`.
