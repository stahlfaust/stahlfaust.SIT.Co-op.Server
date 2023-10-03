# stahlfaust's SIT Coop Serverpack + SIT AIO Installer - [v0.1.0-alpha](https://github.com/stahlfaust/stahlfaust-SIT-Coop-Server/releases)
## Info on this serverpack
### What's included
- [SIT AIO Installer](https://github.com/T4s3rF4c3/SIT-AIO-Installer-3.6.1) + Troubleshooter
- Client modpack for my SIT Server
- [Realistic Lighting for EFT](https://hub.sp-tarkov.com/files/file/1429-realistic-lighting-for-eft/) via [Reshade](https://reshade.me/) + [Amands' Graphics](https://hub.sp-tarkov.com/files/file/813-amands-s-graphics/)
### Client modpack
- [Amands' Graphics by Amands](https://hub.sp-tarkov.com/files/file/813-amands-s-graphics/)
- [Amands' Hitmarker by Amands](https://hub.sp-tarkov.com/files/file/798-amands-s-hitmarker/)
- [Amands' Sense by Amands](https://hub.sp-tarkov.com/files/file/1361-amands-sense/)
- [BigBrain by DrakiaXYZ](https://hub.sp-tarkov.com/files/file/1219-bigbrain/)
- [Custom Main Menu Music by SamSWAT](https://hub.sp-tarkov.com/files/file/589-custom-main-menu-music/)
- [Fontaine's Combat Stance Overhaul by Fontaine](https://hub.sp-tarkov.com/files/file/1098-fontaine-s-combat-stance-overhaul/)
- [Looting Bots by skwizzy](https://hub.sp-tarkov.com/files/file/1096-looting-bots/)
- [More Checkmarks by VIPkiller17](https://hub.sp-tarkov.com/files/file/1159-morecheckmarks/)
- [Sain 2.0 by Solarint](https://hub.sp-tarkov.com/files/file/1062-sain-2-0-solarint-s-ai-modifications-full-ai-combat-system-replacement/)
- [TechHappy's Web Minimap by TechHappy](https://hub.sp-tarkov.com/files/file/1421-techhappy-s-web-minimap/)
- [Waypoints by DrakiaXYZ](https://hub.sp-tarkov.com/files/file/1119-waypoints-expanded-bot-patrols-and-navmesh/)
### Credits
- Without [paulov-t](https://github.com/paulov-t) none of this would be possible!
- All original SPT-AKI mods credited to their respective creators.
- [SIT AIO Installer](https://github.com/T4s3rF4c3/SIT-AIO-Installer-3.6.1) credited to [T4s3rF4c3](https://github.com/T4s3rF4c3).
- All [SIT-AKI mod ports](https://github.com/Lacyway/SIT-Mod-Ports) credited to [Lacyway](https://github.com/Lacyway).

A big thanks to all of them!
## What is SIT?
[SIT (Stay in Tarkov)](https://github.com/paulov-t/SIT.Core) is an Escape From Tarkov BepInEx module designed to be used with the [SPT-AKI (Single Player Tarkov)](https://www.sp-tarkov.com/#features) server with the ultimate goal of "offline" coop-multiplayer.
## Using the SIT AIO Installer and Patching Your Game Files
**Before you attempt to install SIT, please update Tarkov through the BSG launcher and then start the game.**
**Take note of your game version in the lower left corner of the screen. This version number will be important in a future step.**
1. Unzip `stahlfausts.SIT.Coop.Serverpack.v0.1.0-alpha+SIT.AIO.Installer.zip` to an easily accessible place like your Desktop.

2. Open the `stahlfaust's SIT Coop Serverpack + SIT AIO Installer` folder, then the `Stay in Tarkov AIO Installer + Troubleshooter` folder and run `SIT-AIO-Installer.exe`  **as an administrator**.

	- Select your live Escape from Tarkov folder (this is usually under `X:\Battlestate Games\EFT`)

	- Select a destination folder for the SIT installation. I recommend creating a folder named `SIT` under your `C:\` drive (root directory) but any drive will work.

	- Click the `INSTALL - CLIENT ONLY` button. Wait for the installer to finish. If the program stops responding, **DO _NOT_ CLOSE IT!** This is normal and the program should still complete the installation. You should have two folders after completion: `X:\SIT\SIT-EFT-Install` and `X:\SIT\SIT-Launcher`.

	- If you would also like to run your own server instead of joining a friend's, click the `INSTALL - SERVER ONLY` button after the client finishes installing. After completion of the server installation you can view the documentation on configuring it [here](https://github.com/paulov-t/SIT.Core/wiki/Step-By-Step-Installation-Guide-English#configuring-the-server). **The file path will be slightly different due to the way that the installer names the folders.**

3. The installer will then prompt you to patch your new game files. Select a patcher [here](https://hub.sp-tarkov.com/files/file/204-aki-patcher/#versions) that will downgrade the current version of your newly-copied, unmodified EFT files to **13.1.3.25206 SPT**.

	- Extract the contents of the zip file, copy `patcher.exe` and the `Aki_Patches` folder and then paste them into `X:\SIT\SIT-EFT-Install` (so they are in the same folder as EscapeFromTarkov.exe)

	- Run `patcher.exe` **as an administrator**. The patching process will take several minutes. Once completed, move on to the next step.

4. Navigate to `X:\SIT\SIT-Launcher` and run `SIT.Launcher.exe`  **as an administrator**.

	- The first time you run the launcher it will prompt you:
"_No OFFLINE install found. Would you like to install now?_"

	- Click "Yes".

	- Select `X:\SIT\SIT-EFT-Install` as the installation directory.

	- Let the launcher copy your game files, this can take a few minutes.

## How to use the SIT Launcher
1. Enter the server address into the "Server" field. To join my server enter http://beyster.duckdns.org:6969.

2. Enter your desired username.

3. Enter your desired password (don't use any password you care about).

4. Click the `Launch` button to test your installation! If your game loads proceed to the next section. If your game does not load please [click here](https://github.com/blayne-eyster/StahlfaustSITCoopServer/wiki#need-help).
## Installing Client Side Mods
1. Open the `stahlfaust's SIT Coop Serverpack + SIT AIO Installer` folder that you unzipped earlier.

2. Open the `Client Mods` folder.

3. Drag and drop the `BepInEx` folder into your `X:\SIT\SIT-EFT-Install` folder. Click "Yes" to any prompts that require overwriting files.
- **If you are joining my server please do not modify any of the SAIN presets as it will cause de-sync**.
- You can modify other mods like [Amands' Hitmarker](https://hub.sp-tarkov.com/files/file/798-amands-s-hitmarker/), [Amands' Sense](https://hub.sp-tarkov.com/files/file/1361-amands-sense/) or [Fontaine's Combat Stance Overhaul](https://hub.sp-tarkov.com/files/file/1098-fontaine-s-combat-stance-overhaul/) using the "F12" key.
## Realistic Lighting Mod
If you would like to install the Realistic Lighting for EFT mod, open the `Optional Amands' Graphics + Reshade` folder and follow the installation instructions below. If you do not want to use the Reshade preset you can configure [Amands' Graphics](https://hub.sp-tarkov.com/files/file/813-amands-s-graphics/) to your liking via the "F12" key.

![](https://github.com/stahlfaust/stahlfaust-SIT-Coop-Server/assets/135766383/b2cac304-1d70-4917-b297-8b6d81574955)

## Need Help?
- Try to run `SIT-Patcher-Troubleshooter.exe` if you're running into problems loading the game after installation.
Please DM me on Discord: "[stahlfaust](https://discord.com/users/588465573009162251)" for futher assistance.
