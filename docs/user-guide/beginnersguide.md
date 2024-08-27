# Beginner's Guide

The process of installing mods is fairly simple. If you have any questions about modding, consider joining the [Discord](https://discord.gg/JEgxpYe9wt).

Before starting, you'll need an archiving program such as [7Zip](https://www.7-zip.org/download.html) or [Winrar](https://www.rarlab.com/download.htm) to open .7z, .rar, and .zip files. It will vary by system, but you'll typically want the x64 Windows version.

## Installing The Mod Loader

* Begin by opening the root folder for P06. If you see a file called "Sonic the Hedgehog.exe", this is the correct location
* Go to the [Mod Loader GameBanana Page](https://gamebanana.com/tools/10474). Scroll down and press "Download".
* Once downloaded, open the file in your archiving program.
* You should see four folders and a file called "version.dll". You'll need to extract these to your P06 root, next to "Sonic the Hedgehog.exe". You can typically do this by selecting the "MelonLoader" folder, then selecting "version.dll" while holding the Shift key. Once everything is highlighted, click and hold one of the highlighted files with the left mouse button. Drag your cursor to the P06 root folder and release the left mouse button.
* Run the game. If you see a MelonLoader loading screen when the game starts, the mod loader has been successfully installed.

### Installing The Mod Loader On Steam Deck

Using mods on Steam Deck will require some extra steps. Start with the first four steps of __[Installing The Mod Loader]__. You'll also need to install [Protontricks](https://github.com/Matoking/protontricks). 

!!! note

    Thanks to [onyxlebron](https://gamebanana.com/members/2127439) for the following instructions.

* Go to desktop mode and open Konsole. Type "protontricks -s [GameName]" without the quotes. Replace GameName with w.e name you have Project 06 as in steam (mine is Sonic The Hedgehog). It'll give you the app id so remember it.

* In Konsole run "protontricks [appid] winecfg" without the quotes. Replace appid with Project 06's app id.

* In the window that pops up look at the bottom and change the Windows version to Windows 10.

* Go to the libraries tab, click on the "new override for library" drop down and find "version". Click it and select add. Hit apply and ok.

* Install your mods like you normally would and launch Project 06 from steam and everything should be good. MelonLoader should pop up and launch the game normally. Works in game mode and desktop mode.

## Installing Mods

Once the Mod Loader is installed, installing other mods such as stages, characters, and plugins is very simple.

* Make sure you've run the game once after installing the Mod Loader.
* Head to the [GameBanana Page](https://gamebanana.com/games/7579).
* Once you find a mod you want, scroll down and press the button that says "Project '06 Mod Loader  1-CLICK INSTALL".
* You'll have a window pop up titled "Project '06 Mod Loader" asking to install the mod. Click "Yes".
* Another window will pop up with a progress bar. Wait for it to finish, and press "OK". The mod has been installed.

!!! note

    It's recommended to install [Stage Extensions](https://gamebanana.com/mods/402611). Many custom stages rely on features in this mod.

### Assembly Mods

Most mods can be installed with the previous method, and it normally won't matter what version of the game you're running. However, there are other types of mods, referred to as assembly mods, that can't be installed with the previous method and must be installed on a specific version of the game. 

!!! warning

    It's recommended you make a new install of the game before using assembly mods. Assembly mods overwrite important game files preventing you from playing the vanilla game on the same install.

If you see "Assembly-CSharp.dll" when you open the mod archive, navigate to "(Game Root)/Sonic the Hedgehog_Data/Managed" and place "Assembly-CSharp.dll" there. 

If you see "Sonic the Hedgehog_Data" when you open the mod archive, place all the files in the game root.

[Installing The Mod Loader]: #installing-the-mod-loader