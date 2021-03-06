# Mass Enjoyment Loving Everything Installation Guide
- [Mass Enjoyment Loving Everything](#mass-enjoyment-loving-everything)
- [Intro](#intro)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Steam Config](#steam-and-origin-configs)
    - [Origin Config](#steam-and-origin-configs)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Change Origins Update Behavior](#change-origins-update-behavior)
    - [Set the Game language to English Steam](#set-the-game-language-to-english-in-steam)
    - [Set the Game language to English in Origin](#set-the-game-language-to-english-in-origin)
    - [Note on Localization](#note-on-localization)
    - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Disable the Origin Overlay and Other Origin BS](#disable-the-origin-overlay-and-other-origin-bs)
    - [Disable the Nvidia Overlay](#disable-the-nvidia-overlay)
    - [Clean Mass Effect Legendary Install](#clean-mass-effect-legendary-install)
    - [Backing Up Main LE Installation From Your Library](#backing-up-main-le-installation-from-your-library)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Wabbajack-Downloads](#post-wabbajack-downloads)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Launching the Game](#launching-the-game)
- [Manual Downloads](#manual-downloads)
- [Updating](#updating)
- [A Few Notes](#a-few-notes)
- [FAQ](#faq)
- [Controller Support](#controller-support)
- [ReShade](#reshade)
- [Widescreen Support](#widescreen-support)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)

---

# Intro

---

### Mass Enjoyment Loving Everything

Mass Enjoyment Loving Everything is my attempt to bring together as much fun, QOL changes, texture fixes, consistency, combat refining, and additions as I possibly can without breaking the game. [Here it is](url)

Is Mass Enjoyment Loving Everything for you? Probably. If you want lore-friendly fixes and additions, plus some extra goodies to spice things up, you've come to the right place.

**Please read this guide in its entirety.**

**Please read the FAQ again before reporting an issue or asking me a question.**

---

## Installation

---

## Pre-Installation

You need a legal copy of Mass Effect Legendary Edition through Steam or Origin

These steps are only for installing this Modlist for the first time. If you are updating the Modlist, go to [Updating](#updating).

---

## Steam and Origin Configs

If you're installing Origin for the first time I recommend choosing these settings; however, you can change this in the Origin launcher too.

![image](https://user-images.githubusercontent.com/77590002/165959635-a8a5b6c0-aaf2-49ac-8fff-d3ff5e19393b.png)

## Change Steams Update Behavior

To ensure that Steam does not automatically update the game for you, Open steam > right click Mass Effect LE > Properties > UPDATES > choose "Only update this game when I launch it" under AOUTOMATIC UPDATES and select Never allow

## Change Origins Update Behavior

To ensure that Origin does not automatically update the game for you, Open Origin > click Origin at the top left of the window > application settings > scroll down and turn off "Automatic Game Updates"

## Set the Game Language to English in Steam

Right click Mass Effect Legendary Edition > properties > language > select English from the dropdown menu.

## Set the Game Language to English in Origin

Open Program Files(x86) > Origin > double click "Origin.exe" > click "My Game Library" (right clicking the game in "Recent game" under "My Home" doesen't work for some reason) > right click Mass Effect LE > game properties > advanced lanch options > select English from the dropdown menu > save > close Origin 

## Note on Localization

I'm not really sure how to localize, you guys are totally up to it if you can. This Modlist is in English and so are 99% of all mods made for Mass Effect LE. I think the most compatible, or only compatible, way to play the game is to have it be in English. I'm also not sure how region lock effects the game, but I personally don't think it should be an issue, except for countries that basically ban freedom of thought.

**I will not give support to people with a non-English game**. I'd liked to if I could, but I won't be able to.

## Disable the Steam Overlay

Open steam > right click Mass Effect LE > Properties > GENERAL > uncheck Steam Overlay

## Disable the Origin Overlay and Other Origin BS

### UNDER THE "APPLICATION" TAB:

Default Screen -> Game Library
Show Origin after gameplay -> Off
Automatic game updates -> Off
Automatically update Origin -> Off
Participate in Origin technical previews -> Off
Automatically start Origin -> Off
Origin Helper service -> Off

### UNDER THE "DIAGNOSTICS" TAB:

Share hardware info -> Off
Share system interaction data -> Off
Origin crash reporting -> Off
Origin In-Game logging -> Off

(optional) UNDER THE "INSTALLS & SAVES" TAB:

Saves -> Off

### UNDER THE "INSTALLS & SAVES" TAB:

Enable Origin In-Game -> Off
Display FPS Counter -> Off

## Disable the Nvidia Overlay

Open Nvidia GeForce Experience > click the settings cog at the top of the window near your profile name > General > turn off IN-GAME OVERLAY

## Clean Mass Effect Legendary Install

I absolutely recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You also need to delete the `Mass Effect Legendary Edition` folder in `Documents/My Games/BioWare`. **Make sure you run the game once** to establish your registry path - otherwise, Wabbajack will be unable to locate the game directory, and you won't be able to download the mods :(

## Backing Up Main LE Installation From Your Library

In steam, right click on Mass Effect Legendary Edition > Manage > Browse Local Files > right click "Game" > copy to a folder of your choice, but I recomend `c:/WJ/Vanilla Game Backups`

For Origin, you'll have to find the games manually in your Origin installation

---

### Using Wabbajack

#### Preparations

---

This is where the fun begins...

Download Wabbajack [here](https://www.wabbajack.org/#/) (click the Download button). Place the `Wabbajack.exe` file in a blank folder at the root of a drive, I advise `C:/wj/Wabbajck`. Please do not put it in a Windows Protected Directory, such as Program Files or your Desktop. 

If you're using Windows 11, follow the steps below to give yourself admin permissions for `C:/wj` folder you created in your `C drive`



Launch Wabbajack. The program will be installed where you placed it. When it finishes installing, run wabbajack and click `Browse Modlists`. Click the Download arrow for Mass Enjoyment Loving Everything, and you will be forwarded to the next screen when it is finished.

Set the `Installation Location` to a blank folder at the root of a drive, such as `c:\wj\Mass Enjoyment Loving Everything`. The `Download Location` will update automatically. Again, please avoid using Windows Protected Directories.

Click the `Play` arrow. If you have a Nexus Premium account, all of your downloads will be automated. Without Premium, you will need to manually click the Download button for each mod. Installation will be automated regardless of your account status.

---

### Manual Downloads

Some mods for MELE only have manual download links. Sorry, you'll have to download these manually. Place them in the Downloads folder within the Mass Enjoyment Loving Everything modpack folder that wabbajack created (example: `c:/wj/mass effectiveness/mo2/downloads)`. I'll specify the version of the mod you'll need if necessary, so always get the most recent version of all mods listed below.

[ME3 Tweaks](https://www.nexusmods.com/masseffectlegendaryedition/mods/2?tab=files)

---

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

---

### Post-Installation

---

#### Launching the Game

---

## Updating

---

## FAQ

---

## Controller Support

---

## Widescreen Support

---

## Credits and Thanks

---

## Contact

I'm available on the [Wabbajack Discord](https://discord.gg/wabbajack).
