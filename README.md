# Gothic 3 VR

**Gothic 3 VR** is an unofficial PC VR mod for Gothic 3, created and maintained by **PeCOS2k5**. Explore Myrtana in stereoscopic VR with 6DoF head and hand tracking, room-scale movement and physical crouching.

- Fight with physical melee swings, dual wield, two-handed weapons and shields. Draw bows by hand, support crossbows with both hands and aim spells with a controller.
- Use the in-headset radial for quick slots, Quicksave and the main menu. Bind actions to buttons, double taps and two-button combinations.
- Calibrate in the headset. Test the detected controller inputs, remap actions, set your standing height and align both hands. With Gothic 3 closed, select **Start headset setup** in **Hands**, **VR comfort settings** or **Controller mapping**.
- Choose smooth or snap turning, a motion vignette, third-person orbit and **VR World Scale** from **80% to 120%** in **VR comfort settings**. **Camera & controls** has **Player height** and a separate seated profile. Save and restart the game after changing world scale.
- Adjust the HUD, VR resolution and graphics in the launcher. Optional Union+ 1.7.3 integration is available through the protected workflow.

## Requirements

- A copy of **Gothic 3** installed on an SSD. Steam, GOG and retail editions were tested with the supported native patch profile. Forsaken Gods is outside the supported editions.
- **Windows 10 or 11 (64-bit)**, a PC VR headset and two tracked controllers. The launcher supports **Virtual Desktop / VDXR**, **Meta Quest Link / Air Link**, and **SteamVR**. Quest 3 with Touch controllers was the reference configuration.
- For **Meta Link / Air Link**, install the [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vc14/vc_redist.x64.exe). The optional DXVK / FFR component requires Vulkan 1.4 and was tested on NVIDIA RTX.

## Install and launch

1. Install Gothic 3, start it once on the desktop, then exit.
2. Run [**Gothic3VR-1.0.3-Setup.exe**](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/download/v1.0.3/Gothic3VR-1.0.3-Setup.exe) and select the folder containing `Gothic3.exe`.
3. On a clean install, accept the prompt to download and install the missing native patches. Setup verifies the downloads and installs Community Patch 1.75.14, Update Pack 1.04.11, Update Pack 1.05.10 Public Beta, and Parallel Universe Patch 1.1.1 in order. It skips supported patches already in place. The Community Patch download is about 1.6 GB.
4. Open the **Gothic 3 VR** launcher, select your OpenXR runtime under **Camera & controls** and connect your headset. Choose **Start headset setup** to calibrate or **Save and launch** to play. With the default bindings, hold **L3 + R3** for half a second while facing forward to recenter.

**Updating?** Close Gothic 3, the VR launcher and Union+, then run Setup over the existing installation. Your saves, settings, controller bindings and calibration are preserved.

If automatic patching cannot proceed, the **START-HERE.html** guide in **Release.zip** lists the verified downloads and manual steps. In the launcher, **Camera & controls → Check installation** shows the detected patches and OpenXR runtime.

[All releases](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases) · [Verify downloads](https://github.com/PeCOS2k5/Gothic3VR-Releases/blob/main/docs/VERIFY-RELEASES.md) · [Report a bug](https://github.com/PeCOS2k5/Gothic3VR-Releases/issues) · [Nexus Mods](https://www.nexusmods.com/gothic3/mods/115) · [Support development](https://ko-fi.com/pecos2k5)

## Credits and license

Gothic 3 belongs to its original developers and rights holders. Thanks to the Gothic 3 SDK contributors, native patch authors, and VR and graphics dependency authors. The corresponding release source archives include the project's GPL-3.0-or-later license and third-party notices.

