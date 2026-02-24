<div align="center">
  <img src="yai-labs-logo_512.png" width="220" alt="YAI Labs logo" />

  <p><strong>Governed runtimes for accountable execution.</strong></p>

  <p>
    Authority-first execution · Audit-grade traces · Deterministic gates · Reproducible evidence
  </p>

  <p>
    <a href="https://github.com/yai-labs/yai">YAI Runtime</a> ·
    <a href="https://github.com/yai-labs/yai-law">YAI Law</a> ·
    <a href="https://github.com/yai-labs/yai-cli">YAI CLI</a> ·
    <a href="https://github.com/yai-labs/yai-infra">YAI Infra</a>
  </p>
</div>

YAI Labs builds systems where AI-driven execution is **governed by design**: actions require explicit authority, changes are contract-bound, and outcomes are reproducible with evidence.

This is infrastructure thinking applied to intelligence: **no hidden side-effects, no unverifiable behavior, no “trust me” execution.**

## What we mean by “governed runtime”

A governed runtime is not policy-on-paper. It is enforcement in the execution stack:

- **Authority-first execution** — actions require a declared authority context
- **Contract-bound behavior** — versioned law/contract surfaces define what is valid
- **Deterministic gates** — external effects and critical transitions are gated
- **Audit-grade traces** — executions produce evidence sufficient for reconstruction and review

## Repositories

- **`yai`** — the runtime stack and program hub (Boot / Root / Kernel / Engine / Mind boundaries), plus RFC/ADR/Runbooks/Milestone Packs and evidence.
- **`yai-law`** — the canonical normative layer: contracts, schemas, protocol/ABI surfaces, formal artifacts, compliance packs, and test vectors.
- **`yai-cli`** — the operator interface: control-plane commands and verification flows, strictly governed by pinned law.
- **`yai-infra`** — the open factory window: standards, automation, reusable governance workflows, and verification tooling consumed across the ecosystem.

## Status and expectations

This ecosystem is early and disciplined:

- Versions are explicit and reviewed
- Law is pinned deliberately (never floating)
- Compatibility is tracked and enforced
- Upgrades are treated as operations, not “just update and hope”

## Security and contributions

- Security disclosures: see each repository’s `SECURITY.md`
- Contributions: prefer issues/PRs with reproduction steps, expected behavior, and observable evidence
