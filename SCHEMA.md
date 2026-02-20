Classification Schema v2

Each tool must be evaluated across the following dimensions.

1. Core Capability Layer (inferred)

LLM wrapper (API-based)

Proprietary foundation model

Fine-tuned model on external foundation model

Multimodal native model

Orchestrated pipeline (multiple models chained)

Agentic workflow

Unknown

Definition:
This describes the most plausible underlying AI capability based strictly on verifiable evidence.

Do not assume proprietary foundation models unless explicitly documented.

2. Execution Model

Chat interface

Plugin / embedded in design tool

Autonomous workflow (multi-step without user prompting)

API-first platform

Hybrid

Unknown

Definition:
How users interact with the AI functionality in practice.

3. Value Layer

Ideation

Research synthesis

UI generation

Code generation

Testing / validation

Multiple

Unknown

Definition:
Primary user-facing outcome.

4. Architectural Evidence Level

This measures transparency, not capability.

Explicit architecture documentation (technical detail published)

Named external model provider (e.g., OpenAI, Anthropic)

Explicit proprietary foundation model claim

Marketing-level AI claim only

No verifiable AI evidence found

This field must be evidence-based only.
Do not infer beyond citations.

5. Classification Confidence (NEW)

High → Architecture clearly supported by documentation or named model provider.

Medium → Strong behavioral signals but no technical disclosure.

Low → Inference primarily based on marketing language or indirect clues.

Unknown → Insufficient evidence.

Confidence must reflect epistemic certainty, not feature richness.

Rules

Every factual claim must include citation URL.

Inferred classifications must include short reasoning note.

If evidence conflicts, lower confidence.

If marketing language is the only signal, set confidence to LOW.

Unknown is preferable to speculative precision.

Separate factual description from inferred classification at all times.

Do not collapse orchestration and proprietary foundation models.