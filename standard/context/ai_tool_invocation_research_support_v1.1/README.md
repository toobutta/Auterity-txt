# AI Tool/Function Invocation — Context Pack (v1.1)

This folder contains everything required to run **Agent/Deep Research** for the AI Metadata Project’s tool/function invocation mapping.

## Contents
- `ai_tool_invocation_research_support_v1.1.md` — Context addendum overview
- `ai_tool_invocation_context_prompt.md` — **Initializer prompt** (run first)
- `final_ai_tool_invocation_prompt.md` — **Research prompt** (run second)
- `schemas/*.yaml` — Schemas for capture/validation
- `tables/*.csv` — Write targets (comparison, examples, variants, AI SDK diff)
- `appendix/glossary.csv` — Glossary write target
- `mappings/ctis_provider.yaml` — Canonical → provider mappings & behavioral diffs
- `checklists/*.yaml` — Fragmentation & AI SDK checklists
- `changes/` — Delta logs by month

## Run Order
1) Run `ai_tool_invocation_context_prompt.md`
2) Run `final_ai_tool_invocation_prompt.md`
3) Commit results
