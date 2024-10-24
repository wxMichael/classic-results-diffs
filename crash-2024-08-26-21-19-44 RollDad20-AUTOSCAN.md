crash-2024-08-26-21-19-44 RollDad20.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF7A65C89C9 Fallout4.exe+05B89C9	cmp r8, [rax+0xA0]

Detected Buffout 4 Version: Buffout 4 v1.35.1 Jul  5 2024 20:37:23 
* You have the latest version of Buffout 4! *

====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Player Character Crash........ SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for *[Item Crash]................. SUSPECT FOUND! > Severity : 1 # 
-----
* FOR DETAILED DESCRIPTIONS AND POSSIBLE SOLUTIONS TO ANY ABOVE DETECTED CRASH SUSPECTS *
* SEE: https://docs.google.com/document/d/17FzeIMJ256xE85XdjoPvv_Zi3C5uHeSTQh6wOZugs4c *

====================================================
CHECKING IF NECESSARY FILES/SETTINGS ARE CORRECT...
====================================================
* NOTICE: FCX MODE IS DISABLED. YOU CAN ENABLE IT TO DETECT PROBLEMS IN YOUR MOD & GAME FILES * 
[ FCX Mode can be enabled in the exe or CLASSIC Settings.yaml located in your CLASSIC folder. ] 

* NOTICE : InteriorNavCut is disabled in your Buffout 4 settings, is this intentional? * 
-----
* NOTICE : HavokMemorySystem is disabled in your Buffout 4 settings, is this intentional? * 
-----
* NOTICE : ScaleformAllocator is disabled in your Buffout 4 settings, is this intentional? * 
-----
* NOTICE : SmallBlockAllocator is disabled in your Buffout 4 settings, is this intentional? * 
-----
✔️ Achievements parameter is correctly configured in your Buffout 4 settings! 
-----
# ❌ CAUTION : The Baka ScrapHeap Mod is installed, but is redundant with X-Cell # 
 FIX: Uninstall the Baka ScrapHeap Mod, this prevents conflicts with X-Cell.
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
[!] FOUND : [53] Respawnable Legendary Bosses
    - Can sometimes cause Deathclaw / Behemoth boulder projectile crashes for unknown reasons.
    -----
[!] FOUND : [96] Spring Cleaning
    - Abandoned and severely outdated mod that breaks precombines and could potentially even break your save file.
    -----
# [!] CAUTION : ANY ABOVE DETECTED MODS HAVE A MUCH HIGHER CHANCE TO CRASH YOUR GAME! #
* YOU CAN DISABLE ANY / ALL OF THEM TEMPORARILY TO CONFIRM THEY CAUSED THIS CRASH. * 

====================================================
CHECKING FOR MODS THAT CONFLICT WITH OTHER MODS...
====================================================
[!] CAUTION : The Fens Sheriff's Department ❌ CONFLICTS WITH : Varied Diamond City Guards
    Both mods heavily modify Diamond City Guards records.
    Use only one of these mods, not both at the same time.
    -----
[!] CAUTION : Fallout Priority ❌ CONFLICTS WITH : X-Cell
    X-Cell has equivalent functionality to Fallout Priority when the threads feature is enabled.
    -----
[!] CAUTION : Baka ScrapHeap ❌ CONFLICTS WITH : X-Cell
    X-Cell has equivalent functionality to Baka ScrapHeap when the memory feature is enabled.
    -----
[!] CAUTION : Private Profile Redirector ❌ CONFLICTS WITH : X-Cell
    X-Cell has equivalent functionality to Private Profile Redirector when the io feature (changed to profile in v1.2-b2+) is enabled.
    -----
[!] CAUTION : Disk Cache Enabler ❌ CONFLICTS WITH : X-Cell
    X-Cell has equivalent functionality to Disk Cache Enabler when the io feature is enabled.
    -----
# [!] CAUTION : FOUND MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 
* YOU SHOULD CHOOSE WHICH MOD TO KEEP AND DISABLE OR COMPLETELY REMOVE THE OTHER MOD * 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [FE0A7] Everyone's Best Friend
    - This mod needs a compatibility patch to forward changes made by the Unofficial Patch.
      Patch Link: https://drive.google.com/file/d/1JJvrnaxmui22P1X44V2VTkifjmfahtLM
      If you have Horizon installed or don't use UFO4P, this patch is not needed.
    -----
[!] FOUND : [FE051] South Of The Sea
    - Very unstable mod that consistently and frequently causes strange problems and crashes.
      Updated Version: https://www.nexusmods.com/fallout4/mods/63152?tab=files
    -----
[!] FOUND : [AF] Start Me Up
    - Abandoned mod that can cause infinite loading and other problems. Switch to REDUX Version instead.
      Updated REDUX Version: https://www.nexusmods.com/fallout4/mods/56984?tab=files
    -----
[!] FOUND : [29] Super Mutant Redux
    - Causes crashes at specific locations or with certain Super Mutant enemies and items.
      Patch Link: https://www.nexusmods.com/fallout4/mods/51353?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [1C] Tales from the Commonwealth
[!] FOUND : [44] Settlers Of The Commonwealth
[!] FOUND : [2B] Wasteland Imports (Mojave Imports)

* FOR PATCH REPOSITORY THAT PREVENTS CRASHES AND FIXES PROBLEMS IN THESE AND OTHER MODS,* 
* VISIT OPTIMIZATION PATCHES COLLECTION: https://www.nexusmods.com/fallout4/mods/54872 * 

====================================================
CHECKING IF IMPORTANT PATCHES & FIXES ARE INSTALLED
====================================================
❌ Canary Save File Monitor is not installed!
This is a highly recommended mod that can detect save file corruption.
Link: https://www.nexusmods.com/fallout4/mods/44949?tab=files

❌ High FPS Physics Fix is not installed!
This is a mandatory patch / fix that prevents game engine problems.
Link: https://www.nexusmods.com/fallout4/mods/44798?tab=files

✔️ Previs Repair Pack (PRP) is installed!

✔️ Unofficial Fallout 4 Patch is installed!

✔️ Vulkan Renderer is installed!

❓ Nvidia Weapon Debris Fix is installed, BUT IT SEEMS YOU DON'T HAVE AN NVIDIA GPU?
IF THIS IS CORRECT, COMPLETELY UNINSTALL THIS MOD TO AVOID ANY PROBLEMS! 

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- community fixes merged.esp | 18
- m8r complex sorter.esp | 4

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- FormID: AE0081F6 | [Pip2000MkVi_Replacer.esp] | 4

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- GetFullName: "Enclave Laser Turret Mk I" | 3
- GetFullName: "Enclave Laser Turret Mk II" | 6
- GetFullName: "[NonHuman] Pip-Boy 2000" | 4

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
