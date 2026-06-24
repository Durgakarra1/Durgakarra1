# LLM.md — Project Constitution

This document holds data schemas, behavioral rules, and architectural invariants.

- Data-First Rule: Define JSON payloads in `gemini.md` before coding.
- Behavioral rules: Do not guess business logic; be deterministic for actions that affect production systems.
- Privacy: Store secrets in `.env` and never commit tokens.

Update this file whenever schema or rules change.
