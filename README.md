# HQ General

EA has not endorsed and does not support this product.

I started HQ General because I love playing *Command & Conquer: Generals – Zero Hour* and wanted to play it on my phone. The Android port keeps the original game's battles and adds touch controls for selecting an army, giving orders and managing production on a small screen. — Xlucu

**[Download HQ General for Android](https://github.com/xlucu/HQ-General/releases/latest/download/HQ-General.apk)** · [Release notes](https://github.com/xlucu/HQ-General/releases/latest) · [Download the corresponding source](https://github.com/xlucu/HQ-General/releases/latest/download/HQ-General-source.zip)

## Install on Android

You need a 64-bit ARM Android device (Android 7.0 or later) with Vulkan 1.1 support, and your own supported PC installation of both *Generals* and *Zero Hour*. The download contains the Android application. You supply the original game data.

1. On your phone, put both PC game folders inside one parent folder. Keep the files and subfolders in their original layout.
2. Install the APK and open **HQ General**. Tap **Choose game folder**, select the parent folder and allow access. The importer searches its subfolders, checks the files and prepares the game. Give it time to finish on the first launch.
3. **Read the touch guide before your first match.** From the main menu, open **Android settings → Controls → Guide: Simplified → Read offline**. Start with camera movement, selection and the command ring. You can also choose **Save PDF locally** to keep the guide on your phone. For the second preset, open **Guide: Advanced**.

## Android settings

| Open | What you can do |
| --- | --- |
| **Display** | Adjust the view, split-screen layout, frame-rate target and thermal settings. The renderer can target 60 FPS while the simulation runs at 30 updates per second. Large battles may run more slowly. |
| **Language** | Choose from 15 interface languages. Restart the game to apply your selection. Voice audio follows the installed game data. |
| **Controls** | Choose a touch preset, edit gesture assignments, configure keyboard and mouse input, and save up to three production groups for each building type in each army. The illustrated guides cover the command ring, drawing a route, the Humvee joystick and recalling groups. |
| **Play online** | Read the step-by-step phone multiplayer guide, including how to set up the virtual network and find the host's address. |
| **Game maintenance** | Schedule a file check and repair for the next launch, or export a diagnostic report when troubleshooting. |
| **Add a map** | Import a skirmish map or a ZIP map pack from your phone. The touch guide also explains the folder layout. |

## Multiplayer

HQ General multiplayer is **Android phone to Android phone**. PC players cannot join these matches. Use the same HQ General version and map on every phone.

On the same local network, use the game's **Multiplayer → Network** menu. To play from different homes today, the in-game guide walks each player through **ZeroTier One** and **Direct Connect**. Start with **Android settings → Play online**. The host shares the host phone's ZeroTier IPv4 address privately with the other players.

We want players to be able to connect from inside HQ General without installing a separate networking app. If you or your group can **rent servers and provide the project with hosting**, please email Xlucu with the available regions, bandwidth and hosting term. With hosting in place, we can develop and test the service. This is a future project, and hosting offers do not grant gameplay perks.

## Platforms and contact

This release is for **Android only**. An iOS version is planned for the future.

- **Bugs and suggestions:** [Open a GitHub issue](https://github.com/xlucu/HQ-General/issues). For a bug, include your phone model, Android version, HQ General version and the steps that reproduce it.
- **Private contact and hosting offers:** [xlucugamer@gmail.com](mailto:xlucugamer@gmail.com).

## Credits and licensing

Xlucu leads the Android gameplay design, engine adaptation and integration for HQ General. This work builds on Electronic Arts' released engine, community Android and renderer ports, and community fixes. See [Credits](CREDITS.md) and the [engine license and EA additional terms](LICENSE.md). HQ General is a free, non-commercial community project. Original game assets and trademarks belong to their respective owners.
