# South32 Wessels Combined Product Spillage Audit — Phase 7 Front-End Refinement Draft V0.1

## Status
**REPORT-READY CONTENT DRAFT — PASS 7A**

## Purpose
This draft refines the opening reader journey for the inspector-approved V0.2 report architecture. It covers:

- Part I — Why the Audit Was Undertaken;
- Part II — Understanding the Material-Handling System;
- Part III — What the Audit Found.

The intent is to make the opening tighter, more authoritative and easier to follow without changing the accepted report identity or introducing unsupported technical certainty.

Governing rhythm:

> **Explain → Prove → Interpret → Act / Transition**

The front end should give management the complete engineering story once, then hand the reader into the detailed mechanism/evidence chapters without repeating the same full conclusion at every transition.

---

# PART I — WHY THE AUDIT WAS UNDERTAKEN

## 1. Executive Summary

Combined-product spillage was observed at multiple locations across the inspected Wessels Mine material-handling route, extending from the underground crusher and conveyor system through the surface screening plant and loading station. The audit was undertaken to determine whether these deposits represented isolated housekeeping problems or whether they reflected broader failures of material containment within the connected handling process.

The consolidated inspection and evidence review indicates that the observed condition is **not attributable to one universal cause**. Several mechanisms operate across the system and, in some locations, interact. The dominant recurring pattern is fines carryback: residual material remains on the belt after discharge and is progressively redistributed from the return belt onto conveyor structures and surrounding areas. Separate local mechanisms include coarse/mixed-product loss during transit, belt mistracking and alignment-related loss of carrying margin, loading and side-containment limitations, process-water escape within the screening area, and event-driven material removal associated with conveyor trip/restart preparation.

A central finding of the audit is that **the point at which spilled material is observed is not necessarily the point at which the initiating failure occurred**. Carryback can detach progressively downstream of the original discharge; water can transport fines away from the point of escape; mistracking can develop before product leaves the carrying belt; and product removed during trip/restart preparation can be deposited away from the event that initiated the unloading requirement. The visible deposit must therefore be interpreted as evidence of a material-loss process rather than automatically as proof of a defect at the exact deposit location.

The combined evidence supports a broader engineering conclusion: the recurring problem is fundamentally one of **material and process containment**, not simply plant cleanliness. Housekeeping remains necessary to restore access and operating condition, but repeated removal of accumulated material does not by itself correct the mechanism that caused the material to leave the intended process path.

The higher-order control objective is therefore to:

> **Keep the combined product — fines and coarse/lump ore — within the intended process/material-handling envelope throughout transit, using the control mechanism appropriate to the failure mode and local geometry.**

In practical terms, this means:

- remove fines/carryback effectively while ensuring the removed material remains inside the intended process stream;
- retain coarse/lump product within the usable belt carrying envelope through appropriate feed control, belt tracking and location-specific containment;
- retain transferred material within the intended chute/process envelope;
- retain process water and entrained fines within the screening/washing process;
- control and recover material removed during trip/restart preparation through defined operating arrangements;
- use housekeeping as a supporting consequence-control measure rather than the primary response to recurring source-generated spillage.

The audit identified **CV09** as the preferred pilot location for developing and proving the cleaner-and-containment function. CV09 is important because it demonstrates that belt cleaning alone is not sufficient: material removed from the belt must also remain within the intended process stream. The pilot should therefore be used to prove the required function under representative service conditions before wider applicability is assessed. This is not a recommendation to install identical hardware at every conveyor; the function should be standardised and the physical solution adapted to local geometry and service conditions.

Separate targeted engineering actions are required where different mechanisms have been identified:

- **U4 Tripper Car:** quantify and correct the relevant alignment/tracking geometry and prove centred tracking through representative operation and full tripper travel;
- **Sample Conveyor 3:** verify feed, quantify the visually supported lateral offset/mistracking and correct primary contributors before finalising secondary containment;
- **Sample Conveyor 2:** verify feed quantity/product size relative to usable belt width before attributing the condition to mistracking or finalising side containment;
- **W10:** investigate initiating contributors and the normal belt operating envelope before developing any local side-containment barrier as a secondary control;
- **Screens:** identify the actual process-water escape mechanism during safe access/shutdown conditions and separately complete competent structural assessment of the damaged/corroded support members;
- **L1:** complete competent structural assessment and verify representative belt tracking/clearance while preserving the distinction between proven previous/intermittent contact and unproven continuous present contact;
- **trip/restart and housekeeping:** confirm controlled material-removal, temporary placement, recovery and responsibility arrangements so operationally generated deposits are managed separately from chronic source loss.

