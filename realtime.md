# Realtime

## General real-time competition rules

- Entry must be in an **executable form**. Pure animation files are not allowed in real-time competitions. Also executables only including an animation and an animation player will not be accepted.
- Every competition has their own **maximum duration** shown but organizers may choose to stop the production before the end.
- The production must work from **read-only media** and must not modify system settings (for example: Windows registry). However, you may use the platform's standard temporary directory during the execution of your entry for storing data if such a service is available.
- The demo must show in a similar manner every time executed.
- Entries which we cannot be run on the compo machines will be disqualified. To prevent this you can ask us to test your production on the compo machines. Do this early and you will even have time to fix any problems that might pop up.
- A **screenshot** image must be submitted with the entry to the competition management system.
- You must hide the **mouse cursor**.
- You do not have to be present at the party place to compete! **Remote entries are welcome!**
- Although not forbidden, we recommend not using import by ordinal for DLLs with non-fixed ordinals to ensure better compatibility.
- Entries will be recorded at 1080p60 (or possibly 1080p50) resolution.

## Demo

- Demo may not last longer than **8 minutes.**
- Entry must run on a **Desktop platform.**
- The user has to be able to exit at any time by pressing a key. On PC this key must be ESC.
- While there is no specified size limit, we still expect it to be reasonable (i.e. something that fits on an average USB stick). As long as you can deliver it to us either by uploading through the party system or on a physical medium.

## 1K Intro

- Maximum size in executable form is **1024 bytes.**
- The file size of the intro will be shown on the screen before the entry is shown.
- Intro may not last longer than **3 minutes.**
- The production must be a *single file*. Additional info files are fine but they will be deleted prior running the intro.
- Entry must run on a **Desktop or Oldskool platform**.
- The user has to be able to exit at any time by pressing a key. On PC this key must be ESC.
- For oldskool entries, check out the submitting instructions from the oldskool compos rules.

## 4K Intro

- Maximum size in executable form is **4096 bytes.**
- Intro may not last longer than **8 minutes.**
- The production must be a *single file*. Additional info files are fine but they will be deleted prior running the intro.
- Entry must run on a **Desktop or an Oldskool platform**
- The user has to be able to exit at any time by pressing a key. On PC this key must be ESC.
- For oldskool entries, check out the submitting instructions from the oldskool compos rules.

## Oldskool demo 8-bit & 16-bit

This is an demo competition for oldskool hardware in the 8-bit & 16-bit era. There's also separate one for the 32-bit & 64-bit era. So the point is to make a demo that runs on a legacy platform and shows & plays something interesting. Emulators or FPGA hardware can be used for development but the end-product should work and be tested on the real hardware. The division which hardware will go to the 8-bit & 16-bit compo or the 32-bit & 64-bit compo is somewhat arbitrary but the gist of it is to have somewhat similar powered platforms competiting against each other without dividing the compo too much. Also another goal was to accept a wide range of platforms and not only the demoscene classics like Commodore 64 or Amiga 500. Note that some hardware might be very oldskoolish but may not still fit the rules. In that case you can probably entry it to the Real Wild compo. Also any feedback on the division or which platforms should be included or removed are welcome with good argumentation.

- Demo may not last longer than **8 minutes.**
- Demo must run on **Oldskool 8-bit & 16-bit platform.**
- Demo must be launchable using the standard procedure for that platform. If in doubt then please ask us.
- While there is no specified size limit, we still expect it to be reasonable in the context of the platform you're releasing on.
- When submitting:
  - You must specify the applicable exact hardware configuration the entry is made for, e.g. type of machine, PAL/NTSC, memory requirements, possible required add-ons, SID model, etc.
  - You must provide Internet distributable version of the entry, e.g. disk image, CD-ROM image, ZIP containing executable and data files, etc.
  - If your machine isn't listed in the supported compo machines then you must provide video capture from (preferably) real hardware. You can also request if we could accommodate you on the real hardware capture.
- Oldskool compos might be combined if there are less than three entries per compo.

### Oldskool 8-bit & 16-bit platform

