# skyrim-gmoh
A Wabbajak modlist for Skyrim SE

# Brief

- This is the beta version of a Wabbajak modlist for Skyrim SE. If you are new to Wabbajack, Mod Organizer 2 or Skyrim modding, I recommend starting with an official Wabbajak modlist (https://www.wabbajack.org).

- This list has 2 goals:

    1. Completely overhaul the landscape and core gameplay systems of Skyrim.
    2. Build a comprehensive modlist that you can use to start modding Skyrim to your tastes.

- The goal of this list is not gameplay balance. You will likely feel slightly underpowered at lower levels and overpowered at higher levels.

# Requirements

 - The Steam version of Skyrim: Special Edition. Only English is supported.
 - Anniversary Edition Content (https://store.steampowered.com/app/1746860/The_Elder_Scrolls_V_Skyrim_Anniversary_Upgrade).
 - C++ Redistributable for VS2019 (https://aka.ms/vs/17/release/vc_redist.x64.exe).
 - 1 Terabyte of storage (preferably SSD).

# Disclaimer

- Please do not report bugs/issues to individual mod authors. Issues must be reported through the support channels provided {anchor bug report instructions}.
- The list is in beta. You may experience breaking issues during installation or during gameplay.
- This is not a performance friendly list. Expect framerate drops in busy areas.
- With ~2700 mods, expect the installation process to take significant time and bandwidth. 

# Complete Modlist: {Load order library link here}

# Modlist Breakdown

# Gameplay
- Attack & Dodge (MCO|DXP)
- Valhalla Combat
- For Honor in Skyrim
- Vokriinator - Choice Cuts
- Experience and Missives
- Shadows of Skyrim

# Vanilla Questing
- Realm of Lorkhan
- Humble Beginnings
- At Your Own Pace
- BUVARP RE
- More to Say
- Many of the vanilla quest expansions by JaySerpa

# New Quests and Companions
- Beyond Skyrim: Bruma
- Vigilant
- 3DNPC
- EZPG
- Hammet's Dungeons and New Vominheim
- Remiel
- The Wheel of Time
- Katana - Journey in the Shadows
- Song of the Green (Auri)
- Serana Dialogue Addon

# Skyrim Overhauled
- JK's Skyrim
- Northern Roads and Cities of the North
- The great cities, towns and villages series
- Many of the amazing towns and villages by Schlitzohr
- Majestic Mountains Parallax
- Majestic Landscapes Parallax
- Veydosebrom Regions
- Traverse the Ulvenwald
- Rudy ENB for NAT III

# Installation

- Verify the integrity of your Skyrim installation (https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB).

# Wabbajak Installation & Configuration

- Download wabbajak.exe from the official Wabbajak site (www.wabbajak.org).
- Download the latest Wabbajak .meta file for GMOH from this repository {latest release}.
- Create a new folder for Wabbajak at, or close to, the root of your drive (e.g. c:\wabbajak). Do not create this folder in a UAC protected folder (e.g. Program Files or My Games). 
- Move wabbajak.exe into the new folder.
- Run the executable and wait for it to update. 
- Select "Install from Disk".
- Configuring your file paths:

    "Target Modlist"
    
    This will be the path to the .meta file you downloaded in the previous step.

    "Installation Location"
    
    This folder will contain the portable Mod Organizer 2 instance. This folder must be located on the same drive as your Skyrim installation. Like the Wabbajak folder, it must created outside of a UAC protected folder.
    
    An example of a good location: "c:\gmoh"

    "Download Location"

    This folder will contain all of the downloaded archive files required for the installation process. By default, it will be placed in the Mod Organizer 2 folder. If storage space is a concern, it is okay to create this folder on a separate drive.

- Click the play button to start the process.

# Controls

{keyboard map}

# New game and In-game configuration

- Unplug your gamepad while playing. Leaving it plugged in can lead to UI/gameplay issues.  Gamepad is not fully supported yet.
- After creating your character, you will find yourself in the realm of Lorkhan. Before you continue, please allow ~1 minutes for mods to initialize.
- Most configuration steps have already been made through INI files (see the "mod config" separator in MO2).
- You will need to manually activate Shadows of Skyrim in the MCM if you want to use it. If you become a lich or are using some other item/perk that provides it's own death alternative, deactive Shadows of Skyrim in the MCM.

# Known issues

{known issues}

# Reporting a bug

 - I will be unable to provide support if you have made modifications to any part of the list. 
 - Please refer to known issues before reporting a bug.
 - Please report bugs on the Discord.
 - To report a crash (CTD), it must be reasonable to reproduce and include a log file. If the report does not meet this requirement, it will likely be ignored. Your crash logs can be found in the user folder "Documents\My Games\Skyrim Special Edition\SKSE". It should look like this: "crash-[datetime of crash].log". Please do not copy paste text from the log file into a report, just attach the file.

# Help, Tips and FAQ

- I can't find my follower(s). If they are imported into Nether's follower framework, you should be able to teleport them to you from the Follower Framework MCM. If they are exempt from the framework (for example: Auri, Serana or Lucien), they will typically have a follower tracker quest or spell to summon them to you. Failing that, lookup the NPC reference ID on UESP (https://en.uesp.net/wiki/Skyrim:People) or use Google, open the game console -> "prid {referenceId}" -> "moveto player". Keep in mind there are some quests/areas that deliberately seperate you from your followers.
- Skyrim's engine has some documented (https://www.youtube.com/watch?v=PJPzMAXSprU) issues with reloading during play. Consider relaunching the game instead of reloading a save. If you are dying alot, consider enabling Shadows of Skyrim.