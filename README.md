# AI Design Tools Audit

Open-source audit framework and research repository for evaluating AI design and UX research tools using evidence-backed, repeatable criteria.

## What This Repo Does

- Tracks AI design/UX tools with citation-backed evidence
- Classifies technical transparency and differentiation signals
- Publishes findings in both report and per-tool audit formats
- Makes scoring logic reviewable and reproducible

## Current Outputs

- `report.md` and `report.html`: latest synthesized findings
- `SCHEMA.md`: classification schema definitions
- `data/raw/tool_list.csv`: source tool list and evidence references
- `data/processed/classified_tools.csv`: classified dataset
- `outputs/figures/`: chart assets and summary metrics

## Repository Structure

```text
.
├── audits/
│   ├── README.md
│   └── _template/
│       └── audit.md
├── data/
│   ├── raw/
│   └── processed/
├── docs/
│   ├── methodology.md
│   ├── rubric.md
│   └── summary.md
├── outputs/
│   └── figures/
├── scripts/
│   └── README.md
├── templates/
│   └── audit-template.md
├── report.md
├── report.html
└── SCHEMA.md
```

## Audit Workflow

1. Pick a tool and duplicate `templates/audit-template.md`.
2. Save it as `audits/<tool-name>/audit.md`.
3. Fill in evidence links before assigning any score.
4. Map observations to `SCHEMA.md` fields.
5. Update rollups in `docs/summary.md` and datasets if needed.

## Project Roadmap (v0.1)

- Finalize methodology and scoring rubric in `docs/`
- Publish 3-5 complete tool audits
- Produce first comparison matrix in `docs/summary.md`
- Document contribution and review process for outside collaborators

## GitHub Pages

This repository deploys via `.github/workflows/pages.yml`.

After pushing to `main` or `master`:

1. Open repository `Settings` -> `Pages`
2. Set source to `GitHub Actions`
3. Wait for workflow `Deploy GitHub Pages` to succeed

Published URL pattern:

- `https://<github-username>.github.io/<repo-name>/`

`index.html` is the landing page and links to the main research files.

## Contributing

See `CONTRIBUTING.md` for process and standards.

## License

MIT. See `LICENSE`.
