crash-Scarlamagne 1.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF622F8C7AF Fallout4.exe+1DDC7AF

Detected Buffout 4 Version: Buffout 4 v1.26.2 
# [!] CAUTION : YOUR BUFFOUT 4 VERSION MIGHT BE OUT OF DATE, UPDATE BO4 IF NECESSARY #
  Original Buffout Version: https://www.nexusmods.com/fallout4/mods/47359
  Buffout VR / NG Version: https://www.nexusmods.com/fallout4/mods/64880
  Buffout 4 Guide: https://www.nexusmods.com/fallout4/articles/3115
 
====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Script Crash.................. SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for Mesh (NIF) Crash.............. SUSPECT FOUND! > Severity : 4 # 
-----
# Checking for Player Character Crash........ SUSPECT FOUND! > Severity : 3 # 
-----
# Checking for *[Looks Menu Crash]........... SUSPECT FOUND! > Severity : 1 # 
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
[!] FOUND : [15] Weapons Framework Beta
    - Will randomly cause crashes when used with Tactical Reload and possibly other weapon or combat related mods.
      Visit Important Patches List article for possible solutions: https://www.nexusmods.com/fallout4/articles/3769
    -----
# [!] CAUTION : ANY ABOVE DETECTED MODS HAVE A MUCH HIGHER CHANCE TO CRASH YOUR GAME! #
* YOU CAN DISABLE ANY / ALL OF THEM TEMPORARILY TO CONFIRM THEY CAUSED THIS CRASH. * 

====================================================
CHECKING FOR MODS THAT CONFLICT WITH OTHER MODS...
====================================================
[!] CAUTION : Extended Weapon Systems ❌ CONFLICTS WITH : Tactical Reload
    Using both mods can frequently crash the game.
    Use only one of these mods, not both at the same time.
    -----
# [!] CAUTION : FOUND MODS THAT ARE INCOMPATIBLE OR CONFLICT WITH YOUR OTHER MODS # 
* YOU SHOULD CHOOSE WHICH MOD TO KEEP AND DISABLE OR COMPLETELY REMOVE THE OTHER MOD * 

====================================================
CHECKING FOR MODS WITH SOLUTIONS & COMMUNITY PATCHES
====================================================
[!] FOUND : [07] High Resolution DLC. I STRONGLY ADVISE AGAINST USING IT!
    - Right click on Fallout 4 in your Steam Library folder, then select Properties
      Switch to the DLC tab and uncheck / disable the High Resolution Texture Pack.
    -----
[!] FOUND : [0D] Advanced Animation Framework
    - Latest AAF version only available on Moddingham | AAF Tech Support: https://discord.gg/gWZuhMC
      Latest AAF Link (register / login to download): https://www.moddingham.com/viewtopic.php?t=2
    -----
    - Looks Menu versions 1.6.20 & 1.6.19 can frequently break adult mod related (erection) morphs.
      If you notice AAF related problems, remove latest version of Looks Menu and switch to 1.6.18.
    -----
[!] FOUND : [14] Armor And Weapons Keywords
    - If you don't rely on AWKCR, consider switching to Equipment and Crafting Overhaul
      Better Alternative: https://www.nexusmods.com/fallout4/mods/67679?tab=files
      Patches to remove AWKCR: https://www.nexusmods.com/fallout4/mods/40752?tab=files
    -----
[!] FOUND : [FB] Decay Better Ghouls
    - You have to install DECAY Redux patch to prevent its audio files from crashing the game.
      Patch Link: https://www.nexusmods.com/fallout4/mods/59025?tab=files
    -----
[!] FOUND : [DLL] Fallsouls Unpaused Game Menus
    - Occasionally breaks the Quests menu, can cause crashes while changing MCM settings.
      Advised Fix: Toggle PipboyMenu in FallSouls MCM settings or completely reinstall the mod.
    -----
