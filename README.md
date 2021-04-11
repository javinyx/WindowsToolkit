# WindowsToolkit

A collection of **Windows 10 apps and scripts** to optimize user and poweruser experience.

To make it in this list, apps must meet two or more of the following criteria:
* *Free to use* / *Open Source*
* *Theme Support* / *Fluent design*
* *Plugin Support*
* *Available in [Chocolatey Repository](https://community.chocolatey.org/packages)* / [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows)
* *Cross-device compatibility*

This list tries to give at least one alternative to every top pick for each app section, I tried to avoid apps that have been reported to contain spyware or adware in their bundle.

## Table of contents

* [WindowsToolkit](#windowstoolkit)
  * [Why was this repository made?](#why-was-this-repository-made-)
  * [Chocolatey Installation](#chocolatey-installation)
* [Applications](#applications)
  * [Browsers](#browsers)
  * [Email Clients](#email-clients)
  * [Text Editors](#text-editors)
  * [Code Editors](#code-editors)
  * [IDEs](#ides)
  * [Terminals](#terminals)
  * [Gaming](#gaming)
  * [FTP Client](#ftp-client)
  * [Media Players](#media-players)
  * [Media Viewers](#media-viewers)
  * [PDF](#pdf)
  * [Audio](#audio)
  * [SoundBoard](#soundboard)
  * [Social](#social)
  * [Password Managers](#password-managers)
  * [To do lists](#to-do-lists)
  * [Utilities](#utilities)
  * [Torrent Client](#torrent-client)
  * [Other](#other)

## Why was this repository made?

I believe that Windows is still far behind in terms of application installation, making use of a packet manager like Chocolatey can help you keep track of what's installed and of updates.

I also think that many applications are simply unknown to many people, therefore I want to give light to some of them. If, like me, you're using Windows, Android and iOS on a daily basis you will be able to find some nice cross-platform apps.

If you want to provide feedback please do so using GitHub Issues.

## Chocolatey Installation

While Microsoft Store is pre-installed in Windows 10, [Chocolatey](https://chocolatey.org/install) is not, so here is how to install it.

> The information below is taken from the official Chocolatey site, link above.

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

If you haven't done so already, make sure you install Chocolatey first following [Chocolatey Installation](#chocolatey-installation), if you have then you can move forward.

**Notes**:
* In the **Free** table column, if you see a `²` it means the application is also Open Source.
* I recommend using **Revo Uninstaller** to uninstall programs, instead of the default Windows method, this is because Revo also cleans any leftover files and registry entries, it won't break Chocolatey.
* If you're unsure whether to download the **Microsoft Store** version or the **Chocolatey** package of an app then: if it's a very light app that does simple things then I would recommend the Microsoft Store version, otherways the Chocolatey package.
* If you see that there is a **portable version** of the application, I would recommend giving it a try before installing.

## Browsers

Application | Free | Themes | Plugins | Packages | Cross-Platform | Notes |
----------- | ---- | ------ | ------- | -------- | -------------- | ----- |
[Google Chrome](https://www.google.com/chrome/) | :heavy_check_mark: | :heavy_check_mark: [Browse](https://chrome.google.com/webstore/category/themes) | :heavy_check_mark: [Browse](https://chrome.google.com/webstore/category/extensions) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/GoogleChrome) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.android.chrome&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/google-chrome/id535886823) | :star: Most used browser due to its simplicity and tools |
[Microsoft Edge](https://www.microsoft.com/en-us/edge) | :heavy_check_mark: | :heavy_check_mark: [Browse](https://microsoftedge.microsoft.com/addons/microsoft-edge-themes) | :heavy_check_mark: [Browse](https://microsoftedge.microsoft.com/addons/Microsoft-Edge-Extensions-Home) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/microsoft-edge) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.microsoft.emmx&hl=en&gl=US), [iOS](https://apps.apple.com/app/id1288723196) | New Chromium-based build actually makes sense |
[Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) | :heavy_check_mark:² | :heavy_check_mark: [Browse](https://addons.mozilla.org/en-US/firefox/themes/) | :heavy_check_mark: [Browse](https://addons.mozilla.org/en-US/firefox/extensions/) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/Firefox) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=org.mozilla.firefox&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/firefox-private-safe-browser/id989804926) | Great alternative to Chromium-based browsers |
[Vivaldi](https://vivaldi.com/) | :heavy_check_mark: | :heavy_check_mark: In app | :heavy_check_mark: [Browse](https://chrome.google.com/webstore/category/extensions) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/Vivaldi/3.7.2218.49) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.vivaldi.browser&hl=en&gl=US) | Feature-child of Chrome and Opera, but on steroids |

## Email Clients

Application | Free | Themes | Plugins | Packages | Cross-Platform | Notes |
----------- | ---- | ------ | ------- | -------- | -------------- | ----- |
[Mail](https://www.microsoft.com/store/productId/9WZDNCRFHVQM) | :heavy_check_mark: | :heavy_check_mark: Fluent | :x: |:heavy_check_mark: [MS Store](https://www.microsoft.com/store/productId/9WZDNCRFHVQM) | :heavy_check_mark: [Android](https://play.google.com/store/apps/details?id=com.microsoft.office.outlook&hl=en&gl=US), [iOS](https://apps.apple.com/us/app/microsoft-outlook/id951937596) | :star: Plain and simple, the mobile version is basically Outlook for Mobile |
[MailSpring](https://getmailspring.com/) | :heavy_check_mark:² | :heavy_check_mark: In app | :x: |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/mailspring) | :x: | Hidden gem among the email clients |
[Mozilla ThunderBird](https://www.thunderbird.net/en-US/) | :heavy_check_mark:² | :heavy_check_mark: [Browse](https://addons.thunderbird.net/en-US/thunderbird/static-themes/) | :heavy_check_mark: [Browse](https://addons.thunderbird.net/en-US/thunderbird/extensions/) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/thunderbird) | :x: | Great community, has amazing import and export features |

## Text Editors

Application | Free | Themes | Plugins | Packages | Cross-Platform | Notes |
----------- | ---- | ------ | ------- | -------- | -------------- | ----- |
[Notepad++](https://notepad-plus-plus.org/downloads/) | :heavy_check_mark:² | :heavy_check_mark: In app | :heavy_check_mark: [Browse](https://github.com/notepad-plus-plus/nppPluginList/blob/master/doc/plugin_list_x64.md) |:heavy_check_mark: [Choco](https://community.chocolatey.org/packages/notepadplusplus), [MS Store (Unofficial)](https://www.microsoft.com/store/productId/9PHSCTZMKC27) | :x: | :star: Community favorite for a long time |
[Notepads App](https://www.notepadsapp.com/) | :heavy_check_mark:² | :heavy_check_mark: Fluent | :x: |:heavy_check_mark: [MS Store](https://www.microsoft.com/store/productId/9NHL4NSC67WM) | :x: | Great looking new alternative for daily use |

## Code Editors
- Visual Studio Code
- Sublime Text 3

## IDEs
- IntelliJ IDEA Community
- Android Studio

## Terminals
- Fluent Terminal
- Windows Terminal

## Gaming
- Steam
- Playnite
- GOG Galaxy

## FTP Client
- WinSCP
- FFFFTP
- CoreFTP
- CoffeeCup Direct FTP Free
- Smart FTP
- CarrotDAV
- LFTP

## Media Players
- Pot Player
- VLC

## Media Viewers
- IrfanView

## PDF
- Acrobat Reader
- Xodo
- Okular

## Audio
- EarTrumpet
- VB-AudioCable
- VoiceMeeter

## SoundBoard
- SoundPad
- SoundBox
- Touch Portal

## Social
- Telegram
- WhatsApp Web
- Signal

## Password Managers
- BitWarden
- KeePass

## To do lists
- Microsoft To-do
- Trello

## Utilities
- File Converter
- Revo Uninstaller
- Everything

## Torrent Client
- qBitTorrent
- Deluge

## Other
- PreMid
- PowerToys
- ShareX
- Wallpaper Engine
- 7-Zip
- Discord