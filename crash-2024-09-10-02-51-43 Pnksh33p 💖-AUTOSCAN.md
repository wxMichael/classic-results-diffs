crash-2024-09-10-02-51-43 Pnksh33p 💖.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF7D9DD8880 Fallout4.exe+0008880	test byte ptr [rcx+0x40], 0x01

Detected Buffout 4 Version: Buffout 4 v1.35.1 Jul  5 2024 20:37:23 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Script Crash.................. SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Mesh (NIF) Crash.............. SUSPECT FOUND! > Severity : 4 # 
-----
# Checking for NPC Pathing Crash (S)......... SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Player Character Crash........ SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for *[Looks Menu Crash]........... SUSPECT FOUND! > Severity : 1 # 
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

✔️ Achievements parameter is correctly configured in your Buffout 4 settings! 
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
# FOUND NO MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 

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
[!] FOUND : [0E] Homemaker
    - Causes a crash while scrolling over Military / BoS fences in the Settlement Menu.
      Advised Fix: Make sure you are using at least version 1.73 of this mod.
      Alternate Fix: https://www.nexusmods.com/fallout4/mods/41434?tab=files
    -----
[!] FOUND : [1E] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [33] Raider Children

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
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- ll_fourplay_1_10_163.dll | 5
- commonwealthchooksandbunnies.esp | 28

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- FormID: 00000007 | [Fallout4.esm] | 2
- FormID: 00000014 | [Fallout4.esm] | 4
- FormID: 000002CE | [Fallout4.esm] | 5
- FormID: 000002F7 | [Fallout4.esm] | 3
- FormID: 0000DA6E | [Fallout4.esm] | 2
- FormID: 0000DE33 | [Fallout4.esm] | 2
- FormID: 0003180F | [Fallout4.esm] | 1
- FormID: 000BACBE | [Fallout4.esm] | 1
- FormID: 0013350D | [Fallout4.esm] | 2
- FormID: 00133511 | [Fallout4.esm] | 2
- FormID: 001C4996 | [Fallout4.esm] | 4
- FormID: 001C4997 | [Fallout4.esm] | 2
- FormID: 00225B71 | [Fallout4.esm] | 1
- FormID: 31011894 | [CommonwealthChooksAndBunnies.esp] | 13
- FormID: 31015C5A | [CommonwealthChooksAndBunnies.esp] | 13

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- (void* -> LL_fourPlay_1_10_163.dll+0002CFC	lea rcx, [rax+0x27]) | 1
- (void* -> LL_fourPlay_1_10_163.dll+0002E08	nop) | 1
- (void* -> LL_fourPlay_1_10_163.dll+000EFB6	mov r15, rax) | 1
- (void* -> LL_fourPlay_1_10_163.dll+0013DC3	nop) | 1
- (void* -> LL_fourPlay_1_10_163.dll+001E3E0	mov [rbx+0x08], rax) | 1
- EditorID: "POIJS025" | 2
- EditorID: "RotationSpeedCondition" | 5
- EditorID: "WaterWalking" | 3
- EditorID: "Wilderness" | 2
- Name: "LL_fourPlay" | 1
- Name: "ObjectLODRoot" | 1
- Name: "UNIQUEWaterDamLock" | 1
- Name: "WorldRoot Node" | 1
- Name: "aaf:aaf_mainquestscript" | 1
- Name: "shadow scene node" | 1
- RTTIName: "BSFadeNode" | 1
- RTTIName: "BSMultiBoundNode" | 2
- RTTIName: "NiNode" | 2
- RTTIName: "SceneGraph" | 1
- RTTIName: "ShadowSceneNode" | 1

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
