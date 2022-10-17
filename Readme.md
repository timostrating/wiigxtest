1. Install version v1.02 of devkitPro https://github.com/devkitPro/pacman/releases/tag/v1.0.2
2. Fetch all the new packages `sudo dkp-pacman -Sy`.
3. Install the new packages `sudo dkp-pacman -Syu`.
4. Install the Wii development tools `sudo dkp-pacman -S wii-dev`.
5. open a new terminal and navigate to the root of this repository.
6. Run make `make`, this automaticcally calls make build.
7. A wiigxtest.dol file will now be created. Load this in an emulator such as Dolphin-emu to see the result.