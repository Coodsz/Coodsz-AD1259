# Coodsz AD1259

Client launcher and dedicated server tool for playing Mount & Blade II: Bannerlord with **Anno Domini 1259** and Coop.

I made these tools for ease of access. I am not affiliated with the AD1259 team. They are here so hosting and playing AD1259 with friends is easier.

Tools **v1.0.2**. Works with Bannerlord **1.4.8**, AD1259 **1.4.6**, Workshop Coop **0.1.6** and RBM **4.5.4**.

Download the programs from the [latest release](https://github.com/Coodsz/Coodsz-AD1259/releases/latest).

- Players: `Coodsz-AD1259-Client-Launcher-v1.0.2.zip`
- The person hosting also downloads `Coodsz-AD1259-Server-v1.0.2.zip`

Both are single programs, no install needed. Unzip each to its own folder and run the exe. Later updates show an **Install update** button inside the tool.

## Thanks

The AD1259 coop fixes are by **SkyApolo**, bundled with permission:

- **AD1259 - Coop Compatibility** (server): builds a fresh AD1259 world on the dedicated server, fixes the map's travel distances, and keeps RBM's economy off.
- **AD1259 - Coop Client Stability** (players): stops a map crash caused by AD1259's custom terrain.

Players never install either one by hand. The tools do it.

## Mods

Every player and the host need exactly these mods and versions. They are not included here: get them from the Steam Workshop or Nexus Mods. The client launcher checks every one and has a **Get it** button next to anything missing.

| Mod | Version | Where |
| --- | --- | --- |
| Harmony | 2.4.2.248 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2859188632) |
| ButterLib | 2.12.0 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2859232415) |
| UIExtenderEx | 3.0.3 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2859222409) |
| Mod Configuration Menu v5 | 5.12.3 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2859238197) |
| Realistic Battle Mod | 4.5.4 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2859251492) |
| Expanded Armoury | e1.5.2 + the FIX file | [Nexus](https://www.nexusmods.com/mountandblade2bannerlord/mods/11487) |
| Swadian Armoury | 1.0.0 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2875090166) |
| Open Source Armory | 2.0.0 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3011479883) |
| Open Source Saddlery | 2.0.0 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3010990914) |
| Open Source Weaponry | 2.0.1 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3010984416) |
| Templar Armor + Templar Equipment | 1.0.3 | [Nexus](https://www.nexusmods.com/mountandblade2bannerlord/mods/4736) (not the NBR version) |
| Settlement Icons - Redesign | 1.1.4 | [Nexus](https://www.nexusmods.com/mountandblade2bannerlord/mods/2717) |
| Anno Domini 1259 | 1.4.6 | [Nexus](https://www.nexusmods.com/mountandblade2bannerlord/mods/6723) |
| Bannerlord Coop | 0.1.6 | [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3770450698) |

Nexus mods go in the game's `Modules` folder. For Expanded Armoury, also download the file called **FIX** from its Files tab and copy it over `Modules\ExpandedArmouryBL`.

## The first start takes a long time

The first time the game starts with AD1259 it builds shaders and downloads the server's large world. It can take **20 minutes or more**, and the game window can go white or say **Not Responding**. That is normal. After **Connect**, the launcher shows a box that says the game is still loading and still working. Do not close the game while that box says it is still working. Later starts are much faster.

If the game closes while starting, click **Connect** again. A second start usually gets past it.

## Known issues

- On some NVIDIA RTX 50 series cards (5070 / 5080 / 5090) the campaign map ground can look black. Towns, trees and water still show. It happens in AD1259 singleplayer too, so it is not caused by Coop or these tools.
- Keep RBM's **Campaign** part off on the server and every player. RBM's economy empties town shops and stops workshops on a Coop server. Both tools turn it off by default.

How to install, join and host is in `Coodsz-AD1259-Instructions.txt`.
