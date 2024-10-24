crash-2023-09-17-21-43-29 AceofSpades.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF6A0500393 Fallout4.exe+27B0393

Detected Buffout 4 Version: Buffout 4 v1.28.6 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Script Crash.................. SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Mesh (NIF) Crash.............. SUSPECT FOUND! > Severity : 4 # 
-----
# Checking for Animation / Physics Crash..... SUSPECT FOUND! > Severity : 5 # 
-----
* FOR DETAILED DESCRIPTIONS AND POSSIBLE SOLUTIONS TO ANY ABOVE DETECTED CRASH SUSPECTS *
* SEE: https://docs.google.com/document/d/17FzeIMJ256xE85XdjoPvv_Zi3C5uHeSTQh6wOZugs4c *

====================================================
CHECKING IF NECESSARY FILES/SETTINGS ARE CORRECT...
====================================================
* NOTICE: FCX MODE IS DISABLED. YOU CAN ENABLE IT TO DETECT PROBLEMS IN YOUR MOD & GAME FILES * 
[ FCX Mode can be enabled in the exe or CLASSIC Settings.yaml located in your CLASSIC folder. ] 

# ❌ CAUTION : The Achievements Mod and/or Unlimited Survival Mode is installed, but Achievements is set to TRUE # 
 FIX: Open Buffout 4's TOML file and change Achievements to FALSE, this prevents conflicts with Buffout 4.
-----
✔️ Memory Manager parameter is correctly configured in your Buffout 4 settings! 
-----
✔️ F4EE (Looks Menu) parameter is correctly configured in your Buffout 4 settings! 
-----
❌ FCX Mode is disabled, skipping game files check... 
-----
====================================================
CHECKING FOR MODS THAT CAN CAUSE FREQUENT CRASHES...
====================================================
# FOUND NO PROBLEMATIC MODS THAT MATCH THE CURRENT DATABASE FOR THIS CRASH LOG #
THAT DOESN'T MEAN THERE AREN'T ANY! YOU SHOULD RUN PLUGIN CHECKER IN WRYE BASH 
Plugin Checker Instructions: https://www.nexusmods.com/fallout4/articles/4141 

====================================================
CHECKING FOR MODS THAT CONFLICT WITH OTHER MODS...
====================================================
[!] CAUTION : Frost Survival Simulator ❌ CONFLICTS WITH : Previs Repair Pack
    For precombine fixes, remove PRP and switch to FROST Cell Fixes (FCF).
    FROST Cell Fixes: https://www.nexusmods.com/fallout4/mods/59652?tab=files
    -----
[!] CAUTION : Vulkan Renderer ❌ CONFLICTS WITH : Nvidia Reflex Support
    Vulkan Renderer can break GPU recognition from NV Reflex Support. This can crash the game or cause weird mod behavior.
    If you encounter Nvidia Driver crashes, CLASSIC suggests using Vulkan Render only. Otherwise, use Nvidia Reflex Support.
    -----
# [!] CAUTION : FOUND MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 
* YOU SHOULD CHOOSE WHICH MOD TO KEEP AND DISABLE OR COMPLETELY REMOVE THE OTHER MOD * 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [0D] Advanced Animation Framework
    - Latest AAF version only available on Moddingham | AAF Tech Support: https://discord.gg/gWZuhMC
      Latest AAF Link (register / login to download): https://www.moddingham.com/viewtopic.php?t=2
    -----
    - Looks Menu versions 1.6.20 & 1.6.19 can frequently break adult mod related (erection) morphs.
      If you notice AAF related problems, remove latest version of Looks Menu and switch to 1.6.18.
    -----
[!] FOUND : [3F] Combat Zone Restored
    - Contains few small issues and NPCs usually have trouble navigating the interior space.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59329?tab=files
    -----
[!] FOUND : [92] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [3A] Raider Overhaul
    - Old mod that requires several patches to function as intended. Use ONE Version instead.
      Updated ONE Version: https://www.nexusmods.com/fallout4/mods/51658?tab=files
    -----
[!] FOUND : [19] Super Mutant Redux
    - Causes crashes at specific locations or with certain Super Mutant enemies and items.
      Patch Link: https://www.nexusmods.com/fallout4/mods/51353?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [16] Tales from the Commonwealth
[!] FOUND : [53] Settlers Of The Commonwealth
[!] FOUND : [6F] Xander's Aid
[!] FOUND : [49] Fourville (Vault 4)
[!] FOUND : [5D] Lost Building of Atlantic
[!] FOUND : [3E] Sector V

* FOR PATCH REPOSITORY THAT PREVENTS CRASHES AND FIXES PROBLEMS IN THESE AND OTHER MODS,* 
* VISIT OPTIMIZATION PATCHES COLLECTION: https://www.nexusmods.com/fallout4/mods/54872 * 

====================================================
CHECKING IF IMPORTANT PATCHES & FIXES ARE INSTALLED
====================================================
✔️ Canary Save File Monitor is installed!

✔️ High FPS Physics Fix is installed!

✔️ Previs Repair Pack (PRP) is installed!

✔️ Unofficial Fallout 4 Patch is installed!

✔️ Vulkan Renderer is installed!

❓ Nvidia Weapon Debris Fix is installed, BUT IT SEEMS YOU DON'T HAVE AN NVIDIA GPU?
IF THIS IS CORRECT, COMPLETELY UNINSTALL THIS MOD TO AVOID ANY PROBLEMS! 

❓ Nvidia Reflex Support is installed, BUT IT SEEMS YOU DON'T HAVE AN NVIDIA GPU?
IF THIS IS CORRECT, COMPLETELY UNINSTALL THIS MOD TO AVOID ANY PROBLEMS! 

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- g2m_workshop_nexus.esp | 21
- outcastsandremnants.esp | 54
- thuggysmurf_optimization.esp | 3

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- Form ID: 000002CF | [Fallout4.esm] | 1
- Form ID: 000002D5 | [Fallout4.esm] | 2
- Form ID: 0003D773 | [Fallout4.esm] | 21
- Form ID: 001CD02B | [Fallout4.esm] | 1
- Form ID: 37003B03 | [OutcastsAndRemnants.esp] | 17
- Form ID: 37008DD6 | [OutcastsAndRemnants.esp] | 1
- Form ID: 37008DEC | [OutcastsAndRemnants.esp] | 1
- Form ID: 37016743 | [OutcastsAndRemnants.esp] | 16
- Form ID: 37016EFC | [OutcastsAndRemnants.esp] | 16
- Form ID: 3702DBFD | [OutcastsAndRemnants.esp] | 3
- Form ID: 3702E3B6 | [OutcastsAndRemnants.esp] | 3

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- Full Name: "Door" | 4
- Name: "ObjectReference" | 3

[Last number counts how many times each Named Record shows up in the crash log.]
These records were caught by Buffout 4 and some of them might be related to this crash.
Named records should give extra info on involved game objects, record types or mod files.

FOR FULL LIST OF MODS THAT CAUSE PROBLEMS, THEIR ALTERNATIVES AND DETAILED SOLUTIONS
VISIT THE BUFFOUT 4 CRASH ARTICLE: https://www.nexusmods.com/fallout4/articles/3115
===============================================================================
Author/Made By: Poet (guidance.of.grace) | https://discord.gg/DfFYJtt8p4
CONTRIBUTORS | evildarkarchon | kittivelae | AtomicFallout757 | wxMichael
FO4 CLASSIC | https://www.nexusmods.com/fallout4/mods/56255
CLASSIC v7.30.3 | 24.10.11 | END OF AUTOSCAN 
