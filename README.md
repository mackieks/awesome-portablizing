 # ✨🎮 Awesome Portablizing 👾✨

A curated list of portablizing and portablizing-adjacent modding projects for various video game consoles, with a focus on cool and/or open-source hardware & software!

## Contents

* [Community](#community)
* [Hardware](#hardware)
    * [Nintendo](#nintendo)
        * [NES](#nes)
        * [SNES](#snes)
        * [N64](#n64)
        * [GameCube](#gamecube)
        * [Wii](#wii)
    * [Sony](#sony)
        * [PS1](#pa1)
        * [PS2](#ps2)
    * [Sega](#sega)
        * [Master System](#ms)
        * [Mega Drive / Genesis](#md)
* [Software](#software)
* [Guides](#guides)
* [Documentation](#documentation)
* [Videos](#videos)

## Community

* [BitBuilt - Giving Life to Old Consoles](https://bitbuilt.net) -The home of modern portablizing since 2016

BitBuilt.net is where GC, Wii, N64, NES, SNES, Virtual Boy, PS1, PS2, Dreamcast, Saturn, Xbox, Xbox 360, and Wii U portablizing have all been taken even further beyond.

The BB forums are an invaluable resource; the various console boards have literally thousands of threads and worklogs, containing vast amounts of portablizing knowledge and info.

## Hardware

### Nintendo
#### NES
* [TinyTendo](https://github.com/Redherring32/TinyTendo) - An open source Gameboy sized handheld NES using real hardware
* [TNY-NROM](https://github.com/MouseBiteLabs/TNY-NROM) - Custom NROM cartridge PCBs for TinyTendo
* [TinyNES](https://github.com/loglow/TinyNES) - Open source miniature NES console
* [OpenTendo](https://github.com/Redherring32/OpenTendo) - An open source hardware recreation of the 1985 frontloading NES
* [OpenTendo Toploader](https://github.com/Redherring32/OpenTendo-TopLoader) - An open source hardware recreation of the 1993 toploading NES (NES-101)
* [fiNESse](https://github.com/mmoracantallops/fiNESse) - TinyNES, NESRGB, OpenTendo and Power Module Redesign in one PCB
* [NullCIC](https://github.com/Redherring32/NullCIC) - CIC replacement for NES
* [PicoPad](https://github.com/Redherring32/PicoPad) - World's smallest functional NES controller
* [NES ProtoCart](https://github.com/Redherring32/NES-ProtoCart) - Protoboard NES cartridge
* [FDSKey](https://github.com/ClusterM/fdskey) - Open source, low cost Famicom Disk System Emulator
* [COOLGIRL](https://github.com/ClusterM/coolgirl-famicom-multicart) - Open source hardware ultimate multigame cartridge for Famicom
* [FamicomPowerBoard](https://github.com/hakkslab/FamicomPowerBoard) - Open source power board replacement for Famicom which adds AV RCA jacks

#### SNES
* [nonSNES](https://github.com/stonedDiscord/nonSNES) - An open source recreation of the SNSP-CPU-01 Rev5 SNES motherboard
* [snesp](https://github.com/tdoug870/snesp) - An old school SNES portable using a PSOne screen, designed in openSCAD
* [αSNES](https://bitbuilt.net/forums/index.php?threads/2022-contest-entry-%CE%B1snes.5055/) - Incomplete SNES portable based on 1-Chip motherboard redesign
* [Lazy Man's SNES Reset](https://github.com/Nold360/lazy_mans_snes_reset) - In-game reset for SNES, activated by button combo
* [SNES Dejitter](https://github.com/marqs85/snes_dejitter) - Dejitter mod for NES/SNES
* [SNES Multi-Region with Dejitter](https://github.com/borti4938/SNES_MultiRegion_with_DeJitter_QID) - Region-free mod with SuperCIC, dejitter, and IGR
* [SNES Jr. (SNN-CPU-01) Board Scans](https://bitbuilt.net/forums/index.php?threads/snes-jr-snn-cpu-01-scans.3488/) - 2400DPI Jr. scans + digital audio pinout
* [sd2snes](https://github.com/mrehkopf/sd2snes) - Open source SNES flashcart that supports every enhancement chip
* [sd2snes-ecp5](https://github.com/samlittlewood/sd2snes_ecp5) - Port of sd2snes to ECP5. Enhancement chip support incomplete.

#### N64
* [usb64](https://github.com/Ryzee119/usb64) - Feature-packed controller (CNT-NUS) emulator for N64. Works standalone or with USB controllers
* [atmega328-N64-controller](https://github.com/jtryba/atmega328-N64-controller) - 328P-based N64 controller emulator with rumble and memory pak support.
* [cube64-dx](https://github.com/darthcloud/cube64-dx) - Adapter to use GameCube controllers on N64
* [N64-Controller-Module](https://github.com/Gmanmodz/N64-Controller-Module) - Replacement N64 controller PCB for portables. Uses CNT-NUS and FRAM for mempak
* [N64-Joystick-Converter](https://github.com/Gmanmodz/N64-Joystick-Converter) - PIC application code to connect pot-based joysticks to CNT-NUS
* [N64 Stick Converter PCB v3](https://github.com/Nold360/n64_stick_converter) - AVR-based N64 stick converter by Jakob Schäfer
* [64AMP](https://github.com/Gmanmodz/64AMP) - Digital audio amp for N64 based on LM49450
* [N64-FRAM-Memory-Pak](https://github.com/Element18592/N64-FRAM-Memory-Pak) - An FRAM-based N64 controller pak replacement
* [SummerCart64](https://github.com/Polprzewodnikowy/SummerCart64) - Robust OSHW FPGA-based N64 flashcart
* [Brutzelkarte (PCB](https://github.com/jago85/Brutzelkarte_PCB)[/Gateware)](https://github.com/jago85/Brutzelkarte_FPGA) - Prototype FPGA-based N64 flashcart
* [DaisyDrive64](https://github.com/nopjne/DaisyDrive64) - In-development STM32H750-based N64 flashcart
* [El Barato 64](https://github.com/Hazematman/El-Barato-64) - Incomplete FPGA-based N64 flashcart
* [PicoCart64](https://github.com/kbeckmann/PicoCart64) - RP2040-based N64 flashcart (development stalled)
* [N64cart](https://github.com/pdaxrom/N64cart) - In-development RP2040 N64 flashcart based on PicoCart64
* [UltraPIF (PCB](https://github.com/jago85/UltraPIF_Hardware)[/Gateware](https://github.com/jago85/UltraPIF_FPGA)[/Firmware)](https://github.com/jago85/UltraPIF_MCU) - FPGA-based N64 PIF replacement
* [N64RGB, N64Advanced](https://github.com/borti4938/n64rgb_project_overview) - A series of FPGA-based HDMI mods for the N64 by borti4938
* [GCVideo Lite](https://github.com/ikorb/gcvideo) - FPGA-based replacement video DAC for N64
* [PPR](https://bitbuilt.net/forums/index.php?threads/ppr.910/) - An epic thread documenting the first working N64 motherboard reimplementation
* [N64-AIO](https://bitbuilt.net/forums/index.php?threads/n64-aio.3883/) - Gman's working N64 motherboard reimplementation
* [N64 Tríos](https://bitbuilt.net/forums/index.php?threads/n64-tr%C3%ADos-a-3x3-inspired-motherboard-redesign.5029/) - SparkleBear's in-progress N64 motherboard reimplementation
* [N64 Micro](https://bitbuilt.net/forums/index.php?threads/n64-micro.6204/) - thedrewm's in-progress N64 motherboard reimplementation

#### GameCube
* [GC+](https://github.com/Aurelio92/GCPlus) - PIC18F-based GameCube controller emulator
* [GC+ 2.0](https://github.com/Aurelio92/GCPlus-2.0) - Improved GameCube controller emulator
* [pico-rectangle](https://github.com/JulienBernard3383279/pico-rectangle) - RP2040-based GameCube fightstick
* [PhobGCC](https://github.com/PhobGCC) - RP2040-based GameCube controller emulator with hall-effect sticks
* [JohbGCC](https://github.com/8n1/JohbGCC) - Phob fork with DFM improvements
* [BlueRetro HW2 GameCube QSB](https://github.com/Arthrimus/BlueRetro-HW2-GameCube) - BlueRetro GameCube add-on board
* [SD2SP2](https://github.com/citrus3000psi/SD2SP2) - Open source Serial Port 2 to microSD adapter
* [SD2SP2 Nano](https://github.com/ndoo/SD2SP2-Nano) - Tiny Serial Port 2 to microSD adapter
* [SD2SP2 Pro](https://github.com/misteraddons/SD2SP2-Pro) - Improved Serial Port 2 to microSD adapter
* [XenoGC-Flex](https://github.com/HDR/XenoGC-Flex) - Flex PCB XenoGC clone
* [PicoBoot](https://github.com/webhdx/PicoBoot) - Open source Pico-based IPL modchip
* [NeoPicoBoot](https://github.com/paulmreese/NeoPicoBoot) - Fork of PicoBoot with Wi-Fi controlled RGB LEDs
* [weird-flex-boot-ok](https://github.com/GameboxSystems/weird-flex-boot-ok) - Flex PCB for installing Picoboot
* [KunaiGC](https://github.com/KunaiGC/KunaiGC) - Open source FPGA-based IPL modchip
* [flippydrive](https://github.com/OffBroadway/flippydrive) - Upcoming open source RP2040/ESP32-based GameCube ODE
* [DOL-PD](https://github.com/sj3603/DOL-PD) - USB-C PD mod for GameCube
* [GCVideo](https://github.com/ikorb/gcvideo) - FPGA-based DVI/HDMI mod for GameCube
* [GCVideo-Hardware-Designs](https://github.com/citrus3000psi/GCVideo-Hardware-Designs) - Various closed-source GCVideo PCB designs
* [Shuriken Video](https://github.com/novi/shuriken-video) - Old GCVideo PCB design
* [GameCube Wasp QSB](https://github.com/citrus3000psi/GameCube-Wasp-QSB) - QSB for installing Wiikey/Wasp Fusion ODEs on GC
* [Gamecube Memory Card Breakout](https://github.com/silverstee1/Gamecube-Memcard-Slot-Breakout-PCB) - Breakout board for GC memcard slots
* [NGCP by Nikoil](https://bitbuilt.net/forums/index.php?threads/ngcp-by-nikoil-finished.1279/) - A groundbreaking thread documenting the most ambitious GameCube handheld ever built
* [Juicy Green and Opaque Purple NGCPs](https://bitbuilt.net/forums/index.php?threads/nintendo-gamecube-portable.3284/) - Further revisions of the NGCP utilizing 3D-printed shells
* [juankamq's Modern GC Portable](https://bitbuilt.net/forums/index.php?threads/my-attempt-at-making-a-gamecube-portable.5707/) - A tiny, modern GameCube portable with Picoboot

## Software

## Guides

## Documentation

## Videos
