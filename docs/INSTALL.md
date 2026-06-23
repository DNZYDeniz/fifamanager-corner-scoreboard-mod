# Install guide

**Fifa Manager Unlock Corner Scoreboard Mod**

FIFA Manager 13, 14, and 26.

## Preview

<p align="center">
  <img src="../images/corner-scoreboard-preview-1.webp" alt="Corner scoreboard in-game" width="800">
</p>

<p align="center">
  <img src="../images/corner-scoreboard-preview-2.webp" alt="Editor video screen menu on corner" width="800">
</p>

## Before you install

| Works | Broken |
|-------|--------|
| Corner tribunes | Behind-goal tribunes |
| Video Screen on corners | Main / marathon stands |

Install only if you need corner scoreboards. Back up your files first.

## Requirements

- FIFA Manager 13, 14, or 26
- Corner-type stadium in the editor

## Steps

1. Close the game.
2. Back up:
   ```
   [Game]\data\stadium\generator\StadiumDB.xml
   [Game]\data\stadium\generator\Stadelems.big
   ```
3. Download `Fifa_Manager_Unlock_Corner_Scoreboard_Mod.zip` from Releases, or copy the files from this repo.
4. Copy into `[Game]\data\stadium\generator\` and overwrite.
5. Start the game.

## In the editor

1. Open a corner-type stadium.
2. Click a corner tribune (not behind-goal, not marathon).
3. Choose Video Screen.
4. Delete the old board on that corner if needed, then place again.
5. Save.

All sizes on corners use the Large A mesh. They may look the same size. That is normal.

## Uninstall

Restore your backed-up files to `data\stadium\generator\`.

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Board still behind roof | Delete and re-place on that corner |
| Broken on behind-goal stand | Restore vanilla backup |
| Crash on launch | Restore vanilla backup |
| Mod not working | Check files are in `data\stadium\generator\` |

## Files changed

| File | Role |
|------|------|
| `StadiumDB.xml` | Scoreboard links per tribune type |
| `Stadelems.big` | 3D mesh placement |
