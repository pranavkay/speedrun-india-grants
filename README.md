# India Startup Grants Knowledge Base

An open-source, community-maintained knowledge base of **38+ active grants, funds, and non-dilutive financing** available to Indian startups and companies.

**[Browse the live site →](https://pranavkay.github.io/speedrun-india-grants/)** | [Open in Obsidian](#option-2-obsidian-vault)

> **⚠️ Disclaimer:** This is a community-maintained project. Grant information may be inaccurate, outdated, or incomplete even after review and verification. Always verify details directly with the official funder's website before applying. This is not financial, legal, or investment advice.

## What's Inside

| Category | Count | Examples |
|----------|-------|---------|
| Central Govt | 19 | SISFS, IndiaAI Mission, BIRAC, NIDHI PRAYAS, NABARD funds |
| State Govt | 8 | Karnataka Elevate, TN TANSEED, Maharashtra, Kerala, Telangana |
| International | 5 | EU EIC Accelerator, USAID DIV, World Bank, EU-India R&D |
| Private/Corporate | 8 | Google, Villgro, NVIDIA Inception, DeepScale |
| Cloud Credits | 3 | AWS ($100K), Google Cloud ($350K), Microsoft Azure ($150K) |

**Focus sectors:** AI / Deep Tech, Climate / Clean Energy (with broader coverage).
**Focus stages:** Pre-seed and Seed (with coverage up to growth stage).

## Features

### Interactive Knowledge Graph
A D3.js force-directed graph with color-coded categories — drag, zoom, click any node to explore relationships between grants, funders, and sectors.

### Grant Matcher ("Find My Grants")
Describe your startup in a few sentences, select your stage and sectors, and get the top 10 matching grants ranked by relevance. Client-side keyword scoring — no API calls, no data leaves your browser.

### Search & Filter
Full-text search across all grants with filters for category, stage, and sector. Every grant links to related grants for rabbit-hole exploration.

### Community Contributions
Submit new grants via GitHub Issues with structured templates. Community reviewers verify submissions using a standardized checklist before they're added to the database.

Have an idea? [Open a feature request](https://github.com/pranavkay/speedrun-india-grants/issues/new?template=feature-request.yml).

## How to Use

### Option 1: Interactive Website
Visit **[pranavkay.github.io/speedrun-india-grants](https://pranavkay.github.io/speedrun-india-grants/)** or open `index.html` locally in any browser.

### Option 2: Obsidian Vault
1. Download and install [Obsidian](https://obsidian.md) (free)
2. Clone this repo or download as ZIP
3. Open the folder as a vault in Obsidian
4. Start at `Home.md`
5. Explore via Maps of Content or Graph View

Every grant has YAML frontmatter for structured queries (install the [Dataview](https://github.com/blacksmithgu/obsidian-dataview) plugin for powerful live queries).

## Vault Structure

```
IndiaGrantsVault/
├── Home.md                          # Dashboard and entry point
├── index.html                       # Interactive web version (live site)
├── _MOC/                            # Maps of Content
│   ├── MOC - By Funder Type.md
│   ├── MOC - By Sector.md
│   ├── MOC - By Stage.md
│   └── MOC - By Grant Size.md
├── grants/
│   ├── central-govt/                # 19 central government schemes
│   ├── state-govt/                  # 8 state government schemes
│   ├── international/               # 5 international grants
│   ├── private-corporate/           # 8 private/corporate programs
│   └── cloud-credits/               # 3 cloud credit programs
├── entities/                        # 15 funder/agency reference pages
├── templates/
│   └── Grant Template.md            # Template for adding new grants
└── .github/
    └── ISSUE_TEMPLATE/              # Structured submission & reporting forms
        ├── submit-grant.yml         # Submit a new grant
        ├── report-outdated-info.yml # Flag incorrect info
        └── verification-checklist.md # Reviewer verification template
```

## Contributing

We welcome contributions! There are several ways to help:

### Submit a New Grant
Use our **[structured submission form](https://github.com/pranavkay/speedrun-india-grants/issues/new?template=submit-grant.yml)** — it walks you through all the required fields. A community reviewer will verify the information using our [verification checklist](.github/ISSUE_TEMPLATE/verification-checklist.md) before it gets added.

### Report Incorrect Info
Found something outdated or wrong? Use the **[report form](https://github.com/pranavkay/speedrun-india-grants/issues/new?template=report-outdated-info.yml)** to flag it.

### Other Ways to Help
- Update deadlines or funding amounts via PR
- Add state government schemes for states we haven't covered
- Improve the web interface or grant matcher algorithm
- Translate grant descriptions

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

### Verification Process
Every submitted grant goes through community review:
1. Submitter fills the structured Issue form (confirms active status, official source, no conflicts)
2. A reviewer uses the verification checklist to cross-check against official sources
3. Once approved, the grant is added to both the Obsidian vault and `index.html`
4. The Issue is closed and the contributor credited

## Data Freshness

Last comprehensive update: **April 2026**

Grant information changes frequently. If you find outdated info, please [report it](https://github.com/pranavkay/speedrun-india-grants/issues/new?template=report-outdated-info.yml) or submit a PR.

## Disclaimer

This project is community-maintained and provided "as is." Grant information may be inaccurate, outdated, or incomplete even after review. Always verify details directly with the official funder's website before making any decisions. This project does not constitute financial, legal, or investment advice. The maintainers are not responsible for any decisions made based on information in this database.

## License

[MIT License](LICENSE) — use it, fork it, share it.

## Acknowledgements

Built with iterative deep-research methodology. Inspired by [Andrej Karpathy's](https://karpathy.ai/) auto-research and knowledge base wiki ideas.

Data sourced from official government portals, scheme websites, and verified news sources.
