Purpose

A dedicated ward mod aimed at improving the way wards work in Valheim.


Known Mod Conflicts


* Anything that toggles PvE/PvP and forces the value will conflict if you have this mod toggle the values. Current known mods that do this are:
﻿World of Valheim - Zones
﻿PvP-Always-On

Features

* The hotkey can be adjusted by the configuration file.
*  Changelog on main menu shows updates for your version
*  Allow permitted users on the ward to toggle the ward on and off
*  PvP/PvE forced configurations
*  Ward Range configuration (Enemy spawns will query the range to prevent spawning inside base)
* Health/Stamina Boosts for all players inside ward
* Show area marker for the ward (configurable)
* Indestructible structures can be defined for further custom config (inside ward) (FULL LIST)
* Auto Close Doors inside ward (configurable)
* Enforced Config with server (besides client custom configs)
* Reduce damage to player structures inside ward from other players, or increase default health of structure (applies to all inside ward)
* Notification of being inside a ward and who the owner is (configurable)
* Sync Admin list from server for additional configurations (auto permit on nearby wards, permit/unpermit/enable/disable/destroy/flash with command)
* Damage boosts to Players against NPCs while inside ward (configurable)
* Server version checking, must have mod & must be same version as server
* Warded portal interact/teleport configurable
* Ward pushout
* Unlimited fireplace fuel in warded area configurable
* Configurable interaction in warded area
* No Weather Damage
* Visual Bubble
* Offline Raid protection (BETA Phase!)
* Configurable ward recipe for Better Wards
* Auto repair structures inside ward

Client Custom Config Options

* Hotkey option for ward toggle (Default is "G").
* Auto Close Doors (enable/disable)
* Notification of being inside a ward and who the owner is (enable/disable)
* Show area marker for the ward (enable/disable)

Admin Only


* Hotkeys are UpArrow for enabling a ward, DownArrow for disabling a ward (must be looking at it)
* Auto permit on enabled wards nearby (client configurable)
* Admin only chat/console(F5) commands (/permit, /unpermit, /enable, /flash, /disable, /destroy)


Installation Instructions
NOTE: The archive comes with the default config file and DLL inside the correct folder structure.

Windows (Steam)
1. Locate your game folder manually or start Steam client and :
   a. Right click the Valheim game in your steam library
   b. "Go to Manage" -> "Browse local files"
   c. Steam should open your game folder
2. Extract the contents of the archive into the game folder.
3. Locate azumatt.BetterWards.cfg under BepInEx\config and configure the mod to your needs

Server
﻿Must be installed on both the client and the server for syncing to work properly.
1. Locate your main folder manually and :
   a. Extract the contents of the archive into the main folder that contains BepInEx
   b. Launch your game at least once to generate the config file needed if you haven't already done so.
   c. Locate azumatt.BetterWards.cfg under BepInEx\config on your machine and configure the mod to your needs
2. Reboot your server. All clients will now sync to the server's config file even if theirs differs. Config Manager mod changes will only change the client config, not what the server is enforcing.


Feel free to reach out to me on discord if you need manual download assistance.


What if the game updates?

Game updates are unlikely to do more than partially break Better Wards at worst. In case you encounter any issues, please reach out to the me.


Where is the configuration file?

The Config file's name is "azumatt.BetterWards.cfg" it needs to be placed in "BepInEx\config"



TO-DOs

- [X]  Disable interaction of items that aren't doors and chests inside the ward from unpermitted users.
- [X] Auto repair for items inside ward (requested feature)
- [X]  Version enforcement. Disconnect from server if version is different.
- [X]  Admins bypass indestructible items
- [X]  Passivedamage in warded area (Better Wards Only)
- [X]  Visual Bubble
- [X]  Check if more than {x} people permitted/owner on ward are online, if not, everything inside that ward is indestructible for the grief fight
- [X] Configurable ward recipe
- [X] Prevent ship interaction (non-permitted)
- [X] MCE dependency drop in v1.5.0
- [ ]  Tribe/Clan system using wards
- [ ]  Ward creation limit (no guarantees on this one...)
- [ ]  No food loss inside ward (requested feature)

Open to suggestions!








Author Information

Azumatt
DISCORD: Azumatt#2625
STEAM: https://steamcommunity.com/id/azumatt/﻿

Special thanks

Special thanks to Pfhoenix0 for his MCE mod for config syncing in early stages of the mod! Made syncing very easy!
Special thanks to Sarcenzzz for his help with the visual bubble and general advice!
Special thanks to Zarboz for his help in creating the new ward look!