crash-2022-12-29-01-19-04 LikeMikeRyan.log -> AUTOSCAN REPORT GENERATED BY CLASSIC v7.30.3 
# FOR BEST VIEWING EXPERIENCE OPEN THIS FILE IN NOTEPAD++ OR SIMILAR # 
# PLEASE READ EVERYTHING CAREFULLY AND BEWARE OF FALSE POSITIVES # 
====================================================

Main Error: Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF6BB818E16 Fallout4.exe+2878E16

Detected Buffout 4 Version: Buffout 4 v1.26.2 
# [!] CAUTION : YOUR BUFFOUT 4 VERSION MIGHT BE OUT OF DATE, UPDATE BO4 IF NECESSARY #
  Original Buffout Version: https://www.nexusmods.com/fallout4/mods/47359
  Buffout VR / NG Version: https://www.nexusmods.com/fallout4/mods/64880
  Buffout 4 Guide: https://www.nexusmods.com/fallout4/articles/3115
 
====================================================
CHECKING IF LOG MATCHES ANY KNOWN CRASH SUSPECTS...
====================================================
# Checking for Nvidia Driver Crash........... SUSPECT FOUND! > Severity : 5 # 
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
[!] FOUND : [FE002] Advanced Animation Framework
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
[!] FOUND : [3B] Everyone's Best Friend
    - This mod needs a compatibility patch to forward changes made by the Unofficial Patch.
      Patch Link: https://drive.google.com/file/d/1JJvrnaxmui22P1X44V2VTkifjmfahtLM
      If you have Horizon installed or don't use UFO4P, this patch is not needed.
    -----
[!] FOUND : [3C] Natural And Atmospheric Commonwealth
    - If you notice weird looking skin tones with either NAC or NACX, install this patch.
      Patch Link: https://www.nexusmods.com/fallout4/mods/57052?tab=files
    -----
[!] FOUND : [7F] Rusty Face Fix
    - Make sure you have the latest 2.0 version installed or try the REDUX Version instead.
      Original Rusty Face Fix: https://www.nexusmods.com/fallout4/mods/31028?tab=files
      Alternative REDUX Version: https://www.nexusmods.com/fallout4/mods/64270?tab=files
    -----
[!] FOUND : [82] Start Me Up
    - Abandoned mod that can cause infinite loading and other problems. Switch to REDUX Version instead.
      Updated REDUX Version: https://www.nexusmods.com/fallout4/mods/56984?tab=files
    -----
[!] FOUND : [11] Tactical Reload
    - Can cause weapon and combat related crashes. TR Expansion For ECO is highly recommended.
      TR Expansion For ECO Link: https://www.nexusmods.com/fallout4/mods/67716?tab=files
    -----
# [!] CAUTION : FOUND PROBLEMATIC MODS WITH SOLUTIONS AND COMMUNITY PATCHES # 
[Due to limitations, CLASSIC will show warnings for some mods even if fixes or patches are already installed.] 
[To hide these warnings, you can add their plugin names to the CLASSIC Ignore.yaml file. ONE PLUGIN PER LINE.] 

====================================================
CHECKING FOR MODS PATCHED THROUGH OPC INSTALLER...
====================================================
[!] FOUND : [1D] Tales from the Commonwealth

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
* COULDN'T FIND ANY PLUGIN SUSPECTS *

# LIST OF (POSSIBLE) FORM ID SUSPECTS #
* COULDN'T FIND ANY FORM ID SUSPECTS *

# LIST OF DETECTED (NAMED) RECORDS #
- Name: "shadow scene node" | 1
- void* -> GFSDK_SSAO_D3D11.win64.dll+0004D4F) | 1
- void* -> GFSDK_SSAO_D3D11.win64.dll+0009551) | 1
- void* -> NvCamera64.dll+00F1C7F) | 3
- void* -> NvCamera64.dll+00F262F) | 4

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
