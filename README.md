# Security as Code

`security-as-code` explores how to represent threat models, hardening baselines, detection rules, secure defaults, and security-review checks as version-controlled, reviewable, testable, auditable, and agent-operable source material.

## Working Definition

`Security-as-Code` means treating threat models, hardening baselines, detection rules, secure defaults, and security-review checks as canonical operational state expressed through files, schemas, examples, tests, and reviewable change history.

## Goals

- Define the domain clearly.
- Collect prior art and examples.
- Provide reusable schemas and templates.
- Support human review and agent execution.
- Preserve auditability, provenance, and governance boundaries.

## Non-Goals

- This repo is not a universal standard.
- This repo is not legal, operational advice, or platform policy.
- This repo does not canonize HUMMBL/BaseN/Ownward concepts unless explicitly marked and audited.

## Packet status

- `seed` -> `v0.1-draft`

## v0.1 packet locations

- Boundary: [`docs/v0.1-boundary.md`](docs/v0.1-boundary.md)
- Schema: [`schemas/security-as-code-v0.1.json`](schemas/security-as-code-v0.1.json)
- Example: [`examples/security-check-v0.1.example.json`](examples/security-check-v0.1.example.json)
- Fixtures: [`fixtures/valid/security-check-v0.1.valid.json`](fixtures/valid/security-check-v0.1.valid.json), [`fixtures/invalid/security-check-v0.1.invalid.json`](fixtures/invalid/security-check-v0.1.invalid.json)
- Receipt: [`receipts/security-as-code-v0.1-packet-receipt.md`](receipts/security-as-code-v0.1-packet-receipt.md)

## Status

Public seed repository. Initial executable packet in progress as `seed` -> `v0.1-draft`.
