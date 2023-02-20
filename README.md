![Lagom](https://raw.githubusercontent.com/thomasfrandsen01/logo/main/lagomlogo.jpg)
## Preface

'Lagom' translates to just the right amount in Scandinavian culture. I believe that is what I have done here. This is a vanilla plus styled list based off of Skyrim Modding Essentials and modeled after AVO and Nolvus. My goal was to completely modernize the graphics, overhaul animations and combat, and add as much lore friendly content as possible (still going to work on that). Mods like ESO Imports, LotD, Bruma, and many others help me in doing so. This is a very rough version that is not complete, I have barely spent time in the world so I am not for sure of any bugs. Any bugs, glitches, missing textures, anything out of place or etc. could be, with great apprecation, reported in my discord which I will link. Thank you!

**Anniversay Edition is required**

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

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
2. Click `browse modlists` (don't forget to tick show `unofficial lists`), and download Elysium Remastered from the Modlist Gallery. Wait until you are forwarded to the next window.
3. Adjust the download and installation paths. The recommended Installation Path is a blank folder at the root of a drive, such as C:\Elysium Remastered. The Download Path will update automatically. You can move it elsewhere if you want.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
