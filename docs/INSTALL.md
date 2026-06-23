# Installation & warnings

**FM13 / FM26 Corner Stadium Scoreboard Mod**

Compatible with **FIFA Manager 13** and **FIFA Manager 26** (same install path: `data\stadium\generator\`).

![Corner scoreboard preview](../images/corner-scoreboard-preview-1.webp)

---

## Important — read before installing

This mod is a **trade-off**, not an all-in-one fix.

| | |
|---|---|
| **Works** | **Corners** — video screens on corner sections (corner-type stadium editor) |
| **Breaks** | **Behind goal**, **main/marathon**, and **other non-corner** tribunes |

If you need scoreboards on behind-goal or marathon stands, **do not install** — or restore vanilla files when editing those areas.

---

## What this mod does

1. Unlocks Video Screen options on **corner** sections (corner-type stadiums).
2. Places corner scoreboards in front of the stands (not behind the roof).
3. Uses stable Large A placer on corners (all sizes look like Large A; no crashes).

## What it breaks

- Behind-goal tribunes (Blocktype 4)
- Main / marathon tribunes
- Other non-corner sections
- No free X/Y placement (vanilla snap rows only)

---

## Requirements

- FIFA Manager **13** or **26**
- Corner-type stadium in the stadium editor

---

## Installation

1. **Fully close the game.**

2. **Back up** (important):
   ```
   [Game]\data\stadium\generator\StadiumDB.xml
   [Game]\data\stadium\generator\Stadelems.big
   ```

3. Copy from this repository:
   ```
   data/stadium/generator/StadiumDB.xml
   data/stadium/generator/Stadelems.big
   ```
   Into your game’s `data\stadium\generator\` folder (overwrite).

4. Launch the game.

---

## In-game usage

1. Open a corner-type stadium.
2. Select a **corner** section (e.g. Corner 3).
3. Pick a Video Screen size.
4. **Delete** any old corner scoreboard, then **place again**.
5. Scoreboard should sit in front of the stands.

Scoreboards on behind-goal / marathon tribunes will **not** work correctly while this mod is installed.

---

## Uninstall

Restore your backed-up `StadiumDB.xml` and `Stadelems.big`.

---

## Files changed

| File | Role |
|------|------|
| `StadiumDB.xml` | Corner links, editor unlock |
| `Stadelems.big` | Corner mesh placement (`bc_5_0903`) |

---

## Troubleshooting

- **Wrong position on corner:** delete and re-place on that corner.
- **Broken on behind-goal / main stand:** expected — restore vanilla backup.
- **Crash on launch:** restore backup.
- **Other stadium mods:** may conflict if they edit the same files.
