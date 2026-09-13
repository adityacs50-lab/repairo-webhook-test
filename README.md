# repairo-webhook-test

Throwaway repo for exercising the Repairo GitHub App.

- `openapi.yaml` — Shipping API v1 (reset from Payments v1 — see PR #1's
  history for that earlier positive-review-gate test)
- `src/` — TypeScript consumer pinned to the v1 shapes

A PR that swaps the spec to v2 should get a breaking-change comment
and, since every generated fix here is deterministic and safe, an
automatic fix PR.
