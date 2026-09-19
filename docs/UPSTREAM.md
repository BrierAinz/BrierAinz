# Upstream Work

BrierAinz public work includes local-first agent systems, but also compatibility
and reliability contributions across adjacent open-source projects.

## Contribution Themes

| Theme | What I look for |
|---|---|
| Responses API compatibility | Streaming edge cases, tool-call replay, `null` preservation, partial outputs, and local-server compatibility. |
| Agent tooling on Windows | Native install paths, terminal assumptions, shell portability, and CI coverage that catches Windows-specific regressions. |
| Memory and retrieval systems | Migration safety, scoping bugs, partial-result contracts, deletion lifecycle, and recall semantics. |
| Operator recoverability | Audit trails, rollback paths, durable state, and explicit failure modes before automation gets trusted. |

## Review Style

I try to leave comments that are small enough to act on but concrete enough to
be useful: acceptance checks, regression cases, migration notes, or boundary
conditions that maintainers can verify.

The goal is not drive-by noise. The goal is to make agent, memory, and tooling
projects easier to operate when they meet real machines, real state, and real
failure modes.

## Useful Links

- [Open pull requests authored by BrierAinz](https://github.com/pulls?q=is%3Apr+author%3ABrierAinz)
- [Open issues authored by BrierAinz](https://github.com/issues?q=is%3Aissue+author%3ABrierAinz)
- [Recent public activity](https://github.com/BrierAinz?tab=overview&from=2026-09-01&to=2026-09-30)
