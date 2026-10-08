# PortalCraft

**Play Minecraft in the Source engine.** PortalCraft is a mod for **Portal (2007)** that brings Minecraft-style worlds, building, crafting, and survival into Portal.

Explore generated worlds, visit the Nether and the End, encounter mobs and villages, or play the original Portal campaign with Minecraft building.

## Download

[**Download the latest PortalCraft release**](https://github.com/XxHackerBoixX/PortalCraft/releases/latest)

Download `PortalCraft-2026-10-08.zip` from the release's **Assets** section. This repository distributes the packaged Windows mod; the playable files are in the release ZIP. GitHub's automatically generated “Source code” archives contain this repository's documentation, not the game package.

## Requirements

- Windows
- Portal (2007), also known as Portal 1, installed through Steam
- Steam running when you launch the mod

Portal is required and is not included.

## Install and play

1. Download the release ZIP.
2. Extract the entire **PortalCraft** folder anywhere on your computer.
3. Open the extracted folder and double-click **Play PortalCraft.cmd**.
4. The launcher finds Portal through Steam and opens PortalCraft's title menu.

If the launcher cannot find Portal, open PowerShell in the extracted PortalCraft folder and supply its installation path:

```powershell
.\Launch-PortalCraft.ps1 -PortalPath "D:\Games\Steam\steamapps\common\Portal"
```

Worlds, saves, and settings are stored in the `portalcraft` folder. **Back up that folder before replacing it with a newer release.**

## What you can play

- **Play Game:** open your worlds, create a new world, or play the guided tutorial.
- **Portal Chapters:** play the original Portal campaign with PortalCraft building enabled.
- **Creative and Survival:** switch modes with F4.
- **Help & Options:** adjust settings, view controls, and change your skin.

## Controls

| Key / action | Control |
| --- | --- |
| 1–9 / mouse wheel | Select hotbar slot; select the portal gun to fire portals |
| E (tap) / Tab | Open or close inventory |
| E (hold) | Use: pick up cubes or press buttons |
| Right mouse | Place or use a block; hold to eat or drink |
| Left mouse | Break a block; hold to mine in Survival |
| Middle mouse | Pick block |
| Q / Shift+Q | Drop one item / the whole stack |
| Ctrl | Sprint |
| Shift | Sneak |
| Space twice | Toggle flying in Creative |
| F4 | Switch between Creative and Survival |
| F5 | Change view |
| F7 | Go to the Minecraft world |
| L | Achievements |
| F8 | Console |
| Esc | Pause menu, including Save and Exit |

## Troubleshooting

- **“Portal 1 was not found”:** install Portal through Steam, or provide its location with `-PortalPath` as shown above.
- **“game files are missing or damaged”:** extract the ZIP again into a fresh folder.
- **Heavy stutter on NVIDIA cards with G-SYNC:** the included README recommends disabling G-SYNC or setting it to full-screen only in NVIDIA Control Panel.

## Release integrity

SHA-256 for `PortalCraft-2026-10-08.zip`:

```text
281e7261e688e02b755a46abf0f02d0d2ef566d0028f7fb721cb5862fefc2c2b
```

PortalCraft is a fan project and is not affiliated with Mojang, Microsoft, or Valve.