The principal recommended programme is therefore to move from **repeated consequence management toward verified source control and process containment**. Corrective actions should not be regarded as complete merely because equipment has been repaired, a barrier has been installed or accumulated material has been removed. Close-out should demonstrate, at a level appropriate to the action, that the relevant material-loss mechanism has been controlled under representative operating conditions and that the intervention has not introduced an unacceptable new operating, maintenance or safety condition.

### Executive takeaway

> **The inspected system does not present one spillage defect or a collection of unrelated housekeeping problems. It presents several material-containment mechanisms that require one coherent control philosophy and different location-specific engineering responses.**

---

## 1.1 Executive Action Dashboard

| Theme / priority | What the evidence currently establishes | Immediate engineering direction |
|---|---|---|
| Fines / carryback | Recurring cross-system condition supported across multiple underground and surface conveyors | Prove improved cleaner + containment function at CV09, then assess wider applicability by function rather than identical hardware |
| Coarse / mixed-product containment | Local loss from the carrying envelope is established at W10 and the Sample Conveyors; mechanisms differ by location | Verify feed, tracking and local geometry before final secondary-containment design |
| Belt tracking / alignment | U4 mistracking and one-side loss are visually verified; Sample 3 offset/mistracking is supported but unmeasured; L3 remains a verification case | Measure, correct where required and prove representative operating tracking before close-out |
| Screen water containment | Active water escape is verified; exact equipment-level mechanism remains unresolved | Safe-shutdown mechanism investigation before detailed containment modification |
| Structural condition | Screen support damage/corrosion and L1 deterioration are verified; remaining capacity is not established by photographs | Competent structural assessment and controlled repair/replacement definition |
| Trip/restart + housekeeping | Event-driven unloading and reactive cleaning are operational consequence controls | Confirm procedures, responsibilities, controlled temporary placement/recovery and retain source correction as the long-term priority |

The dashboard is intentionally high level. Detailed evidence, qualifications and acceptance criteria remain in the relevant narrative sections, case studies and technical registers.

---

## 2. Purpose and Objectives

The purpose of this audit is to provide a mechanism-focused engineering assessment of combined-product spillage across the selected Wessels Mine material-handling areas and to translate the consolidated evidence into practical corrective and verification actions.

The audit is intended to determine:

- what material is being lost and where the loss becomes visible;
- the immediate mechanism associated with the observed condition;
- which contributing conditions or probable causes are supported by the available inspection record;
- which mechanisms recur across the conveyor ecosystem and which remain local to individual assets;
- where the available evidence is sufficient for corrective action and where measurement, shutdown inspection, structural assessment or detailed design is still required;
- what engineering, maintenance and operational controls are appropriate to the mechanism identified;
- how corrective actions should be verified before being regarded as closed.

The assessment is qualitative and mechanism-focused. It is **not intended to calculate total spillage tonnage or volume from the photographic record**, and it does not introduce unverified numerical limits where no project-, mine- or OEM-specific criteria were supplied.

The report therefore places greater weight on **mechanism, evidence strength, qualification and corrective logic** than on unsupported quantification of the visible deposits.

---

## 3. Scope of the Audit

The inspected assets are treated as one connected material-handling journey rather than as a collection of unrelated conveyors. This is necessary because material lost at one stage may become visible further downstream.

### 3.1 Underground material route

- Underground Crusher;
- UC05 / UC04 / UC03 / UC02 / UC01 — treated as one logical continuous conveyor transport route;
- U3 Conveyor;
- U4 Conveyor — Tripper Car;
- U5A Conveyor;
- U5B Conveyor.

### 3.2 Surface screening and transfer route

- W10 Conveyor — Primary Feed;
- CV01;
- CV02;
- CV03;
- CV04;
- CV06;
- CV09;
- CV14;
- CV15;
- Screens / screen-chute assemblies.

The report does not integrate CV05, CV07, CV08, CV10, CV11, CV12 or CV13 into the controlled audit findings.

### 3.3 Loading Station

- L1 Conveyor — Primary Feed;
- L2 Conveyor;
- L3 Conveyor;
- L4 Conveyor;
- Sample Conveyor 1;
- Sample Conveyor 2;
- Sample Conveyor 3.

The detailed evidence registers retain asset-level traceability, while the body narrative groups the assets according to the engineering mechanism they help demonstrate.

