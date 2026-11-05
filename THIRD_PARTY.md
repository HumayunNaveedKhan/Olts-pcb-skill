# Third-party skills

Vendored copies, unmodified except where noted. Both upstreams are MIT; each
skill directory carries its upstream `LICENSE`. Imported 05-11-2026.

| Skill(s) in `.claude/skills/` | Upstream | Commit (date) | Licence |
|---|---|---|---|
| `plan-electronic-product`, `design-and-review-circuit`, `schematic-humanizer`, `pcb-layout-review`, `qualify-pcba-sourcing`, `release-pcba-fabrication`, `operate-jlcpcb-order`, `manage-pcba-program` | [Keitark/pcba-design-skills](https://github.com/Keitark/pcba-design-skills) `.agents/skills/*` | `d41e9996f052016727403236cf0f7476f8f23a1b` (18-07-2026, `main`, after release `v1.0.0`) | MIT © 2026 keitark |
| `pcb` | [daishuge/pcb-skill](https://github.com/daishuge/pcb-skill) `skills/pcb/` + `scripts/` + `setup/` (layout per upstream README) | `6e939b64907e3c63236c7522c511af5d7d1afaad` (10-09-2026) | MIT © 2026 daishuge |

Notes:

- Upstream `LICENSE` copied into `.claude/skills/pcb/` (upstream keeps it at repo root).
- Keitark's CC BY-SA 4.0 case-study assets live outside the skill directories and are not included.
- Keitark recommends pinning production work to `v1.0.0`; this copy is from `main`.
- To update: replace the whole skill directory from a newer upstream commit and update this table. Do not merge versions.
