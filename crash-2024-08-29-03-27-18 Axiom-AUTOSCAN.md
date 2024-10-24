crash-2024-08-29-03-27-18 Axiom.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF6194CAD01 Fallout4.exe+070AD01	movsx ecx, byte ptr [rcx+0x24] 
  FUN_14070acf0_70AD01)

Detected Buffout 4 Version: Buffout 4 v1.35.1 Jul  5 2024 20:37:23 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for LOD Crash..................... SUSPECT FOUND! > Severity : 5 # 
-----
# Checking for NPC Pathing Crash (S)......... SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Particle Effects Crash........ SUSPECT FOUND! > Severity : 4 # 
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
[!] FOUND : [0C] Advanced Animation Framework
    - Latest AAF version only available on Moddingham | AAF Tech Support: https://discord.gg/gWZuhMC
      Latest AAF Link (register / login to download): https://www.moddingham.com/viewtopic.php?t=2
    -----
    - Looks Menu versions 1.6.20 & 1.6.19 can frequently break adult mod related (erection) morphs.
      If you notice AAF related problems, remove latest version of Looks Menu and switch to 1.6.18.
    -----
[!] FOUND : [FE] Everyone's Best Friend
    - This mod needs a compatibility patch to forward changes made by the Unofficial Patch.
      Patch Link: https://drive.google.com/file/d/1JJvrnaxmui22P1X44V2VTkifjmfahtLM
      If you have Horizon installed or don't use UFO4P, this patch is not needed.
    -----
[!] FOUND : [41] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [23] Militarized Minutemen
    - Can occasionally crash the game due to a broken mesh on some minutemen outfits.
      Patch Link: https://www.nexusmods.com/fallout4/mods/32369?tab=files
    -----
[!] FOUND : [2E] Natural And Atmospheric Commonwealth
    - If you notice weird looking skin tones with either NAC or NACX, install this patch.
      Patch Link: https://www.nexusmods.com/fallout4/mods/57052?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [1A] Wasteland Imports (Mojave Imports)
[!] FOUND : [16] Mutilated Dead Bodies

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
- elfx-previs.esp | 4
- acemalerace.esp | 4
- prp-compat-pointlookout.esp | 2
- tumba_minutemenmarshaloutfit.esp | 1
- militarizedminutemen.esp | 1
- x-cell-fo4.dll | 1

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- FormID: 00000000 | [Fallout4.esm] | 13
- FormID: 00000007 | [Fallout4.esm] | 4
- FormID: 00000014 | [Fallout4.esm] | 4
- FormID: 00000034 | [Fallout4.esm] | 3
- FormID: 0000003C | [Fallout4.esm] | 2
- FormID: 0000031C | [Fallout4.esm] | 2
- FormID: 00019FD9 | [Fallout4.esm] | 1
- FormID: 0001A4D7 | [Fallout4.esm] | 1
- FormID: 000210B4 | [Fallout4.esm] | 1
- FormID: 00042A1C | [Fallout4.esm] | 3
- FormID: 00066EBA | [Fallout4.esm] | 1
- FormID: 000A02D8 | [Fallout4.esm] | 1
- FormID: 000AB334 | [Fallout4.esm] | 3
- FormID: 000F4BF4 | [Fallout4.esm] | 4
- FormID: 0011C4EB | [Fallout4.esm] | 1
- FormID: 0015D3FD | [Fallout4.esm] | 3
- FormID: 0015D3FE | [Fallout4.esm] | 13

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- EditorID: "Commonwealth" | 2
- EditorID: "MassFusion01" | 4
- EditorID: "RemoveBeforeFastTravel" | 1
- EditorID: "WaitingForPlayer" | 2
- GetFullName: "Arcjet Lab Password" | 1
- GetFullName: "Clayton" | 1
- GetFullName: "Commonwealth" | 2
- GetFullName: "Kellogg's Terminal Password" | 1
- GetFullName: "Mass Fusion Building" | 2
- GetFullName: "Synth" | 3
- GetFullName: "The Castle" | 1
- Name: "Package" | 3
- Name: "WorldRoot Node" | 1
- Name: "shadow scene node" | 1
- RTTIName: "BSMasterParticleSystem" | 1
- RTTIName: "BSParticleSystemManager" | 1
- RTTIName: "SceneGraph" | 1
- RTTIName: "ShadowSceneNode" | 1
- void* -> x-cell-fo4.dll+0019D55	movzx eax, bl) | 1

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
