crash-2023-05-24-10-35-13 JustcallmeDots.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FFA7D46A9C1 MODExplorer.dll+001A9C1

Detected Buffout 4 Version: Buffout 4 v1.26.2 
# [!] CAUTION : YOUR BUFFOUT 4 VERSION MIGHT BE OUT OF DATE, UPDATE BO4 IF NECESSARY #
  Original Buffout Version: https://www.nexusmods.com/fallout4/mods/47359
  Buffout VR / NG Version: https://www.nexusmods.com/fallout4/mods/64880
  Buffout 4 Guide: https://www.nexusmods.com/fallout4/articles/3115
 
====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
* NOTICE : MAIN ERROR REPORTS THAT A DLL FILE WAS INVOLVED IN THIS CRASH! * 
If that dll file belongs to a mod, that mod is a prime suspect for the crash. 
-----
# Checking for Nvidia Driver Crash........... SUSPECT FOUND! > Severity : 5 # 
-----
* FOR DETAILED DESCRIPTIONS AND POSSIBLE SOLUTIONS TO ANY ABOVE DETECTED CRASH SUSPECTS *
* SEE: https://docs.google.com/document/d/17FzeIMJ256xE85XdjoPvv_Zi3C5uHeSTQh6wOZugs4c *

====================================================
CHECKING IF NECESSARY FILES/SETTINGS ARE CORRECT...
====================================================
* NOTICE: FCX MODE IS DISABLED. YOU CAN ENABLE IT TO DETECT PROBLEMS IN YOUR MOD & GAME FILES * 
[ FCX Mode can be enabled in the exe or CLASSIC Settings.yaml located in your CLASSIC folder. ] 

✔️ Achievements parameter is correctly configured in your Buffout 4 settings! 
-----
# ❌ CAUTION : The Baka ScrapHeap Mod is installed, but is redundant with Buffout 4 # 
 FIX: Uninstall the Baka ScrapHeap Mod and open Buffout 4's TOML file and change MemoryManager to TRUE, this improves performance.
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
[!] CAUTION : The Fens Sheriff's Department ❌ CONFLICTS WITH : Varied Diamond City Guards
    Both mods heavily modify Diamond City Guards records.
    Use only one of these mods, not both at the same time.
    -----
# [!] CAUTION : FOUND MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 
* YOU SHOULD CHOOSE WHICH MOD TO KEEP AND DISABLE OR COMPLETELY REMOVE THE OTHER MOD * 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [0A] Armor And Weapons Keywords
    - If you don't rely on AWKCR, consider switching to Equipment and Crafting Overhaul
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
      Patches to remove AWKCR: https://www.nexusmods.com/fallout4/mods/40752?tab=files
    -----
[!] FOUND : [FE06D] Combat Zone Restored
    - Contains few small issues and NPCs usually have trouble navigating the interior space.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59329?tab=files
    -----
[!] FOUND : [1A] Homemaker
    - Causes a crash while scrolling over Military / BoS fences in the Settlement Menu.
      Advised Fix: Make sure you are using at least version 1.73 of this mod.
      Alternate Fix: https://www.nexusmods.com/fallout4/mods/41434?tab=files
    -----
[!] FOUND : [1C] Tactical Reload
    - Can cause weapon and combat related crashes. TR Expansion For ECO is highly recommended.
      TR Expansion For ECO Link: https://www.nexusmods.com/fallout4/mods/67716?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [12] Fourville (Vault 4)
[!] FOUND : [FE085] More Xplore

* FOR PATCH REPOSITORY THAT PREVENTS CRASHES AND FIXES PROBLEMS IN THESE AND OTHER MODS,* 
* VISIT OPTIMIZATION PATCHES COLLECTION: https://www.nexusmods.com/fallout4/mods/54872 * 

====================================================
CHECKING IF IMPORTANT PATCHES & FIXES ARE INSTALLED
====================================================
✔️ Canary Save File Monitor is installed!

✔️ High FPS Physics Fix is installed!

✔️ Previs Repair Pack (PRP) is installed!

✔️ Unofficial Fallout 4 Patch is installed!

✔️ Nvidia Weapon Debris Fix is installed!

✔️ Nvidia Reflex Support is installed!

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- modexplorer.dll | 4
- highfpsphysicsfix.dll | 6
- espexplorerfo4.esp | 1

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- Form ID: 00102249 | [Fallout4.esm] | 2

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- RDX 0x7FFA7D4C1298     (void* -> MODExplorer.dll+0071298) | 1
- [ 0] 0x7FFA7D46A9C1       MODExplorer.dll+001A9C1 | 1
- [ 1] 0x7FFA7D4531AB       MODExplorer.dll+00031AB | 1
- [ 6] 0x7FFA7D5F0B46 HighFPSPhysicsFix.dll+0030B46 | 1
- void* -> HighFPSPhysicsFix.dll+0030B10) | 4
- void* -> HighFPSPhysicsFix.dll+0030B46) | 1
- void* -> MODExplorer.dll+00031AB) | 1
- void* -> gameoverlayrenderer64.dll+006BD53) | 2
- void* -> gameoverlayrenderer64.dll+00971FE) | 1
- void* -> nvapi64.dll+0348FA5) | 1

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
