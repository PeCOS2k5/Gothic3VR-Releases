# Gothic 3 VR

**Gothic 3 VR** is an unofficial PC VR mod for Gothic 3, created and maintained by **PeCOS2k5**. Explore Myrtana in stereoscopic VR with 6DoF head and hand tracking, room-scale movement and physical crouching.

- Fight with physical melee swings, dual wield, two-handed weapons and shields. Draw a bow by hand, support a crossbow with both hands, and aim spells with a controller.
- Use the in-headset radial for quick slots, Quicksave and the main menu. Remap buttons, double taps and controller combinations in the launcher.
- Adjust camera and hand calibration, HUD, VR resolution and graphics settings. Optional Union+ 1.7.3 integration is available through the launcher's protected workflow.

## Requirements

- A copy of **Gothic 3** on an SSD. Steam, GOG and retail editions were tested with the patch versions below. **Forsaken Gods** is outside the supported editions.
- **Windows 10 or 11 (64-bit)**, a PC VR headset and two tracked controllers. The launcher supports **Virtual Desktop / VDXR**, **Meta Quest Link / Air Link**, and **SteamVR**. Quest 3 with Touch controllers was the reference configuration.
- For **Meta Link / Air Link**, install the [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vc14/vc_redist.x64.exe). The optional DXVK / FFR component requires Vulkan 1.4 and was tested on NVIDIA RTX.

## Install and launch

1. Install Gothic 3, start the flat game once, then exit.
2. Apply the following four native patches in order, using the same game folder. Download them separately from the VR installer.

   | Order | Patch | What to do |
   | --- | --- | --- |
   | 1 | [Community Patch 1.75.14](https://www.ds.thqnordic.com/gothic3ee/Gothic_3_EE_Patch_v1.75.14_Int_Full.exe) | Run the installer, then start and exit the flat game again. |
   | 2 | [Update Pack 1.04.11](https://drive.google.com/file/d/1-TVJcAT61D4fMvDNg67K2_TZqoTBpEXD/view) | Run the EXE before applying the beta. |
   | 3 | [Update Pack 1.05.10 Public Beta](https://drive.google.com/file/d/1PPdBRVHd5TYtrnqd0Na8HFUFyPV9Kzng/view) | Extract the complete ZIP over 1.04.11 and replace its supplied files. |
   | 4 | [Parallel Universe Patch 1.1.1](https://drive.google.com/file/d/1xD0x0GoadgotsDZL4dAjd0DDNRaOrFjk/view) | Install it last, then check that the flat game starts. |

   The two Update Packs are separate required steps. [Team Sefaris' patch page](https://www.sefaris.eu/g3-mod-pack/installation) also lists the patch downloads.

3. Close Gothic 3, the VR launcher and Union+. Run [**Gothic3VR-1.0.2-Setup.exe**](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/download/v1.0.2/Gothic3VR-1.0.2-Setup.exe) and select the folder containing `Gothic3.exe`. Keep **VR core** selected. Start with the optional DXVK / FFR component unchecked if your GPU configuration is untested.
4. Open the **Gothic 3 VR** launcher, choose your OpenXR runtime under **Camera & controls**, connect your headset and controllers, then select **Save and launch**. Recenter while facing forward by holding both stick clicks (**L3 + R3**) for half a second on the default bindings.

**Already using Gothic 3 VR?** Run Setup over the existing installation with the game and launcher closed. The update preserves saves, settings and calibration.

**Need the offline guide or source?** The full **Release.zip** contains the installer, **START-HERE.html**, controls and licenses. **Source.zip** is the corresponding source archive for that build.

[All releases](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases) · [Verify downloads](https://github.com/PeCOS2k5/Gothic3VR-Releases/blob/main/docs/VERIFY-RELEASES.md) · [Report a bug](https://github.com/PeCOS2k5/Gothic3VR-Releases/issues) · [Nexus Mods](https://www.nexusmods.com/gothic3/mods/115) · [Support development](https://ko-fi.com/pecos2k5)

## Credits and license

Gothic 3 belongs to its original developers and rights holders. Thanks to the Gothic 3 SDK contributors, native patch authors, and VR and graphics dependency authors. The corresponding source archives contain the project's GPL-3.0-or-later license and third-party notices.
