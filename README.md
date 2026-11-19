# Sekiro Haptics

Haptic feedback for **Sekiro: Shadows Die Twice** on PC, driven by what happens in the game:
your blocks and deflects, enemies blocking your attacks, prosthetic tools, Mikiri Counter, the stomp
and Lightning Reversal.

| Controller | Output | Status |
|---|---|---|
| DualSense (USB) | PCM haptics, adaptive triggers, optional controller-speaker sounds | Supported |
| Xbox controller | Rumble | Experimental (since alpha.9) |

The program only **reads** the game's memory: no memory writes, no injection, no hooks.
This is alpha software.

## Download

**Latest: [v0.1.0-alpha.9](https://github.com/MHKim-mods/sekiro-haptics/releases/tag/v0.1.0-alpha.9)**
(Xbox controller support, vibration strength setting)

| Version | Download | SHA-256 |
|---|---|---|
| v0.1.0-alpha.9 | [SekiroHaptics-0.1.0-alpha.9-win64.zip](https://github.com/MHKim-mods/sekiro-haptics/releases/download/v0.1.0-alpha.9/SekiroHaptics-0.1.0-alpha.9-win64.zip) | `d5dc710e758bb80455a7834c57c28762d685948dbecc6d135d8a190405ce51a5` |
| v0.1.0-alpha.8 | [SekiroHaptics-0.1.0-alpha.8-notices-corrected-win64.zip](https://github.com/MHKim-mods/sekiro-haptics/releases/download/v0.1.0-alpha.8/SekiroHaptics-0.1.0-alpha.8-notices-corrected-win64.zip) | `55b77608736aeade9b1d2993661998a733e0f9d813bf1f42405f42f42bf18545` |

All versions are listed on the [Releases](https://github.com/MHKim-mods/sekiro-haptics/releases) page.

## Install and run

1. Windows 10/11 64-bit and the Sekiro PC build named in the ZIP's `README.txt` (other builds are refused).
2. Download the ZIP and unzip it anywhere you can write to. It does not go into the game folder.
3. Connect **one** controller: a DualSense with a USB cable, or an Xbox controller.
4. Start Sekiro and load your save.
5. Double-click `Start.cmd` and answer the questions: sound mode, volume and vibration strength.
   Press Enter to keep the default.
6. To stop, press Ctrl+C or close the window.

See `README.txt` in the ZIP for details and known issues. When you report a problem, include the version from `BUILD_INFO.txt`.
