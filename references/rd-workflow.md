# R&D And Design Controls Workflow

Use this workflow when the user asks for medical device R&D support, design control documentation, design review preparation, user needs, design inputs and outputs, verification and validation planning, DHF readiness, design transfer, sustaining engineering, or product development traceability.

## 1. R&D Scope Intake

Capture these fields when available:

- Device concept, device family, or product variant
- Intended purpose, indication, users, patient population, and use environment
- Device type: implant, reusable instrument, software, SaMD, diagnostic, active device, sterile device, combination product, or accessory
- Development phase: concept, feasibility, design input, prototype, verification, validation, transfer, launch, sustaining, or change control
- Target markets and quality/regulatory framework
- Materials, mechanism of action, body contact, duration of contact, sterility, software, electronics, packaging, or connectivity features
- Main clinical, usability, technical, manufacturability, and safety questions
- Available source documents: VOC, IFU, risk file, technical specs, CAD notes, test data, CER, complaint/PMS data, competitor evidence, standards, or meeting notes

If development phase is unclear, infer cautiously and state the assumption.

## 2. Source Inventory For R&D

Group sources by use:

- Voice of customer and user needs: interviews, surgeon feedback, workflow observations, complaints, PMS/PMCF, clinical literature, guidelines.
- Clinical and state-of-the-art evidence: CER literature, competitor papers, clinical outcomes, adverse event patterns, standard of care.
- Design definition: product requirements, design inputs, design outputs, drawings, material specs, software requirements, architecture, BOM, labeling, packaging.
- Risk and quality: risk analysis, FMEA, FTA, hazard analysis, usability risks, cybersecurity risks, biocompatibility, sterilization, shelf-life, process risks.
- Verification and validation: protocols, acceptance criteria, test methods, reports, traceability matrix, clinical simulations, usability studies.
- Transfer and lifecycle: manufacturing process, process validation, supplier controls, DMR, DHR, change orders, CAPA, complaints, post-market signals.

Record source reliability, version/date, owner, and whether the source is controlled, draft, public, or unverified.

## 3. User Needs And Design Inputs

Translate evidence into structured requirements.

User needs should describe what users, patients, or stakeholders need in the intended use context. They may be qualitative but must not become marketing claims.

Design inputs should be:

- Specific
- Measurable or verifiable
- Clinically or technically justified
- Traceable to user needs, risks, standards, or regulatory requirements
- Written without embedding the design solution unless the solution is fixed by the product concept

Flag vague inputs and propose measurable acceptance criteria only when the source supports them. If acceptance criteria are not available, mark them as "to be defined".

## 4. Design Outputs

Map design outputs to inputs. Outputs may include:

- Drawings and dimensions
- Material specifications
- Software requirements and architecture
- Algorithms and performance specifications
- Sterilization and packaging specifications
- Labeling and IFU content
- Manufacturing process specifications
- Inspection methods
- Risk control measures

Do not claim an output satisfies an input unless verification or rationale is available.

## 5. Risk Management Integration

Use clinical evidence and R&D evidence to support hazard identification and risk controls.

Consider:

- Biological, chemical, mechanical, electrical, software, usability, cybersecurity, sterility, packaging, and manufacturing hazards
- Event sequence, hazardous situation, harm, severity, probability, detectability when used locally, and risk acceptability
- Risk controls by design, protective measures, information for safety, and process controls
- Verification of risk control implementation
- Verification of risk control effectiveness
- Residual risk and benefit-risk support

For FMEA support, keep failure mode, cause, effect, control, detection, and action fields separate.

## 6. Verification And Validation

Keep verification and validation distinct.

Verification asks whether design outputs meet design inputs. It may use inspection, bench testing, analysis, software testing, biocompatibility testing, sterilization validation, packaging testing, or comparison to a justified previous design.

Validation asks whether the device meets user needs and intended use under actual or simulated use conditions. It may use usability validation, clinical simulation, cadaver or wet-lab evaluation, clinical investigation, PMCF, or representative user evaluation.

For each planned activity, define:

- Requirement or user need tested
- Test article or configuration
- Method
- Acceptance criteria
- Sample rationale
- Data to collect
- Responsible function
- Required report or record
- Open risks if the test fails or is not performed

Label early feasibility and exploratory tests separately from formal V&V.

## 7. Competitor And State-Of-The-Art For R&D

Use competitor and state-of-the-art evidence to inform:

- User needs
- Design constraints
- Feature tradeoffs
- Materials and degradation profile
- Clinical endpoints
- Known adverse events
- Benchmark performance
- Usability and workflow risks
- Claims that need evidence

Avoid copying competitor claims into requirements unless they are supported by independent evidence or a documented product strategy.

## 8. DHF Readiness Gap Check

Check whether the workpack has:

- Design and development plan or phase assumption
- User needs
- Design inputs
- Design outputs
- Risk management links
- Design review records or planned review questions
- Verification protocols and reports
- Validation protocols and reports
- Traceability matrix
- Design transfer considerations
- Design change rationale when relevant

Report missing items as gaps, not as completed records.

## 9. Typical Deliverables

Depending on the request, produce one or more of:

- R&D source inventory
- User needs table
- Design input table
- Design output map
- Requirements traceability matrix
- Risk-to-requirement traceability table
- Verification and validation plan outline
- Design review question list
- DHF gap register
- Sustaining engineering change impact assessment
- R&D section for a technical documentation file

Use the schemas in `output-templates.md` when a table is useful.
