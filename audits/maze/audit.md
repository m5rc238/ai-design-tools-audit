# Audit: Maze

## Metadata

- Tool name: Maze
- Website: https://maze.co/
- Category: UX research platform
- Audit date (YYYY-MM-DD): 2026-02-20
- Auditor: Codex
- Version or pricing tier reviewed: Public marketing/docs pages

## Evidence Log

| Claim area | Source URL | Evidence note | Confidence (High/Medium/Low) |
|---|---|---|---|
| AI positioning | https://maze.co/ai/ | Maze describes the product as AI-powered product research | High |
| Model/provider disclosure | https://maze.co/ai/ | Maze states use of OpenAI (text) and Rev AI (voice) | High |
| Official product context | https://maze.co/ | Official homepage and platform positioning context | Medium |

## Product Snapshot

- Primary user: Product, UX, and research teams
- Core jobs-to-be-done: Plan studies, collect feedback, synthesize research findings
- Key workflows tested: Publicly documented AI-powered research workflows
- Claimed AI capabilities: AI-powered product research plus provider-backed text/voice AI features

## Scoring Summary

| Dimension | Score (1-5) | Notes |
|---|---|---|
| Transparency | 4 | Named external providers are disclosed, but deep architecture detail is not |
| Workflow depth | 3 | Multi-step research workflow is clear, but full technical implementation depth is not published |
| Ecosystem embedding | 3 | Moderate integration and operational embedding signal in cited evidence |
| Differentiation evidence | 3 | Practical differentiation in execution, limited hard moat evidence |
| Switching cost signals | 3 | Moderate team/process stickiness suggested, not strongly evidenced as high |

## Schema Mapping

| Schema field | Value | Evidence reference |
|---|---|---|
| core_capability_layer_inferred | LLM wrapper (API-based) | `data/processed/classified_tools.csv` Maze row; https://maze.co/ai/ |
| execution_model_inferred | Hybrid | `data/processed/classified_tools.csv` Maze row |
| value_layer_inferred | Research synthesis | `data/processed/classified_tools.csv` Maze row |
| architectural_evidence_level | Named external model provider | `data/processed/classified_tools.csv` Maze row; https://maze.co/ai/ |
| classification_confidence | High | `data/processed/classified_tools.csv` Maze row |
| estimated_differentiation_surface | medium | `data/processed/classified_tools.csv` Maze row |

## Strengths

- Clear AI value proposition in UX/product research workflows
- Explicit external model-provider signal improves evidence confidence
- Strong baseline candidate for comparison with other research-synthesis tools

## Risks / Gaps

- Public evidence does not establish a proprietary model moat
- Limited architecture detail beyond provider naming
- Differentiation appears execution-led rather than uniquely technical

## Verdict

- Overall assessment: Credible AI-enabled research platform with medium defensibility signal
- Best fit teams: Teams needing practical AI support in recurring UX research workflows
- Not a fit for: Teams requiring verified proprietary-model differentiation
- Follow-up verification needed: Integration depth, data retention model, and workflow lock-in signals beyond marketing pages
