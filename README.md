# PortalCraft

**Play Minecraft in the Source engine.** PortalCraft is an experimental mod for **Portal (2007)** that brings Minecraft-style building and gameplay into Portal.

> [!WARNING]
> **Very buggy and unfinished.** Many features and mechanics are **not implemented yet**, and existing features may be incomplete or unreliable. Expect bugs, broken behavior, and rough edges. This is an experimental pre-release for testing and feedback.

[**Download the experimental build**](https://github.com/XxHackerBoixX/PortalCraft/releases) · [Report a bug](https://github.com/XxHackerBoixX/PortalCraft/issues)

## Project status

PortalCraft is a work in progress. It explores Minecraft-style worlds, block building, crafting, and survival inside Portal, alongside the original campaign with building enabled. These systems are still being developed; their presence does not mean they are complete or work reliably.

Many Minecraft features are missing, and this build does not offer complete Minecraft feature parity. Please try it with the expectations of an early experimental mod.

## Download

Open [Releases](https://github.com/XxHackerBoixX/PortalCraft/releases) and download **`PortalCraft-2026-10-08.zip`** from the experimental preview's **Assets** section.

The named ZIP contains the playable Windows mod. GitHub's automatically generated **Source code** archives contain this repository's documentation only. This repository currently distributes the packaged mod; the mod's source code is not included.

## Requirements

- **Windows**
- **Portal (2007)**, also known as Portal 1, installed through Steam
- **Steam running** when you launch the mod

You need your own installed copy of Portal. Portal is not included.

## Install and play

1. Download the mod ZIP from [Releases](https://github.com/XxHackerBoixX/PortalCraft/releases).
2. Extract the entire **PortalCraft** folder anywhere on your computer.
3. Open the extracted folder and double-click **Play PortalCraft.cmd**.
4. The launcher finds Portal through Steam and opens PortalCraft's title menu.

If the launcher cannot find Portal, open PowerShell in the extracted PortalCraft folder and supply your installation path:

```powershell
.\Launch-PortalCraft.ps1 -PortalPath "D:\Games\Steam\steamapps\common\Portal"
```

Worlds, saves, and settings are stored in the `portalcraft` folder. **Back up that folder before updating or replacing your installation.**

## Finding your way around

These are the menu options and modes described by the included build. Gameplay is experimental and incomplete.

- **Play Game:** your worlds, Create New World, and the guided tutorial.
- **Portal Chapters:** the original Portal campaign with PortalCraft building enabled.
- **Creative / Survival:** switch modes with F4.
- **Help & Options:** settings, controls, and Change Skin.

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

## Feedback and bug reports

Bug reports help make the unfinished parts easier to track. Search [existing issues](https://github.com/XxHackerBoixX/PortalCraft/issues) before opening a new one, and include:

- The release date or ZIP filename.
- What you were doing and the steps needed to reproduce the problem.
- What you expected to happen and what actually happened.
- Screenshots or a short video, if useful.
- Your Windows version and graphics card for launch or performance problems.

## File verification

SHA-256 for `PortalCraft-2026-10-08.zip`:

```text
281e7261e688e02b755a46abf0f02d0d2ef566d0028f7fb721cb5862fefc2c2b
```

PortalCraft is a fan project and is not affiliated with Mojang, Microsoft, or Valve.
