# Mission: RAG Evaluation for Program Docs

## Why
Build the ability to evaluate a small RAG system against the PMP program docs, then explain what failed and why. This module should turn evals from vague score-watching into a reproducible engineering loop that can support the first portfolio AI backend system.

## Success looks like
- Create a tiny dataset with questions, expected facts, expected source files, and failure labels.
- Separate retrieval failures from generation failures and end-to-end failures.
- Build a transparent Python baseline over the PMP docs corpus.
- Run a DeepEval-based check against the same or closely related cases.
- Write a compact synthesis that explains metric tradeoffs, observed failures, and limits.

## Constraints
- Planned effort is 12-16 focused hours.
- Stay grounded in the module contract and named sources from `RESOURCES.md`.
- Assume basic Python, command-line workflow, embeddings, retrieval, and prompting.
- Keep outputs small, reproducible, and artifact-oriented.

## Out of scope
- Production observability platform rollout.
- Large synthetic dataset generation.
- Multi-turn RAG evaluation before the single-turn baseline is solid.
- Broad tool adoption beyond the comparison needed for this module.
