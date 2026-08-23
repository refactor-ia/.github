# Discord Scale Plan

Build clarity and value before scale. Discord supports community and public work; it does not replace repositories, documentation, or product decisions.

Each batch requires specific authorization before execution. Approval of this strategy does not authorize automatic later changes.

## Principles

- Staff and the RefactorIA Team have separate responsibilities; this plan does not describe private spaces or permissions.
- Do not promise automatic migration, unlimited support, or outcomes without evidence.
- Do not create structure to simulate activity. Community growth follows usefulness, clarity, and collaboration.
- Keep each change reversible, bounded, and verifiable before widening scope.
- Hand product work to dedicated repositories and sessions. Discord coordinates only the necessary context.
- Prioritize cortex-brains before PCSoft. PCSoft progresses only after meeting its own publication gates.

## Reversible strategic batches

| Batch | Objective | Gate | Reversal |
| --- | --- | --- | --- |
| 1. Clarity | Explain participation, contribution, and help paths. | Approve copy and scope. | Remove or correct published communication. |
| 2. Public flow | Connect conversation to issues, documentation, and repositories. | Confirm the flow adds value. | Return to the prior flow without migrating content. |
| 3. Collaboration | Trial limited review and learning practices. | Review evidence and moderation load. | Stop the practice without promising continuation. |
| 4. Product publication | Communicate only products that pass their gates. | Approve publication evidence. | Remove communication and use the product rollback plan. |

These batches exclude automation, telemetry, identity data, permissions, internal maps, and operational details.

## Public product requirements

### Personal or default deployment

| Area | Requirement |
| --- | --- |
| Delivery | Compose-first for reproducible setup. |
| Data | SQLite is canonical. |
| Text search | FTS5 is the degraded fallback. |
| Semantic index | Zvec is derived and rebuildable from canonical data. |
| Local models | Ollama with `nomic-embed-text`. |
| Expected value | Semantic search is normal product value, not an optional enhancement. |

### Team or optional deployment

| Area | Requirement |
| --- | --- |
| Shared data | PostgreSQL with pgvector and Ollama/Nomic. |
| Perimeter | Authenticated access through TLS or VPN. |
| Condition | PostgreSQL is optional for the product, but required for a shared concurrent Team deployment. |
| Security | Raw database or MCP exposure is not assumed safe. |

Gentle AI and Engram are optional adapters, not core product dependencies or requirements for the basic flow.

## Publication gates

Before announcing or publishing, provide reviewable evidence for:

- license;
- provenance;
- privacy;
- security;
- release ownership;
- rollback; and
- behavior and known limits.

An incomplete gate blocks publication. Do not replace evidence with hype, commercial promises, or unverified estimates.

## Batch checklist

- [ ] Scope and authorization are specific.
- [ ] The public benefit is explained plainly.
- [ ] Evidence is proportionate to the change.
- [ ] A reversal plan is tested or documented.
- [ ] Product handoff is recorded in its dedicated repository or session.
- [ ] No operational data or automatic-migration promise is exposed.
