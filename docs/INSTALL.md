# Install guide

**Fifa Manager Unlock Corner Scoreboard Mod**

FIFA Manager 13, 14, and 26.

---

## READ THIS FIRST

### Corner sections only

This mod works on **corners only**. Behind-goal and marathon scoreboards **break** while it is installed. Use it only for corner tribunes.

### Roof is required

The scoreboard **hangs from the roof**. You must:

1. **Build the roof first**
2. Place the roof on the **lowest row** during construction
3. Place the **scoreboard after the roof**

### Scoreboard hidden inside the stand?

A **small roof** can leave the board **inside the tribune** where you cannot see it.

Extend the roof outward (see images below), then place the scoreboard **after** the roof.

<p align="center">
  <img src="../images/roof-build-order.png" alt="Roof first on lowest row" width="800">
</p>

<p align="center">
  <img src="../images/roof-extend-fix.png" alt="Extend roof so scoreboard is visible" width="800">
</p>

---

## Install files

1. Close the game.
2. Back up:
   ```
   [Game]\data\stadium\generator\StadiumDB.xml
   [Game]\data\stadium\generator\Stadelems.big
   ```
3. Download `Fifa_Manager_Unlock_Corner_Scoreboard_Mod.zip` from Releases.
4. Copy into `[Game]\data\stadium\generator\` and overwrite.
5. Start the game.

## In the editor (corners)

1. Open a corner-type stadium.
2. On the corner: **build roof** (lowest row).
3. Select the corner tribune.
4. Choose **Video Screen**.
5. Place **after** the roof.
6. Not visible? **Extend the roof**, delete the board, place again.
7. Save.

## Uninstall

Restore your backed-up files to `data\stadium\generator\`.

## Troubleshooting

| Problem | Fix |
|---------|-----|
| No scoreboard / wrong spot | Build roof first, scoreboard after roof |
| Board inside stand, not visible | Extend roof outward, re-place scoreboard |
| Broken on behind-goal / marathon | Expected. Restore vanilla backup |
| Crash on launch | Restore vanilla backup |

## Preview (mod)

<p align="center">
  <img src="../images/corner-scoreboard-preview-1.webp" alt="Corner scoreboard in-game" width="800">
</p>

<p align="center">
  <img src="../images/corner-scoreboard-preview-2.webp" alt="Editor video screen menu" width="800">
</p>