---

## 4. Methodology, Evidence Basis and Limitations

The audit combines direct site inspection records, photographic evidence, video evidence, completed questionnaire/context records and subsequent controlled visual review. The evidence set comprises **23 controlled evidence groups and 197 media files**, all of which have completed the controlled visual-review process.

The report distinguishes between:

- **direct visual evidence** — a photograph or video independently demonstrating the stated physical condition;
- **supporting/context evidence** — evidence that establishes location, extent or operating context without independently proving the complete causal statement;
- **source-recorded inspection information** — conditions recorded during the inspection that may not be independently measurable from the supplied media;
- **engineering interpretation** — conclusions drawn from the combined evidence within the stated limitations;
- **working/conceptual engineering options** — possible corrective arrangements that remain subject to measurement, feasibility review and detailed design.

This distinction is fundamental to the report. A photograph may prove that a component is damaged without proving its dynamic operating state; a visible offset may support a tracking concern without quantifying the offset; a structural defect may be obvious without allowing remaining capacity to be calculated from the image alone.

### Principal interpretation limitations

The following boundaries remain applicable unless later measurement or investigation resolves them:

- total spillage mass/volume was not measured;
- not every belt cleaner/discharge chute was directly accessible, so similar cleaner deficiencies at inaccessible locations remain inference pending local verification;
- formal maintenance schedules, cleaner replacement criteria, maintenance histories and applicable OEM cleaner standards were not reviewed as part of the supplied source set;
- Sample Conveyor 2 significant mistracking remains unconfirmed;
- Sample Conveyor 3 lateral offset/mistracking is visually supported but unmeasured;
- L3 offset is supported, but a direct causal chain to significant solid-product loss remains unconfirmed;
- U4 mistracking and one-sided product loss are visually verified, while the magnitude of the source-recorded tail-pulley/alignment condition remains unquantified;
- active screen water escape is verified, while the exact equipment-level escape mechanism remains unresolved;
- cut/notched screen supports are verified, while the reason for the modifications and the remaining structural capacity remain unresolved;
- L1 previous/intermittent belt contact is supported, while continuous current contact is not proven;
- structural remaining capacity cannot be established from photographs and requires competent assessment;
- no unsupported dimension, alignment tolerance, feed rate, structural capacity or project/OEM limit is to be inferred from the evidence.

The remaining uncertainties are therefore primarily **engineering verification, measurement, design-development and competent-assessment items**, rather than gaps in the controlled media review.

---

# PART II — UNDERSTANDING THE MATERIAL-HANDLING SYSTEM

## 5. The Material Journey

The inspected system transports **combined product** comprising coarse/lump ore together with fines through successive underground, surface screening and loading stages. Fines are already present in the material stream and may be further generated during crushing and handling. In the screening process, water is also deliberately introduced to support washing and separation.

The presence of fines is therefore not, by itself, a defect. The engineering problem arises when part of the conveyed material or process water **leaves the intended handling envelope before reaching the stage designed to receive, transfer, separate or recover it**.

From the underground crusher onward, each conveyor and transfer point performs part of one connected transport function. The process is intended to:

- keep coarse and fine material on the carrying belt until the intended transfer/discharge;
- control the trajectory through transfer/chute interfaces;
- remove residual carryback at appropriate discharge locations;
- keep material removed by belt cleaners within the intended process stream;
- retain process water and entrained fines within the screening/washing system;
- manage unavoidable operational material removal in a controlled and recoverable manner.

This system view is important because a deposit observed beneath one conveyor may be the downstream consequence of an earlier discharge or containment failure. Treating every deposit as an isolated local housekeeping problem would therefore risk correcting the consequence while leaving the initiating mechanism active.

### Reader takeaway

> **The audit concerns loss of control of the product/process stream during transit — not the mere presence of fines, lump ore or water within a material-handling plant.**

---

## 6. Central Audit Principle — Spillage Location Is Not Always Cause Location

A principal finding of the audit is that the physical location of accumulated material must not automatically be treated as the location of the initiating failure.

Several mechanisms can separate the **cause location** from the **deposit location**:

- **carryback:** residual fines remain on the belt after discharge and detach progressively along the return route;
- **wet fines / slurry:** escaping water or wet material can move fines away from the point at which containment was first lost;
- **mistracking:** a belt can move laterally before material finally leaves the usable carrying envelope at another position;
- **trip/restart unloading:** product can be intentionally removed from a loaded belt and placed at a secondary location while restart conditions are being restored.

