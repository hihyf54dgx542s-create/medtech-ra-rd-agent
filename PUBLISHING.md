# Publishing To GitHub

## 1. Review The Skill

Check that the skill contains no private, confidential, company, patient, or unpublished product information.

Files to review:

- `SKILL.md`
- `README.md`
- `references/cer-workflow.md`
- `references/rd-workflow.md`
- `references/output-templates.md`
- `references/regulatory-checkpoints.md`
- `SANITIZATION.md`

Search specifically for:

- Employer, internship company, client, hospital, physician, and supplier names
- Product trade names, unreleased device names, internal project codenames, and UDI/catalog references
- Patient, complaint, PMS, PMCF, CAPA, vigilance, and adverse event details from non-public sources
- Internal document titles, template language, screenshots, file paths, author metadata, and version histories
- Examples that are too close to real internship work, even if the names are removed

## 2. Choose Visibility

Use a private GitHub repository if the skill is still experimental or tied to internship/company workflows.

Use a public repository only if the content is generic, does not include confidential examples, and you are comfortable with others reading it.

## 3. Choose A License

Recommended options:

- MIT: simple, permissive, common for small open-source projects.
- Apache-2.0: permissive, includes explicit patent language.
- No license: others may view the code but do not receive clear reuse rights.

Do not copy proprietary templates, company documents, or paid database content into the repository.

## 4. Create The Repository Locally

From the parent folder:

```bash
cd path/to/cer-evidence-agent
git init
git add .
git commit -m "Initial medical device evidence and R&D agent skill"
```

## 5. Create A GitHub Repository

On GitHub:

1. Click New repository.
2. Name it `cer-evidence-agent`.
3. Choose Public or Private.
4. Do not initialize with README if this folder already has one.
5. Create repository.

## 6. Push To GitHub

Replace `YOUR-USERNAME` with your GitHub username:

```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/cer-evidence-agent.git
git push -u origin main
```

## 7. Suggested Repository Topics

Add these topics on GitHub:

```text
codex-skill
clinical-evaluation
medical-device
cer
regulatory-affairs
evidence-synthesis
medical-device-rd
design-controls
dhf
verification-validation
```

## 8. First Release

After the first push, create a GitHub release:

- Tag: `v0.1.0`
- Title: `Initial Medical Device Evidence and R&D Agent skill`
- Notes: `Initial version with CER workflow, R&D design-control workflow, output templates, and regulatory checkpoints.`
