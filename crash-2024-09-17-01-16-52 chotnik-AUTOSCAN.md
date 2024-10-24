crash-2024-09-17-01-16-52 chotnik.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF7080CEC43 Fallout4.exe+0D9EC43	call [rax+0x168]

Detected Buffout 4 Version: Buffout 4 v1.35.1 Jul  5 2024 20:37:23 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for LOD Crash..................... SUSPECT FOUND! > Severity : 5 # 
-----
# Checking for Mesh (NIF) Crash.............. SUSPECT FOUND! > Severity : 4 # 
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

* NOTICE : HavokMemorySystem is disabled in your Buffout 4 settings, is this intentional? * 
-----
* NOTICE : ScaleformAllocator is disabled in your Buffout 4 settings, is this intentional? * 
-----
* NOTICE : SmallBlockAllocator is disabled in your Buffout 4 settings, is this intentional? * 
-----
✔️ Achievements parameter is correctly configured in your Buffout 4 settings! 
-----
✔️ Memory Manager parameter is correctly configured for use with X-Cell in your Buffout 4 settings! 
-----
✔️ HavokMemorySystem parameter is correctly configured for use with X-Cell in your Buffout 4 settings! 
-----
✔️ BSTextureStreamerLocalHeap parameter is correctly configured for use with X-Cell in your Buffout 4 settings! 
-----
✔️ ScaleformAllocator parameter is correctly configured for use with X-Cell in your Buffout 4 settings! 
-----
✔️ SmallBlockAllocator parameter is correctly configured for use with X-Cell in your Buffout 4 settings! 
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
[!] FOUND : [FE08C] Decay Better Ghouls
    - You have to install DECAY Redux patch to prevent its audio files from crashing the game.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59025?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [1F] Tales from the Commonwealth
[!] FOUND : [22] Fourville (Vault 4)

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
- prp.esp | 12
- x-cell-fo4.dll | 3
- lost audio tweaks.esp | 1

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- FormID: 00000007 | [Fallout4.esm] | 5
- FormID: 00000014 | [Fallout4.esm] | 10
- FormID: 00002374 | [Fallout4.esm] | 12
- FormID: 0002179F | [Fallout4.esm] | 1
- FormID: 000340C0 | [Fallout4.esm] | 1
- FormID: 00077CFC | [Fallout4.esm] | 1
- FormID: 00093221 | [Fallout4.esm] | 5
- FormID: 000E8D0A | [Fallout4.esm] | 1

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- EditorID: "UniversityPoint01" | 12
- GetFullName: "University Point" | 1
- GetFullName: "University Point: Sedgwick Hall" | 6
- Name: "4" | 1
- Name: "LODRoot" | 1
- Name: "LandAndObjectLOD" | 1
- Name: "ObjectLODRoot" | 2
- Name: "Objects" | 1
- Name: "WorldRoot Node" | 3
- Name: "obj" | 3
- Name: "shadow scene node" | 3
- RTTIName: "BSClearZNode" | 1
- RTTIName: "BSFadeNode" | 2
- RTTIName: "BSMultiBoundNode" | 5
- RTTIName: "BSSubIndexTriShape" | 1
- RTTIName: "BSWaterShaderProperty" | 1
- RTTIName: "NiNode" | 8
- RTTIName: "SceneGraph" | 3
- RTTIName: "ShadowSceneNode" | 3
- void* -> x-cell-fo4.dll+0019B80	lea r11, [rsp+0x60]) | 1
- void* -> x-cell-fo4.dll+001AE16	mov al, 0x01) | 1
- void* -> x-cell-fo4.dll+001B066	mov al, 0x01) | 1

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
