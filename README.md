<p align="center">
  <img src="screenshots/mark.webp" width="132" alt="Spades Client">
</p>

<h1 align="center">Spades Client</h1>

<p align="center">
  <b>121 modules for Minecraft 1.21.11 on Fabric.</b><br>
  Dark-red glass, tight spacing, and a HUD you can drag into place.
</p>

<p align="center">
  <a href="https://spades.clienturl.net/"><b>Download</b></a> &nbsp;·&nbsp;
  <a href="https://spades.clienturl.net/#modules">Module list</a> &nbsp;·&nbsp;
  <a href="https://spades.clienturl.net/#install">Install</a>
</p>

<p align="center">
  <img src="screenshots/promo-1280x720.png" alt="Spades Client" width="720">
</p>

---

## What this is

Spades is a client-side utility mod for Minecraft 1.21.11. It adds a module menu, a
customisable HUD, and a catalogue of combat, movement, render and base-raid modules.
Everything runs on your own machine: no account, no telemetry, no background service.

This repository ships **builds and documentation only**. It is closed source; there is no
source code here.

## Requirements

| | |
|---|---|
| Minecraft | 1.21.11 |
| Loader | Fabric Loader 0.20.1 (0.16.0 or newer works) |
| Java | 21 |
| OS | Windows, macOS, Linux |

## Install

1. Install **Fabric Loader** for **1.21.11**.
2. Download the jar from [spades.clienturl.net](https://spades.clienturl.net/).
3. Drop it into `.minecraft/mods`.
4. Launch the **Fabric 1.21.11** profile.
5. Press **Right Shift** to open the menu.

Profiles and layouts are written to `.minecraft/config/spades`. Delete that folder to reset.

## Modules

| Suit | Modules |
|---|---:|
| Combat | 20 |
| Movement | 18 |
| Render | 18 |
| Visuals | 18 |
| Misc | 15 |
| Donut | 13 |
| Base Raid | 11 |
| Spades Client | 8 |
| **Total** | **121** |

715 settings are exposed in the menu, and every HUD element can be dragged, scaled and
toggled from **Edit HUD**.

## Version

**0.9.9+mc1.21.11** — `spades-client-0.9.9+mc1.21.11.jar`

```
sha256 52045b383ae3783dba9116b76edbbed70e48ead477ad151c94f59ce834983bae
```

Verify on Windows:

```powershell
Get-FileHash .\spades-client-0.9.9+mc1.21.11.jar -Algorithm SHA256
```

## FAQ

**Does it work on any server?**
Module behaviour always depends on the server and the anticheat in use. There are no
universal detection guarantees.

**Do I need an account or a key?**
No. The jar is the whole product.

**Will it conflict with Sodium or OptiFine?**
Sodium works. OptiFine and OptiFabric are explicitly incompatible; the mod refuses to load
with them.

**How do I report a bug?**
Open an issue here with your log and the exact steps. Do not paste session tokens.

## License

The jar is distributed under **GPL-3.0-only**, matching the licence declared in its
`fabric.mod.json`. Source is not published in this repository; buildable source is provided
to recipients on request, as the licence requires.
