CitraDumper
===========
CitraDumper is a script for [GodMode9](https://github.com/d0k3/GodMode9) that lets you dump all of the system files necessary for [Citra](https://citra-emu.org) to function normally.

# Quickstart
* Download `CitraDumper.gm9` and place it in `/gm9/scripts/` on your SD card.
* Start up GodMode9, and press your HOME button (or your POWER button).
* Select `Scripts...`
* Select `CitraDumper`

# Usage
You are able to dump the following with this script:
* System archives (Mii data, ClCertA)
* Shared fonts
* System applets
* System config
* ARM9 bootrom

It is recommended you dump all of these, however you are able to dump the file sets individually if you only need a certain set.

# Finishing up
Once you have dumped all of the files necessary:
* Exit GodMode9 and put your SD card back in your computer.
* Navigate to `/gm9/out/citra/`.
* Copy the `nand` and `sysdata` folders and drop them into your user directory. (if necessary, overwrite any existing files)

(Just for reference, if you are not running portable mode, your Citra user directory will be located in `%appdata%/Citra/` on Windows, and `~/.local/share/citra-emu/` on macOS and Linux.)

If everything went well, you should be able to play your games ~~that you didn't download off the internet~~ on Citra.
