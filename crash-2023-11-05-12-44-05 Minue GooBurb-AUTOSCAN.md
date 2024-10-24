crash-2023-11-05-12-44-05 Minue GooBurb.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF7877386FD Fallout4.exe+01786FD	mov rdx, [r15+0x28] 
  BGSConstructFormsInFileMap::ConstructForms(TESFile*,BGSConstructedForms*)_1786FD)

Detected Buffout 4 Version: Buffout 4 v1.31.1 Feb 28 2023 00:32:02 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Player Character Crash........ SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for *[Save Crash]................. SUSPECT FOUND! > Severity : 1 # 
-----
* FOR DETAILED DESCRIPTIONS AND POSSIBLE SOLUTIONS TO ANY ABOVE DETECTED CRASH SUSPECTS *
* SEE: https://docs.google.com/document/d/17FzeIMJ256xE85XdjoPvv_Zi3C5uHeSTQh6wOZugs4c *

====================================================
CHECKING IF NECESSARY FILES/SETTINGS ARE CORRECT...
====================================================
* NOTICE: FCX MODE IS DISABLED. YOU CAN ENABLE IT TO DETECT PROBLEMS IN YOUR MOD & GAME FILES * 
[ FCX Mode can be enabled in the exe or CLASSIC Settings.yaml located in your CLASSIC folder. ] 

* NOTICE : PipboyLightInvFix is disabled in your Buffout 4 settings, is this intentional? * 
-----
# ❌ CAUTION : The Achievements Mod and/or Unlimited Survival Mode is installed, but Achievements is set to TRUE # 
 FIX: Open Buffout 4's TOML file and change Achievements to FALSE, this prevents conflicts with Buffout 4.
-----
# ❌ CAUTION : The Baka ScrapHeap Mod is installed, but is redundant with Buffout 4 # 
 FIX: Uninstall the Baka ScrapHeap Mod, this prevents conflicts with Buffout 4.
-----
# ❌ CAUTION : Looks Menu is installed, but F4EE parameter under [Compatibility] is set to FALSE # 
 FIX: Open Buffout 4's TOML file and change F4EE to TRUE, this prevents bugs and crashes from Looks Menu.
-----
❌ FCX Mode is disabled, skipping game files check... 
-----
====================================================
CHECKING FOR MODS THAT CAN CAUSE FREQUENT CRASHES...
====================================================
[!] FOUND : [FF] Scrap Everything (Core Or Ultimate)
    - Weird crashes and issues due to multiple unknown problems. This mod must be always last in your load order.
    -----
[!] FOUND : [11] Spring Cleaning
    - Abandoned and severely outdated mod that breaks precombines and could potentially even break your save file.
    -----
# [!] CAUTION : ANY ABOVE DETECTED MODS HAVE A MUCH HIGHER CHANCE TO CRASH YOUR GAME! #
* YOU CAN DISABLE ANY / ALL OF THEM TEMPORARILY TO CONFIRM THEY CAUSED THIS CRASH. * 

====================================================
CHECKING FOR MODS THAT CONFLICT WITH OTHER MODS...
====================================================
[!] CAUTION : Unique Player ❌ CONFLICTS WITH : Classic Holstered Weapons
    Classic Holstered Weapons will not work correctly with mods that modify the player skeleton or add new skeleton paths.
    If you encounter problems or crashes, see here how to add additional skeletons: https://www.nexusmods.com/fallout4/articles/2496
    -----
[!] CAUTION : High Heels System ❌ CONFLICTS WITH : Classic Holstered Weapons
    Classic Holstered Weapons will not work correctly with mods that modify the player skeleton or add new skeleton paths.
    If you encounter problems or crashes, see here how to add additional skeletons: https://www.nexusmods.com/fallout4/articles/2496
    -----
# [!] CAUTION : FOUND MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 
* YOU SHOULD CHOOSE WHICH MOD TO KEEP AND DISABLE OR COMPLETELY REMOVE THE OTHER MOD * 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [0F] Advanced Animation Framework
    - Latest AAF version only available on Moddingham | AAF Tech Support: https://discord.gg/gWZuhMC
      Latest AAF Link (register / login to download): https://www.moddingham.com/viewtopic.php?t=2
    -----
    - Looks Menu versions 1.6.20 & 1.6.19 can frequently break adult mod related (erection) morphs.
      If you notice AAF related problems, remove latest version of Looks Menu and switch to 1.6.18.
    -----
[!] FOUND : [09] Armor And Weapons Keywords
    - If you don't rely on AWKCR, consider switching to Equipment and Crafting Overhaul
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
      Patches to remove AWKCR: https://www.nexusmods.com/fallout4/mods/40752?tab=files
    -----
[!] FOUND : [0C] Homemaker
    - Causes a crash while scrolling over Military / BoS fences in the Settlement Menu.
      Advised Fix: Make sure you are using at least version 1.73 of this mod.
      Alternate Fix: https://www.nexusmods.com/fallout4/mods/41434?tab=files
    -----
[!] FOUND : [66] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [FC] Start Me Up
    - Abandoned mod that can cause infinite loading and other problems. Switch to REDUX Version instead.
      Updated REDUX Version: https://www.nexusmods.com/fallout4/mods/56984?tab=files
    -----
[!] FOUND : [1F] Tactical Reload
    - Can cause weapon and combat related crashes. TR Expansion For ECO is highly recommended.
      TR Expansion For ECO Link: https://www.nexusmods.com/fallout4/mods/67716?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [34] Tales from the Commonwealth

* FOR PATCH REPOSITORY THAT PREVENTS CRASHES AND FIXES PROBLEMS IN THESE AND OTHER MODS,* 
* VISIT OPTIMIZATION PATCHES COLLECTION: https://www.nexusmods.com/fallout4/mods/54872 * 

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

✔️ Nvidia Weapon Debris Fix is installed!

❌ Nvidia Reflex Support is not installed!
This is a highly recommended mod that can improve performance on Nvidia GPUs.
Link: https://www.nexusmods.com/fallout4/mods/64459?tab=files

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# [!] CAUTION : ONE OF YOUR PLUGINS HAS THE [FF] PLUGIN INDEX VALUE #
* THIS MEANS YOU ALMOST CERTAINLY WENT OVER THE GAME PLUGIN LIMIT! *
Disable some of your esm/esp plugins and re-run the Crash Logs Scan.
-----
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- vis-g item sorting.esp | 2
- f4z ro d'oh.dll | 1
- uniqueplayer.esp | 1
- ss2.esm | 1
- ss2-prarandomaddon.esp | 6

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- FormID: 00000007 | [Fallout4.esm] | 1
- FormID: 00000014 | [Fallout4.esm] | 2
- FormID: 000BD56F | [Fallout4.esm] | 2
- FormID: 000F7C5D | [Fallout4.esm] | 1
- FormID: 0013C8D0 | [Fallout4.esm] | 1
- FormID: 04034525 | [DLCworkshop02.esm] | 5
- FormID: 04034527 | [DLCworkshop02.esm] | 1
- FormID: 13014576 | [SS2.esm] | 1

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- (void* -> F4z Ro D'oh.dll+000F16C	add rsp, 0x78) | 1
- EditorID: "ElevatorMeterHiTech" | 1
- EditorID: "Fatman" | 2
- EditorID: "SS2_WorkbenchTag_CityPlannersDesk" | 1
- EditorID: "praSS2_PackedLargeCityPlannerDesk" | 1
- EditorID: "praSS2_co_CityPlannerDesk_Packed" | 5
- GetFullName: "Packed Huge Leader Desk" | 1
- Name: "Gun" | 2

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