For this reason, each significant finding should be interpreted through the same engineering sequence:

> **Observed deposit → material type → immediate mechanism → contributing condition → initiating cause → consequence → control.**

Not every step in that sequence is proven at every location. Where the initiating cause remains unresolved, the report retains it as a verification item rather than promoting a working hypothesis into a confirmed fact.

This distinction also explains why the report prioritises **source control**. Cleaning the point at which the material finally accumulates may restore access, but it may have little effect on recurrence if the initiating material-loss mechanism is elsewhere.

---

# PART III — WHAT THE AUDIT FOUND

## 7. The Overall Spillage Picture

The audit did not identify one uniform plant-wide condition. It identified **three recurring material/process-loss families together with one event-driven operational mechanism**:

1. **Fines / carryback** — residual material remains on the belt after discharge and is redistributed progressively along the return path;
2. **Coarse or mixed combined-product loss during transit** — material leaves the carrying envelope because of location-specific feed, tracking, geometry, transfer or lateral-containment conditions;
3. **Water-related escape / wet fines / slurry** — process water leaves the intended screen/chute envelope and can transport fines into surrounding areas;
4. **Trip/restart and manual unloading events** — product is temporarily removed as an operational requirement and can become secondary spillage if placement/recovery is not controlled.

These mechanisms overlap in consequence but require different controls.

### 7.1 Systemic recurring theme — fines / carryback

Recurring fines accumulation across multiple underground and surface conveyors supports a system-level carryback problem. The significance is not that every deposit has been proven to arise from an identical cleaner defect. Rather, the evidence demonstrates that residual fines are not consistently being removed and contained at all relevant discharge interfaces, allowing material to remain on return belts and be redistributed downstream.

CV06 and CV09 provide two different direct case examples that help explain the wider control problem:

- CV06 demonstrates loss of cleaner function through compromised/missing cleaner components;
- CV09 demonstrates that material removal from the belt is not sufficient if the removed wet fines can still escape the intended discharge containment.

Together, these cases support the system-level requirement to treat **belt cleaning and containment of the removed material as one material-control function**.

### 7.2 Local coarse / mixed-product containment mechanisms

Coarse-product loss cannot be explained by return-side carryback and must be assessed through local carrying-belt conditions.

The principal cases are deliberately not treated as identical:

- **W10** demonstrates material loss into a restricted tunnel/access zone, while the exact initiating contributor for every deposit remains unresolved;
- **Sample Conveyor 2** demonstrates a confirmed loading/product-size-versus-usable-width containment concern, without sufficient evidence to promote significant mistracking to fact;
- **Sample Conveyor 3** demonstrates the same broad loading/containment concern with additional visually supported lateral offset/mistracking;
- **U4** provides the strongest local tracking/product-loss case, with visually verified mistracking and concentrated one-sided product-loss consequence.

The engineering response must therefore follow the local evidence rather than applying one universal side-containment or alignment solution.

### 7.3 Process-water loss and structural consequences

At the Screens, active process-water escape is directly verified by dynamic evidence. The equipment-level escape mechanism was not safely established during the inspection and therefore requires close shutdown investigation before detailed modification is specified.

The same area also contains damaged/cut/corroded structural members. Their condition is directly verified, but the reason for the cut-outs and the remaining structural capacity are unresolved. Water containment and structural adequacy are therefore related in plant context but remain **separate engineering workstreams**.

L1 similarly combines extensive accumulation, evidence of previous/intermittent belt interaction and serious structural deterioration. These findings are connected by location and consequence, but the report must retain the distinction between what is physically proven and what requires structural or mechanical verification.

### 7.4 Event-driven and operational spillage

Trip/restart product removal represents a different mechanism from chronic carryback or local conveyor leakage. It is an operational response to a loaded conveyor condition and must therefore be controlled through responsibility, temporary placement, recovery and reintroduction arrangements.

Housekeeping remains necessary across all mechanism types, but its role is different from source correction:

> **Housekeeping controls the consequence. Source control should reduce the recurrence.**

### Transition to the detailed mechanism chapters

The remainder of the report follows these mechanism families in turn. It first examines recurring fines/carryback and the cleaner-containment function; then coarse-product transport and local lateral containment; then alignment/tracking cases; then water/structural consequences and operationally generated spillage. Selected asset evidence is used to **prove and qualify the mechanism story**, while the complete controlled evidence record remains available through the technical appendices and registers.
