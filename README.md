**WANDERLUST** - a free, auto-installable Wabbajack Modlist by Fornication.

**Wanderlust** is the culmination of my years of playing and modding Skyrim. Using the beautiful graphics overhaul _Aurora_ as a starting point, I've created a fine balance of graphics and gameplay. With well over 2,000 mods, there is a strong focus on emergent gameplay and exploration of the world, along with roleplaying mechanics to make you re-experience Skyrim for the first time again.

List of mods included here: https://modwat.ch/u/Arkays%20Commandment

Feel free to join my discord! [Click Here! ](https://discord.gg/JycmyqzZz7)

- [**Wanderlust**]
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Skyrim Anniversary Edition](#skyrim-anniversary-edition)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Set the Game language and Windows Region to English](#set-the-game-language-and-windows-region-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
  	- [How to start up Wanderlustt](#how-to-start-up-wanderlust)
  	- [Starting a new game](#starting-a-new-game)
  	- [In-Game MCM Options](#in-game-mcm-options)
 	- [Updating](#updating)
  - [Gameplay](#Gameplay)
    - [Changes to Gameplay](#Changes-to-Gameplay) 
    - [Gameplay Tips](#Gameplay-Tips)
    - [FAQ](#FAQ)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [BethINI](#bethini)
    - [In-Game Settings](#in-game-settings)
    - [Widescreen Users](#widescreen-users)
    - [Zoomed in Display](#zoomed-in-display)
    - [Non-standard or Custom Monitor Resolution](#non-standard-or-custom-monitor-resolution)
    - [Information for Content Creators](#information-for-content-creators)
    - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

I've been playing and modding Skyrim for well over a decade. I've played with all sorts of mods and all sorts of builds. All of that experience has shaped this list into something that I hope you all can enjoy. I want to share the roleplaying experience I've made and make it something to remember.

**Please read the ReadMe in Full. The installation process is not completed once you have finished the Wabbajack installation.**

## System Requirements

- Windows 10+
- Skyrim Special Edition on Steam
	- You’ll need to launch Skyrim Special Edition from Steam at least once before playing if you haven’t before
- Latest version of Wabbajack installed to a root folder (example C:\Wabbajack)
- Enough space to download and install this list 
	- i. About 95 GB to download and about 130 GB for the installation. In total you'll need around 225 GB of space, but then after the installation completes, you can decide to delete the download folder if you'd like. Note that if you delete the downloads, and if you try to update the list, you will need to redownload all of the files.
- Nexus Mods account (Nexus premium membership is highly recommended for convenience)
- Microsoft Visual C++ x64
	- i. Specifically, the file: vc_redist.x64.exe found here: https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0
	- ii. You may already have this installed; it’s safe to try to install it again if you’re unsure

## Skyrim Anniversary Edition

- This list does not require the paid creation club mods. This list requires you to have updated to the most recent build of Skyrim Special Edition on Steam, dubbed "Skyrim Anniversary Edition". This only contains 4 free creation club mods. The list itself uses an older Skyrim version, and will automatically be downgraded for you. Your Steam folder will not be touched. Do not run the Downgrade Patcher or the list will not install.

- If for some reason you DO NOT want to upgrade to the latest Skyrim version, there is a workaround. Rename your current "Skyrim Special Edition" folder in your steam folder to something else. Go to steam and verify the integrity of the games files, or simply try to play Skyrim Special Edition, and this will trigger Steam to reinstall Skyrim Special Edition. Once it's finished downloading, you can install this list. Upon finalizing the installation, you can optionally delete the newly installed "Skyrim Special Edition" Steam folder, and rename your old folder back to the original name.

## Installation

### Pre-Installation

- These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

- I doubt you need to do this since you likely already have this installed. The package is required for Mod Organizer 2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

- The Steam Overlay is recommended to be turned off.

- Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language and Windows Region to English

- This entire Modlist is in English and 99% of all mods you will find are also in English. Some mods can break when using a non English version of Windows. Ensure that your Windows Regional Format is set to English. 

- Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

- I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133) to complelety wipe the game.

#### Start Skyrim

- After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.

- Start the game. Once in the main menu, click on Creations. You need to download Saints and Seducers, Rare Curios, Survival Mode, and Fishing. You will not have the correct version of the four free CC mods if you do not do this.

### Using Wabbajack

#### Preparations

- Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, OneDrive or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

- The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack and click on browse lists.
2. Download the modlist from the Wabbajack UI.
3. Once the download is done, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Wanderlust`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

- There are a lot of different scenarios where Wabbajack will produce an error. **I highly recommend re-running the Wabbajack install process before posting anything.** Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

- If a mod updated and the old files got deleted (which is very rare), it is impossible to download them. In this case, wait until I update the Modlist.

**x is not a whitelisted download**:

- This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

- Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

- Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. An example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

## How to start up Wanderlust

- Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to 'Play Wanderlust' and then hit the run button. 

## Starting a new game

- Create a new character like usual
	- I highly recommend you saving your character preset in the racemenu options if you’re fond of your character. Feel free to share presets that you make in our discord channel!
- Once done character creating, there will be several automated initialization steps that play. Wait maybe 15 seconds for everything to finish, and then you can continue on with your gameplay.

## In-Game MCM Options

- All mandatory MCMs are pre-loaded. Nothing needs to be done. You don't have to touch any MCMs!
- You can change various MCM settings to your liking. Most changes will NOT persist between saves. This is mod-dependent. If you change something, then have any bugs to report, please make a note of what has been changed.

## Updating

- Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

- This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!
- Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Gameplay

### Changes to Gameplay

**Please do not expect the game to be functionally similar to vanilla.** There are a lot of mods installed that modify core base game functionality as well as adding on new mechanics.

Wanderlust is the Skyrim that I've built to match what I find the most fun. I enjoy exploration, immersion, roleplaying, difficulty, and a strong sense of progression. Wanderlust is a summation of what I enjoy most about Skyrim and is a forever ongoing work in progress. There are way too many details to discuss in a readme, but I invite you to experience Wanderlust more as a journey through your character into Skyrim to really integrate yourself into the world. Pretend it's your first time playing again!

### Gameplay Tips

- Your race matters; choose this carefully.
- You are provided with 3 starting perks. I recommend that you focus at least 1 of these on combat-related skills to help you through combat.
- You can choose your standing stone and divine blessing right after starting your character by using the lesser power given to you. Daedric blessings tend to have a downside and normally require a murder before they benefit you.
- Always keep food buffs up to benefit your character; food can be cooked or bought from innkeepers. Make sure to have a meal and a snack effect active when you can!
- Having a good night sleep or even a poor night sleep increase the rate at which your stamina and magicka regenerate. Be sure to sleep before adventuring.
- Exploration and even wildlife can be very punishing. Animals tend to be easier and more predictable than bandits, but are less rewarding. The world is deleveled, so think twice before trying to take on vampires or daedra! There is nothing wrong with trial and error. See what works for you.
- Don’t leave town without being prepared for a fight. Be prepared to run away. Always watch your back. Carefully planning your adventure, including routes taken, will always be beneficial.
- Items will be very expensive to purchase and very cheap when selling: speech level and perks are actually important. Don't expect to get rich off selling goods without proper investment.
- The most important tip: you are an absolute weakling at level 1. You will feel yourself grow dramatically stronger at every level. Don't give up! This list is not intended to feel difficult. It's intended to reward progression and make every encounter feel important.

### FAQ

- Do not select any other profile besides the default one provided!

## Other Post Installation FAQ

### BethINI

- Included as an installed program with this list is BethINI, which is a tool that can quickly change INI settings, which can have a drastic impact on your game performance. The default setting that I used is a somewhat modified 'low'. If you're looking to get slightly better performance, or better graphics, you may want to look here.
1. Completely close out of Mod Organizer.
2. Navigate to the folder where you installed this mod list. Open the "Tools" folder, open the "BethINI Standalone" folder, and then open the BethINI.exe file.
3. Once opened, navigate to the 'Setup' tab on the top left. The first 4 lines should read as follows, and if not, change it:
	- Game: Skyrim Special Edition
	- Game Path: Installed location\Stock Game\
		- To manually change this, navigate to Installed location\Stock Game\ and double click SkyrimSE.exe
	- Mod Organizer: Installed location\
		- - To manually change this, navigate to Installed location\ and double click on ModOrganizer.exe
	- INI Path: Mod Organizer > Wanderlust
		- To manually change this, navigate to Installed location\Profiles\Wanderlust\ and double click Skyrim.ini
- Once complete, click on the 'Basic' tab and you can try choosing Poor, Low, Medium, High, or Ultra, depending on what your hardware can handle, keeping in mind the default I use is somewhere inbetween Low and Medium. I wouldn't recommend tweaking individual settings without prior experience. When done, hit 'Save and Exit'.

### In-Game Settings

- Feel free to adjust any in-game settings as you wish, they shouldn't cause any issues. This includes changing draw distance to gain some frames, changing sound settings, among other things.
- Note that some in-game settings will simply not work, like enabling the compass, and this is intentional. If something is not working, it cannot be changed by only changing something from in-game settings.

### Zoomed in Display

- This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

	- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
-or 
	- Edit the mod **High performance configuration for SSE Display Tweaks**, specifically the file named SSEDisplayTweaks.ini
		- Under `[Render]`
			- Set Fullscreen to `True`
			- Set Borderless to `False`

### Widescreen Users, Non-standard or Custom Monitor Resolution

- Widescreen is not officially supported. My monitor is 1440p and the UI is designed to fit on a 1440p monitor. The UI may look not as fully intended if not using this resolution. Visit the discord to inquire about any issues you may have. To change the game's resolution to a custom resolution, do as follows:
	- Edit the mod **SSE Display Tweaks**, specifically the file named SSEDisplayTweaks.ini
	- Find the line that says **#Resolution=1920x1080**
	- Remove the # from the beginning, and replace 1920x1080 with your desired resolution.

### Information for Content Creators

- There is no nudity in this list. Nothing in this list is worse than vanilla Skyrim in terms of violence or sexual content. The furthest this list varies from vanilla Skyrim in graphic content is enemies can be burned/electricuted and they will appear to have a charred texture, which already exists in the vanilla game.

- If using the Music Mod in the optional files which is defaultly enabled, you may or may not have issues with copyright on streaming or video services.

## Removing the Modlist

- Delete the installation folder.

## Credits and Thanks

- Althro for letting me fork his readme!

## Contact

Official support takes place on my discord channel. You can join [my discord](https://discord.gg/JycmyqzZz7) for less support-related inquiries and chatting as well!
