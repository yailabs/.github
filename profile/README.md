<div align="center">
  <img src="yai-labs-logo_512.png" width="220" alt="YAI Labs logo" />

  <p><strong>We build systems that don’t lie.</strong></p>

  <p>
    Governed runtimes for accountable execution.<br/>
    Explicit authority. Deterministic boundaries. Explainable failure.
  </p>

  <p>
    <a href="https://github.com/yai-labs/yai">Runtime</a> ·
    <a href="https://github.com/yai-labs/yai-specs">Specs</a> ·
    <a href="https://github.com/yai-labs/yai-cli">CLI</a> ·
    <a href="https://github.com/yai-labs/yai-infra">Governance Tooling</a> ·
    <a href="https://github.com/yai-labs/yai-skin">Design System</a>
  </p>
</div>

YAI Labs builds *governed runtimes*: systems where authority is explicit, behavior is reproducible, and failures are explainable.

If a machine can’t tell you:
- who did what
- under which constraints
- and why the outcome happened

…it’s not trustworthy. It’s theater.

**Rule:** if it can’t be audited, it doesn’t ship.

## What “governed runtime” means here

Governance is not a policy doc you hope people follow.
It’s enforced by the runtime:

- Actions require explicit authority.
- Behavior is constrained by versioned contracts.
- External effects are gated.
- Execution produces traces/logs sufficient to reconstruct causality.

## The ecosystem (start here)

- **yai** — the runtime stack (Boot / Root / Kernel / Engine), built for deterministic boundaries and auditable execution.
- **yai-specs** — the canonical contract layer (protocol, schemas, ABI surfaces, compliance artifacts). Consumers pin specs on purpose.
- **yai-cli** — the operator interface: boot, control, inspect, and audit via pinned contracts.
- **yai-infra** — shared delivery + governance tooling (workflows, enforcement, release/verify tools).

## Status

This ecosystem is early and disciplined:
- Versions are explicit.
- Specs are pinned (never “floating”).
- Compatibility is tracked and enforced.

Expect intentional change; treat upgrades as deliberate operations.

## If you care about proof, not demos

We optimize for:
- deterministic checks
- repeatable builds
- hard gates that refuse regressions
- post-incident explainability (reconstruction without guesswork)

## Security and contribution

- Security disclosures: follow each repository’s `SECURITY.md`.
- Contributions: prefer issues/PRs that include reproduction steps, expected behavior, and observable evidence.
