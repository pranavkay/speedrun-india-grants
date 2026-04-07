# 🏃 India Startup Grants Knowledge Base

*A [Startup Speedrun](https://startupspeedrun.com) open-source resource*

---

An open-source, community-maintained knowledge base of **38+ active grants, funds, and non-dilutive financing** available to Indian startups and companies.

Browse the **[interactive web version →](index.html)** (just open `index.html` in your browser) or explore the interlinked markdown files in **[Obsidian](https://obsidian.md)**.

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

## How to Use

### Option 1: Interactive Website
Open `index.html` in any browser. Features:
- Force-directed knowledge graph (D3.js) with color-coded categories
- Full-text search across all grants
- Filter by category, stage, and sector
- Click any node or list item for detailed grant information
- Related grants navigation

### Option 2: Obsidian Vault
1. Download and install [Obsidian](https://obsidian.md) (free)
2. Open this folder as a vault
3. Start at `Home.md`
4. Explore via Maps of Content or Graph View

Every grant has YAML frontmatter for structured queries (install the [Dataview](https://github.com/blacksmithgu/obsidian-dataview) plugin for live queries).

## Vault Structure

```
IndiaGrantsVault/
├── Home.md                          # Dashboard and entry point
├── index.html                       # Interactive web version
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
└── templates/
    └── Grant Template.md            # Template for adding new grants
```

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Quick ways to help:**
- Add a grant that's missing
- Update deadlines or funding amounts
- Add a state government scheme
- Fix broken links or outdated info
- Improve the web interface

## Data Freshness

Last comprehensive update: **April 2026**

Grant information changes frequently. If you find outdated info, please open an issue or PR.

## License

[MIT License](LICENSE) — use it, fork it, share it.

## Acknowledgements

Built with iterative deep-research methodology. Inspired by [Andrej Karpathy's](https://karpathy.ai/) auto-research and knowledge base wiki ideas.

Data sourced from official government portals, scheme websites, and verified news sources.
