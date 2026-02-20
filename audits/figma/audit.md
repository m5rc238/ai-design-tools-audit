# Audit: Figma

## Metadata

- Tool name: Figma
- Website: https://www.figma.com/
- Category: Product design and prototyping
- Audit date (YYYY-MM-DD): 2026-02-20
- Auditor: Codex
- Version or pricing tier reviewed: Public marketing/docs pages

## Evidence Log

| Claim area | Source URL | Evidence note | Confidence (High/Medium/Low) |
|---|---|---|---|
| AI positioning | https://www.figma.com/ | Figma markets AI features for product design and prototyping | High |
| Prompt-to-code feature | https://www.figma.com/ | Figma Make is presented as prompt to code inside Figma workflows | Medium |
| First Draft generation | https://help.figma.com/hc/en-us/articles/23955143044247-Use-First-Draft-with-Figma-AI | First Draft transforms ideas into editable wireframes/designs | High |

## Product Snapshot

- Primary user: Product designers and design teams
- Core jobs-to-be-done: Move from idea to wireframe/prototype and implementation faster
- Key workflows tested: Prompt-assisted design creation, early draft generation, design iteration
- Claimed AI capabilities: Prompt-to-code and AI-generated editable first drafts

## Scoring Summary

| Dimension | Score (1-5) | Notes |
|---|---|---|
| Transparency | 2 | AI features are clear, but technical provider/model details are not disclosed in cited sources |
| Workflow depth | 4 | AI appears across ideation-to-prototype paths within a mature design workflow |
| Ecosystem embedding | 4 | Strong embedding inside a major design environment with broad team usage |
| Differentiation evidence | 3 | Differentiation appears mostly execution and product-surface led |
| Switching cost signals | 3 | Moderate switching friction from established workflows and collaboration artifacts |

## Schema Mapping

| Schema field | Value | Evidence reference |
|---|---|---|
| core_capability_layer_inferred | Orchestrated pipeline (multiple models chained) | `data/processed/classified_tools.csv` Figma row |
| execution_model_inferred | Hybrid | `data/processed/classified_tools.csv` Figma row |
| value_layer_inferred | Multiple | `data/processed/classified_tools.csv` Figma row |
| architectural_evidence_level | Marketing-level AI claim only | `data/processed/classified_tools.csv` Figma row |
| classification_confidence | Medium | `data/processed/classified_tools.csv` Figma row |
| estimated_differentiation_surface | medium | `data/processed/classified_tools.csv` Figma row |

## Strengths

- AI capability is tightly integrated into existing design workflows
- Supports multiple lifecycle stages, from first draft to implementation handoff
- Strong practical utility for teams already operating in Figma

## Risks / Gaps

- Public evidence does not disclose architecture/provider details
- No explicit proprietary-model moat in cited evidence
- Differentiation may be vulnerable to feature parity from adjacent platforms

## Verdict

- Overall assessment: Strong workflow-integrated AI experience with medium defensibility signal
- Best fit teams: Teams already centralized on Figma wanting AI acceleration in daily design work
- Not a fit for: Teams that require transparent model-stack disclosure before adoption
- Follow-up verification needed: Enterprise-level data handling, model governance, and provider disclosures
