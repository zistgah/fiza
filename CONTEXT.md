<!-- context: https://zistgah.org/fiza/CONTEXT.md -->
# CONTEXT — cold-start map for Fiza

_Rebuild full context from this file plus the sources it points to. **Maintain contract and
context.** © 1993–2026 Abhishek Choudhary. All rights reserved. · AyeAI._

## Mission (one line)
Let environmental scientists, practitioners and communities contribute to a shared,
verification-gated environmental knowledge manifold without writing code — the VGC-Health
method retargeted from clinic to climate and ecology.

## Rebuild context from three sources, in order
1. **[`CONTRACT.md`](CONTRACT.md)** — what Fiza is. Read first.
2. **The template** — VGC-Health: https://obonac.github.io/vgc-health.html
   (doi:10.5281/zenodo.21303401) — the structure Fiza replicates for the environment domain.
3. **The parent method (VGC)** — https://doi.org/10.5281/zenodo.21264248.

## Invariants (never violate)
- Same gate discipline as VGC-Health: acceptance belongs to an oracle; no-oracle → Honest
  Deferral; multi-oracle stack; exact-anchor revision; guarded irreversibility; named human
  sign-off (provenance ledger).
- Three non-collapsing axes, retargeted to environment (Sprint-1 task to fix precisely, e.g.
  sphere [atmosphere/biosphere/anthroposphere] · scale [local/regional/planetary] · system
  [monitoring/policy/intervention]). **Do not finalise the axes without the author.**
- AyeAI only; sole authorship; per-category licences; no fabrication; stay in run folder.

## File map
| Path | Role |
|---|---|
| `index.html` | Sprint-0 intent landing (full paper is Sprint 1) |
| `CONTRACT.md` / `CONTEXT.md` | handling rules / cold-start map |
| `BACKLOG.md` | scrum backlog (Sprint 1 builds the paper) |
| `misty.json` / `CITATION.cff` / `LICENSES.md` | DOI metadata / citation / licences |
| `provenance/*.ots` | OpenTimestamps proof(s) |

## Working rules
Safe-by-default; gated irreversible steps; tokens/ORCID from env; logs to `~/work/logs/`;
canonical home `zistgah/fiza`; short increments; the paper is built in Sprint 1 by adapting
VGC-Health section by section under the gate.
