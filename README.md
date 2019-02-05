CitraDumper
===========
CitraDumper is a script for [GodMode9](https://github.com/d0k3/GodMode9) that lets you dump all of the system files necessary for [Citra](https://citra-emu.org) to function normally.

# Quickstart
* Download `CitraDumper.gm9` and place it in `/gm9/scripts/` on your SD card.
* Start up GodMode9, and press your HOME button (or your POWER button).
* Select `Scripts...`
* Select `CitraDumper`

# Usage
Upon starting the script, you will be asked if you are running Citra in portable mode.
To check for this, go to the folder your Citra build is in. If there is a `user` folder inside your Citra folder, you are running in portable mode, and that is your user directory.

(Just for reference, if you are not running portable mode, your Citra user directory will be located in `%appdata%/Citra/` on Windows, and `~/.local/share/citra-emu/` on macOS and Linux.)

You are able to dump your system archives, shared fonts and your system config. It is recommended you dump all of these, however you are able to dump the file sets individually if you only need a certain set.

# Finishing up
Once you have dumped all of the files necessary:
* Exit GodMode9 and put your SD card back in your computer.
* Navigate to `/gm9/out/citra/` or `/gm9/out/citra/user/` if you're running portable mode.
* Copy the `nand` folder and drop it into your user directory. (if necessary, overwrite any existing files)

If everything went well, you should be able to play your games ~~that you didn't download off the internet~~ on Citra.