[!] FOUND : [FE082] HUD Caps
    - Often breaks the Save / Quicksave function due to poor script implementation.
      Advised Fix: Download fixed pex file and place it into HUDCaps/Scripts folder.
      Fix Link: https://drive.google.com/file/d/1egmtKVR7mSbjRgo106UbXv_ySKBg5az2
    -----
[!] FOUND : [B1] Looks Menu Customization Compendium
    - If you are getting broken hair colors, install this mod and make sure it loads after LMCC.
      Mod Link: https://www.nexusmods.com/fallout4/mods/18287?tab=files
    -----
[!] FOUND : [10] Tactical Reload
    - Can cause weapon and combat related crashes. TR Expansion For ECO is highly recommended.
      TR Expansion For ECO Link: https://www.nexusmods.com/fallout4/mods/67716?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [19] Tales from the Commonwealth
[!] FOUND : [1D] Glowing Sea EXPANDED
[!] FOUND : [1B] Minutemen Supply Caches
[!] FOUND : [17] Mutilated Dead Bodies
[!] FOUND : [18] Raider Children

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

❌ Unofficial Fallout 4 Patch is not installed!
If you own all DLCs, make sure that the Unofficial Patch is installed.
Link: https://www.nexusmods.com/fallout4/mods/4598?tab=files

❌ Nvidia Weapon Debris Fix is not installed!
This is a mandatory patch / fix required for almost all Nvidia GPUs.
Link: https://www.nexusmods.com/fallout4/mods/48078?tab=files

✔️ Nvidia Reflex Support is installed!

====================================================
SCANNING THE LOG FOR SPECIFIC (POSSIBLE) SUSPECTS...
====================================================
# LIST OF (POSSIBLE) PLUGIN SUSPECTS #
- 3dnpc_fo4.esp | 14
- kshairdos.esp | 1
- uniqueplayer.esp | 1
- sanctuary-estates-clean-bos.esp | 1

[Last number counts how many times each Plugin Suspect shows up in the crash log.]
These Plugins were caught by Buffout 4 and some of them might be responsible for this crash.
You can try disabling these plugins and check if the game still crashes, though this method can be unreliable.

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
- Form ID: 00000007 | [Fallout4.esm] | 1
- Form ID: 00000010 | [Fallout4.esm] | 1
- Form ID: 00000014 | [Fallout4.esm] | 1
- Form ID: 0000003B | [Fallout4.esm] | 4
- Form ID: 0000003C | [Fallout4.esm] | 1
- Form ID: 0002A4BB | [Fallout4.esm] | 1
- Form ID: 0006B500 | [Fallout4.esm] | 1
- Form ID: 0006B505 | [Fallout4.esm] | 1
- Form ID: 000D811C | [Fallout4.esm] | 1
- Form ID: 00102249 | [Fallout4.esm] | 1
- Form ID: 0012221F | [Fallout4.esm] | 1
- Form ID: 00195909 | [Fallout4.esm] | 1
- Form ID: 001A43EE | [Fallout4.esm] | 1
- Form ID: 190030BA | [3DNPC_FO4.esp] | 7
- Form ID: 19004320 | [3DNPC_FO4.esp] | 7
- Form ID: E70008C7 | [KSHairdos.esp] | 1

[Last number counts how many times each Form ID shows up in the crash log.]
These Form IDs were caught by Buffout 4 and some of them might be related to this crash.
You can try searching any listed Form IDs in xEdit and see if they lead to relevant records.

# LIST OF DETECTED (NAMED) RECORDS #
- Full Name: "Commonwealth" | 1
- Full Name: "Prep School" | 1
- Full Name: "Sleepwalker Alt" | 1
- Full Name: "The Glowing Sea" | 1
- Name: "BSFaceGenNiNodeSkinned" | 2
- Name: "MarkerX" | 2
- Name: "MarkerX:0" | 1
- Name: "Sleepwalker2" | 4
- Name: "WorldRoot Node" | 1
- Name: "shadow scene node" | 1

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
