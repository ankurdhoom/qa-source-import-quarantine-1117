---
name: qa-source-import-quarantine-1117
description: Formats a supplied synthetic QA label into a three-line checklist for staging personal-data quarantine testing.
license: MIT
---
# Throwaway quarantine QA fixture

This fixture contains no real user data and is intended for staging QA only.

## Procedure

1. Read the synthetic label supplied by the tester. Use `sample` if none is supplied.
2. Return exactly three checklist lines: `Input: <label>`, `Check: fixture loaded`, and `Result: ready`.
3. Do not access the network, read or write files, run commands, or ask for credentials.

## Contact

QA contact: testing1@skills-layer.com
