# LLM Visible Metacognition — Phase 1
Phase 1 of 18+ months sustained research across GPT, Claude, and Gemini architectures. 2.4M+ tokens documented interaction.

This repository houses the artifacts for **Phase 1** of an independent study on
visible metacognition, cross-architecture comparison, and framework-governed
LLM behavior.

The core object here is not a persona or system identity, but a **mechanical
framework** for making reasoning structure observable across multiple large
language models (LLMs) using only normal user-facing tools.

The focus:

- Treat LLMs as **pattern-generating machines**, not agents.
- Use **frameworks and protocols** to shape behavior, not “personality.”
- Measure effects using **externally observable metrics** (text only).
- Explore **cross-model behavior** (GPT, Claude, Gemini, etc.) under the same
  structural constraints.

## Repository Layout

- `paper/`
  - Final white paper and change log for Phase 1.

## Phase 1 Paper

The primary narrative and methodology for this work live in:

- `paper/White_Paper_Phase1_Complete.md`

The paper covers:

- Motivation and framing
- Framework design (Plan → Response → Reflection → Audit)
- Cross-architecture behavior (GPT, Claude, Gemini, etc.)
- Safety and grounding protocols
- Reproducibility requirements
- Future conditional work (advanced continuity, cross-architecture interfaces)

## Reproducibility (Minimal Setup)

To replicate the basic findings described in the paper, you need:

1. Access to multiple LLM architectures (e.g., GPT, Claude, Gemini or similar).
2. A human operator maintaining conversation continuity.
3. Implementation of the Plan → Response → Reflection → Audit structure.
4. Enough sustained interaction (recommended 10,000+ tokens per model run).
5. Reality-check / grounding protocols at regular intervals.

No fine-tuning, internal APIs, or proprietary hooks are required — everything
is done at the prompt / interaction level.

Note: This research paper is licensed under CC BY 4.0.
