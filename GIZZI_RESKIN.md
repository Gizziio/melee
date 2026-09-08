# Gizzi Brawl × Melee decomp — reskin plan

## Trees (keep separate)
| Path | Role |
|------|------|
| `~/Projects/basement-temp/public/games/kombat/` | Live web Brawl (rollback) → https://brawl.allternit.com |
| `~/Projects/gizzi-brawl-melee/` | Fork working tree (`Gizziio/melee`, branch `gizzi-reskin`) |
| `~/Desktop/gizzi-brawl/melee-decomp/` | Desktop mirror of the decomp |
| `~/Projects/basement-temp/public/games/brawl-melee/` | Melee-*feel* web prototype (no disc; playable in browser) |

## GitHub
- Fork: https://github.com/Gizziio/melee
- Branch: `gizzi-reskin`
- Upstream: https://github.com/doldecomp/melee

## Phases
1. **Cast map** — `GIZZI_CAST_MAP.md` (done). Donor physics stay until models land.
2. **Legal ISO** — extract into `orig/GALE01` (Joe provides disc). Required to build / swap art.
3. **Name + CSS labels** — overlay Gizzi names on select / results once string tables are located in rebuilt assets.
4. **Texture/model swap** — per mapped CKIND, starting with Mario→Gizzi, Fox→Grok, Falcon→Codex.
5. **Web parallel** — `brawl-melee` platform-fighter using live Brawl sprites so we can play Melee-feel without waiting on ISO.

## Rules
- Never merge this tree into live `kombat/`.
- No disc data in git.
- Prefer identity-preserving art from live Brawl sheets when generating substitutes.

## Status (2026-09-08)
- Cast map committed on `gizzi-reskin`.
- Web Melee-feel prototype scaffolded at `~/Desktop/gizzi-brawl/brawl-melee/` and `~/Projects/basement-temp/public/games/brawl-melee/` (Gizzi vs Grok, %/stocks). Live `kombat` untouched.
- Decomp build still blocked on legal ISO → `orig/GALE01`.
