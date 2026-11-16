# Kingdom Hearts VR

**In development · No public mod release yet · PC VR**

A VR project for the **Kingdom Hearts collection**, beginning with **Kingdom Hearts Final Mix** in the Steam HD 1.5 + 2.5 ReMIX collection. The goal is to bring its worlds, Keyblade combat and interactions into a tracked, first-person VR experience.

[Future downloads & release notes](https://github.com/NullxVoid00/Kingdom-Hearts-VR/releases) · [Report an issue](https://github.com/NullxVoid00/Kingdom-Hearts-VR/issues) · [Abyssal Light Games](https://nullxvoid00.github.io/)

## Release status

This is the public project and future release hub. **There is no downloadable mod build published here yet.** The repository currently contains project information and release documentation; GitHub's **Code → Download ZIP** downloads those documents, not an installable mod.

When a build is ready, its installer or archive, supported game version, controls, installation steps and known issues will be published under [Releases](https://github.com/NullxVoid00/Kingdom-Hearts-VR/releases). Use **Watch → Custom → Releases** to follow future downloads. No release date is announced.

## What is being developed

| Area | Current development work |
| --- | --- |
| **KH1 first** | Development includes stereo rendering, head/body tracking, tracked Keyblade swing handling and native combat integration. |
| **Interaction** | Menu pointing, hand radials, climbing/ledge work, dialogue/cinematic handling and Gummi-flight adaptation are under development. |
| **Collection launcher** | A native Windows launcher checks the installed game and VR components, offers setup/repair, and presents collection entries in one library. |
| **Comfort and continuity** | Recenter/turning controls, game-settings preservation and continued use of the original save data are part of the local launcher design. |

## Target setup

- **Game / platform:** Windows Steam edition of KINGDOM HEARTS -HD 1.5+2.5 ReMIX-. KH1 Final Mix is the active conversion. Each future download will identify its supported executable/build.
- **VR setup:** Quest 3 / Touch controllers through Virtual Desktop is the documented development setup. A Windows PC, the supported installed game and a compatible OpenXR runtime are required.
- **Game ownership:** Supply your own required game files. No commercial game data, ROM, disc image, BIOS or save data is provided by this repository.

## Collection scope

| Entry | Current scope |
| --- | --- |
| Kingdom Hearts Final Mix | Active VR conversion; local development builds |
| Re:Chain of Memories | Planned; launcher placeholder |
| Kingdom Hearts II Final Mix | Planned; launcher placeholder |
| Birth by Sleep Final Mix | Planned; launcher placeholder |
| 358/2 Days HD cinematics | Planned VR theater presentation; not a playable game conversion |
| Re:coded HD cinematics | Planned VR theater presentation; not a playable game conversion |

This table describes the HD 1.5 + 2.5 collection work found in the project. It does not imply support for other Kingdom Hearts releases.

## Known limitations and next work

- KH1 has local headset testing history, but current combat, body alignment, menus, rendering transitions and comfort still need acceptance across the game.
- A launcher card is not evidence of completed VR support for that entry.
- No release date or collection-wide compatibility is promised.

Builds, automated checks and desktop captures do not by themselves establish headset comfort, full-game compatibility or a release-ready experience. The descriptions above distinguish implemented development work from unfinished work.

## Installing a future release

Installation instructions will accompany each published build. Until then, there is no supported public installation procedure or binary to download from this repository. Game-version and runtime requirements may change as development continues.

## Feedback

Use [Issues](https://github.com/NullxVoid00/Kingdom-Hearts-VR/issues) for questions or reports. For a future build, include its version, game version, headset/runtime and clear reproduction steps. Remove personal paths and private information from logs, and do not attach game files or saves.

## Credits

VR project by **NullxVoid / Abyssal Light Games**. This is an unofficial fan project and is not affiliated with or endorsed by the original game's creators or publishers.

Original games, names and assets belong to their respective owners. Upstream code and dependencies retain their own licenses. Future distributions will include the applicable notices and source obligations; this documentation hub does not relicense upstream or game material.

## Maintaining releases

See the [release guide](docs/RELEASE_GUIDE.md) and [release notes template](docs/RELEASE_TEMPLATE.md).

*Project information reviewed 2026-11-16 against local development documentation. This date is not a release or headset-certification date.*
