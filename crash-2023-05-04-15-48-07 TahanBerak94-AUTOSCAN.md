crash-2023-05-04-15-48-07 TahanBerak94.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FFD70C5B7A4 d3d11.dll+012B7A4

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
# Checking for Rendering Crash............... SUSPECT FOUND! > Severity : 4 # 
-----
# Checking for *[Looks Menu Crash]........... SUSPECT FOUND! > Severity : 1 # 
-----
# Checking for *[Camera Position Crash]...... SUSPECT FOUND! > Severity : 1 # 
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
[!] FOUND : [49] Respawnable Legendary Bosses
    - Can sometimes cause Deathclaw / Behemoth boulder projectile crashes for unknown reasons.
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
[!] FOUND : [0B] Armor And Weapons Keywords
    - If you don't rely on AWKCR, consider switching to Equipment and Crafting Overhaul
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
      Patches to remove AWKCR: https://www.nexusmods.com/fallout4/mods/40752?tab=files
    -----
[!] FOUND : [92] Decay Better Ghouls
    - You have to install DECAY Redux patch to prevent its audio files from crashing the game.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59025?tab=files
    -----
[!] FOUND : [91] Give Me That Bottle
    - Can rarely cause crashes in the Pip-Boy inventory menu. Switch to Fill'em Up Again instead.
      Better Alternative: https://www.nexusmods.com/fallout4/mods/12674?tab=files
    -----
[!] FOUND : [FE0B3] Legendary Modification
    - Old mod plagued with all kinds of bugs and crashes, can conflict with some modded weapons.
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
    -----
[!] FOUND : [85] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [3D] Militarized Minutemen
    - Can occasionally crash the game due to a broken mesh on some minutemen outfits.
      Patch Link: https://www.nexusmods.com/fallout4/mods/32369?tab=files
    -----
[!] FOUND : [61] Natural And Atmospheric Commonwealth
    - If you notice weird looking skin tones with either NAC or NACX, install this patch.
      Patch Link: https://www.nexusmods.com/fallout4/mods/57052?tab=files
    -----
[!] FOUND : [8F] Northland Diggers Resources
    - Contains various bugs and issues that can cause crashes or negatively affect other mods.
      Fix Link: https://www.nexusmods.com/fallout4/mods/53395?tab=files
    -----
[!] FOUND : [2E] Raider Overhaul
    - Old mod that requires several patches to function as intended. Use ONE Version instead.
      Updated ONE Version: https://www.nexusmods.com/fallout4/mods/51658?tab=files
    -----
[!] FOUND : [27] Super Mutant Redux
    - Causes crashes at specific locations or with certain Super Mutant enemies and items.
      Patch Link: https://www.nexusmods.com/fallout4/mods/51353?tab=files
    -----
[!] FOUND : [16] Tactical Reload
    - Can cause weapon and combat related crashes. TR Expansion For ECO is highly recommended.
      TR Expansion For ECO Link: https://www.nexusmods.com/fallout4/mods/67716?tab=files
    -----
[!] FOUND : [1B] Unique NPCs Creatures And Monsters
    - Causes crashes and breaks precombines at specific locations, some creature spawns are too frequent.
      Patch Link: https://www.nexusmods.com/fallout4/mods/48637?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [29] Wasteland Imports (Mojave Imports)
[!] FOUND : [1F] Mutilated Dead Bodies
[!] FOUND : [21] Raider Children

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

❌ Vulkan Renderer is not installed!
This is a highly recommended mod that can improve performance on AMD GPUs.
Link: https://www.nexusmods.com/fallout4/mods/48053?tab=files

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
* COULDN'T FIND ANY PLUGIN SUSPECTS *

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
* COULDN'T FIND ANY FORM ID SUSPECTS *

# LIST OF DETECTED (NAMED) RECORDS #
- (void* -> GFSDK_SSAO_D3D11.win64.dll+0004D4F) | 1
- (void* -> GFSDK_SSAO_D3D11.win64.dll+0009551) | 1
- (void* -> atidxx64.dll+003AD76) | 1
- (void* -> atidxx64.dll+003ADDB) | 1
- (void* -> atidxx64.dll+00B9A2B) | 2
- (void* -> atidxx64.dll+00C6B38) | 1
- (void* -> atidxx64.dll+00C6B76) | 1
- (void* -> atidxx64.dll+09656E7) | 1
- Name: "shadow scene node" | 1
- R10 0x7FFD6A4D4FF0     (void* -> atidxx64.dll+1C64FF0) | 1

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
