# CER Evidence Workflow

Use this workflow for a complete clinical evaluation evidence workpack or any substantial part of one.

## 1. Scope Intake

Capture these fields before analysis when available:

- Device name and variants
- Manufacturer or project owner
- Device type and risk class
- Intended purpose, indication, target population, anatomical site, and user group
- Materials, mode of action, duration of contact, and body contact type
- Target market or regulatory framework
- Comparator devices, alternative materials, standard of care, or legacy device
- Source package available from the user

If any critical field is missing, continue with a stated assumption unless the output would be misleading.

## 2. Source Inventory

Group sources by type:

- Product documents: IFU, device description, risk management report, biological evaluation, technical specifications, labeling.
- Clinical evidence: published literature, clinical investigation reports, PMCF/PMS reports, registries, complaints, vigilance data.
- Competitor and alternative evidence: competitor IFUs, public summaries, 510(k) summaries, clinical papers, guidelines, standard therapy references.
- Regulatory references: MDR, MDCG guidance, ASEAN CSDT, FDA public databases, local authority guidance.

For each source, record title, year/date, source type, reliability, relevance, and what questions it can answer.

## 3. Search Strategy

For literature search tasks, create a search protocol before extracting conclusions.

Include:

- Database: PubMed, ClinicalTrials.gov, FDA databases, regional registration databases, or user-specified sources.
- Core concepts: device type, material, indication, procedure, comparator, adverse events.
- MeSH terms where useful.
- Free-text synonyms and spelling variants.
- Boolean search string.
- Inclusion and exclusion criteria.
- Screening fields.

Example search structure:

```text
("implantable surgical device" OR "soft-tissue repair device" OR "surgical implant")
AND
("repair" OR reconstruction OR reinforcement)
AND
("clinical outcome" OR complication OR infection OR "cerebrospinal fluid leak")
```

Do not claim a search was performed unless a tool or supplied search result confirms it. If only drafting a strategy, label it as a proposed strategy.

## 4. Screening

Screen sources against the CER purpose.

Common inclusion criteria:

- Same or similar intended purpose
- Same anatomical site or clinically relevant adjacent use
- Same or comparable material or mode of action
- Human clinical data when available
- Outcomes relevant to clinical benefit, performance, or safety

Common exclusion criteria:

- Animal-only or bench-only evidence when clinical evidence is required
- Unrelated material, indication, or procedure
- Non-systematic opinion without extractable data
- Duplicates or superseded reports

Record exclusion reasons. Do not silently discard evidence.

## 5. Evidence Extraction

Extract before interpreting. Use the evidence table schema in `output-templates.md`.

Prioritize:

- Study design and evidence level
- Sample size and population
- Device, material, comparator, and procedure
- Follow-up duration
- Clinical endpoints
- Performance outcomes
- Safety outcomes and adverse events
- Statistical findings and limitations
- Relevance to the subject device

For adverse events, capture event name, count/rate, seriousness, relatedness, timing, management, and outcome when available.

## 6. Comparator And Alternative Analysis

Comparator analysis should include:

- Direct competitor devices when available
- Alternative materials or technologies
- Standard clinical practice
- No-treatment or conservative treatment only when clinically relevant

Compare:

- Intended use and indication
- Material and degradation profile
- Mechanism or mode of action
- Contact duration and anatomical site
- Clinical performance endpoints
- Adverse event profile
- Usability or procedural burden
- Evidence maturity and follow-up

Avoid saying the subject device is better unless evidence directly supports the comparison.

## 7. Benefit-Risk Reasoning

Structure benefit-risk reasoning as:

1. Clinical need and current treatment context
2. Demonstrated or reasonably supported clinical benefits
3. Known and foreseeable risks
4. Frequency and severity of adverse events
5. Risk controls and residual risk evidence
6. Comparison with alternative therapies or competitor devices
7. Evidence limitations
8. Draft conclusion for reviewer consideration

Use conservative language when evidence is indirect, low quality, or based on analogous devices.

## 8. Gap Check

Before final output, check for:

- Claims without source locators
- Missing comparator or alternative therapy discussion
- Benefit-risk conclusion based only on product claims
- Adverse events not grouped by relatedness or seriousness
- Literature search missing synonyms or MeSH terms
- No inclusion/exclusion criteria
- Equivalence claim missing clinical, technical, or biological support
- PMCF/PMS gap not acknowledged
- Terminology inconsistency across device names, materials, and endpoints

Report gaps as actionable next steps.
