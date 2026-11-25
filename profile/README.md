<div align="center">

<img src="https://raw.githubusercontent.com/retrogc/retrogc-launcher/main/Data/retrogc-256.png" alt="Retro Game Card logo" width="180" />

# Retro Game Card

### 🕹️ Plug in a card. Play the game. That's it.

[![Windows](https://img.shields.io/badge/Windows-x64-0078D6?style=for-the-badge&logo=windows&logoColor=white&labelColor=0A0C12)](https://github.com/retrogc/retrogc-launcher)
[![Linux](https://img.shields.io/badge/Linux-x64-FCC624?style=for-the-badge&logo=linux&logoColor=white&labelColor=0A0C12)](https://github.com/retrogc/retrogc-launcher)
[![Recalbox](https://img.shields.io/badge/Recalbox-10-3D9CE8?style=for-the-badge&labelColor=0A0C12)](https://github.com/retrogc/retrogc-launcher#-recalbox)
[![MiSTer](https://img.shields.io/badge/MiSTer-FPGA-E5426E?style=for-the-badge&labelColor=0A0C12)](https://github.com/retrogc/retrogc-launcher#-mister-fpga)

</div>

---

Remember blowing into a cartridge, pushing it in, and the game just *starting*? **Cartridges are back,
on USB sticks.** A Retro Game Card holds one game (ROMs, BIOS, cover art and a tiny `.rgc` file that
describes it), and turns any PC, Recalbox or MiSTer into a plug-and-play retro console.

No menus to browse, no emulator to configure. **Insert coin… er, card.** 🪙

## 🎮 How it works

```text
   💾 pick a card   ──▶   🔌 plug it in   ──▶   🕹️ the game starts
                                                  pull it out: back to the waiting screen
```

**One card, everywhere.** The same stick starts its game on Windows, Linux, Recalbox and MiSTer FPGA.

## 🧩 The projects

| | Project | What it does |
|:-:|---|---|
| 🕹️ | [**retrogc-launcher**](https://github.com/retrogc/retrogc-launcher) | The heart of it: the Windows / Linux launcher that watches for cards and starts the game in RetroArch, the MiSTer FPGA and Recalbox background scripts, and the `.rgc` card format. |
| 📺 | [**retrogc-launcher-mister**](https://github.com/retrogc/retrogc-launcher-mister) | The launcher screen, native on MiSTer FPGA: cover art and details on your TV (HDMI or a good old 15 kHz CRT), press **A** to play. The stock MiSTer menu stays one button away. |
| 💳 | [**retrogc-installer**](https://github.com/retrogc/retrogc-installer) | RetroArch and all its emulator cores, packaged for the launcher, plus the ready-to-flash **installer card** that sets up a computer offline in one go. |
| 🛠️ | [**retrogc-creator**](https://github.com/retrogc/retrogc-creator) | The card workshop: a desktop app to create and edit cards, add their files, open card images, build the `.img.xz` and write it to a USB stick. |
| 🎨 | [**retrogc-covers**](https://git.mydedibox.fr/cpasjuste/retrogc-covers) | Printable box art for the USB stick cases, with GIMP templates per platform. Because a game deserves a shelf. |

## 🚀 Press START (in about 60 seconds)

1. ⬇️ Grab `retrogc-installer-<version>.img.xz` from the
   [**retrogc-installer releases**](https://github.com/retrogc/retrogc-installer/releases/latest).
2. 🔥 Flash it to a USB stick with [balenaEtcher](https://etcher.balena.io/).
3. ▶️ Run `retrogc-launcher` from the stick and click **Install**: launcher, RetroArch and cores, no internet needed.
4. 🎴 Plug in a game card (or [make your own](https://github.com/retrogc/retrogc-creator)) and play!

On a MiSTer or a Recalbox? One script and you're done:
[MiSTer](https://github.com/retrogc/retrogc-launcher#-mister-fpga) ·
[Recalbox](https://github.com/retrogc/retrogc-launcher#-recalbox).
On MiSTer, the launcher screen even runs on a CRT. Your Trinitron has been waiting for this. 📺

## 🏆 High scores

| Rank | System | Cards seen in the wild |
|:-:|---|---|
| 🥇 | **Arcade** | Final Fight, Street Fighter III, Sunset Riders, Turtles in Time… |
| 🥈 | **Neo Geo** | Metal Slug, Blazing Star, Shock Troopers, Windjammers |
| 🥉 | **NES** | Super Mario Bros, Bart vs. the Space Mutants |
| 4 | **Amiga** | Rick Dangerous |
| 5 | **PlayStation** | Metal Gear Solid (yes, multi-disc) |

<sub>Any system RetroArch (or your MiSTer) can run fits on a card. Your favorite is one `.rgc` away.</sub>

---

<div align="center">

**GAME OVER?** Never. **CONTINUE?** ▶️ **YES**

Made with ❤️ for retro gaming · Free software under the [GPL-3.0](https://github.com/retrogc/retrogc-launcher/blob/main/LICENSE)

<sub>Retro Game Card ships no games. Only use ROMs you legally own.</sub>

</div>
