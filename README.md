# Nt-Mini-Legacy-Jailbreak

Custom _Jailbreak_ firmware [released by kevtris](https://atariage.com/forums/topic/242970-fpga-based-videogame-system/) for the original "OG" Analogue Nt Mini V1, released in 2017.

It supports the following cores:

- NES/Famicom
- Sega Master System
- Game Gear
- Colecovision
- Gameboy
- Gameboy Color
- Atari 2600
- Atari 7800
- Supervision
- Gamate
- Game King
- Channel F
- Arcadia 2001
- Creativision
- Adventure Vision
- Videobrain
- Odyssey<sup>2</sup>
- RCA Studio 2

Release notes and directions are included in README.txt within the zip file for the [latest jailbreak firmware (version 2.0)](https://github.com/tjanas/Nt-Mini-Legacy-Jailbreak/raw/main/firmware/ntm_firmware_verJB2.0.zip).

------------------------------

# NES/Famicom Core Release Notes

Save game RAM is saved in the current directory (typically the directory where the game is launched). Save game RAM filenames are truncated to the first 30 characters of the NES ROM, plus ".sav". For example, `Legend of Zelda, The (USA) (Re.SAV` will be created for `Legend of Zelda, The (USA) (Rev 1).nes`. 
