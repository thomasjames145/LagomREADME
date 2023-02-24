![Lagom](https://raw.githubusercontent.com/thomasjames145/logo/main/lagomlogo.jpg)
## Preface

Join my [Discord](https://discord.gg/nYWjDEcb56) ! Feedback and troubleshooting is welcomed/available.

'Lagom' translates to "just the right amount" in Scandinavian culture. I believe that is what I have done here. This is a vanilla plus styled list based off of [Skyrim Modding Essentials](https://thephoenixflavour.com/skyrim-se/sme/introduction/) and modeled after [AVO](https://github.com/The-Animonculory/AVO-AE/blob/main/Readme.md) and [Nolvus](nolvus.net). My goal was to completely modernize the graphics, overhaul animations and combat, and add as much lore friendly content as possible (still going to work on that). Mods like ESO Imports, LotD, Bruma, ADXP-MCO, Immersive Armors Rexture, and many others help me in doing so. This is a very rough version that is not complete, I have barely spent time in the world so I am not for sure of any bugs. Any bugs, glitches, missing textures, anything out of place or etc. could be, with great apprecation, reported in my discord which I will link [here](https://discord.gg/nYWjDEcb56). Thank you!

**Anniversay Edition is required**

**Creation Kit is required**

### Setting Up Pagefile

Due to the resources required to run modlists like these, you will need to configure the pagefile on your system in order to avoid crashes and bugs that may occur from running out of memory. This step is **NOT** optional, I do not care how much RAM or VRAM you have, please do this step.
  I suggest a 40GB fixed-size pagefile for Lagom solely for safety, but it is very possible that you could get away with a 20GB (20480 instead of 40960 in the **Initial** and **Maximum Size** boxes). While a 20GB pagefile may be usable, I do not plan on testing it any time soon, so do so at your own risk.

To set up your pagefile:
1. Press **Win Key + R**
2. Type *sysdm.cpl ,3* and hit **ENTER**
3. Navigate to *Performance* and click the box "Settings..."
4. Click the *Advanced* tab at the top
5. Under *Virtual Memory* click the box "Change..."
6. Uncheck *Automatically manage* if it is checked
7. Select your disk drive, ideally your fastest solid state drive
8. Click the **Custom size:** button
9. In the box next to **Initial Size (MB)** type 40960(or 20480)
10. In the box next to **Maximum Size (MB)** type 40960(or 20480)
11. Click the *Set* button
12. Click *OK*
13. Click *Apply*
14. Click *OK*
15. Restart your computer in order for your new pagefile to take effect.

## System Requirements

### Minimum Specifications for ~60 fps gameplay at 1920x1080

>  Please note these specs are the best idea of a baseline that I can provide at the current moment, based on my own experiences. I play at 1440p with an upscaler and get 60fps on these specs so adjust as needed.

| Spec Category | Default Profile |
|     :---:    |     :---:     |
| **CPU**   | i5 9600k |  
| **Video Card**    | RTX 2060        |
| **Ram**    | 16gb (2x16) DDR4 3200mhz RAM     |
| **Storage**    | SATA SSD     |

Requires 238gb space total
77gb download folder


## Installation

### Pre-Installation


#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab, and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

Bethesda is still updating SSE (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. It would be best if you also disabled the Steam Cloud while you're at it.

Another problem with Steam is that if you have it installed with it's suggested paths, your first Steamlibrary will be in your Program Files folder which is a protected folder. Moving your Steamlibrary out of your Program Files folder is a key setup for a working modded experience. If you are having trouble doing so check [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting its contents.

#### Start Skyrim

After you have done everything above and got a clean SSE installation-ready, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace these graphics settings, then Start Skyrim.

**Now, log in to the Creation Club and download all of the Creation Club content.**

Once that done, close Skyrim.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near your drive's root level like `C:/Wabbajack.`

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the number of threads it will use at the start of the installation. To have the highest amount of threads and fastest speed, it is advised to place the working folder on an SSD.

1. Open Wabbajack.
2. Download my wabbajack file from [here](https://mega.nz/file/fVFR0bBD#nKMVYqioBRRJXCdtSfRReYjT01Jg6PnOlsTy4Pt7_2w) 1.04
3. Adjust the download and installation paths. I recommend c:\Lagom. The Download Path will update automatically. You can move it elsewhere if you want.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

##### Could not download x

**High Poly Head:** Mirror available [here](https://drive.google.com/drive/folders/1V_jcYzwTiKnSv8Dbv-7Z0hh9SWbkn6Bi) aswell as in the discord. Download the missing files manually, drop them in the WJ downloads folder **WITHOUT EXTRACTING** and rerun Wabbajack.

**x is not a whitelisted download:**

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder:**

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation


## Finishing Line

Please join my discord server and leave any feedback or suggestions for the modlist. Im also looking to improve and I am very new to this. Consider this an alpha version, so much can be changed or improved. Thank you and Enjoy!


I would also recommend checking out PureDark's (the author of the new upscaler mod) patreon for an enb compatible upscaler. I use it on my RTX 2060 and it makes my frames a stable 60 anywhere.
