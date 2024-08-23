This repository is for adding new systems to the Knulli linux retro gaming build.  Knulli is based on Batocera and is oriented to handheld portable gaming devices.

Some like to break out the various consoles into smaller specific systems.  For example, the NES is also known as Famicom.  While they shared most of the same games there were some Famicom exclusives that the NES didn’t get.  This is the same for other consoles that also had releases in Japan.

By breaking them out into individual consoles, this allows more customization to the EmulationStation menu and game browsing.

Most themes are setup to support the majority of these new systems however some may need to be added.

The following systems are added (or updated) via this repository.  
```
SYSTEM						ROM FOLDER

Arcade						arcade
Capcom Play System I				cps1
Capcom Play System II				cps2
Capcom Play System III				cps3
Commodore CDTV					cdtv
NEC TurboGrafx-16				tg16
NEC TurboGrafx-CD				tg-cd
Nintendo 64 Hacks				n64h
Nintendo 64 Japan				n64-japan
Nintendo Entertainment System Hacks		nesh
Nintendo Famicom				famicom
Nintendo Game Boy Advance Hacks			gbah
Nintendo Game Boy Color Hacks			gbch
Nintendo Game Boy Hacks				gbh
Panasonic 3DO					3do
Philips CD-i					cdimono1
Sega Game Gear Hacks				ggh
Sega Genesis Hacks				genh
Sega Genesis					genesis
Sega Mark III					markiii
Sega Mega-CD Japan				megacd-japan
Sega Mega-CD					megacd
Sega Mega Drive Japan				megadrive-japan
Sega Saturn Japan				saturn-japan
Sega SC-3000					sc-3000
Sony PlayStation Japan				psx-japan
Sony PSP Japan					psp-japan
Sony PSP Minis					pspminis
Super Famicom					sfc
Super Nintendo Entertainment System Hacks	snesh
```

===============================
Panasonic 3DO Additional Modifications

The 3DO Retroarch core is not currently included in Knulli.  This repository includes the Retroarch core file that can be copied over.

The file resides in:  /usr/lib/libretro

However, due to how Knulli works, an additional manual command must be performed in order to keep Knulli from deleting the core file after a restart.

To stop this from happening, there’s a special command to run via SSH.

Run your SSH program (like Putty, etc) and log into your Anbernic to get to a terminal command line.

Type the following command:

batocera-save-overlay    –> and then hit enter

You’ll see some text scrolling on the screen while the command is saving an overlay file.  Once finished, restart your Anbernic system.


===============================
BIOS FILES

There may be some additional BIOS files you are required to obtain in order to get some of these systems  working.  Refer to the Batocera Wiki for that information.
