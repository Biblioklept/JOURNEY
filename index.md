![JOURNEY](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/branding/journey.png)

### Goal
The goal of this modlist is to provide a base to build upon with mods of your own choosing, whilst providing a perfectly good experience on its own, should you choose to not go any further. Initially a remake of EXPIDITION with less crashes, more vanilla assets, less overkill ReShades, and modularity, it's quickly become it's own modlist.

### First, Important, and Final Warning Before Starting
***Support will NOT be given towards people who have modified the modlist further than what's provided within the guide. Although this modlist is designed to give you the essentials for a smooth and relatively fun experience to build on with mods you want to use, I simply cannot and will not provide support for everyone's modlist setups.***

### Pre-requisites
- A decent internet connection
- A computer that can run S.T.A.L.K.E.R.: Anomaly, in the words of seargedp:  
> "I recommend at least 16 GB of RAM, a recent quad-core CPU and a graphics card with at least 4 GB of VRAM, ideally at least something as powerful as a GTX 970 or higher. It's also only tested on Windows 10 and requires a 64 bit version of Windows."  
- [S.T.A.L.K.E.R.: Anomaly](https://www.moddb.com/mods/stalker-anomaly/downloads/stalker-anomaly-151)

## Mod Organizer 2 Setup

***This section was completely ripped off and converted from [Viva New Vegas](https://vivanewvegas.github.io/mo2.html). All credits to Qolore07***.

### Installing Mod Organizer 2

1.  Download the `Mod Organizer 2` latest file from [here](https://github.com/ModOrganizer2/modorganizer/releases/latest)
2.  Once the download has finished, run the installer
3.  When prompted to choose an install location, pick any location outside of any default Window folders (like `Program Files x86`) and outside of the game's `Root` folder (the installer's default location will work)
4.  Click `Next` until the installer finishes

### Configuring Mod Organizer 2

### Initial Setup

1.  Run `ModOrganizer.exe`
2.  You will be prompted with a pop-up called `Creating an instance`, in which you should just select `Next`
3.  On the next page, select `Create a portable instance`
5.  On the next page, select `STALKER Anomaly`
6.  On the next page, keep the `Location` file path default

> If you have MO2 installed on an SSD or a HDD with little space, you can check the **Show advanced options** box and change the **Downloads** file path to a different drive with more space. This will not effect download/game performance, and the downloads can be deleted after the mods have been installed.

6.  On the last page, select `Finish`
7.  MO2 will launch and prompt you with a pop-up called `Show tutorial?``, in which you should select `No`
8.  From the pop-up called `Register?`, select `Yes`

- This pop-up will not show up if you have already registered a different instance of MO2

### Configuring Settings

1.  Select the `X` in the bottom right of MO2 to close the log window
2.  Select the `Settings` button at the top of MO2 to open the settings
3.  In the **Theme** tab, you can select a different style from the drop-down menu at the top

- I use the `1809 Dark Mode` theme

4.  In the `Nexus` tab, select `Connect to Nexus`

- This option will not show up if you have already connected your Nexus account on a different MO2 instance

5.  MO2 will open your browser and prompt you to authorize the connection
6.  Once you authorize it, you can close out of your browser and of the MO2 settings
7.  Allow MO2 to restart if it asks

### Creating Profiles

Mod Organizer 2's "Profiles" feature allows for easy switching between different mod configurations. In this step, we will create a profile for the guide while keeping a strictly-vanilla profile for testing/de-bugging. Profiles can be selected via the drop-down menu above the left pane.

1.  Select the `Profiles` button at the top of MO2 to open the profiles menu
2.  Select the `Default` profile, then select `Copy`
3.  Name the new profile `JOURNEY`
4.  Select the `JOURNEY` profile and make sure both `Use profile-specific Game INI Files` is checked at the bottom

> You may get a pop-up called `INI file is read-only` when attempting to make/select a new profile. If so then select `Remember my choice` from the drop-down at the bottom then click `Clear the read-only flag`

5.  Exit out of the profiles menu and select the `JOURNEY` profile from the drop-down above the left pane

### Mod Installation Advice

> If you are completely unfamiliar with Mod Organizer 2, I recommended watching [GamerPoet's video](https://www.youtube.com/watch?v=7v0wWVuOagA) about mod installation in MO2. As it was made for Skyrim, it has some information that does not apply to New Vegas, such as the Steam Workshop part. However, the rest of the information about downloading/installing mods from Nexus applies to all Bethesda games.

1.  Click the `DOWNLOAD NOW!` button (or whatever the download button is for the respective site)

> I recommend moving the downloaded files to your JOURNEY MO2 `downloads` (i.e. `JOURNEY\downloads`) folder.

2.  Once the download has finished, click the `Archive` button at the top of MO2
3.  From the new window, navigate to where the file was downloaded to and double-click it

When downloading multiple files from the same page, you will be prompted with a box in Mod Organizer 2 with the options `Merge`, `Replace`, and `Rename`. You should select the `Rename` option and rename the mod to its respective file name. This will make MO2 install them as separate files for easier management. If you are updating from an old version of a mod, you should select `Replace`. This will delete all the files from the old version of the mod and replace them,with the ones from the new version. This is the only time you should use the `Replace` option, otherwise always use `Rename`.

## Modlist Setup

### Initial Setup
To begin, you will need to download the [Anomaly Modded EXE Files](https://github.com/themrdemonized/STALKER-Anomaly-modded-exes/raw/main/STALKER-Anomaly-modded-exes.zip) and extract the files into your root STALKER Anomaly game folder.

Then, extract the contents of the [Mod Organizer 2](https://github.com/ModOrganizer2/modorganizer/releases/latest) file to a folder called `JOURNEY`, once done, run the `ModOrganizer.exe` file. Go through the installation, when prompted for the game to manage, search for STALKER Anomaly, and find your root game directory, and select it.

### User Interface
[Anomaly Mod Configuration Menu](https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-mod-configuration-menu)  
[DLTX'd Persistent MCM Configuration](https://www.moddb.com/mods/stalker-anomaly/addons/dltxs-persistent-mcm-configuration) 
[OPFOR ClearHUD and ClearMask - Minimalistic and Immersive HUD](https://www.moddb.com/mods/stalker-anomaly/addons/opfor-clearhud-and-clearmask-minimalistic-and-immersive-hud)   
[Hunger, Thirst, Sleep UI Improved](https://www.moddb.com/mods/stalker-anomaly/addons/patch-hunger-thirst-sleepiness-bars)  
[Crook's Faction Identification UI](https://www.moddb.com/mods/stalker-anomaly/addons/crooks-faction-identification-ui)  
[Instant Tooltip](https://www.moddb.com/mods/stalker-anomaly/addons/instant-tooltip-for-rc18-23)  
[Cost In Tooltip](https://www.moddb.com/mods/stalker-anomaly/addons/cost-in-tool-tip-u4h8-and-rc18-23)  
[Battery Warning](https://www.moddb.com/mods/stalker-anomaly/addons/batterywarning)

### Fixed Vanilla Visuals
[Glossy Surfaces and Water SSR](https://www.moddb.com/mods/stalker-anomaly/addons/glossy-surfaces-ssr)  
![Glossy Surfaces and Water SSR Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/GSSSRTUT.png)  
[Fixed Vanilla Models & Textures](https://www.moddb.com/mods/stalker-anomaly/addons/fvm)  
[Dux's Innumerable Character Kit](https://www.moddb.com/mods/stalker-anomaly/addons/dick)  
![Dux's Innumerable Character Kit Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/DICKTUT1.png)  
![Dux's Innumerable Character Kit Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/DICKTUT2.png)  
- Alternative (Do **NOT** use `Fixed Vanilla Models & Textures` and `Dux's Innumerable Character Kit` if using): [Anomaly HD Models](https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-hd-models-addon) OR [Anomaly HD Models Lite](https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-hd-models-addon-151-lite), and be sure to **grab the latest fixes in the description of the mod**.

[Torch Animation Fixed](https://www.moddb.com/mods/stalker-anomaly/addons/torch-animation-fixed)  
[MP-133 Fix](https://www.moddb.com/mods/stalker-anomaly/addons/mp-133-fix)

### Additional Visuals
[Camera Reanimation Project - I.N.E.R.T.I.A.](https://www.moddb.com/mods/stalker-anomaly/addons/camera-reanimation-project-inertia)  
[T.H.A.P. Rework](https://www.moddb.com/mods/stalker-anomaly/addons/thap-rework)  
![T.H.A.P. Rework Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/THAPTUT.png)  
[Food, Drug and Drinks Animations](https://www.moddb.com/mods/stalker-anomaly/addons/food-drug-and-drinks-animations-reuploaded)  
![FDDA Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/FDDATUT.png)

### Gunplay
[EFT Weapon Reposition Updated](https://www.moddb.com/mods/stalker-anomaly/addons/alternate-aim-sights-for-eft-reposition)  
![BAIN Prompt Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/BAINPROMPT1.png)  
![EFT Weapon Reposition Updated Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/EFTWRTUT.png)  
[Lowered Sprinting Animations](https://www.moddb.com/mods/stalker-anomaly/addons/lowered-weapon-sprint-animation)
[Sights Without Dirt/Clean Sights](https://www.moddb.com/mods/stalker-anomaly/addons/sights-without-dirt-clean-sights)  
[Shader Based 2D Scopes](https://www.moddb.com/mods/stalker-anomaly/addons/shader-based-2d-scopes-151dx11engine-mod)  
![Shader Based 2D Scopes Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/SB2DSTUT.png)  

### Gameplay
[RF Receiver Hidden Package Sidequests](https://www.moddb.com/mods/stalker-anomaly/addons/tbs-rf-receiver-hidden-package-sidequests)  
[Bounty Squads Expanded](https://www.moddb.com/mods/stalker-anomaly/addons/bounty-squads-expanded1)  
[Stealth](https://www.moddb.com/mods/stalker-anomaly/addons/stealth1)

### Tweaks
[Nitpicker's Modpack](https://www.moddb.com/mods/stalker-anomaly/addons/nitpickermodpack)  
![Nitpicker's Modpack Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/NPMPTUT.png)  
[Modular Miscellaneous Tweaks](https://www.moddb.com/mods/stalker-anomaly/addons/modular-miscellaneous-tweaks)  
![Modular Miscellaneous Tweaks Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/MMTTUT.png)  
[Crafting With Multi-Use Items Fix](https://www.moddb.com/mods/stalker-anomaly/addons/fixed-crafting-with-multi-use-items)  
[UNISG Hollow Boundaries Fixes](https://www.moddb.com/mods/stalker-anomaly/addons/unisg-hollow-boundaries-fixes-v110)  
![Crafting With Multi-Use Items Fix Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/CWMUIFTUT1.png)  
![Crafting With Multi-Use Items Fix Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/CWMUIFTUT2.png)  
![Crafting With Multi-Use Items Fix Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/CWMUIFTUT3.png)  
[Fixed Player Thermal Resistance](https://www.moddb.com/mods/stalker-anomaly/addons/fixed-player-thermal-resistance)  
[He Is With Me](https://www.moddb.com/mods/stalker-anomaly/addons/he-is-with-me)  
[Quick Companion Teleport](https://www.moddb.com/mods/stalker-anomaly/addons/quick-companion-teleport-151)  
[Rats Are Not Enemies](https://www.moddb.com/mods/stalker-anomaly/addons/rats-are-not-enemies)  
![Rats Are Not Enemies Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/RANETUT1.png)  
![Rats Are Not Enemies Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/RANETUT2.png)  
![Rats Are Not Enemies Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/RANETUT3.png)  
[Angry Chimera Growls](https://www.moddb.com/mods/stalker-anomaly/addons/tbs-angry-chimera-growls-v10)  
[Coordinate Based Safe Zones](https://www.moddb.com/mods/stalker-anomaly/addons/tb-coordinate-based-safe-zones-v1-0)  
[Fairer Thermal Anomalies](https://www.moddb.com/mods/stalker-anomaly/addons/tbs-fairer-thermal-anomalies-v1-0)  
[Companions Deactivate Headlamps When In Stealth](https://www.moddb.com/mods/stalker-anomaly/addons/tbs-companions-deactivate-headlamps-when-in-stealth)  
[475 New Stash Locations](https://www.moddb.com/mods/stalker-anomaly/addons/tbs-475-new-stash-locations)  
[Bugged Stashes Fix](https://www.moddb.com/mods/stalker-anomaly/addons/tbs-bugged-stashes-fix)

### Final Steps/Patches
[OPFOR HUD + Quick Companion Teleport Patch](https://github.com/Biblioklept/JOURNEY/raw/main/mod_files/OPFOR%20HUD%20%2B%20Quick%20Companion%20Teleport%20Patch.7z)  
Open your `axr_options.ltx` file in `gamedata\configs\` and find the `[mcm]` tab, paste and replace the contents with the contents of [this text file](https://raw.githubusercontent.com/Biblioklept/JOURNEY/main/mod_files/mcmsettings.txt).  
Finally, if you want some sort of indicator as to how your modlist should be ordered, [this should do nicely](https://loadorderlibrary.com/lists/journey-modlist). Simply expand the `modlist.txt` tab.  
**NOTE**: *The modlist.txt file features both the `FVM + DICK` mod combination and the `HD Models + HD Models Fixes + THAP HD Models Patch` mod combination. Do not have both of these turned on, they are only both on for demonstration's sake.*

## Optional Mods

### Azazel Mods [OPTIONAL]
[Azazel Tweaks](https://www.moddb.com/mods/stalker-anomaly/addons/azazel-tweaks)

### Warfare Mods [OPTIONAL]
[Warfare ALife Overhaul](https://www.moddb.com/mods/stalker-anomaly/addons/warfare-alife-overhaul)  
![Warfare ALife Overhaul Installation Tutorial Image](https://raw.githubusercontent.com/Biblioklept/JOURNEY/gh-pages/img/tutorialimgs/WALOTUT.png)  
[Hawkie's Warfare Mechanic Fix](https://www.moddb.com/mods/stalker-anomaly/addons/hawkies-warfare-mechanic-fix)

### ReShade [OPTIONAL]
1. Download [ReShade](https://reshade.me/)
2. Install ReShade by going into your S.T.A.L.K.E.R.: Anomaly `bin` folder and choosing the DX version you use.
3. Install any of these presets into your `bin` folder.

[в.о.л.к. ReShade](https://www.moddb.com/mods/stalker-anomaly/addons/reshade)  
[LUSH - ReShade](https://www.moddb.com/mods/stalker-anomaly/addons/lush-reshade)  
[Clear Sky ReShade](https://www.moddb.com/mods/stalker-anomaly/addons/clear-sky-reshade)  
[METRO-STALKER ReShade](https://www.moddb.com/mods/stalker-anomaly/addons/metro-stalker-reshade)  
