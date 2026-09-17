# Sanitization Checklist

Use this checklist before publishing the skill publicly.

## Remove Or Generalize

- Employer, internship company, client, hospital, physician, supplier, and reviewer names
- Product trade names, unreleased product names, internal codenames, catalog numbers, UDI values, batch numbers, and project IDs
- Patient, complaint, PMS, PMCF, CAPA, vigilance, adverse event, or clinical investigation details from non-public sources
- Internal document names, file paths, screenshots, tracked comments, author metadata, and version histories
- Exact wording copied from company templates, IFUs, risk files, protocols, CERs, CSDT files, test reports, or design-control procedures
- Examples that are so specific they could reveal the internship project even after names are removed

## Keep

- Generic medical device workflow concepts
- Public regulatory terms such as CER, PMCF, DHF, design inputs, verification, validation, and risk management
- Generic device categories such as implantable surgical device, software medical device, diagnostic device, reusable instrument, or sterile accessory
- Original templates written from scratch for public educational use

## Safer Example Style

Prefer:

```text
implantable soft-tissue repair device
software medical device
sterile single-use accessory
reusable surgical instrument
diagnostic monitoring device
```

Avoid:

```text
specific employer product names
unreleased trade names
exact indications from internal projects
company-specific template section names
real adverse event patterns from non-public files
```

## Final Pre-Publish Search

Run a keyword search across the repository before pushing:

```bash
rg -n --hidden --glob '!/.git/**' "company|client|confidential|internal|patient|complaint|CAPA|supplier|hospital|physician|Desktop|Intern|工作日志|实习|公司" .
```

Then search for any actual company names, product names, and project names you worked with. Do not publish until every hit is either removed or clearly generic.
