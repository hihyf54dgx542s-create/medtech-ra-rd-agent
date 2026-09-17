# Medical Device Evidence And R&D Agent

Medical Device Evidence And R&D Agent is a Codex skill for preparing traceable clinical evaluation and product development workpacks for medical devices. It supports CER/CEAR evidence, literature search strategy, clinical benefit extraction, adverse event analysis, comparator analysis, benefit-risk reasoning, user needs, design inputs and outputs, verification and validation planning, risk traceability, DHF readiness, and regulatory-style gap review.

This skill is designed for reviewer-ready evidence preparation and R&D documentation support, not for unsupported final regulatory, quality-system, or engineering release decisions. Human review remains required.

## What It Helps With

- Building reproducible literature search strategies
- Screening clinical evidence using PICO or PICOS logic
- Extracting clinical benefits, safety outcomes, and adverse events
- Comparing competitor devices, alternative materials, or standard of care
- Drafting benefit-risk reasoning from structured evidence
- Checking common MDR, MDCG, ASEAN CSDT, FDA public evidence, PMCF, and equivalence gaps
- Translating clinical, user, competitor, and risk evidence into user needs and design inputs
- Mapping design inputs to outputs, risk controls, verification, validation, and DHF gaps
- Preparing V&V plan outlines, design review questions, and requirements traceability matrices

## Skill Structure

```text
cer-evidence-agent/
|-- SKILL.md
|-- agents/
|   `-- openai.yaml
`-- references/
    |-- cer-workflow.md
    |-- rd-workflow.md
    |-- output-templates.md
    `-- regulatory-checkpoints.md
```

## Installation

Copy the `cer-evidence-agent` folder into your Codex skills directory:

```bash
~/.codex/skills/cer-evidence-agent
```

On Windows, this is usually:

```text
C:\Users\<your-user>\.codex\skills\cer-evidence-agent
```

Restart Codex or open a new session if the skill does not appear immediately.

## Example Usage

```text
Use $cer-evidence-agent to create a CER evidence workpack for an implantable soft-tissue repair device.
```

```text
Use $cer-evidence-agent to draft a PubMed search strategy and adverse event extraction table for a surgical implant CER.
```

```text
Use $cer-evidence-agent to review whether this CER benefit-risk section has MDR or MDCG-style evidence gaps.
```

```text
Use $cer-evidence-agent to turn these surgeon interview notes and clinical risks into user needs, design inputs, and a V&V planning matrix.
```

```text
Use $cer-evidence-agent to prepare a DHF readiness gap review for this medical device development project.
```

## Important Boundaries

- Do not treat the skill output as final regulatory, legal, or medical advice.
- Do not treat the skill output as released design control records without qualified review and document control.
- Verify all cited studies, adverse event rates, comparator claims, and regulatory requirements before submission.
- Do not claim device equivalence unless clinical, technical, and biological evidence support it.
- Do not claim verification, validation, design transfer, or DHF completion unless controlled evidence supports it.
- Keep source traceability for every claim used in a CER, CEAR, design review, or R&D workpack.

## Public Repository Sanitization

Before publishing, remove company names, unreleased product names, internal document titles, patient or complaint data, screenshots, source file paths, and examples copied from internship or employer materials. Keep examples generic, such as "implantable soft-tissue repair device" or "software medical device", unless the example is fully public and independently sourced.

## License

Add a license before publishing if you want others to reuse the skill. MIT is simple and permissive; Apache-2.0 is also permissive and includes an explicit patent grant. If you do not add a license, others can view the repository but do not automatically receive reuse rights.
