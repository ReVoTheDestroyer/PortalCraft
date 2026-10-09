# PortalCraft — Minecraft in Portal (2007)

**Minecraft-style building meets the portal gun.** PortalCraft is an experimental **Portal (2007)** mod that brings block building, generated worlds, and portal gameplay to **Valve’s Source engine**. Play on **Windows** using your own Steam installation of **Portal 1**.

> [!WARNING]
> **Very buggy and unfinished.** Many features and mechanics are **not implemented yet**, and existing features may be incomplete or unreliable. Expect bugs, broken behavior, and rough edges. This is an experimental pre-release for testing and feedback.

[**Download the experimental build**](https://github.com/ReVoTheDestroyer/PortalCraft/releases/tag/2026-10-08) · [Screenshots](#screenshots) · [Watch gameplay](#gameplay-showcase) · [Install and play](#install-and-play)

[Report a bug](https://github.com/ReVoTheDestroyer/PortalCraft/issues) · [VirusTotal report](#file-verification) · [Follow development on TikTok](https://www.tiktok.com/@wedoinit2341)

## Screenshots

Development screenshots; scenes and features may differ from the October 8, 2026 download. **The mod is still very buggy and many features remain unimplemented.**

### Portals at night

[![Steve seen through linked portals at night, holding a diamond pickaxe.](docs/screenshots/recursive-portals-at-night.jpg)](docs/screenshots/recursive-portals-at-night.jpg)

| Jungle | Village |
| :---: | :---: |
| [<img src="docs/screenshots/jungle-canopy-overlook.jpg" alt="Jungle trees and a river viewed from above with the portal gun." width="420">](docs/screenshots/jungle-canopy-overlook.jpg) | [<img src="docs/screenshots/village-overlook.jpg" alt="Village houses, a stone tower, and crops viewed from above." width="420">](docs/screenshots/village-overlook.jpg) |
| **Woodland mansion** | **Sandstone building** |
| [<img src="docs/screenshots/woodland-mansion.jpg" alt="Woodland mansion surrounded by forest." width="420">](docs/screenshots/woodland-mansion.jpg) | [<img src="docs/screenshots/sandstone-and-glass-hall.jpg" alt="Sandstone building with glass windows and torches." width="420">](docs/screenshots/sandstone-and-glass-hall.jpg) |
| **Ender Dragon death effect** | **Sunset** |
| [<img src="docs/screenshots/ender-dragon-purple-burst.jpg" alt="Purple light around the Ender Dragon during its death effect." width="420">](docs/screenshots/ender-dragon-purple-burst.jpg) | [<img src="docs/screenshots/sunset-with-personality-core.jpg" alt="Sunset with a Portal personality core held in the foreground." width="420">](docs/screenshots/sunset-with-personality-core.jpg) |

[**More screenshots**](docs/screenshots/README.md)

## Gameplay showcase

Clips and screenshots from [@wedoinit2341’s development posts](https://www.tiktok.com/@wedoinit2341). Footage may show earlier builds. **PortalCraft is still very buggy, and many features remain unimplemented.**

| Generated worlds | Playing with portals | Test chamber building |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/75c43540-d10a-452f-a6ce-fd39d5d6ac32" alt="Portal gun and a blue portal in a grassy Minecraft-style world" width="220"> | <img src="https://github.com/user-attachments/assets/76c4be67-5a97-4032-a455-940562fb7e71" alt="Blue and orange portals beside a cake in PortalCraft" width="220"> | <img src="https://github.com/user-attachments/assets/4238b552-7502-42e0-8e15-33e01496e96f" alt="Wooden blocks being placed inside a Portal test chamber" width="220"> |

Expand a clip below to watch it on GitHub.

<details>
<summary><strong>Generated worlds and the portal gun — 25 seconds</strong></summary>

Exploring procedurally generated terrain with the portal gun.

https://github.com/user-attachments/assets/e254eb4e-c070-4d5a-85c7-56546959f577

[Watch the original TikTok](https://www.tiktok.com/@wedoinit2341/video/7690437699680914702)

</details>

<details>
<summary><strong>Playing with portals — 30 seconds</strong></summary>

Portal gameplay in a Minecraft-style world.

https://github.com/user-attachments/assets/098c1910-02eb-42f8-82fd-8623bac2991c

[Watch the original TikTok](https://www.tiktok.com/@wedoinit2341/video/7693749525701217549)

</details>

<details>
<summary><strong>Building in a Portal test chamber — 30 seconds</strong></summary>

Placing blocks inside one of Portal’s test chambers.

https://github.com/user-attachments/assets/32441c72-207a-4e42-8078-f7373a4c7bc6

[Watch the original TikTok](https://www.tiktok.com/@wedoinit2341/video/7692156885239139598)

</details>

## Project status

PortalCraft is a work in progress. It explores Minecraft-style worlds, block building, crafting, and survival inside Portal, alongside the original campaign with building enabled. These systems are still being developed; their presence does not mean they are complete or work reliably.

Many Minecraft features are missing, and this build does not offer complete Minecraft feature parity. Please try it with the expectations of an early experimental mod.

## Download

Open [Releases](https://github.com/ReVoTheDestroyer/PortalCraft/releases) and download **`PortalCraft-2026-10-08.zip`** from the experimental preview's **Assets** section.

The named ZIP contains the playable Windows mod. GitHub's automatically generated **Source code** archives contain this repository's files at the selected tag. Download the named ZIP above to play the mod. This repository currently distributes the packaged mod; the mod's source code is not included.

## Requirements

- **Windows**
- **Portal (2007)**, also known as Portal 1, installed through Steam
- **Steam running** when you launch the mod

You need your own installed copy of Portal. Portal is not included.

## Install and play

1. Download the mod ZIP from [Releases](https://github.com/ReVoTheDestroyer/PortalCraft/releases).
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

Bug reports help make the unfinished parts easier to track. Search [existing issues](https://github.com/ReVoTheDestroyer/PortalCraft/issues) before opening a new one, and include:

- The release date or ZIP filename.
- What you were doing and the steps needed to reproduce the problem.
- What you expected to happen and what actually happened.
- Screenshots or a short video, if useful.
- Your Windows version and graphics card for launch or performance problems.

## File verification

**[View the VirusTotal report for this release ZIP](https://www.virustotal.com/gui/file/281e7261e688e02b755a46abf0f02d0d2ef566d0028f7fb721cb5862fefc2c2b)** · Submitted October 8, 2026.

VirusTotal warned that this multi-file ZIP exceeds its archive inspection limit, so this report does **not** verify every file inside the mod. Scan results can change and are not a guarantee of safety.

SHA-256 for `PortalCraft-2026-10-08.zip`:

```text
281e7261e688e02b755a46abf0f02d0d2ef566d0028f7fb721cb5862fefc2c2b
```

PortalCraft is a fan project and is not affiliated with Mojang, Microsoft, or Valve.
