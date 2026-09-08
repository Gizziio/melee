# Gizzi Brawl × Melee decomp — reskin plan

## Trees (keep separate)
| Path | Role |
|------|------|
| `~/Projects/basement-temp/public/games/kombat/` | Live web Brawl (rollback) |
| `~/Projects/gizzi-brawl-melee/` | Full doldecomp/melee clone for platform-fighter redo |
| `~/Desktop/gizzi-brawl/melee-decomp/` | Desktop mirror of the decomp |

## GitHub fork
Upstream: https://github.com/doldecomp/melee
Create Joe’s fork via GitHub UI or `gh repo fork doldecomp/melee --clone=false` after `gh auth login`.
Then: `git remote rename origin upstream && git remote add origin <your-fork-url>`

## Build requirements (upstream)
Legal Melee ISO → extract system data into `orig/GALE01` (see upstream README). No disc data in this tree.

## Reskin direction
Replace fighter visuals/names with Gizzi cast (Codex, Grok, …) on a branch `gizzi-reskin`. Do not merge into live web kombat.
