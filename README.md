# Gothic 3 VR

**Explore Myrtana in full stereoscopic PC VR.** Gothic 3 VR adds 6DoF head and hand tracking, room-scale movement, physical crouching, motion combat and controller-operated menus to the original Gothic 3.

[**Download Gothic 3 VR 1.0.6**](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/download/v1.0.6/Gothic3VR-1.0.6-Setup.exe) · [Release notes and full download](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/tag/v1.0.6) · [Report a bug](https://github.com/PeCOS2k5/Gothic3VR-Releases/issues)

[Install and launch](#install-and-launch) · [Default controls](#default-quest--touch-controls) · [Calibration and comfort](#calibration-and-comfort) · [Troubleshooting](#troubleshooting)

## What you can do

| Feature | In game |
| --- | --- |
| Physical combat | Swing and stab with one-handed weapons, dual wield, or use both hands to guide heavy weapons and staffs. Raise a weapon or shield to block. The game's skills, stamina and ammunition still apply. |
| Bows, crossbows and magic | Draw the bowstring by hand, steady a crossbow with your support hand, and aim spells with a controller. |
| Interactions and menus | Point to interact, use Quick Loot, and use the radial for quick slots with item names, icons and quantities, plus Quicksave and Main menu. The native quick-slot bar is shown in Inventory and the Spellbook. |
| Camera and tracking | Play in first person with tracked hands and weapons. Conversations and stationary activities use a stabilized third-person view by default. Dialogue, chests, lecterns, sleeping and shrines can be switched to first person under **Interaction**. Knockdown recovery uses third person. **Hands only** hides the first-person body. |
| Custom controls | Assign buttons, holds, double taps, two-button combinations and right-stick up/down. Test your controller inputs before entering a save. |

## Requirements and compatibility

- **Gothic 3** installed on an SSD. Steam, GOG and CD/retail were tested with the supported native patch profile. A separate copy of the game is required. **Forsaken Gods** is unsupported.
- **Windows 10 or 11 (64-bit)**, a VR-capable PC, a PC VR headset and two tracked controllers. The mod runs on the Windows PC.
- **Quest 3 with Touch controllers** is the reference headset. Other OpenXR profiles are available where the runtime exposes them. Check detected inputs and test bindings under **Headset setup**. Hardware support varies by headset, controller and runtime.

| How you connect | Launcher setting under Camera & controls → OpenXR runtime |
| --- | --- |
| Virtual Desktop | **Virtual Desktop / VDXR**. Start Virtual Desktop and connect the headset first. |
| Quest Link or Air Link | **Meta Quest Link / Air Link (64-bit host)**. Enter the Link environment before launching and install the [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vc14/vc_redist.x64.exe). |
| SteamVR | **SteamVR (OpenXR)**. Start SteamVR with both controllers active. If Steam captures the menu button, use **Main menu** on the radial's **Actions** page. |

## Install and launch

1. Install Gothic 3, launch it once on the desktop, then close it.
2. Run [**Gothic3VR-1.0.6-Setup.exe**](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/download/v1.0.6/Gothic3VR-1.0.6-Setup.exe) and select the folder that contains `Gothic3.exe`.
3. On a clean install, accept **automatic patch installation**. Setup downloads, verifies and installs the missing patches before installing VR. It skips patches that already match the supported files. The Community Patch download is about **1.6 GB**.
4. Keep **VR core** selected. DXVK / FFR, main-menu artwork and music are optional components. For an untested GPU, start with the optional DXVK / FFR component unchecked and set FFR to Off in the launcher.
5. Open the **Gothic 3 VR** launcher, choose your runtime, and connect your headset and controllers. Use **Headset setup → Start headset setup** to calibrate or **Save and launch** to start playing. Hold **L3 + R3 for 0.5 seconds** while facing forward to recenter.

**Updating from an earlier Gothic 3 VR release?** Close the game, launcher and Union+, then run Setup over the existing installation. The update preserves saves, settings, controller bindings and calibration.

<details>
<summary>Required patch versions and manual fallback</summary>

Setup uses these patches in order.

| Order | Patch | What to do if installing manually |
| --- | --- | --- |
| 1 | [Community Patch 1.75.14](https://www.ds.thqnordic.com/gothic3ee/Gothic_3_EE_Patch_v1.75.14_Int_Full.exe) | Run the installer, then start and exit the desktop game once. |
| 2 | [Update Pack 1.04.11](https://drive.google.com/file/d/1-TVJcAT61D4fMvDNg67K2_TZqoTBpEXD/view) | Run the EXE before applying the Public Beta. |
| 3 | [Update Pack 1.05.10 Public Beta](https://drive.google.com/file/d/1PPdBRVHd5TYtrnqd0Na8HFUFyPV9Kzng/view) | Extract the complete ZIP over 1.04.11, replacing the supplied files. |
| 4 | [Parallel Universe Patch 1.1.1](https://drive.google.com/file/d/1xD0x0GoadgotsDZL4dAjd0DDNRaOrFjk/view) | Install last and confirm the desktop game starts. |

If a download fails, choose **Retry** in Setup. You can also place the verified packages next to Setup.exe and run it again. **START-HERE.html** in [Release.zip](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/download/v1.0.6/Gothic3VR-1.0.6-Release.zip) lists the expected filenames and complete instructions. Use **Camera & controls → Check installation** to see which patch files match.

</details>

## Default Quest / Touch controls

**L3** and **R3** mean pressing the left or right stick as a button.

| Input | Action |
| --- | --- |
| Left stick / L3 tap | Move / sprint until you stop moving |
| Right stick / R3 tap | Turn / open the radial |
| Right stick, then A | Choose and confirm a radial entry. B changes page and X closes it. |
| Right trigger | Interact, cast or fire a crossbow. Hold and release when drawing the bow. |
| Right grip | Quick Loot or block with a raised weapon, depending on context. Transfers one item in trade. |
| Left grip | Attach the support hand to a compatible weapon, or block with a raised shield when using a one-handed weapon. |
| B / X outside the radial | Draw or sheath weapon / open inventory |
| Double-tap Y / double-tap left trigger | Toggle Sneak / use a health potion from inventory |
| L3 + R3 held for 0.5 seconds | Recenter |
| Left controller menu button | Main menu or Back. The radial also offers Main menu. |

## Calibration and comfort

1. With Gothic 3 closed, open **Headset setup → Start headset setup**.
2. In the headset, point at a setup button and squeeze either trigger. Use **Test controls** to see detected inputs, **Remap controls** to change bindings, or **Start calibration** to set your height and align your hands.
3. If you have a save in a safe place, choose **Load a save** in the guide to finish hand calibration there. Starting fresh? Choose **Save & finish**, then open **Radial → Actions → Calibrate hands** once you reach a safe spot in the same setup session.

| Setting | Where to find it and how it works |
| --- | --- |
| **Player height** | **Camera & controls**. Enter your full standing height, enable **Match player height**, save and recenter while standing. The headset guide edits the same calibration. |
| **Seated mode** | **Camera & controls**. Save and recenter while seated. The seated camera height is separate and room-scale walking and physical crouching are disabled in this mode. |
| **Snap turn and motion vignette** | **VR comfort settings**. Choose smooth turning or 30°/45° snap turns. Use the vignette to dim the edges during stick movement. |
| **Third-person orbit** | **VR comfort settings**. Use the right stick to orbit the character during supported third-person interactions. |
| **VR World Scale** | **VR comfort settings**. 100% is the default. 80% makes the world feel smaller and 120% makes it feel larger. Save and restart Gothic 3 to apply it. |

## Performance and optional mods

- **If gameplay stutters**, lower **Output resolution per eye** first and compare the same location. Busy towns and large fights can remain CPU limited. Raise draw distance, vegetation distance or NPC simulation range one at a time in **INI tweaks** so you can see the cost of each change.
- **Fixed foveated rendering** requires the bundled compatible DXVK backend and has been tested on NVIDIA RTX hardware. FXAA and SMAA are available in **Graphics**.
- **Union+ is optional.** First verify that the base VR install works. For [Union+ 1.7.3](https://www.nexusmods.com/gothic3/mods/46?tab=files), use **Optional mods → Open protected Union+** in the VR launcher. It protects the VR files while Union+ applies mods. **ICS Classic Camera is not recommended** with Gothic 3 VR.

## Troubleshooting

| Symptom | First thing to check |
| --- | --- |
| The game opens flat on the monitor | Check **OpenXR runtime** in the launcher. Connect the headset through that provider before launch, then use **Check installation**. On Meta Link, verify that Quest Link is active and the x64 Visual C++ runtime is installed. |
| Setup reports missing or unsupported patches | Confirm Setup points at the correct `Gothic3.exe`. Use a clean game folder for automatic patching. For a modified installation, use the manual fallback above and check the actual patch files in the launcher. |
| Setup reports a graphics wrapper conflict | Remove the old third-party wrapper using its own uninstall steps, then retry. Setup detects unknown `d3d9.dll`, `dxgi.dll` and `d3d11.dll` proxies. |
| Controller buttons seem missing | Open **Headset setup → Start headset setup**, then choose **Test controls** and check the active OpenXR profile. Assign a button the runtime reports. For Main menu, the radial bypasses the system menu button. |
| Duplicate filename warning | Move old VR DLL/INI backups and extracted installers outside the Gothic 3 directory. Gothic scans its resource subfolders. |
| VR stopped working after Union+ | Close Union+ and use **Optional mods → Verify / recover VR**. |

When [reporting a bug](https://github.com/PeCOS2k5/Gothic3VR-Releases/issues/new), include the mod version, game edition, headset and controllers, selected VR provider, optional mods, and steps to reproduce. Logs are in `scripts/Gothic3VRDiagnostics/logs` under the game folder. Attach the latest relevant `diagnostic-*.jsonl` or `stereo-game-*.jsonl` if available.

## Downloads, credits and support

[All releases](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases) · [Verify release checksums and signatures](docs/VERIFY-RELEASES.md) · [Nexus Mods](https://www.nexusmods.com/gothic3/mods/115) · [Support development on Ko-fi](https://ko-fi.com/pecos2k5)

Created and maintained by **PeCOS2k5**. Gothic 3 belongs to its original developers and rights holders. Thanks to the Gothic 3 SDK contributors, native patch authors, and VR and graphics dependency authors. The corresponding source archive on each release contains the project's GPL-3.0-or-later license, build instructions and third-party notices.

