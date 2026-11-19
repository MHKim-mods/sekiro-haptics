# Sekiro Haptics — controller feedback that responds to combat

Sekiro Haptics is an independent Windows utility that adds game-event-driven feedback for **Sekiro: Shadows Die Twice** on PC. Rather than using the same vibration for every action, it responds to detected combat events, including deflects, enemy reactions, prosthetic tools, Mikiri Counter, stomps and Lightning Reversal.

## Controller support

- **DualSense (USB):** PCM haptics, adaptive triggers and optional controller-speaker sounds.
- **Xbox controllers:** Experimental rumble support introduced in **alpha.9**. Please read the known issues before using it.
- **DualSense Edge:** Experimental; not yet verified on real Edge hardware.

## Installation

Download the ZIP from the [Releases](https://github.com/MHKim-mods/sekiro-haptics/releases) page and read its included README.txt for installation and game-version requirements. Extract the full package to a writable folder outside the Sekiro game directory, start Sekiro, connect one supported controller, and run Start.cmd. The utility reads the game’s memory without writing to it or injecting code.

## Latest experimental build

The latest alpha.9 preview introduces Xbox rumble and vibration strength settings. It is **experimental**, not a stable release. The release history, downloads and detailed notes are on the [Releases](https://github.com/MHKim-mods/sekiro-haptics/releases) page:

- [v0.1.0-alpha.9](https://github.com/MHKim-mods/sekiro-haptics/releases/tag/v0.1.0-alpha.9) — Xbox rumble (experimental), vibration strength setting
- [v0.1.0-alpha.8](https://github.com/MHKim-mods/sekiro-haptics/releases/tag/v0.1.0-alpha.8) — DualSense only

Check the included notes before choosing an experimental build.

## Known issues

Some combat events, including stomps, may occasionally fail to trigger feedback. Xbox support is still being tested, especially sleep/reconnect and wireless use. No game crash is currently known from this intermittent detection issue, but this is not a guarantee of crash-free operation.

## Feedback

When reporting issues, please include your mod version, game executable version, controller model and connection type, steps to reproduce, and relevant logs with personal/device details removed.

*Independent fan-made project; not affiliated with FromSoftware, Sony or Microsoft.*
