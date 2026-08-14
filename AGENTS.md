# AGENTS.md — repo-local guardrails for public repositories

Read this before opening a pull request, filing an issue, or editing public-facing docs in this
repository.

This file is intentionally short. The full policy lives in
`Vev-software/engineering/AGENTS.md`. If there is any ambiguity, the engineering policy wins.

## Public disclosure rules

- Treat this repository as **public-by-default** communication space.
- In public PR titles/bodies, issue bodies, README/docs, ADRs, and `.github` templates, describe
  only:
  - the code and behaviour in this public repo
  - published public contracts and schemas
  - public-safe architectural boundaries
- Do **not** include:
  - private repo names or private module names
  - proprietary deployment topology or control paths
  - licence enforcement or entitlement-verification detail
  - trial mechanics, internal hostnames, customer names, or security-control specifics
  - secrets, credentials, tokens, or customer data

## Escalation

- Security vulnerabilities do **not** belong in a public issue or PR. Follow `SECURITY.md`.
- If the useful explanation seems to require private implementation detail, stop and move that
  detail to a private channel. Keep only the public-safe summary here.
