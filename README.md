# WindowsToolkit
A collection of **Windows 10 apps and scripts** to optimize user and poweruser experience.

To make it in this list, apps must meet two or more of the following criteria:
* *Open Source* / *Free to use*
* *Theme Support*
* *Plugin Support*
* *Available in [Chocolatey Repository](https://community.chocolatey.org/packages)* / [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows)
* *Cross-device compatibility*

The list tries to give at least one alternative to each top pick for each app section, if a Chocolatey Package is available I prioritize it over the Microsoft Store alternative.

## Why was this repository made?

I believe that Windows is still far behind in terms of application installation, making us of a packet manager like Chocolatey can help you keep track of what's installed and of updates.

I also think that many applications are simply unknown to many people, therefore I want to give light to some of them. If, like me, you're using Windows, Android and iOS on a daily basis you will be able to find some nice cross-platform apps.

If you want to provide feedback please do so using GitHub Issues.

## Chocolatey Installation

While [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows) is pre-installed in Windows 10, [Chocolatey](https://chocolatey.org/install) is not, so here is how to install it.

> All of the information below is taken from the official Chocolatey site, link above.

**Requirements:**
* Windows 7+ / Windows Server 2003+
* PowerShell v3+
* .NET Framework 4.5+

**Installation:**
1. Press **Windows+R** to open the *Run* box.
2. Type `cmd` into the box and then press **Ctrl+Shift+Enter** to run the command as an administrator.
3. Run `Get-ExecutionPolicy`. If it returns `Restricted`, then run `Set-ExecutionPolicy AllSigned` ***OR*** `Set-ExecutionPolicy Bypass -Scope Process`.
4. Run the code below:

       Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

5. Wait a few seconds for the command to complete.
6. If you don't see any errors, you are ready to use Chocolatey! Type `choco` or `choco -?` now, or see [Getting Started](https://docs.chocolatey.org/en-us/getting-started) for usage instructions.

Now that the Chocolatey installation is done, let's get started!

# Applications

If you haven't done so, make sure you install Chocolatey first at #Chocolatey Installation, if you have then you can move forward.

**Notes**:
1. In the **Free** table column, if you see a `²` it means the application is also Open Source.


## Browsers
Application | Free | Themes | Plugins | Packages | Cross-Platform | Notes |
----------- | ---- | ------ | ------- | -------- | -------------- | ----- |
[Google Chrome](https://www.google.com/chrome/) | :heavy_check_mark: | :heavy_check_mark: [Browse](https://chrome.google.com/webstore/category/themes) | :heavy_check_mark: [Browse](https://chrome.google.com/webstore/category/extensions) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/GoogleChrome) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.microsoft.emmx&hl=en&gl=US), [iOS](https://apps.apple.com/app/id1288723196) | :star: Personal Favorite |
[Microsoft Edge](https://www.microsoft.com/en-us/edge) | :heavy_check_mark: | :heavy_check_mark: [Browse](https://microsoftedge.microsoft.com/addons/microsoft-edge-themes) | :heavy_check_mark: [Browse](https://microsoftedge.microsoft.com/addons/Microsoft-Edge-Extensions-Home) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/microsoft-edge) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.android.chrome&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/google-chrome/id535886823) | New Chromium-based build |
[Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) | :heavy_check_mark:² | :heavy_check_mark: [Browse](https://addons.mozilla.org/en-US/firefox/themes/) | :heavy_check_mark: [Browse](https://addons.mozilla.org/en-US/firefox/extensions/) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/Firefox) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=org.mozilla.firefox&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/firefox-private-safe-browser/id989804926) | Great alternative to Chromium-based browsers |

## Text Editors
- Notepad++
- Visual Studio Code

## Gaming
- Steam
- Playnite
- GOG Galaxy

## FTP Client
- WinSCP
- FileZilla

## Media Players
- Pot Player
- VLC

## Media Viewers
- IrfanView

## PDF
- Acrobat Reader
- Xodo

## Audio
- EarTrumpet
- VB-AudioCable
- VoiceMeeter

## SoundBoard
- SoundPad
- Resanance

## Social
- Telegram
- WhatsApp Web
- Discord

## Password Managers
- BitWarden
- KeePass

## To do lists
- Microsoft To-do
- Trello

## Utilities
- File Converter
- CCleaner
- Ditto Clipboard
- Everything

## Torrent Client
- qBitTorrent

## Other
- PreMid
- PowerToys
- ShareX
