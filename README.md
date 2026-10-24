# Tagalong

Two people, one Silksong game.

Only the host's game really runs. The mod puts a second Hornet in it, and the guest sees
the host's game as video and sends their buttons back, so rooms, bosses and cutscenes can
never drift apart.

## Install

1. Download **Install-Tagalong.bat** from the [latest release](../../releases/latest).
2. Run it.

It finds Silksong through Steam, puts the mod loader in if you don't have it, and
downloads Tagalong. Then start Silksong as usual.

To play together, one of you invites the other through Steam. The guest stays on the
title screen; their screen switches to the host's game and their controls move the blue
Hornet.

## Updates

Nothing to do. Your game keeps itself current: most updates go in while you play, the
rest the next time you start. If an update needs a restart the game says so on screen.

To stay on the version you have, put an empty file called `TagalongUpdater.off` next to
`BepInEx/patchers/TagalongUpdater.dll` in your Silksong folder.

## Removing it

Delete `winhttp.dll` from your Silksong folder and the game goes back to normal.

---

This repo holds only the finished files. It replaces
[silksongbesties-releases](https://github.com/Jacobalicious/silksongbesties-releases).
