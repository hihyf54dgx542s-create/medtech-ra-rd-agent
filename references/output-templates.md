# Output Templates

Use these schemas when the user asks for tables, workpacks, or CER drafting support. Adapt column names to the device and source package.

## Source Inventory

| Source ID | Source title | Type | Year or date | Region | Relevance | Key information available | Limitations |
|---|---|---|---|---|---|---|---|

## Literature Search Strategy

| Element | Content |
|---|---|
| Objective | |
| Database | |
| Device or intervention terms | |
| Indication terms | |
| Comparator terms | |
| Outcome terms | |
| Safety terms | |
| Proposed Boolean string | |
| Inclusion criteria | |
| Exclusion criteria | |
| Screening notes | |

## Evidence Extraction Table

| Source ID | Study or source | Population | Device or comparator | Design | Sample size | Follow-up | Endpoints | Clinical benefits | Adverse events | Key results | Limitations | Relevance to CER |
|---|---|---|---|---|---:|---|---|---|---|---|---|---|

## Adverse Event Table

| Source ID | Event | Count or rate | Seriousness | Relatedness | Timing | Management or outcome | Comparator context | CER interpretation |
|---|---|---:|---|---|---|---|---|---|

Relatedness values should remain conservative: device-related, procedure-related, disease-related, unrelated, unclear, or not reported.

## Clinical Benefit Table

| Benefit category | Evidence source | Outcome measure | Result | Patient or clinical relevance | Strength of evidence | Limitations |
|---|---|---|---|---|---|---|

Benefit categories may include symptom relief, anatomical repair, reduced complication risk, reduced procedure burden, quality of life, functional outcome, or health-system benefit.

## Comparator Matrix

| Attribute | Subject device | Comparator 1 | Comparator 2 | Interpretation |
|---|---|---|---|---|
| Intended purpose | | | | |
| Indication and population | | | | |
| Material or technology | | | | |
| Mode of action | | | | |
| Contact duration and site | | | | |
| Clinical benefits | | | | |
| Adverse events | | | | |
| Evidence maturity | | | | |
| Residual risks | | | | |

## Benefit-Risk Draft

Use this structure for prose:

```text
The available evidence indicates that [device/device type] may provide [benefits] for [population/indication], based on [source types]. The main clinical benefits identified were [benefit 1], [benefit 2], and [benefit 3].

The principal risks identified were [risk/adverse event categories]. Reported adverse events included [events], with [frequency/severity] where available. Attribution was [device-related/procedure-related/unclear] based on the available sources.

Compared with [comparators/standard of care], the evidence suggests [balanced comparison]. However, the conclusion is limited by [limitations].

Overall, the benefit-risk profile appears [draft assessment] for reviewer consideration, provided that [risk controls/PMCF/PMS/follow-up actions] are maintained or addressed.
```

## Evidence Gap Register

| Gap ID | Gap | Why it matters | Risk level | Recommended action | Owner or next source |
|---|---|---|---|---|---|

Risk level should be low, medium, high, or critical. Use critical only when the gap could block the intended regulatory conclusion.

## R&D Source Inventory

| Source ID | Source title | Source type | Version or date | Controlled status | R&D use | Key content | Limitations |
|---|---|---|---|---|---|---|---|

## User Needs Table

| Need ID | User or stakeholder | Use context | User need | Source | Related risks | Notes |
|---|---|---|---|---|---|---|

## Design Input Table

| Input ID | Design input | Rationale | Source or user need | Acceptance criteria | Verification method | Risk link | Status |
|---|---|---|---|---|---|---|---|

Status values should be draft, defined, under review, verified, changed, or requires definition.

## Design Output Map

| Output ID | Design output | Output type | Linked design input | Document or record | Verification evidence | Open issue |
|---|---|---|---|---|---|---|

Output type may include drawing, specification, software requirement, algorithm design, material specification, labeling, packaging, manufacturing process, inspection method, or risk control.

## Requirements Traceability Matrix

| User need | Design input | Design output | Risk control | Verification | Validation | Evidence status |
|---|---|---|---|---|---|---|

Evidence status should make gaps visible: complete, partial, missing, planned, not applicable, or requires review.

## Verification And Validation Plan Outline

| V&V ID | Type | Requirement or need | Method | Test article | Acceptance criteria | Sample rationale | Output record | Open risk |
|---|---|---|---|---|---|---|---|---|

Type should be verification, validation, exploratory, process validation, software verification, usability validation, clinical validation, or not yet classified.

## Risk-To-Requirement Traceability

| Hazard or failure mode | Harm or effect | Risk control | Related design input | Verification of implementation | Verification of effectiveness | Residual risk note |
|---|---|---|---|---|---|---|

## Design Review Questions

| Review area | Question | Evidence expected | Owner | Decision needed |
|---|---|---|---|---|

## DHF Gap Register

| Gap ID | DHF area | Gap | Why it matters | Risk level | Recommended action | Evidence needed |
|---|---|---|---|---|---|---|
