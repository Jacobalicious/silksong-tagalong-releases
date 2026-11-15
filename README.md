<div align="center">

# 🧵 Tagalong - Downloads

**Two people, one Silksong game. This is the download page for the Tagalong co-op mod.**

![Game](https://img.shields.io/badge/Hollow%20Knight-Silksong-8B1E3F?style=for-the-badge)
![Platform](https://img.shields.io/badge/Windows-Steam-1B2838?style=for-the-badge&logo=steam&logoColor=white)
[![Download](https://img.shields.io/badge/Download-latest%20release-2EA44F?style=for-the-badge&logo=github)](../../releases/latest)

</div>

## ✨ What it is

Tagalong lets a friend join your Silksong game as a second Hornet. Only the host's game really runs, and the guest
sees the host's game as video and sends their buttons back, so rooms, bosses and cutscenes can never drift apart.
This repo holds only the finished files; nothing here needs building.

## 📦 Install

1. Download **Install-Tagalong.bat** from the [latest release](../../releases/latest).
2. Run it.

It finds Silksong through Steam, puts the mod loader in if you don't have it, and downloads Tagalong. Then start
Silksong as usual.

To play together, one of you invites the other through Steam. The guest stays on the title screen; their screen
switches to the host's game and their controls move the blue Hornet.

## 🔄 Updates

Nothing to do. Your game keeps itself current: most updates go in while you play, the rest the next time you start.
If an update needs a restart the game says so on screen.

To stay on the version you have, put an empty file called `TagalongUpdater.off` next to
`BepInEx/patchers/TagalongUpdater.dll` in your Silksong folder.

## 🗑️ Removing it

Delete `winhttp.dll` from your Silksong folder and the game goes back to normal.

---

This replaces [silksongbesties-releases](https://github.com/Jacobalicious/silksongbesties-releases), the download page
of the earlier co-op mod.
