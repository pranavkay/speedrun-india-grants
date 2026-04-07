# Contributing Guide

Thanks for helping keep this knowledge base accurate and comprehensive!

## Adding a New Grant

1. Copy `templates/Grant Template.md`
2. Place it in the appropriate folder under `grants/`
3. Fill in all YAML frontmatter fields
4. Write the overview, eligibility, and funding details
5. Add `[[wikilinks]]` to related grants and entities
6. Update relevant MOC files in `_MOC/`
7. If the funder doesn't have an entity page, create one in `entities/`
8. Update the `GRANTS` array in `index.html` to include the new grant

## Frontmatter Schema

Every grant file must have these YAML fields:

```yaml
---
grant_name: "Full name of the grant"
funder: "Organization name"
funder_type: "central-govt | state-govt | international | private-corporate | cloud-credits"
country: "India"
sectors: ["ai", "climate", "biotech", "agritech", "healthcare", "general"]
stage: ["ideation", "pre-seed", "seed", "early", "growth"]
grant_type: "grant | equity-free | debt | hybrid | credits | prize"
amount_min: "Minimum amount with currency"
amount_max: "Maximum amount with currency"
currency: "INR | USD | EUR"
equity_taken: false
application_mode: "rolling | deadline | cohort"
deadline: "Date or 'Ongoing'"
url: "https://official-website.com"
status: "active | upcoming | closed | recurring"
last_verified: "YYYY-MM"
tags: [relevant, searchable, tags]
---
```

## Updating Existing Grants

- Update `last_verified` when you confirm information is still current
- Change `status` to `closed` if a grant has ended
- Add new deadline dates when announced

## Style Guidelines

- Use `[[wikilinks]]` for all internal references
- Keep descriptions factual and concise
- Include specific numbers (amounts, dates, counts)
- Always cite the source of updated information in your PR description

## Web Interface Updates

When adding grants, also add them to the `GRANTS` array in `index.html`. Follow the existing object structure and include the `related` array for graph connections.

## Reporting Issues

- Outdated information → Open an issue with the correct info and source
- Missing grants → Open an issue or submit a PR
- Broken links → Open an issue
