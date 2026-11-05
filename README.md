# Olts-pcb-skill

PCB / PCBA design skills for Claude Code, vendored as project skills under
`.claude/skills/`. Any Claude Code session opened in this repo loads them;
invoke with `/<skill-name>`.

| Skill | Use |
|---|---|
| `manage-pcba-program` | Orchestrates the gated flow below; start here for end-to-end work |
| `plan-electronic-product` | Idea → engineering brief and architecture |
| `design-and-review-circuit` | Circuit design / audit: power, ratings, protection, safe states |
| `schematic-humanizer` | Make netlist-like schematics readable without changing connectivity |
| `qualify-pcba-sourcing` | BOM part verification, stock, substitutes, sourcing lock |
| `pcb-layout-review` | Placement / routing audit, DRC, porting a proven board |
| `release-pcba-fabrication` | Frozen Gerber/drill/BOM/CPL release manifest |
| `operate-jlcpcb-order` | JLCPCB quote/order review (does not pay) |
| `pcb` | End-to-end EasyEDA Pro (MCP) + JLC/LCSC flow, with Python checkers in `scripts/verify/` |

`pcb` needs EasyEDA Pro with its MCP bridge and a logged-in browser — see
`.claude/skills/pcb/setup/README.md`. The others work on files alone.

Sources, commits and licences: [THIRD_PARTY.md](THIRD_PARTY.md).

Install personally instead of per-project:
`cp -R .claude/skills/<name> ~/.claude/skills/`.
