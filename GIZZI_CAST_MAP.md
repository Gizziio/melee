# Gizzi cast → Melee `CharacterKind` map

Identity remap for branch `gizzi-reskin`. Physics/specials stay on the donor
fighter until models/textures are swapped. CSS order uses `CKIND_*` (select
screen), not `FTKIND_*` (internal fighter table).

| CKIND | Melee donor | Gizzi cast | Notes |
|------:|-------------|------------|-------|
| 08 | Mario | **Gizzi** | Base player; Super later via costume/effect |
| 02 | Fox | **Grok** | Fast antagonist (Story final) |
| 00 | Captain Falcon | **Codex** | Order / ship-it rival |
| 14 | Falco | **Clawd** | Rival spark |
| 12 | Zelda | **Hermes** | Gatekeeper |
| 04 | Kirby | **Qwen** | Warmup / copycat energy |
| 0D | Pikachu | **Kimi** | Small / zippy |
| 06 | Link | **OpenCode** | Tooling / swordy |
| 10 | Samus | **DeepSeek** | Charge / tech |
| 09 | Marth | **Gemini** | Dual / precise |
| 0C | Peach | **Muse** | Float / art |
| 05 | Bowser | **GLM** | Heavy |
| 01 | Donkey Kong | **Nemotron** | Power |
| 11 | Yoshi | **Ollama** | Local / egg-ish |
| 0B | Ness | **OMP** | PSI / quirky |
| 19 | Ganondorf | **Husk** | Heavy villain |
| 0A | Mewtwo | **OpenClaw** | Psychic / claws |

Unmapped Melee slots (keep vanilla / lock later): Luigi, Jigglypuff, Ice Climbers, Sheik, Young Link, Dr. Mario, Roy, Pichu, Mr. Game & Watch.

## Asset paths (when ISO extracted)
Disc fighter archives live under `orig/GALE01/` (see upstream README). Replace
per-character DAT/textures after match; do not commit disc dumps.
