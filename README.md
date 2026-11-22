# Star Wars Episode I: Racer (N64)

Star Wars Episode I: Racer, the Nintendo 64 game, as a native program for PC,
PC VR, Meta Quest 3 and Steam Frame. Built from Game Or Die's own full
reconstruction of the game's code: not an emulator.

Play it on your monitor with a pad or the keyboard, or in VR with the race all
around you.

## Install

1. Download **`Star Wars Episode I Racer (N64) Installer.exe`** from the
   [latest release](../../releases/latest) and double-click it. (Windows may
   say it protected your PC: click More info, then Run anyway. It is not
   code-signed.)
2. Choose **PC**, **PC VR**, **Quest 3** or **Steam Frame**. It finds your
   cartridge file by itself; if not, drop the file (or its .zip) on the window.
3. Press **INSTALL**, then **PRESS START**.

### Steam Deck and Linux

The installer is for Windows. On a Steam Deck or a Linux PC:

1. In Desktop Mode, download **`SWE1R-N64-<version>-Linux.tar.gz`** from the
   [latest release](../../releases/latest), right-click it and choose
   **Extract**.
2. Open the folder and double-click **`Setup.sh`**. It finds your cartridge
   file by itself and adds the game to Steam with its pictures.
3. Back in Gaming Mode, it is in your Library under Non-Steam.

### Installing by hand

- `SWE1R-N64-<version>-Windows.zip`: PC and PC VR. Unzip and run `Setup.bat`
  (it finds your cartridge file and makes a shortcut for your monitor and one
  for VR), or just double-click `SWE1R-N64.exe`.
- `SWE1R-N64-<version>-Quest.zip`: Quest 3 (`Setup.bat`, over USB) and Steam
  Frame (`Setup Steam Frame.bat`).
- `SWE1R-N64-<version>-Linux.tar.gz`: Steam Deck and Linux, on the screen
  (`Setup.sh`, or run `swe1r-n64`).

`sha256sums.txt` lists every file's checksum.

## You need

Your own cartridge file of Star Wars Episode I: Racer for the Nintendo 64
(USA, first release: .z64, .n64 or .v64, any name, or a .zip with it inside).
Nothing of the game is in these downloads.

## License

All rights reserved. Free to install and play; nothing else is licensed. The
source code is not public. See [LICENSE](LICENSE).

Star Wars Episode I: Racer and its names belong to their owners. Nintendo 64
is a trademark of Nintendo. This project is not affiliated with or endorsed by
either.
