# FM13 / FM26 Corner Stadium Scoreboard Mod

Unlock **Video Screen (scoreboard)** placement on **corner sections** in the stadium editor for **corner-type stadiums** in **FIFA Manager 13** and **FIFA Manager 26**.

> **Trade-off:** This mod fixes corners at the cost of other tribunes. Scoreboards on **behind-goal**, **main/marathon**, and **non-corner** sections will **no longer work properly** after installation. Read [Installation & warnings](docs/INSTALL.md) before installing.

## Preview

| In-game (corner section) | Stadium editor |
|---|---|
| ![Corner scoreboard placed on a corner stand](docs/images/corner-scoreboard-preview-1.webp) | ![Video screen placement in the FM stadium editor](docs/images/corner-scoreboard-preview-2.webp) |

## Compatibility

| Game | Status |
|------|--------|
| **FIFA Manager 13** | Supported |
| **FIFA Manager 26** | Supported (same `data\stadium\generator\` layout) |

Install path (both games):

```
[Game Folder]\data\stadium\generator\
  ├── StadiumDB.xml
  └── Stadelems.big
```

## Features

- Unlocks all Video Screen sizes on **corners** (not only vanilla ground variants)
- Correct corner placement — in front of stands, not behind the roof
- Stable on corners (Large A placer; all sizes appear as Large A on corners)

## Limitations

- **Breaks** scoreboards on behind-goal and marathon/main tribunes
- No free X/Y editor placement (vanilla snap rows only)
- Replaces global generator files — **always back up first**

## Quick install

1. Close the game completely.
2. Back up your original files:
   - `data\stadium\generator\StadiumDB.xml`
   - `data\stadium\generator\Stadelems.big`
3. Copy the two files from [`data/stadium/generator/`](data/stadium/generator/) in this repo into your game folder (overwrite).
4. In the editor: delete any old corner scoreboard and place again.

Full guide: **[docs/INSTALL.md](docs/INSTALL.md)**

## Uninstall

Restore your backed-up `StadiumDB.xml` and `Stadelems.big`.

## Repository layout

```
data/stadium/generator/   Mod files (install these)
docs/INSTALL.md           Detailed installation & warnings
docs/SHARE_DESCRIPTION.md Copy-paste text for forums / Nexus
docs/images/              In-game preview screenshots
```

## License

See [LICENSE](LICENSE). Redistribution allowed with attribution and this readme.

## Contributing

Issues and pull requests welcome. Do not commit personal game saves, tokens, or unrelated files.
