crash-2022-12-14-05-00-29 Hunter Darksoul.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF70074446C Fallout4.exe+1CC446C

Detected Buffout 4 Version: Buffout 4 v1.26.2 
# [!] CAUTION : YOUR BUFFOUT 4 VERSION MIGHT BE OUT OF DATE, UPDATE BO4 IF NECESSARY #
  Original Buffout Version: https://www.nexusmods.com/fallout4/mods/47359
  Buffout VR / NG Version: https://www.nexusmods.com/fallout4/mods/64880
  Buffout 4 Guide: https://www.nexusmods.com/fallout4/articles/3115
 
====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for *[Precombines Crash].......... SUSPECT FOUND! > Severity : 1 # 
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
[!] FOUND : [46] Tactical Tablet
    - Can cause flickering with certain scopes or crashes while browsing workbenches, most commonly with ECO.
    -----
# [!] CAUTION : ANY ABOVE DETECTED MODS HAVE A MUCH HIGHER CHANCE TO CRASH YOUR GAME! #
* YOU CAN DISABLE ANY / ALL OF THEM TEMPORARILY TO CONFIRM THEY CAUSED THIS CRASH. * 

====================================================
CHECKING FOR MODS THAT CONFLICT WITH OTHER MODS...
====================================================
# FOUND NO MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [0C] Advanced Animation Framework
    - Latest AAF version only available on Moddingham | AAF Tech Support: https://discord.gg/gWZuhMC
      Latest AAF Link (register / login to download): https://www.moddingham.com/viewtopic.php?t=2
    -----
    - Looks Menu versions 1.6.20 & 1.6.19 can frequently break adult mod related (erection) morphs.
      If you notice AAF related problems, remove latest version of Looks Menu and switch to 1.6.18.
    -----
[!] FOUND : [08] Armor And Weapons Keywords
    - If you don't rely on AWKCR, consider switching to Equipment and Crafting Overhaul
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
      Patches to remove AWKCR: https://www.nexusmods.com/fallout4/mods/40752?tab=files
    -----
[!] FOUND : [1B] Fallui Item Sorter (OLD)
    - This is an outdated item tagging / sorting patch that can cause crashes or conflicts in all kinds of situations.
      I strongly recommend to instead generate your own sorting patch and place it last in your load order.
      That way, you won't experience any conflicts / crashes and even modded items will be sorted.
      Generate Sorting Patch With This: https://www.nexusmods.com/fallout4/mods/48826?tab=files
    -----
[!] FOUND : [47] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [58] Natural And Atmospheric Commonwealth
    - If you notice weird looking skin tones with either NAC or NACX, install this patch.
      Patch Link: https://www.nexusmods.com/fallout4/mods/57052?tab=files
    -----
[!] FOUND : [4A] Super Mutant Redux
    - Causes crashes at specific locations or with certain Super Mutant enemies and items.
      Patch Link: https://www.nexusmods.com/fallout4/mods/51353?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
# FOUND NO PROBLEMATIC MODS THAT ARE ALREADY PATCHED THROUGH THE OPC INSTALLER # 

====================================================
CHECKING IF IMPORTANT PATCHES & FIXES ARE INSTALLED
====================================================
❌ Canary Save File Monitor is not installed!
This is a highly recommended mod that can detect save file corruption.
Link: https://www.nexusmods.com/fallout4/mods/44949?tab=files

✔️ High FPS Physics Fix is installed!

❌ Previs Repair Pack (PRP) is not installed!
This is a highly recommended mod that can vastly improve performance.
Link: https://www.nexusmods.com/fallout4/mods/46403?tab=files

✔️ Unofficial Fallout 4 Patch is installed!

❌ Nvidia Weapon Debris Fix is not installed!
This is a mandatory patch / fix required for almost all Nvidia GPUs.
Link: https://www.nexusmods.com/fallout4/mods/48078?tab=files

❌ Nvidia Reflex Support is not installed!
This is a highly recommended mod that can improve performance on Nvidia GPUs.
Link: https://www.nexusmods.com/fallout4/mods/64459?tab=files

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- fo4 npcs travel.esp | 1
- mutantmenagerie_farharbor.esm | 2

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- Form ID: 03000B0F | [DLCCoast.esm] | 1
- Form ID: 03000DCB | [DLCCoast.esm] | 1
- Form ID: 03000DEE | [DLCCoast.esm] | 1

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- Full Name: "The Island" | 1
- Name: "Forest001.001_Untitled.011" | 3

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