- Any oldskool home computer, home console or handheld console which has at most 16-bit data bus.
  - including and up to 4th generation of video game consoles [http://en.wikipedia.org/wiki/History_of_video_game_consoles_(fourth_generation](http://en.wikipedia.org/wiki/History_of_video_game_consoles_(fourth_generation))
  - including and up to 5th generation of handhelds [http://en.wikipedia.org/wiki/History_of_video_game_consoles_(fifth_generation)](http://en.wikipedia.org/wiki/History_of_video_game_consoles_(fifth_generation))
  - examples: C64, Atari 2600, VIC-20, ZX Spectrum, Amiga 500, Atari ST(e), NES, SNES, Mega Drive, Game Boy Color, etc.
- Modern mass storage devices are allowed however, but the production must run equally well when loaded from a period correct tape/disk drive if applicable to the platform.
- Vintage add-on devices which expand the standard configuration are allowed but must be clearly stated. E.g. turbo cards with vintage CPUs.
- FPGA based reimplementations of computers, FPGA CPUs and devices which are considerably newer than the ones listed here are not allowed. These can be submitted to Real Wild compo.
- Note that FPGA solutions for peripherals are OK (such as the Ultimate1541 cartridge) - we're talking full computers here, not multi-cart or storage add-ons.
- We will provide captures from at least the following hardware:
  - Amiga 500 / PAL
    - OCS
    - 68000 / 7 MHz
    - 512 kB Chip RAM / 512 kB Trapdoor RAM
    - Kickstart 1.3
    - Rev 6a, Fat Agnus 8372A, regular Denise 8362R8
    - real floppies or HXC SD MAX floppy emulator
    - No hard disk
    - RGB or c0pperdragon & hoglet67 RGB2HDMI
  - Sharp X68000 XVI
    - 68000 / 10 or 16 MHz
    - 4 MB RAM
    - real floppy or hard disk
  - Atari STe / PAL
    - 68000 / 8 MHz
    - 4 MB RAM
    - TOS 1.62 or 2.06
    - real floppies or HXC SD MAX floppy emulator
    - possible Ultrasatan + HDDRIVER (untested at the time of writing)
  - Commodore 64 / PAL
    - SID 6581 and 8580 are available, please specify which SID you want to hear
    - Action Replay 6
    - 1541-II
    - or 1541 Ultimate II
  - Philips NMS-8245 / PAL
    - MSX 2
    - Z80 @ 3.59 MHz
    - 128kB RAM 
    - real 720 kB floppy or hard disk via Carnivore 2 / MegaFlashROM
    - optional cartridges: Carnivore 2, MegaFlashROM SCC+ SD + 512 kB, Panasonic FM-PAC, real SCC, Moonsound
  - Panasonic FS-A1 WSX / NTSC-J
    - MSX 2+
    - Toshiba T9769C 3.59 MHz / 5.36 MHz (turbo mode)
    - 512 kB internal RAM
    - real 720 kB floppy or hard disk via Carnivore 2 / MegaFlashROM
    - optional cartridges: Carnivore 2, MegaFlashROM SCC+ SD + 512 kB, real SCC, Moonsound
  - NEC PC Engine / NTSC-J
    - Turbo Everdrive V2
- Capturing the entry
  - If you wish that we make the capture the please contact us preferably well before the deadline so we can check if the hardware is still working, bring the hardware to the compo base and make sure capturing actually works.
  - If your intended hardware isn't listed in the capture hardware list then please ask preferably well before the deadline if we could provide the video capture from the hardware anyways.
  - Or bring the hardware yourself to us for recording. We can accommodate most kinds of video signal but if yours is really special, don't hesitate to contact us in advance.
  - Or make your own real hardware capture.
  - Or make your own emulator or FPGA capture but this is discouraged and should be the last resort.
  - In any case you should make sure the entry works with the real oldskool hardware and not only with emulators or FPGA reimplementations.
- If you have questions about the oldskool compos, available hardware or you are unsure if your BYOD hardware is eligible to participate, please contact codise#1950 on Discord or codise on IRCnet or please send an email to: oldskool-contact@assembly.org

## Oldskool demo 32-bit & 64-bit

This is an demo competition for oldskool hardware in the 32-bit & 64-bit era. There's also separate one for the 8-bit & 16-bit era. So the point is to make a demo that runs on a legacy platform and shows & plays something interesting. Emulators or FPGA hardware can be used for development but the end-product should work and be tested on the real hardware. The division which hardware will go to the 8-bit & 16-bit compo or the 32-bit & 64-bit compo is somewhat arbitrary but the gist of it is to have somewhat similar powered platforms competiting against each other without dividing the compo too much. Also another goal was to accept a wide range of platforms and not only the demoscene classics like Commodore 64 or Amiga 500. Note that some hardware might be very oldskoolish but may not still fit the rules. In that case you can probably entry it to the Real Wild compo. Also any feedback on the division or which platforms should be included or removed are welcome with good argumentation.

- Demo may not last longer than **8 minutes.**
- Demo must run on **Oldskool 32-bit & 64-bit platform.**
- Demo must be launchable using the standard procedure for that platform. If in doubt then please ask us.
- While there is no specified size limit, we still expect it to be reasonable in the context of the platform you're releasing on.
- When submitting:
  - You must specify the applicable exact hardware configuration the entry is made for, e.g. type of machine, PAL/NTSC, memory requirements, possible required add-ons, SID model, etc.
  - You must provide Internet distributable version of the entry, e.g. disk image, CD-ROM image, ZIP containing executable and data files, etc.
  - If your machine isn't listed in the supported compo machines then you must provide video capture from (preferably) real hardware. You can also request if we could accommodate you on the real hardware capture.
  - Oldskool compos might be combined if there are less than three entries per compo.

### Oldskool 32-bit & 64-bit platform

- Any oldskool home computer, home console or handheld console which has 32-bit or 64-bit CPU and with the following limits:
  - On Amiga & PC platform it should run on the provided compo machines or machine you provide which do not exceed the compo machine capabilities.
  - On home consoles it should be part of fifth generation of game consoles [https://en.wikipedia.org/wiki/Fifth_generation_of_video_game_consoles](https://en.wikipedia.org/wiki/Fifth_generation_of_video_game_consoles).
  - On handhelds the platform should be about similarly specced as the other machines in this compo. e.g. Virtual Boy, Gameboy Advance, N-Gage or Nintendo DS. Please ask for verification if in doubt for other platforms.
  - On other type of vintage home computers it should be about similarly specced as the other machines listed here. Please ask for verification if in doubt.
  - examples: Pentium 133 MHz, Amiga AGA/060, Atari Falcon, Playstation 1, Sega Saturn, 3DO, Nintendo 64, Nintendo DS, etc.
- Modern mass storage devices are allowed however, but the production must run equally well when loaded from a period correct storage media.
- Vintage add-on devices which expand the standard configuration are allowed but must be clearly stated. E.g. turbo cards with vintage CPUs.
  - On PC platform 3D accelerator cards are not allowed as they would exceed the compo machine specification.
- FPGA based reimplementations of computers, FPGA CPUs and devices which are considerably newer than the ones listed here are not allowed. These can be submitted to Real Wild compo.
  - Note that FPGA solutions for peripherals are OK (such as the PSIO flash cartridge) - we're talking full computers here, not multi-cart or storage add-ons.
- We will provide captures from at least the following hardware:
  - Pentium 133 MHz
    - S3 86C775 graphics card
    - Gravis Ultrasound Extreme (SB Pro compatible)
    - 32 MB RAM
    - MS-DOS 6.22
  - Pentium MMX 233 MHz
    - Not fully tested at the time of writing: small changes are possible!
    - S3 Trio64V2/DX (or some very similarly compatible)
    - Voodoo 1 (4 MB)
    - SB AWE 64 Gold (or at least SB16)
    - Gravis Ultrasound PnP (or some GUS)
    - 32 MB RAM
    - Windows 95 / MS-DOS 7
  - NEC PC-9821 Ap/U7
    - CPU switchable: AMD 5x86 @ 66 MHz (full RAM) / AMD 486SX 16Mhz (full RAM) / NEC V30 10MHz (only 640 kB RAM)
    - ~15.3 MB RAM
    - Integrated PEGC graphics (EGC + 256 color mode), no Window Accelerator
    - Built in PC-9821-86 YM2608 + PCM + added Chibioto
    - hard disk or 3.5" 1.2 MB real floppy
    - NEC MS-DOS 6.2
  - Amiga 1200 (AGA) / PAL
    - Blizzard 1260: 68060 @ 50 MHz
    - 2MB Chip RAM / 80 MB Fast RAM
    - no RTG or AHI
    - Kickstart 3.1
- Capturing the entry
  - If you wish that we make the capture the please contact us preferably well before the deadline so we can check if the hardware is working, bring the hardware to the compo base and make sure capturing actually works.
  - If your intended hardware isn't listed in the capture hardware list then please ask preferably well before the deadline if we could provide the video capture from the hardware anyways.
  - Or bring the hardware yourself to us for recording. We can accommodate most kinds of video signal but if yours is really special, don't hesitate to contact us in advance.
  - Or make your own real hardware capture.
  - Or make your own emulator or FPGA capture but this is discouraged and should be the last resort.
  - In any case you should make sure the entry works with the real oldskool hardware and not only with emulators or FPGA reimplementations.
- If you have questions about the oldskool compos, available hardware or you are unsure if your BYOD hardware is eligible to participate, please contact codise#1950 on Discord or codise on IRCnet or please send an email to: oldskool-contact@assembly.org

## Game Development

- All entries must be previously unreleased (This also means no previous Game Jams, Steam page, App Store page, youtube trailer etc.).
- Entry must run on a Desktop, Oldskool, or Mobile platform.
- Presentation:
  - Showing time is maximum **3 minutes** per entry – the game itself can naturally be longer.
  - Game presentation video options: A recommended way of presenting the game to the audience is to submit a presentation video of the game in the short film delivery format.
- The entry must be **playable!**
- The user has to be able to exit at any time. This may be executed by pressing ESC or other applicable method (e.g. game menu).
- The game may write game settings / savegames / high scores on the hard drive or in the system registry, but this is not a requirement.
- The game may utilize a network connection.
- The PC desktop version must be playable with **1080p resolution.**
- A **screenshot** must be submitted along the entry.
- The game may support multiple platforms: you can make your game to work on Windows, Java, Linux, Mac, 3DS, Android, iPhone/iPad, etc. at the same time.
- For oldskool entries, check out the submitting instructions from the oldskool compos rules.

## Fantasy Console

- Allowed platforms: TIC-80, PICO-8, PICOTRON, Quadplay, Voxatron & IBNIZ
- Entry can run on any number of cartridges (please specify the size in the entry form notes)
- Production may not last longer than **5 minutes**.

