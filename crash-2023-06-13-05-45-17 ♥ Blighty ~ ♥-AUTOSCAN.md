crash-2023-06-13-05-45-17 ♥ Blighty ~ ♥.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF7644EB26A Fallout4.exe+248B26A

Detected Buffout 4 Version: Buffout 4 v1.26.2 
# [!] CAUTION : YOUR BUFFOUT 4 VERSION MIGHT BE OUT OF DATE, UPDATE BO4 IF NECESSARY #
  Original Buffout Version: https://www.nexusmods.com/fallout4/mods/47359
  Buffout VR / NG Version: https://www.nexusmods.com/fallout4/mods/64880
  Buffout 4 Guide: https://www.nexusmods.com/fallout4/articles/3115
 
====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for NPC Pathing Crash (D)......... SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for NPC Pathing Crash (F)......... SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Nvidia Driver Crash........... SUSPECT FOUND! > Severity : 5 # 
-----
# Checking for Player Character Crash........ SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for *[Save Crash]................. SUSPECT FOUND! > Severity : 1 # 
-----
# Checking for *[NPC Patrol Crash]........... SUSPECT FOUND! > Severity : 1 # 
-----
# Checking for *[Precombines Crash].......... SUSPECT FOUND! > Severity : 1 # 
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
# ❌ CAUTION : Looks Menu is installed, but F4EE parameter under [Compatibility] is set to FALSE # 
 FIX: Open Buffout 4's TOML file and change F4EE to TRUE, this prevents bugs and crashes from Looks Menu.
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
# FOUND NO MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [0A] Armor And Weapons Keywords
    - If you don't rely on AWKCR, consider switching to Equipment and Crafting Overhaul
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
      Patches to remove AWKCR: https://www.nexusmods.com/fallout4/mods/40752?tab=files
    -----
[!] FOUND : [1F] Combat Zone Restored
    - Contains few small issues and NPCs usually have trouble navigating the interior space.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59329?tab=files
    -----
[!] FOUND : [3D] Functional Displays
    - Frequently causes object model (nif) related crashes and this needs to be manually corrected.
      Advised Fix: Open its Meshes folder and delete everything inside EXCEPT for the Functional Displays folder.
    -----
[!] FOUND : [0C] Homemaker
    - Causes a crash while scrolling over Military / BoS fences in the Settlement Menu.
      Advised Fix: Make sure you are using at least version 1.73 of this mod.
      Alternate Fix: https://www.nexusmods.com/fallout4/mods/41434?tab=files
    -----
[!] FOUND : [33] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [FE016] Rusty Face Fix
    - Make sure you have the latest 2.0 version installed or try the REDUX Version instead.
      Original Rusty Face Fix: https://www.nexusmods.com/fallout4/mods/31028?tab=files
      Alternative REDUX Version: https://www.nexusmods.com/fallout4/mods/64270?tab=files
    -----
[!] FOUND : [10] Start Me Up
    - Abandoned mod that can cause infinite loading and other problems. Switch to REDUX Version instead.
      Updated REDUX Version: https://www.nexusmods.com/fallout4/mods/56984?tab=files
    -----
[!] FOUND : [0E] Tactical Reload
    - Can cause weapon and combat related crashes. TR Expansion For ECO is highly recommended.
      TR Expansion For ECO Link: https://www.nexusmods.com/fallout4/mods/67716?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [1C] Raider Children
[!] FOUND : [1E] Fourville (Vault 4)

* FOR PATCH REPOSITORY THAT PREVENTS CRASHES AND FIXES PROBLEMS IN THESE AND OTHER MODS,* 
* VISIT OPTIMIZATION PATCHES COLLECTION: https://www.nexusmods.com/fallout4/mods/54872 * 

====================================================
CHECKING IF IMPORTANT PATCHES & FIXES ARE INSTALLED
====================================================
❌ Canary Save File Monitor is not installed!
This is a highly recommended mod that can detect save file corruption.
Link: https://www.nexusmods.com/fallout4/mods/44949?tab=files

✔️ High FPS Physics Fix is installed!

✔️ Previs Repair Pack (PRP) is installed!

✔️ Unofficial Fallout 4 Patch is installed!

✔️ Nvidia Weapon Debris Fix is installed!

✔️ Nvidia Reflex Support is installed!

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- prp.esp | 1
- rustyfacefix.dll | 1
- highfpsphysicsfix.dll | 2
- stm_diamondcityexpansion.esp | 2

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- Form ID: 00000000 | [Fallout4.esm] | 2
- Form ID: 0000003C | [Fallout4.esm] | 1
- Form ID: 00000FDA | [Fallout4.esm] | 2
- Form ID: 00002CE2 | [Fallout4.esm] | 1
- Form ID: 00042A1C | [Fallout4.esm] | 3
- Form ID: 001765E3 | [Fallout4.esm] | 1
- Form ID: 001765E7 | [Fallout4.esm] | 5
- Form ID: 001765FA | [Fallout4.esm] | 1

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- (void* -> HighFPSPhysicsFix.dll+0030AE0) | 1
- (void* -> HighFPSPhysicsFix.dll+0030B16) | 1
- (void* -> RustyFaceFix.dll+000456E) | 1
- (void* -> gameoverlayrenderer64.dll+006BD53) | 1
- (void* -> gameoverlayrenderer64.dll+0097604) | 1
- (void* -> nvapi64.dll+0617710) | 1
- (void* -> nvapi64.dll+06FA5E0) | 2
- Full Name: "Commonwealth" | 1

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
